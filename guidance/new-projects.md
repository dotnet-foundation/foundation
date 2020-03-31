# New Project Checklist

Participation in the .NET Foundation exposes your project to the wider world of .NET developers
and helps you to build a better community. If you would like to learn a bit more about what
joining the .NET Foundation involves then please see the guidance below. To apply for membership,
[fill out a new project application](https://github.com/dotnet-foundation/projects/issues/new?assignees=&labels=project+application&template=application.md&title=).

When projects join the foundation, there are two ways that they can come in.

 - **License** - The first is for the maintainers of the project to sign a
   contribution agreement licensing
   the code to the .NET Foundation under the terms of the open source license and
   confirming that they have the rights to do that. This type of agreement is most
   common when projects have had a long history of being open source, with lots of
   contribution from many different individuals and the project community now wish to
   now be supported by the .NET Foundation.
   
 - **Assignment** - The other is to assign the copyright of the project to the .NET Foundation and
   confirm that they have the rights to do this. This type of agreement is usually
   used when releasing something as open source for the first time or by a project
   that has had a high degree of control over contributions to the existing project 
   in the past.  

When you contact the .NET Foundation, they will help you decide which type of
agreement is most likely to suit you based on your needs.

When on-boarding a project into the .NET Foundation, we typically go through
the following steps to make sure everything is set up properly.  Feel free
to copy the checklist below into a new issue in your project to make sure
we remember to do everything or create individual issues for the items
that are currently missing.

 ```
Title: On-Board project to the .NET Foundation

We're getting ready to bring the project into the .NET Foundation, but before we
do we need to do the following:

## Getting into the .NET Foundation
- [ ] Make sure the project has a good name that is easy to remember and 
  spell. Check that it doesn't [conflict with another existing project](http://ivantomic.com/projects/ospnc/)
- [ ] Make sure the people involved in the project want to join the .NET Foundation
- [ ] Make sure the project has a clear understanding about how it accepts contributions and the process
      it follows when selecting new committers to the project.
- [ ] [Register an interest](https://dotnetfoundation.org/get-involved) in joining the .NET Foundation
- [ ] Work with the .NET Foundation to fill out an On-Boarding Questionaire
- [ ] .NET Foundation sends out completed questionaire to .NET Foundation Advisory Council for comments
- [ ] .NET Foundation Executive Director submits new project proposal to the .NET Foundation Board
- [ ] Configure a CI build for the project and ensure build status badges are available from the README

## Once accepted into the .NET Foundation
 - [ ] Sign the contribution / assignment agreement
 - [ ] Agree a date to move into the .NET Foundation
 - [ ] Prepare a guest blog post announcing the move on the .NET Foundation Blog
 - [ ] Read the [code of conduct](https://dotnetfoundation.org/code-of-conduct), 
       [link to it in your code](be-nice.md) and 
       understand what to do if you are concerned about any behaviour or have
       concerns reported to you.
 - [ ] Tell the world we have joined!
 - [ ] Get CLA Automation enabled to ensure contributors can easily sign the 
       [Contribution License Agreement](https://github.com/dotnet/home/blob/master/guidance/net-foundation-contribution-license-agreement.pdf)
 - [ ] Send a PR to add the Project into the .NET Foundation 
       [list](https://github.com/dotnet/home/tree/master/projects)
 - [ ] Ensure the repo contents are up to date with [.NET Foundation guidance](https://github.com/dotnet/home/blob/master/guidance/repo-guide.md)
 - [ ] Review the [README guidance](readme-guide.md) and update if necessary
 - [ ] If applicable [update the LICENSE file](copyright.md) to show Copyright has been assigned to the .NET Foundation
       and look to update any file headers.
 - [ ] If applicable, update any copyright statements in websites owned by the project to reflect 
       assignment to the .NET Foundation
 - [ ] If applicable, update any websites associated with the project to include
       "Supported by the <a href="https://dotnetfoundation.org">.NET Foundation</a>" or
       similar link back to the .NET Foundation in the footer. If applicable, please
       include image links from [our swag repo](https://github.com/dotnet/swag). (We think a link in the footer using the horizontal logo looks very nice.)
 - [ ] [Sign up for Project Leader news](http://eepurl.com/bOCfJP)
 - [ ] Configure any resources requested from the .NET Foundation (SSL Certs, Code Signing,
       Secret Management, Build Servers etc)
 ```



