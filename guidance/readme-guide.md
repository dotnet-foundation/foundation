# Crafting a good README

README files are very important in welcoming people to your open-source
project for the first time. When someone discovers your code, the README.md file in the root of the repository is the first thing that they will see.  It is worth spending some time on it to make sure it is up to date and contains information relevant to your audience.

Remember that often your project is targeted at fellow developers and developers love code. If your project is a library then show some quick [syntax highlighted](https://help.github.com/articles/creating-and-highlighting-code-blocks/) examples of how to call your project. Ideally link to some examples in your /Documentation folder for reference. A couple of informative images can also be very useful.

If you have a lot of information for a particular topic then it is advisable to create a separate file in your /Documentation folder and link to it the README. However, your README should contain at least the following sections.

- A one paragraph summary of your project.
- The status of the project (i.e. shipping / used in production / experimental / sample / documentation / orphaned or superseeded etc).
- The current CI build status with a red/green badge linking to publicly accessible build results.
- A detailed description of the project, what problem it solves and why it should be used.
- How to install and use your code.
- Any related projects that users should know about. If your project is similar to another popular open-source project describe how your project is different.
- How to contribute to the project or a link to the CONTRIBUTE.md.
- Information on how to get involved as a developer (e.g. Gitter, IRC or mailing list links).
- How to provide feedback (Issues, User Voice, Forums etc).
- License type and link to the project's LICENSE file.
- High level road map or a link to the roadmap documentation / open issues.

### Code of Conduct

The .NET Foundation has adopted the [Contributor Covenant](http://www.dotnetfoundation.org/code-of-conduct) You can read [more about the Code of Conduct here](be-nice.md). However, it is good practice to include the following text somewhere appropriate in your README:

```text
This project has adopted the code of conduct defined by the [Contributor Covenant](http://contributor-covenant.org/)
to clarify expected behavior in our community.
For more information see the [.NET Foundation Code of Conduct](http://www.dotnetfoundation.org/code-of-conduct). 
```

### .NET Foundation Pointer

As .NET Foundation projects can be distributed across a number of different repositories and organization on GitHub, you can also include a link back to the .NET Foundation website in your project to help people discover other projects in the foundation as well as learn more about our joint goals. The following simple MarkDown at the end of your README is more than enough.

```md
### .NET Foundation

This project is supported by the [.NET Foundation](http://www.dotnetfoundation.org).

```
