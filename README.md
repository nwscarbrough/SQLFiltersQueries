<h1>Applying Filters to SQL Queries</h1>

<h2>Project Description</h2>
As part of my responsibility to enhance system security, I utilized SQL queries with various filters to address potential security concerns and maintain up-to-date security measures across employee computers. Below are the tasks performed:
<br />


<h2></h2>


Retrieve after hours failed login attempts: <br/>
<br />
To address a potential security incident after business hours, I crafted a SQL query to filter failed login attempts post-18:00 using:
<br />
<br />
<img src="https://imgur.com/jf4n9UM.png" />
<br />
<br />
This helped identify unauthorized access attempts outside normal operating hours.
<br />
<br />
Retireve login attempts on specific dates:  <br/>
<br />
<br />
Following a suspicious event, I queried login activities on and the day before 2022-05-09, to ensure thorough investigation:
<br />
<br />
<img src="https://imgur.com/EWv7eo3.png" />
<br />
<br />
Retrieve Login Attempts Outside of Mexico:  <br/>
<br />
<br />
Concerns about logins from outside Mexico led to the following query, which excludes Mexican entries:
<br />
<br />
<img src="https://imgur.com/hMR8fyr.png" />
<br />
<br />
Change file permissions on a hidden file:  <br/>
<br />
<br />
To adjust permissions according to organizational policy:

I used the chmod command to remove write access for 'others' from specific files, such as project_k.txt.
Permissions were adjusted for the archived hidden file .project_x.txt, removing write access while maintaining read permissions for the user and group.
<br />
<br />
<img src="https://imgur.com/uiaLhEE.png" />
<br />
<br />
Retrieve Employees in Marketing:  <br/>
<br />
<br />
For updating computer systems in the Marketing department, specifically in the East building:
<br />
<br />
<img src="https://imgur.com/LjSKpZX.png" />
<br />
<br />
Retrieve Employees in Finance or Sales:  <br/>
<br />
<br />
For updating computer systems in the Marketing department, specifically in the East building:
<br />
<br />
<img src="https://imgur.com/OJu1YzT.png" />
<br />
<br />
Retrieve All Employees Not in IT:  <br/>
<br />
<br />
A final update targeted employees outside the IT department:
<br />
<br />
<img src="https://imgur.com/wJR68IP.png" />
<br />
<br />

<h3>Summary</h3>
These SQL filters were critical in retrieving precise information from the log_in_attempts and employees tables to address security issues efficiently. The use of AND, OR, NOT operators, and pattern-matching via LIKE ensured targeted data retrieval essential for implementing security updates.
