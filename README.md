✨ Note: This is an OpenSource Web Application for <a href="https://1alnoory.github.io/476_Website/">LINK</a>
<img src="images/burgreza.png" alt="Logo of the project" align="right"> 

# 🍔 Burgeraza  &middot; [![Build Status](https://img.shields.io/travis/npm/npm/latest.svg?style=flat-square)](https://travis-ci.org/npm/npm)  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 

> The system that we will develop is an open source and free system, I mean that users can download it completely with the code.
> The system is a website for a restaurant that serves fast food, for example, burgers, french fries, and others.
> Users can go to the site and order through it.

# 💥🔥 The Project is Free and OpenSource
Open-source restaurant ordering and management system that is both powerful and simple to use
Note: Developed under the terms of the GNU License, this system is free open-source software. Participation is open to everybody.


There are some limitations which are:<br>
1- The system will be made using (HTML,CSS,PHP,MYSQL,JS).<br>
2- The site will be accessed by users, restaurant owners, developers, and restaurant employees.<br>
3- The project will be completed two months after the start date.

# But first look around 
There are different projects similar to our site But we will definitely work on more and new features as we mintiend in our mission that were not available on such sites, and this is what will make us the best.
here you will find other similar projects https://github.com/1Alnoory/Burgeraza/blob/main/List%20of%20related%20projects
 

# Starting from What You Have
Burgeraza Restaurant Services System should be translated into a free and open-source system, based on the founders of the Burgeraza system, which was developed for the ITCS333 Internet and Web development course. The system has been partially developed and programmed, and it is now time to portably package the code for it to run on any computing platform. "open source software", and give the exact license

The system's improvements will focus on inventory management, customer order, management reporting systems, and ranking in that order. By optimizing inventory management, marketing, and food preparation, the new system will be focused on enhancing customer service (keeping inventory stocked). 

# ⚙️ Technology Used
<ol>
    <il>HTML</li> <br>
 <il>CSS3</li> <br>
     <il>JavaScript</li> <br>
 <il>PHP programming language</li> <br>
 <il>MySQL Relational Database</li> <br>
    </ol>
    
# 🔺 Overall Project Summary
The project's goal is to create a user-friendly and smart food ordering experience for its users. We are working on incorporating various features into the project to make the entire process intelligent and simple.

# 🔺 Mission Statement <br> 
<span style="color:orange;">Burgeraza is an open-source tool that programmers can use to provide restaurant management software that aids in effectively running and managing a restaurant. It is software that used by restaurant uses to speed up the customer service process, and it allows a convenient increase in employee output and boosts overall restaurant productivity. Through its extensive capabilities, this program aims to provide customers with what they desire, shorten wait times, and maximize the potential of the restaurant. Moreover, the system enables quick and simple management of an online menu that clients can browse and use to submit orders with just a few clicks. It is designed for effective processing, restaurant staff uses these orders through an intuitive graphical interface rather than working manually. </span>

# If you wanted a fast summary of the software, we would offer you this list of the features and prerequisites. <br>
# 🧰 Features overview <br> 
- An easy-to-use, minimalist editor You can insert dynamic blocks of content into the editor. It is completely open-source and extensible.
- Visitors and Registered Users have access to all Categories and Food Items.
- Users can easily order from the website.
- Build any type of category, section, format, or flow to meet your specific requirements.
<br><br>

- Various payment processing options: You can take credit cards or mobile payments using payment software.
- Planned 24-hour technical support (planned).
- Access the program from any location and device. 
- Cloud archiving and Security of data (planned).
- Marketing features such as SMS, push and email notifications (planned)
<br><br>

- An easy-to-use interface The market's most user-friendly open-source interface.
- Sorting and Filtering Built-in sorting and filtering: easily manage thousands of entries.
- Admin can manage Admin, Categories, and Food Items.
- The administrator can also manage and track food orders and deliveries.
- Advanced reporting and data features Order management and monitoring features 


# 🧰 Requirements <br>
 • The project works on HTML, CSS, PHP, and MySQL on an Apache server using XAMPP. <br>
 • Atom or Visal Studio Code any version (any Text Editor you want)

# 💬 Development Status
 ACTIVE DEVELOPMENT ▶️ - middle of development of beta  <br>
