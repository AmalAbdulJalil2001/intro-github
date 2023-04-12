# ⌨ Developer Guidlines
Coding Guidelines for Developers

This ongoing document offers helpful advice for software developers who create or contribute to the system. The recommendations cover:

* Documentation and coding style
* Links to codes of conduct
* Links to codes of conduct
* how tasks are ultimately completed and how developers interact with users and one another
* refer to https://github.com/1Alnoory/Burgeraza/blob/main/Code%20of%20conducts

Here every consideration we've listed allows the technical team to collaborate with the executive team to make decisions and guide the process to success. 

* If you only write code on occasion or outside of the Burgeraza system developers' team, you should read the entire document at least once, but there is no expectation that you will remember everything.

* If you are a member of the Burgeraza system development team, you should read these guidelines.
 
### Developers’ Interaction
All members must adhere to the community's guidelines and documentation.
Developers should reach each other through email or MS Teams.
<br> 
In any case, these are *guidelines* rather than hard rules. We believe they would help to streamline our workflow, improve teamwork, and benefit both ourselves individually and the "products" that we create as developers.

The Burgeraza system developers would be delighted to answer any questions you may have about the contents of this document.

Remember, the goal of these guidelines is to improve everything we produce so that we can say, "I was a part of that!" We mustn't lose too much momentum in trying to follow these guidelines. We need to review them if you believe they are slowing things down too much. These are not unchangeable facts.

# Code Format
Each line should contain only one code command.
Each code block should be separated from other code blocks by a two-line margin.

# Code Scope
* Default constructors for classes with only default constructor values.
* "final" keyword unless it is for constants.

# Other code-related information:
Variable names should be meaningful and relevant to each variable's use.
Each group/block of code should have a brief comment explaining its purpose.

# More Considerations when writing code <br>
> Developing secure software
While it is not always the most exciting part of writing code, it is critical to consider the security risks associated with a software project to avoid costly patches and, perhaps more importantly, reputation damage. Security risk analysis should begin early in the project and continue until the project is completed.

The security risks will vary greatly from project to project, but general guidelines are: * Educate yourself, and research what security risks are associated with the various components of your project.
* Don't rely solely on out-of-the-box software and default configurations, such as open-source libraries, AWS services, and so on.
Malicious software may be present, and default configurations usually prioritize simplicity over security.


### Which programming language should I use?

We don't have any _strict_ rules about what programming languages Burgeraza software should be written in. Keep in mind, however, that any software you create will need to be maintained by yourself and your colleagues (both current and future), and we don't want to end up with unmaintainable software. But currently we are using html,css,js and we open the door for any changes to improve our project

### Code comments

The code should be commented to explain *why* it does what it does. What it does should ideally be obvious from the code itself. If the code is cryptic and cannot be easily simplified, explanations may be required. A good remark clarifies the intent.

### Readability

Use consistent indentation.
Make use of horizontal whitespace (code paragraphs/blocks). There is no advantage to compressing code into as few lines as possible.
If at all possible, avoid long lines (more than 75-80 characters).

# Using the issue tracker
The issue tracker is the preferred channel for reporting bugs, requesting features, and submitting pull requests.

If your issue is already present, make relevant comments and use Github's "reactions" feature instead of a "+1" comment. 
- 👍  upvote
- 👎 downvote

# Feature requests
Requests for new features are welcome. Please take a moment to determine whether your idea fits within the scope and goals of the project before submitting a feature request. It is up to you to make a compelling case for the feature to the project maintainers. Please include as much information and context as possible.


# Requests for pulls
- Excellent contributions include good pull requests for patches, improvements, new features, and so on. They should, however, keep their scope in mind and avoid unrelated commits.

- Please ask a maintainer before embarking on any significant pull request if the scope of the pull request is reasonable to merge into the project. Otherwise, you risk wasting a lot of time on something that isn't relevant to the project's goals.


- Please include the intent for which you'd like the changes to land when creating a pull request. By default, we request that you pull from the master branch. 

### Bug Report:
Issues to consider: 
* Title: Keep it brief and specific. Explain in detail what the bug is.
* Summary: Include where, when, and how the bug occurred if the title is insufficient.
* Visual evidence: A screenshot or video helps the developer understand the problem more quickly.
* Expected vs. actual result: Keep it brief and to the point.
* Reproducible steps: Include the steps that caused the bug.
* Environment: Include important information such as browser, operating system, screen size, and zoom level.
* Console log: Determine the source of the problem.
* Source URL: To assist the developer in locating the issue more quickly.
* Severity / priority: The level of impact on your product and how quickly it should be investigated.
* Reporter name, assignee, due date, and customer/user conversation
Keep in mind that adding unhelpful information will make it more difficult to identify the problem. Avoid making duplicates.  Once you've gathered all of this information and you need more help, compile it into a report and email it to burgeraza.10@gmail.com
