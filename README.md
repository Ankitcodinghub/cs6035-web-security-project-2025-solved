# cs6035-web-security-project-2025-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs6035-web-security-project-2025-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127573&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6035 Web Security  Project 2025 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<strong>BACKGROUND:</strong>

Welcome to the GA Tech bookstore website. It’s a place where you can read and review all of the classics. The creators of the website were pretty junior but ambitious. They created the website in only 2 days! They knew a few things about security and did their best but left some vulnerabilities behind. Your job is to seek these out and find the problems.

<strong>SETUP:</strong>

To get set up for the flags, carefully follow the steps below. Log into the VM with the websec user.

The password should be in Canvas.

Run this at the terminal to start the Bookstore Website

./StartContainer.sh

<ul>
<li>Throughout the project you should only <strong>use Chrome</strong>. No other browsers are supported for the student grader. Don’t attempt to update/reinstall the Chrome Browser.</li>
<li>Navigate to this URL using Chrome within the VM to access the Bookstore Website: <a href="http://localhost:7149/">http://localhost:7149/</a></li>
<li>There is one registered user in the database. You can log in as this user as needed. You can log out by closing the Chrome window.</li>
<li>GTID: Your assigned GTID# (e.g. 923456789)</li>
<li>Note: This field will remain the same for the entire project.</li>
<li>See the <a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/RequiredReading">Required Readin</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/RequiredReading">g</a> page to get your GTID.</li>
<li>Username: <strong>ilovetoread</strong></li>
<li>Password: <strong>TheGreatGatsby123</strong></li>
<li>The Bookstore Website uses a database to store data. In some cases you may find the need to reset this database. There are also times when the student grader will reset the database before running your exploit. To do this manually navigate to this URL and click the button to reset the database:</li>
<li><a href="http://localhost:7149/database">http://localhost:7149/database</a></li>
</ul>
<strong>TESTING:</strong>

You will need to execute a StudentGrader script to test your exploits for all flags. The StudentGrader is a <strong>script that will</strong>

<ul>
<li>Launch the html file that you craft for your flag.</li>
<li>On some flags the Bookstore Database will be reset automatically.</li>
<li>Use the Selenium Chrome Driver to test and assert that your exploit worked correctly.
<ul>
<li>Here is a link just in case you’re interested in learning more about the Selenium Chrome driver. Understanding this is not required to be successful on this project.</li>
<li><a href="https://chromedriver.chromium.org/getting-started">Chrome Driver Docs</a></li>
</ul>
</li>
<li>If successful, it will return your flag.</li>
</ul>
Run this at the terminal to test your exploit for a flag

./StudentGrader.sh –flag X –gaTechId Y –filePath Z

Here are the valid parameters for the StudentGrader script

You will be learning about modern web based security vulnerabilities in this project. A majority of the attacks are based on the <a href="https://owasp.org/www-project-top-ten/">OWASP Top 10</a> list which is produced and updated every few years.

In particular we will cover these learning topics:

<ul>
<li>Basic web technologies, HTML, CSS &amp; JavaScript</li>
<li>The HTTP protocol</li>
<li>XSS (Cross-Site Scripting) Attacks</li>
<li>XSRF (Cross-Request Forgery)</li>
<li>SQLi (Sql Injection Attacks)</li>
<li>Mis-configuration of server side web servers</li>
<li>Client-side JavaScript library vulnerabilities</li>
</ul>
<strong>The final deliverables:</strong>

A single JSON formatted file will be submitted to Gradescope.

<strong>See </strong><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Submission.html"><strong>Submission Details</strong></a><strong> for more information.</strong>

<strong>Important Reference Material:</strong>

<ul>
<li><a href="https://en.wikipedia.org/wikiRepresentational_state_transfer">Representational State Transfer</a></li>
<li><a href="https://en.wikipedia.org/wiki/JSON">JSON</a></li>
<li><a href="http://eloquentjavascript.net/">Eloquent Javascript</a></li>
<li><a href="http://www.w3schools.com/html/html_forms.asp">HTML Forms</a></li>
</ul>
<strong>Virtual Machine:</strong>

