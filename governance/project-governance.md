# .NET Foundation Project Governance Models 
 
The governance model of .NET Foundation projects are similar but the details vary across
different projects. That is each project sets its own governance model depending on its
specific needs whilst drawing from a common set of principles and a shared language that
makes it easier to transfer knowledge about the inner workings of one .NET foundation project
to any other project. The goal is to enable projects to share good practice whilst still
allowing the freedom to self-manage.   In this document we outline the common principles and
terminology found in .NET Foundation project. We will discuss:

 - Releasable vs. non-releasable materials
 - Roles that project participants can take
 - Decision making processes   

## Releasable and Non-Releasable Materials

Materials managed and produced by the project are
divided into two distinct categories - releasable and non-releasable materials. We make this
distinction to enable projects to define two levels of "privilege" in a project. That is,
participants with full privileges will have full control over both non-releasable and
releasable materials. Those with the least privileges will have read only access to releasable
materials. Privileges are awarded or earned according to a projects defined governance model,
some examples of which are provided later in this document.

Using this technique it is possible to draw a matrix of who has which privileges in any given
project along with how the privileges are managed. This makes it easier to quickly review and
understand the governance of a project.

Releasable materials are materials that contain intellectual property which is licensed to
project users under an open source license.  Typically such materials will include:

 - Software that has been approved and packaged for release
 - Project designs and roadmaps
 - Documentation that is published as part of a software release
 - Test code and data
 
In order to become releasable materials items must go through a formal review (usually as part 
of the Pull Request or patch review process) which will include a verification that the
materials are aligned with the defined strategy of the project, are correctly licensed and
functions as intended. Documentation that is intended to form part of a release will also be
reviewed to ensure that it reflects the latest release.

The format of this review if defined by the Project Lead[s] (see roles defined below) and the
responsibility for carrying it out falls to the project maintainers and the Lead[s]. All
releasable materials can be assumed to have met the quality bar set by the project and, while
they are provided under an open source license and thus with no warranty, they are considered
to be ready for users.

Non-releasable materials are items that have not been fully reviewed and approved for release.
Alternatively they are items that are not intended to be a part of a formal release and are
managed by the wider community. Non-releasable materials will include:

 - Software patches, pull requests / PR's in the patch queue
 - Data in the projects issue tracker
 - Content in a wiki, mailing list archive, forum or other community managed resource
 
This separation of materials into releasable and non-releasable allows different levels of
control over contributions to the project. Non-releasable materials are community created and
provided with the intent to support the open source development effort. Project leads will
evaluate these materials and, where appropriate, include them in formal releases. However,
where these materials are not included in a release they remain available for the community
to use and build upon should they so desire.
 
Different projects will define a different balance between community driven non-releasable
contributions and formally approved and vetted releasable contributions. In some cases it is
expected that project lead[er]s will want to maintain a tight control over the technical
direction of the project . Such projects will look to the non-releasable materials as
experimental. In other projects the releasable materials may draw more deeply from the community
and thus be more organic. Such projects will see community contributions as a valuable resource
that helps set the direction of future releases.

Understanding the process by which materials are reviewed in preparation for a release is key
to understanding the cultural make-up of a .NET Foundation project. 

## Roles
Five main roles exist in .NET Foundation project:
 - Original Contributor
 - Project Lead
 - Project Maintainer
 - Contributor
 - User

In some projects the Project Leads will be a subset of Project Maintainers, in other projects
the two sets will be identical. This allows for a number of common open source governance
structures including, but not limited to, committee managed, benevolent dictatorships and
community led projects. Each project is free to select the optimal model for their community
needs.

### Original Contributor
A project may choose to recognize an Original Contributor. The Original Contributor brings the
project to the .NET Foundation in the form of an initial open source code base, a proposal,
a specification or some other set of materials that seed the project. This will be an
individual or an organization that appoints an individual to fill the role.

The Original Contributor is a special role that, unlike other roles, cannot be transferred to
others (except in the case where the Original Contributor is an organization who appoint a
representative to fill the role). This role brings with it a set of special privileges which
can best be summarized as having a power of veto over all decisions with the project.  
 
The existence of an Original Contributor role allows .NET projects to adopt governance styles
with highly centralized control, such as the Benevolent Dictator model. Some Original
Contributors choose not to exercise these privileges and will remove them through the projects
bylaws. The decision to preserve or divest the authority the Original Contributor is
afforded provides a strong indication to the community about the intent of this project. 
 
While the title of Original Contributor cannot be transferred it is entirely possible to
create a similar governance structure where, for example, the role of a Benevolent Dictator
is filled by a single Project Lead, a role which is discussed below.

### Project Lead
A project lead is an expert responsible for leading the software development effort. The
project lead oversees the general health of the project and its community. There may be more
than one lead, either sharing responsibility for the project or each leading a specific part
of the project. Leads are also responsible for defining the bylaws. These bylaws define how
the project community is managed, how individuals are recognized as fulfilling the roles
defined below and the privileges that come with each role.

Project lead(s) have full authority over all releasable materials in the project. They define
the review requirements and are responsible for ensuring that reviews are completed before
release. In the event of a dispute within the community, project lead(s) are the final arbiter
in those disputes. Project leads may choose to delegate some of this authority to project
maintainers. Such delegation will be defined in the bylaws for the project.