*The system has reached the end of its basic design and initial functionality. <br>
*The project is still being put into action, though. However, the entire project will be attempted to be implemented by developers and other contributors who are willing to join us.  <br>
* Up until the completion of the project, each implemented function will be published to the repository. <br>

# 📜 License
This project is licensed under the GNU License see the https://github.com/1Alnoory/Burgeraza/blob/main/License.text file for details.


# 📖 How to Download and Run the Project on Your Computer?

1. Download and install XAMPP as a #prerequisite. <br>
<a href="doc:introduction" target="_blank">Download by clicking here</a>
2. Install any Text Editor you want (Visual Studio Code or Atom or Brackets)

# Installation
1.Download this project as a Zip file or clone it.
2.Transfer this project to the main directory.
Local Disk C contains the installation of xampp.

3. Go to the XAMPP Control Panel and launch 'Apache' and 'MySQL.'

4. Database Import

a. Launch phpmyadmin in your browser.
b. Create a database.
c. Import the SQL file included with this project.

5. Modify the settings
Navigate to the config folder and open the 'constants.php' file. Then modify the following constants.
```shell
<?php 
//Start Session
session_start();

//Create Constants to Store Non Repeating Values
define('SITEURL', 'http://localhost/food-order/'); //Update the home URL of the project if you have changed port number or it's live on server
define('LOCALHOST', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_NAME', 'food-order');
    
$conn = mysqli_connect(LOCALHOST, DB_USERNAME, DB_PASSWORD) or die(mysqli_error()); //Database Connection
$db_select = mysqli_select_db($conn, DB_NAME) or die(mysqli_error()); //SElecting Database 

?&gt;"><pre><span class="pl-ent">&lt;?php</span> 
<span class="pl-c">//Start Session</span>
session_start();

<span class="pl-c">//Create Constants to Store Non Repeating Values</span>
define(<span class="pl-s">'SITEURL'</span>, <span class="pl-s">'http://localhost/food-order/'</span>); <span class="pl-c">//Update the home URL of the project if you have changed port number or it's live on server</span>
define(<span class="pl-s">'LOCALHOST'</span>, <span class="pl-s">'localhost'</span>);
define(<span class="pl-s">'DB_USERNAME'</span>, <span class="pl-s">'root'</span>);
define(<span class="pl-s">'DB_PASSWORD'</span>, <span class="pl-s">''</span>);
define(<span class="pl-s">'DB_NAME'</span>, <span class="pl-s">'food-order'</span>);
    
<span class="pl-s1"><span class="pl-c1">$</span>conn</span> = mysqli_connect(<span class="pl-c1">LOCALHOST</span>, <span class="pl-c1">DB_USERNAME</span>, <span class="pl-c1">DB_PASSWORD</span>) or die(mysqli_error()); <span class="pl-c">//Database Connection</span>
<span class="pl-s1"><span class="pl-c1">$</span>db_select</span> = mysqli_select_db(<span class="pl-s1"><span class="pl-c1">$</span>conn</span>, <span class="pl-c1">DB_NAME</span>) or die(mysqli_error()); <span class="pl-c">//SElecting Database </span>

<span class="pl-ent">?&gt;</span></pre></div>
```
6. Open the project in your browser now. It should work fine.

# How to contribute </a>
If you want to contribute, open a Pull Request and include a detailed description and screenshots of the changes,Thank you for considering contributing to Burgeraza!.

# Version Control & Bug Tracker Acccess
GitHub provides free public version control hosting for open source project.specifically, an online, publicly-accessible version
controlled repository, from which anyone can check out the project's materials and subsequently get
updates. A version control repository is a sign — to both users and developers — that this project is
making an effort to give people what they need to participate.While GitHub is not the only choice, nor even the only good choice, it's a reasonable
one for most projects.The same goes for the project's bug tracker. The importance of a bug tracking system lies not only in
its day-to-day usefulness to developers, but in what it signifies for project observers. For many people,
an accessible bug database is one of the strongest signs that a project should be taken seriously — and
the higher the number of bugs in the database, the better the project looks.

# 📩 Communication Channel
We have set up a communication group with the team members contributing to the project through the Google Group: burgeraza@googlegroups.com so that visitors can submit their comments, questions and other things. <br> 
or you can contact with us by email: burgeraza.10@gmail.com

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