<ul>
<li>Apple M1 based systems</li>
<li>You cannot complete this project on an M1 based system.</li>
<li>Intel/AMD x64 version</li>
</ul>
TABLE OF CONTENTS

<ul>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Background.html">Pro</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Background.html">j</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Background.html">ect Back</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Background.html">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Background.html">round</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag1.html">Fla</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag1.html">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag1.html"> 1</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag2.html">Fla</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag2.html">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag2.html"> 2</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag3.html">Fla</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag3.html">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag3.html"> 3</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag4.html">Fla</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag4.html">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag4.html"> 4</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag5.html">Fla</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag5.html">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag5.html"> 5</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag6.html">Fla</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag6.html">g</a><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag6.html"> 6</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Submission.html">Submission</a></li>
</ul>
<h1>Flag 1: Web Intro – 15 Points</h1>
You’ve stumbled upon a publicly available web page that is not finished. It seems like the developers are still working on it but somehow published it to production by accident. The page does not have a link in the main menu so the developers thought no one would find it. Challenge accepted!

<ul>
<li>This flag will introduce you to the very basics of web development technologies and tools for debugging. Specifically you’ll leverage these:</li>
<li><a href="https://www.w3schools.com/html/html_forms.asp">Html Forms</a></li>
<li><a href="https://www.w3schools.com/js/js_events.asp">JavaScript Events</a></li>
<li><a href="https://www.w3schools.com/cssref/css_selectors.php">CSS Selectors</a></li>
<li><a href="https://www.w3schools.com/js/js_cookies.asp">Cookies</a></li>
<li><a href="https://developer.chrome.com/docs/devtools/">The Chrome Developer Tools</a></li>
</ul>
Download the required starter template from the VM using Chrome here:

<ul>
<li><a href="http://localhost:7149/api/template/flag1">Fla</a><a href="http://localhost:7149/api/template/flag1">g</a><a href="http://localhost:7149/api/template/flag1"> 1 Template</a></li>
</ul>
To earn your flag you must alter the template so that it performs these steps when you open it in a browser or run it using the grader:

<ul>
<li>Find the Contact Us web page. Remember that you won’t find a link in the main navigation.</li>
<li>Now that you have the URL to the Contact Us web page you need to “fetch the server content” in the flag1.html file.
<ul>
<li>Double click to open flag1.html in Chrome</li>
<li>Launch the Chrome developer tools using the menu in Chrome</li>
<li>Do some independent research on how you may find and look at JavaScript code using the Chrome developer tools</li>
<li>Write some JavaScript code in your flag1.html file to load up the Contact Us page.</li>
</ul>
</li>
<li><strong>In the getStudentAnswers function, set </strong>var selectedReplyByValue = “Cell”;</li>
<li>In the getStudentAnswers function, write JavaScript code to programmatically fetch the following values and set them to the provided variables:
<ul>
<li>The value provided in the Organization text box</li>
<li>The value of the session storage with key = “contactedBefore”</li>
</ul>
</li>
<li>The Contact Us web page sets one or more cookies. Unfortunately, it won’t show up for you to access using JavaScript. That won’t stop you from learning the value. Use the Chrome Dev tools to search for http requests and find the cookie name and value set by the Contact Us web page. Assign these to the variables provided in flag1.html as hard-coded strings. Note: There may be more than one cookie so find the one that is actually set by the Contact Us page or simply try all values by trial and error.
<ul>
<li><strong>While copying the cookie Value make sure you have the Show URL-decoded option checked</strong></li>
</ul>
</li>
<li>Events are an extremely important concept to understand when working with websites. They allow you to execute code at a later time when something interesting happens.
<ul>
<li>Write code that will set the City text input to <strong>Seattle</strong> and the State text input to <strong>Washington</strong></li>
<li>Somehow delay this code so that it only executes when the submit button at the bottom is clicked.</li>
<li><strong>Note: We’re not asking you to click the button either using code or manually on the webpage.</strong></li>
</ul>
</li>
</ul>
<strong>HINTS:</strong>