### Project Maintainer
A project maintainer has some authority over the projects releasable artifacts. They will
typically have write access to some, or all, releasable materials in the project and will
be responsible for maintaining the health of the projects releasable artifacts.

In some projects the set of maintainers is the same as the set of project leads, in others the
project leads will be a subset of the maintainers.

Project Maintainers are responsible for helping project leads define the direction and
objectives of the project and for delivering on those objectives through their day to day
actions. Project maintainers are typically close to the project community, they understand
the needs of community members and ensure that their views and needs are adequately represented
in all aspects of planning for the project.

Project maintainers write code, review contributions / pull requests, perform QA, recruit
contributors and generally ensure the project functions on a daily basis. Contributions from
project maintainers are, for the most part, expected to be releasable materials
(unless explicitly part of a community experiment).

Since maintainers are able to review and commit community contributions they have the
ability to "promote" non-releasable contributions from the community to releasable status.
The role of project maintainer is therefore a critical one to the health of any community led
project.

It is good practice for the project maintainers to follow the same process for making and
reviewing code contributions that they wish general Contributors to follow, for example by
submitting a Pull Request (PR), allowing it to be reviewed by the community and ideally
having it be merged by a different maintainer or project lead.

Whilst project maintainers have control over releasable artifacts they do not have full
authority over them. That is, the project lead(s) have the final say in any strategic,
community or technical decision within the project.   

### Contributor
Anyone can contribute to a .NET foundation project by providing feedback, user requests, 
issue triage, pull requests, code contributions, documentation or any other constructive
contribution.

A contributor is self-identifying and has limited access to project coordination tools.
For example, they may have write access to community wiki pages, authoring (but not reviewing)
access for the projects issue tracker and full access to the communities’ discussion channels.
However, a contributor does not have the ability to make changes directly to releasable
materials, such as formal documentation and code.

### User

All software from the .NET foundation is open source. This means that anyone can use,
share, modify and study it. All projects should actively welcome feedback from our users.
Without users our projects a merely digital data stored in the cloud.

### Governance Matrix
A governance matrix provides an "at a glance" summary of governance model employed by the
project.

For example, the following matrix represents a project in which there are a number of project
maintainers who have partial write access to the release repository. Users in this project
need to register in some way to get access to anything other than the releasable materials
(such as by signing up for a GitHub account) but once they have registered they are considered
potential contributors and have full read/write access to those non-releasable materials.
Only the project lead has full read/write access to all materials.

|                    | Releasable         | Non-Releasable |
| ------------------ | ------------------ | -------------- |
| Project Lead       | Read/Write         | Read/Write     |
| Project Maintainer | Read/Partial Write | Read/Write     | 
| Contributor        | Read               | Read/Write     | 
| User               | Read               | None           |

A more complete version of this matrix can be provided that breaks down each of the types
of nonreleasable materials. This allows us to be more expressive. For example, in the matrix
below we see that the contributor is able to submit issues and read other peoples issues, but
does not have full control over

|                    | Releasable         | Issues              | Wiki       | Forum      | PR's       | 
| ------------------ | ------------------ | ------------------- | ---------- | ---------- | ---------- |
| Project Lead       | Read/Write         | Full                | Full       | Full       | Full       | 
| Project Maintainer | Read/Partial Write | Read/Write          | Full       | Full       | Read/Write | 
| Contributor        | Read               | Read/Submit/Comment | Read/Write | Read/Write | Read/Write | 
| User               | Read               | Read                | Read       | Read       | Read       |   

### Decision Making
There are two levels of decision making in a typical .NET foundation project. The first is
strategic and the second is tactical. Strategic decisions are focused on the long term direction
of the project. Tactical decisions are focused on implementation details. Generally speaking
strategy is defined by project leads, with support from project maintainers, while tactics are
defined by project maintainers with support from contributors.

Contributors can influence the tactical direction of a project through positive contribution
to the project. However, they do not have any authority over the project. Some projects will
reward valuable contributors with project maintainer status. The process for moving from one
role to another will be defined in the projects bylaws.

Decision making is always consensus based, however, this does not mean that a project needs to
demonstrate consensus through endless rounds of voting. In fact the common practice is for project
maintainers to track consensus within the community and to act in the best interests of the community
at all times. It is assumed that the absence of any objection to a maintainers actions is a sufficient
demonstration of consensus.

When an objection is raised a formal process of conflict resolution is triggered. This conflict resolution
varies from project to project and is defined in a projects bylaws, but it is invariably drawn from
common processes found in open source projects.

Conflict resolution is easiest in a project which has just one project lead. This model is commonly known
as a Benevolent Dictatorship. In such a model whatever the project lead decides is the best decision for
the community as a whole is the decision that will be taken. Where there are multiple Project Leads
exist there will likely be discussion with the intent of reaching consensus. If consensus proves elusive
a vote may break the deadlock. Another possible model is a combination of these two approaches, in this
situation the existence of an Original Contributor role may mean that the Original Contributor has a veto
over any decision.

The possibilities are endless, but it is expected that a small number of common practices will emerge
amongst .NET Foundation projects as the Foundation and the community matures.
 
 