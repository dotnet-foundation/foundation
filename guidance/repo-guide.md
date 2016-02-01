# Repository Layout Guidance

This guidance is aimed at helping ensure people can navigate your project
source code easily and have a good experience when browsing and contributing
to your project.

Your repository should contain the following files in the root folder

 - LICENSE (or LICENSE.txt / LICENSE.md) - Always provide a full copy of the open source
   license associated with the project. At the top of the license file you should have
   the project copyright statement, i.e.
```
           Copyright (c) .NET Foundation and Contributors
           All Rights Reserved
```
 - [*README.md*](readme-guide.md)
 
 - *.gitignore* - To configure which files should not be checked in to version
   control (see the [Visual Studio template](https://github.com/github/gitignore/blob/master/VisualStudio.gitignore))
   
 - *.gitattributes* - Specify file ending conversion used and other common configuration parameters for your repo

 - *CONTRIBUTING.md* - Details on how to contribute to the project, what coding standards to use
   what the criteria are to decide if a pull request will be accepted, 
   how to build and test, how to sign the CLA,
   how to log a good issue / bug etc. Note that this information
   may be in the README.md but if it is in a seperate file called
   CONTRIBUTING.md then a link will be displayed when someone
   created a new issue or PR against your project.
   
 - *NOTICE.md* - _optional_ If the project contains and third party open source code
   then full details of that along with a full copy of the associated
   open source license should be provided.
   
 - *Documentation/* - Is is a good practice to include project documentation in 
    MarkDown format and have a link to it in the README. If included
    with the source code then place in a folder called "Documentation"
    with a capital D so that it appears towards the top of the
    directory structure when browsing in GitHub.
    Note that storing documentation in a repo means
    that anyone can contribute to that documentation and you can
    use Pull Requests to review / discuss changes. For many projects
    a documentation repo or folder works better than a GitHub Wiki.
 
You should set up alerts so that you get notified when someone creates a new issue
or submits a pull request so that you can respond quickly with feedback.
