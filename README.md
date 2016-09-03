# Principles of Developer-Centric Software

In the world of digital technology, one of the most talked about topics is User Centric Design. The idea is that digital technology should serve users, and everything that can be done to improve the user experience should be done. Too much noise can lead to a bad user experience, while not enough direction can force users to leave.

In tech, we often talk about users as the reason for everything we do. Users are our customers, whether they're purchasing a product or service, consuming content, or managing data through user interfaces. They are external as well as internal.

But rarely do we consider software developers "customers."

I believe that's largely because software developers often determine the destiny of the software they create and typically prioritize customer needs over their own.

The end result is a mix of poorly documented software, a lack of well-thought-out organization, and significant knowledge in the hands of a relatively small number of software developers.

It's up to software developers to do the work of making the software they produce well-documented, organized, readable, and easily understood. Software developers should ask themselves: if all of us were to leave this project, would the newcomers be able to easily continue it without significant disruption to its evolution?

With that in mind, here are some principles to follow to keep your software developer-centric.

## 1. Stick to an enforced coding style.

As developers, you should meet to discuss coding styles and patterns you want to follow. This will make code look consistent across your codebases. Make sure you have something that will actually enforce those styles and patterns to prevent diverging away from the original agreement. If possible, meet regularly to discuss potential changes that could improve readability.

## 2. Make your code readable.

That means naming things with meaning. If you're creating a class, function, or variable, make sure it's easy to understand what it's supposed to create, do, or hold just by it's name. Give meaning to your directory structure by associating sub-directories and files with pages, components, or units on your application. And remember, README files aren't just for projects, so use them inside your projects to document code.

## 3. Modularize.

Bundle things together in discrete modules when it makes sense. This includes test files. And avoid having files with more than 500 lines of code. If something makes sense to be on its own file, move it to its own file.

## 4. Provide usage examples.

When creating classes and functions, provide examples of how they can be used along with their definitions. When appropriate, describe the inputs and outputs. Create style guides for UIs and use tools like Swagger for documenting REST APIs. 

## 5. Use READMEs as your project's hub.

Include links to further documentation like Swagger, style guides, drawings and diagrams, contact information, build and deployment details, how to access the apps, etc. If you need to break up your README, there's no reason why you can't create additional .md files and link to them in your README.

## 6. Draw concepts and workflows.

As you build out your project, take some time to think about the complexity of components, services, and workflows. If the complexity is high, consider using tools like Google Drawings to draw diagrams that conceptualize them. Drop those images into README files alongside the code, and link to them when appropriate from your README.

## 7. Have regular learning sessions.

You will find that as you build your project, certain people will start to accrue specific knowledge others won't have. Learning sessions are opportunities to disseminate that knowledge. Make an effort to have them on a regular basis.

## 8. Avoid dependencies.

By this, I don't necessarily mean code dependencies, though you should always consider the trade-off with using a third-party dependency vs. building your own code to meet your need. I'm talking about dependencies with other teams or services you have little control over. If those dependencies are not reliable, don't wait for them to become reliable. Build an easy way to mock that dependency to prevent developers having to deal with it when it's not reliable.

The last thing you want is for a new team to come in and not know they need to talk to another team to even start local development.

## 9. Encourage feedback.

Create opportunities for feedback, whether it be anonymous (for larger teams) or not. And don't just collect feedback. Make it available, review it, and act on the feedback that makes sense to act on.

## 10 . Learn from others.

Constantly be on the look out for what others are doing. When possible, share your own learnings with the public at large, and share what others share with your own team.