<ul>
<li>Often times, websites will publish sitemaps that contain page URLs. Hint: find and inspect the sitemap contents.</li>
<li>Are you using AJAX to fetch server content? You’re headed down a wrong path. Examine ALL JavaScript available to the page and use this hint from above to continue forward: “fetch the server content”.</li>
<li>Use the Chrome dev tools to Inspect html elements. The “Elements” tab shows a graph of the entire html dom</li>
<li>The Network tab allows you to see the raw http requests between the browser and server</li>
<li>Do not hard code any values except the cookie name and value detailed above. We check for this in your file and it will fail the grader.</li>
<li>Getting Selenium errors about missing content? Try to open the file directly in Chrome and look for errors in the console.</li>
</ul>
<strong>FLAG TESTING:</strong>

To test your flag1.html file and receive the flag, run this command at the command line. Note: replace the <strong>gaTechId</strong> with your actual GTID.

./StudentGrader.sh –flag 1 –gaTechId 923456789 –filePath /home/websec/Desktop/flag1.html Your web output will look similar to this:

&nbsp;

<h1>Flag 2: XSS Part I – 20 Points</h1>
Congratulations, you’ve made it this far! Now you’ve noticed some strange behavior. You were experimenting with reviews and found you can post basic html tags and images in the reviews! The developers of the site wanted reviews to be a rich user experience and not just plain text. With great power comes great responsibility though. You’ve found a way to nefariously inject code that runs when any victim loads a page with your exploited review.

This flag will introduce you to the basics of XSS (Cross-Site Scripting) attacks. Specifically you’ll leverage these:

<ul>
<li><a href="https://owasp.org/www-community/attacks/xss/">OWASP XSS Pa</a><a href="https://owasp.org/www-community/attacks/xss/">g</a><a href="https://owasp.org/www-community/attacks/xss/">e</a></li>
<li><a href="https://owasp.org/www-community/Types_of_Cross-Site_Scripting">Types of Cross Site Scriptin</a><a href="https://owasp.org/www-community/Types_of_Cross-Site_Scripting">g</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cross-site_scripting">Wikipedia XSS Pa</a><a href="https://en.wikipedia.org/wiki/Cross-site_scripting">g</a><a href="https://en.wikipedia.org/wiki/Cross-site_scripting">e</a></li>
</ul>
Download from the WebSec VM the required starter template here:

<ul>
<li><a href="http://localhost:7149/api/template/flag2">Fla</a><a href="http://localhost:7149/api/template/flag2">g</a><a href="http://localhost:7149/api/template/flag2"> 2 Template</a></li>
</ul>
To earn your flag you must alter the template so that it performs these steps when you open it in a browser or run it using the grader.

<ul>
<li>Create a nefarious review for the book <strong>Hamlet</strong>:
<ul>
<li>The title of the review should be <strong>“I bet some cookies may be at the top”</strong></li>
<li>The rating should be <strong>3</strong></li>
<li>Recommended should be <strong>true</strong></li>
<li>The reviewer should be your <strong>GTID (ex: 923456789)</strong></li>
</ul>
</li>
<li>The review should contain a script that you craft. This script will execute anytime the review loads in a browser. It will execute for anyone and everyone, very dangerous! You are not a bad hacker out to make money so you only want to make an example and not do real damage.
<ul>
<li>The script must print out all of the site cookies to the user’s screen. To do this, your code must replace the text <strong>“Welcome to the Georgia Tech Bookstore. Here you will find the classics.”</strong> with the <strong>cookie contents</strong> <strong>(There could be one or more cookies that replace the text)</strong>.</li>
</ul>
</li>
</ul>
<h2>Site With Original Text</h2>
<h2>Site With Text Replaced</h2>
<ul>
<li><strong>Note: Your script must not change the structure of the “h5” tag. Only replace the text contained within the “h5” tag.</strong></li>
<li>After creating the review with the nefarious code, your file must redirect (load) the details page for <strong>Hamlet</strong>.</li>
</ul>
<strong>HINTS:</strong>

