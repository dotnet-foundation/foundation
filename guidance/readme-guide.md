# Crafting a good README
README files are very important in welcoming people to your open source
project for the first time. When someone discovers your code, the README.md
file in the root of the repository is the first thing that they will see
there. It is worth spending some time on it to make sure it has relevant
information to your audience and is kept up to date.

Remember that often your project is targeted at fellow developers and
developers love code. If your project is a library then show some quick
[syntax highlighted](https://help.github.com/articles/creating-and-highlighting-code-blocks/)
examples of how to call your project. Ideally link to some examples in your 
/Documentation folder for more information. A couple of informative Images can
also very useful.

If you have lots of information for a particular topic then it is good to split that
out into a seperate file in your /Documentation folder with a link in the README. 
But you should make sure you have the following areas referenced in your README. 

 - A one paragraph summary of your project
 - The status of the project (i.e. shipping / used in production / 
   experimental / sample / documentation / orphaned or superseeded etc)
 - The current CI Build Status with a red/green badge linking to publicly
   accessible build results.
 - Details description of the project, what problem it solves and why they
   should use it.
 - How do you install and use your code?
 - Any related projects that the user should know about. If your project is 
   similar to another open source project that is popular then how does your
   project solve the problem differently.
 - How to contribute to the project or a link to the CONTRIBUTE.md
 - Information on how to get started as a developer, information on Gitter, IRC, mailing list etc
 - How to provide feedback (Issues, User Voice, Forums etc)
 - License type and link to the project LICENSE
 - High level road map or link to roadmap documentation / open issues

### Code of Conduct
The .NET Foundation has adopted the [Contributor Covenant](https://dotnetfoundation.org/code-of-conduct)
You can read [more guidance on the Code of Conduct here](be-nice.md). However, it is
good practice to include the following text somewhere appropriate in your README.

 ```
This project has adopted the code of conduct defined by the Contributor Covenant to clarify expected behavior in our community.
For more information see the [.NET Foundation Code of Conduct](https://dotnetfoundation.org/code-of-conduct). 
 ```

### .NET Foundation Pointer
As .NET Foundation projects can be located across a number of different locations
and organization on GitHub, if possible your project can also include a link back
to the .NET Foundation website to help people discover other projects in the foundation
as well as learn more about our joint goals.  The following simple MarkDown at the 
end of your README is more than enough.
 ```
### .NET Foundation

This project is supported by the [.NET Foundation](https://dotnetfoundation.org).
 
 ```