# 📌 FAQs
Here are answers to questions are frequently asked. If you have a question not addressed here plase contact us.
https://github.com/1Alnoory/Burgeraza/blob/main/FQA%20maintaining.md
# 📹 Demos, Screenshots, Videos, and Example Output
![](images/Home1.PNG)
<p align="center"> <strong> Home page-1</strong> </p>
<br><br>

![](images/Home2.PNG)
<p align="center"> <strong> Home page-2</strong> </p>
<br><br>

![](images/Menu.PNG)
<p align="center"> <strong> Menu page </strong> </p>
<br><br>

![](images/Profile.PNG)
<p align="center"> <strong> Profile page </strong> </p>
<br><br>

![](images/SignIn.PNG)
<p align="center"> <strong> Sign In page </strong> </p>
<br><br>

![](images/SignUp.PNG)
<p align="center"> <strong> Sign Up page </strong> </p>
<br><br>

![](images/StaffView.PNG)
<p align="center"> <strong> Staff View page </strong> </p>
<br><br>

![](images/MyOrders.PNG)
<p align="center"> <strong> My Orders page </strong> </p>
<br><br>

![](images/HistoryOrders.PNG)
<p align="center"> <strong> History Orders page </strong> </p>
<br><br>

![](images/AdminView.PNG)
<p align="center"> <strong> Admin View page </strong> </p>
<br><br>

![](images/About1.PNG)
<p align="center"> <strong> About-1 page </strong> </p>
<br><br>

![](images/About2.PNG)
<p align="center"> <strong> About-2 page </strong> </p>
<br><br>

![](images/About3.PNG)
<p align="center"> <strong> About-3 page </strong> </p>
<br><br>

![](images/About4.PNG)
<p align="center"> <strong> About-4 page </strong> </p>
<br><br>

# Code of Conduct
In order to ensure that the Burgeraza community is welcoming to all, please review and abide by the https://github.com/1Alnoory/Burgeraza/blob/main/Code%20of%20conducts
 
# 🔗Hosting
>Hosting is the place where the project will be placed so that everyone can access it, so we will put our project in GitHub because it is an open source project and free so that everyone can access it from users and developers to give us feedback.<br>
so we choose GitHub to put the project on it: https://github.com/1Alnoory/Burgeraza

# User Classes and Characteristics

Our system has three types of users:
1. Customer Group
Customers interact directly with our system to place orders, modify orders, receive bills, and provide feedback. We do store minimal of the customer information in our system. Customers place orders, and then the other series of events begin. 
<br>

2. Chefs do not interact with the system. 
They only need to look at the dishes in their queues and prepare them accordingly. The database stores the chef's name, address, specialty, and so on.
<br>

3. Admin
The administrator's job is to manage the inventory and other menu and chef information in the system.
<br>


# 💻 About us
This system is an effort to reduce some common issues that arise during the business for this type of company. We are providing this software without warranty; use as desired, modify as necessary and don't forget to contribute to the project's improvement if you find any bugs. <br>
There is still much to be done, but with enough time, we think we can develop a standard piece of software for this kind of business. Although this piece of software is not even close to being competitive with those used in the industry, it offers a modest alternative for those who cannot afford the high costs of proprietary software. Enjoy.


# 👩‍💻 Contributors
<table>
<tr>
<td><b>UserName in GitHub</b><td>
<td><b>GitHub link account</b><td>
</tr>
<tr>
<td>@1Alnoory<td>
<td>https://www.github.com/1Alnoory<td>
</tr>
<tr>
<td>@WordRashed<td>
<td>https://github.com/WordRashed<td>
</tr>
<tr>
<td>@Zain111ab<td>
<td>https://github.com/Zain111ab<td>
</tr>
<tr>
<td>@AALA-17<td>
<td>https://github.com/AALA-17<td>
</tr>
</table>

Here more information about all Contributors in 🍔 Burgeraza system👇🏻<br>
https://github.com/1Alnoory/Burgeraza/blob/main/Contributors.md

# 👨‍💻 Technical Knowledge & Experience
Design and creation of desktop, mobile, and web applications
creation and application of machine learning and deep learning models
Python scripting, automated browsers, and web scraping

# 😁 Contributions Welcome
![](images/Capture.PNG)
<br><br>
If you find a bug in the code or have suggestions for improvements, please submit a pull request.