<ul>
<li>Tackle the problem in small parts and then layer in complexity. You can test some of your code exploits directly in the bookstore website before compiling it into the template</li>
<li>There are some features in React that should set off red flags. Ex: https://legacy.reactjs.org/docs/dom-elements.html#dangerouslysetinnerhtml</li>
<li>Use the Chrome dev tools to watch what happens outside of an attack. The Network tab should give clues. The “Preserve Log” checkbox is your friend.</li>
<li>You will need to write JavaScript. Some of this code will execute immediately in your flag2.html file while the remaining part of the code should not be executed but instead be injected into the review somehow to run later.</li>
<li>The developers knew about XSS and put some protections in place. It would be helpful to find and understand this as you may need to defeat it.</li>
<li>You may need to reset the database from time to time to start with a clean slate. Be sure to follow the steps in the Setup section above to complete this.</li>
</ul>
<strong>FLAG TESTING:</strong>

To test your flag2.html file and receive the flag, run this command at the command line. Note: replace the <strong>gaTechId</strong> with your actual GTID.

./StudentGrader.sh –flag 2 –gaTechId 923456789 –filePath /home/websec/Desktop/flag2.html

<strong>Note: The grading script will reset the database before it executes your file. Be prepared as any data you have created will be lost.</strong>

Your web output will look similar to this:

<h1>Flag 3: XSS Part II – 15 Points</h1>
Malicious user input can be provided using the same techniques, but through different attack vectors. You’ve already persisted malicious data in a review and want to see if there are any other areas of the site that are susceptible to data manipulation. Using your newly acquired XSS skills, you go hunting for more ways to perform this method of attack.

In order to successfully exploit another XSS attack, you will need to figure out another way the site accepts user input and employ a similar technique to perform what’s called a reflected XSS attack. This means the XSS code does not reside in the webpage and does not persist, but is malicious code input in the request and returned in the response. You notice there is a page that allows the user to search for a book and wonder if this page can be exploited.

Your goal is to display a javascript alert containing the text CS6035 on the search page.

You can use the same XSS resources from the previous flag in addition to reflected XSS resources:

<ul>
<li><a href="https://portswigger.net/web-security/cross-site-scripting/reflected">PortSwi</a><a href="https://portswigger.net/web-security/cross-site-scripting/reflected">gg</a><a href="https://portswigger.net/web-security/cross-site-scripting/reflected">er Reflected XSS</a></li>
<li><a href="https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/01-Testing_for_Reflected_Cross_Site_Scripting">OWASP Reflected XSS</a></li>
</ul>
Download from the WebSec VM the required starter template here:

<ul>
<li><a href="http://localhost:7149/api/template/flag3">Fla</a><a href="http://localhost:7149/api/template/flag3">g</a><a href="http://localhost:7149/api/template/flag3"> 3 Template</a></li>
</ul>
To earn this flag by performing the following steps:

<ul>
<li>Examine the search page.</li>
<li>Find a way to pop up a javascript alert containing the text <strong>CS6035</strong>.</li>
<li>Add your code to the input of the flag 3 template.</li>
<li>Launch the template which should auto-submit to the search page and perform the attack.</li>
</ul>
<strong>HINTS:</strong>

<ul>
<li>The search result may be returned after the page is loaded which means you may not be able to inject a script that relies on the loading phase of the document object model (DOM). Find other elements and script techniques to inject after page load.</li>
</ul>
https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag3.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1/2 2/17/25, 2:35 AM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 3 | CS 6035

<strong>FLAG TESTING:</strong>

To test your flag3.html file and receive the flag, run this command at the command line. Note: replace the <strong>gaTechId</strong> with your actual GTID.

./StudentGrader.sh –flag 3 –gaTechId 923456789 –filePath /home/websec/Desktop/flag3.html Your web output will look similar to this:

<h1>Flag 4: CSRF – 20 Points</h1>
Congratulations on reaching this stage! You’ve already navigated through various challenges, and now it’s time to delve into the intricacies of Cross-Site Request Forgery (CSRF) attacks. CSRF is a type of attack that tricks a user into submitting a request to a web application where they are authenticated without their knowledge or intent. This can lead to unauthorized actions being performed on behalf of the user.

