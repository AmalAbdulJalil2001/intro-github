
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
