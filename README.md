# CP3402 Assignment2 PB Group2

## Overview and Goals
This project goal is to make a theme and website for JCU Open House. By making this website, we wish to increase the number of attendees to the open house by 10% and by the end of open house project, increase the number of applicants by 5%. The time for the whole project to be done is between 8 and 14 January 2024. 

## End result
Link to the website: https://yulinc.sgedu.site/a2/ \
There are 3 pages on this website, the home page, about us page and contact us page. The home page has the main information about the open house so it has schedule table, details about admission question day, and registering. The about us page is a page about the JCU and why you would want to pick JCU. The contact us page has a form that users can fill in to ask their questions and hear from JCU soon. There are also contacts of JCU in that page. 

Home page
<img src="images\home page.gif" width=400> \
About us page
<img src="images\about us page.png" width=400> 
Contact us page
<img src="images\contact us page.png" width=400> 

## Website Features
**Animations and integrated menu**
![Animation and integrated menu](<images/feature.gif>)

**Simple contents / not to many pages**
![Simple contents](<images/home page.png>)

## Communication
For communications we used WeChat and WhatsApp. Sometimes we meet up so that we can directly work on it and if there is any problems we can directly deal with it together, like shown in the image below.\
<img src="images/communication screenshot.png" width=400>

## Project Management
For project management, we used Trello board as it helps keep track of the small tasks we have to reach the goal of the project. A screenshot of our Trello board is below:
<img src="images/trello board screenshot.png">

## Deployment Tools
For local deployment, we used XAMPP and VVV. We used XAMPP becuase not only it is open sourced but it is easy to use as we only need to start the Apache and MySQL that comes with it. The Apache for the website and MySQL for the database. A screenshot of the XAMPP control panel is shown below. As shown, it is easy to start and stop the Apache and MySQL needed for local deployment. 
<img src="images/XAMPP control panel.png" width=550>

We also used VVV which is similar to XAMPP as it can do local deployment however VVV is configured for developers who are developing a theme for WordPress. Since our project is to make a theme and we are also using WordPress, we used VVV. However, unlike XAMPP, VVV do not have a easy to look and click. To run VVV, we need to open either terminal or git bash to run VVV, like shown in the picture below.
![running VVV](<images/running VVV.png>)

For hosting deployment, we used Site Ground because several reasons. One of them is because there is a free trial using Site Ground from the university. Another reason is because it is very realiable because of its uptime and it has never failed. We also have made a domain before in Site Gound therefore it is much easier to host the website.

## Hosting Site Comparison
**InfinityFree** \
Pros:
- Offers free package with free subdomain
- Free SSL certificate
- No ads

Cons:
- No direct support
- Limited resoruces

**000webhost** \
Pros:
- Offer free package with free domain
- Uptime 99.9%
- Wordpress supported

Cons:
- Limited hosting type
- Limited storage and bandwith with the cheapest package

**Site Ground** \
Pros:
- Free using university email
- High uptime
- More support

Cons:
- Without university email, expensive
- No free package

## Development Tools
We used VS Code to code the themes and used WordPress to make the contents of the website for the JCU Open House. 

## Versions
There are 3 versions made in total, you can see them in the different files in this repository. The firs version is to check the set up of the PHP plugin, therefore it only has simple codes to check if the PHP setup is correct in the VS Code. This time the deployment is using XAMPP. The picture below shows the code and how the first version looked. 
![First version](<images/first version screenshot.png>)

The second version is a blank theme from Underscore. The Underscore theme provides the bare base what a theme needs, which would be a great help as we mold our own theme and the contents of the website for our third version. At this time, we also use VVV. So the testing for this version also helps us setup the VVV. The screenshot below shows the code and what the second version looks like in a local deployment using VVV.
![Second version](<images/second version screenshot.png>)

The third and last version is the end product of this project. Using the Underscore theme as the base we created the theme by adding codes. We also did the contents later after the theme is done. Below is a picture of what the third version is like and its code. 
![Third version](<images/third version screenshot.png>)

## Workflow
Below is digram of our workflow for the project.
![Alt text](<images/workflow diagram.png>)

We would say that out workflow management is agile because we keep going back to check and test our development to reduce the risk of trying to find what is wrong when everything is done instead.

At the start of the project, we get to know each other, exchange contacts and set up communication groups, Trello board and set the goal for the project. Then we set up the initial environment needed to do the project such as the PHP plugin for VS Code and have XAMPP installed and ready. Then we made the first version mentioned before to test out the PHP plug in using XAMPP. If there is anything wrong, we go back and test again. Once that is done, we went to Underscore theme and download them and have it set up ready. We also installed and set up VVV as we are going to use it soon. For testing the second version, we used VVV instead of XAMPP. Again if there are any problems then we modify and then back again to testing. Once things are working, we start developing the third version. As we develop the third version, like agile management, we test our codes again and again. So when we made an edit on the code, we test it to see if that is what we wanted. If it isnt, then we change the code again until we get the result wanted. If we get the result wanted, then we continue to the next task of code. For testing, we used VVV to test it out. Once the theme is correct, we made the content, again also testing it. Once both the theme and the content for the website is done, we host it up to Site Ground.