For further exploration and a deeper understanding of CSRF and its prevention, consider the following resources:

<ul>
<li><a href="https://portswigger.net/web-security/csrf">Portswi</a><a href="https://portswigger.net/web-security/csrf">gg</a><a href="https://portswigger.net/web-security/csrf">er CSRF</a></li>
<li><a href="https://owasp.org/www-community/attacks/csrf">Cross Site Request For</a><a href="https://owasp.org/www-community/attacks/csrf">g</a><a href="https://owasp.org/www-community/attacks/csrf">er</a><a href="https://owasp.org/www-community/attacks/csrf">y</a> <a href="https://owasp.org/www-community/attacks/csrf">(</a><a href="https://owasp.org/www-community/attacks/csrf">CSRF</a><a href="https://owasp.org/www-community/attacks/csrf">)</a><a href="https://owasp.org/www-community/attacks/csrf"> – OWASP Foundation</a></li>
<li><a href="https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/06-Session_Management_Testing/05-Testing_for_Cross_Site_Request_Forgery">Cross-Site Request For</a><a href="https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/06-Session_Management_Testing/05-Testing_for_Cross_Site_Request_Forgery">g</a><a href="https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/06-Session_Management_Testing/05-Testing_for_Cross_Site_Request_Forgery">er</a><a href="https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/06-Session_Management_Testing/05-Testing_for_Cross_Site_Request_Forgery">y</a><a href="https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/06-Session_Management_Testing/05-Testing_for_Cross_Site_Request_Forgery"> Prevention – OWASP Cheat Sheet Series</a></li>
<li><a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Cross-site%20request%20forgery%20-%20Wikipedia">Wikipedia CSRF</a></li>
</ul>
You’ve learned of a vulnerability that exists on the bookstore website. It appears you can craft an html file that resets a user’s password to one of your choosing when they open it. You plan to embed this file in an email and see who actually clicks on it. They’ll never know!

Download from the WebSec VM the required starter template here:

<ul>
<li><a href="http://localhost:7149/api/template/flag4">Fla</a><a href="http://localhost:7149/api/template/flag4">g</a><a href="http://localhost:7149/api/template/flag4"> 4 – Template</a></li>
</ul>
You must reset an unsuspecting user’s password to <strong>HanSolo77</strong> Note: You will <strong>not</strong> know who the user is so your crafted html file should work for any user of the website.

Earn this flag by performing the following steps:

<ul>
<li>Log into the book store website using the account we provided earlier in the project description</li>
<li>Note: If you don’t understand why logging in ahead of time is required, be sure to read more about CSRF attacks.</li>
<li>Launch your crafted flag4.html file by double clicking in a new tab</li>
<li>The new tab will open and automatically reset the user’s password to HanSolo77
<ul>
<li>Note: The file must auto-submit. The autograder will not click any buttons you may have put on flag4.html</li>
</ul>
</li>
</ul>
<strong>Hints:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<ul>
<li>Use Chrome dev tools to watch what happens outside of an attack. The Elements, Sources, and Network tab should be helpful.</li>
<li>The developers knew about CSRF and put some protections in place. Understanding where these protections are and how they work is the key to exploiting them.</li>
<li>You may need to reset the database from time to time to start with a clean slate. Be sure to follow the steps in the Setup section above to complete this.</li>
<li>Be sure to pass the GTID as a string and not an int</li>
</ul>
<strong>FLAG TESTING:</strong>

To test your flag4.html file and receive the flag, run this command at the command line. Note: replace the <strong>gaTechId</strong> with your actual GTID.

./StudentGrader.sh –flag 4 –gaTechId 923456789 –filePath /home/websec/Desktop/flag4.html Your web output will look similar to this:

<h1>Flag 5: Bypass Permissions – 15 Points</h1>
The developers built an Admin page for power users of the site. Obviously, they couldn’t just let everyone have access to this page so they built a simple RBAC (Role-based access control) system and put it into place. Unfortunately for them, they didn’t do the best job of building these permissions and it can be bypassed! Your job is to bypass any security checks and gain access to this Admin page.

The Admin page can be accessed by clicking the link at the top right of the page. In order for this to work correctly in your html file, you may need to write a little JavaScript and find a place where this can be XSS injected. Knowing these developers, I bet they left some clues. Maybe some files they should have removed before production.

Download from the WebSec VM the required starter template here:

<ul>
<li><a href="http://localhost:7149/api/template/flag5">Fla</a><a href="http://localhost:7149/api/template/flag5">g</a><a href="http://localhost:7149/api/template/flag5"> 5 – Template</a></li>
</ul>
To earn your flag you must alter the template so that it performs these steps when you open it in a browser or run it using the grader:

1 Bypass all permissions checks and open the Admin page fully loaded a Note: You must do all of this in the html template and it must automatically load/open the page

b The URL must start with http://localhost:7149/admin

<strong>Hints:</strong>

<ul>
<li>You need to investigate and find out how the Admin page is being protected. The Chrome developer tools are where you’ll find this.</li>
<li>The Admin page may shed some light with its security messages. The message may change depending on the state of the site.</li>
<li>Try to bypass the checks before constructing your html file.</li>
<li>You’ll likely need to do some script injection in order to defeat the security checks. Follow the hints above closely, “remove before production”.</li>
</ul>
https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag5.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1/2 2/17/25, 2:36 AM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 5 | CS 6035

<strong>FLAG TESTING:</strong>

To test your flag5.html file and receive the flag, run this command at the command line. Note: replace the <strong>gaTechId</strong> with your actual GTID.

./StudentGrader.sh –flag 5 –gaTechId 923456789 –filePath /home/websec/Desktop/flag5.html Your web output will look similar to this:

<h1>Flag 6: CORS – 15 Points</h1>
Congratulations on making it this far! You’ve already overcome several obstacles, and now it’s time to dive into Cross-Origin Resource Sharing (CORS). CORS is a security feature in web browsers that allows applications to request resources from domains other than the one hosting the application.

To complete this task, we’ll be working with a different flavour to CORS. Specifically, we will explore how CORS can limit the type of requests that can be made and how expanding on the allowed access control methods will help accomplish this task.

Download the required starter template here:

<ul>
<li><a href="http://localhost:7149/api/template/flag6">Fla</a><a href="http://localhost:7149/api/template/flag6">g</a><a href="http://localhost:7149/api/template/flag6"> 6 – Template</a></li>
</ul>
Your goal is to update the title of book 6 to “<strong>Let the fun begin!</strong>” and redirect to its Detail View. This needs to be done using JavaScript only. Use this endpoint to make the update:

PUT api/book/{bookId}

Body:

{

“newTitle”: “Title 2” }

Did the attempt fail? Investigate and troubleshoot—think about what might have gone wrong.

Ensure your script addresses the issue and updates the book title. Once you’ve successfully updated the book title, submit the script and earn your flag!

<strong>Hint:</strong>

<ul>
<li>Use Chrome dev tools to watch what happens outside of an attack. The Console and Network tab should be helpful.</li>
<li>Go to the Book Detail page and check the Network Tab in your browser’s developer tools.</li>
</ul>
Identify an endpoint that can assist you in configuring the CORS allowed methods.

<strong>FLAG TESTING:</strong>

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag6.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1/2 2/17/25, 2:36 AM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Flag 6 | CS 6035

To test your flag6.html file and receive the flag, run this command at the command line. Note: replace the <strong>gaTechId</strong> with your actual GTID.

./StudentGrader.sh –flag 6 –gaTechId 923456789 –filePath /home/websec/Desktop/flag6.html Your web output will look similar to this:

The grader from the output will look similar to this. Copy the flag to flag6 in project_websecurity.json.

Disclaimer: You are responsible for the information on this website. The content is subject to change at any time. © 2024 Georgia Institute of Technology. All rights reserved.

https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/Projects/Web_Security/Flag6.html&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2/2

&nbsp;
