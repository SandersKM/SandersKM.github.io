---
title: "Central Arkansas United Way Community Resources Page"
excerpt: "Final project for Databases and Web Systems at Hendrix College (CSCI 340)<br/><img src='https://github.com/SandersKM/SandersKM.github.io/blob/master/images/CommunityResourcesScreenshots/screencapture-localhost-53661-2018-07-08-21_23_58.png'>"
collection: portfolio
---

During the spring semester of 2018, I took CSCI 340: Databases and Web
Systems. The final project for this class was to create a website with a database for a
nonprofit community partner in Central Arkansas. My 6-member team created a community
resources page for United Way of Central Arkansas. I contributed primarily to database construction and framework integration.

The United Way website currently has a [community resources page](https://www.uwcark.org/help), which helps
people in the community find organizations that have the resources they need.
However, the data on this website is not standardized and the page was written entirely
in HTML. After talking with our community partner, we decided to create a database to
keep track of community resources and make it easy for United Way to add or edit
organization information. We wanted to have filtering capabilities based on available
times and make it accessible to users who cannot read in English. We hope that a
version of our final product is integrated into the United Way website and helps people
in our community get access to the resources they need.

I feel that this experience built on and expanded my computer science
knowledge. Our project contains code in HTML, CSS, JavaScript, SQL, and C#. I did
not know any of those languages before beginning this class. I also didn’t know
anything about creating databases and working with web frameworks. 
This class embodied the Hendrix Computer Science goal of “learning how to
learn”. Now at the end of the semester, I feel reasonably confident doing both frontend
and back-end website construction.

Overall, this was a great learning experience that has the potential to create
positive change in the community. Through this project, I have learned how to work with
a team to create a complex technological solution for a community partner’s needs. The
skills I learned can be used in the future to address other needs in my community. 


## Overview of Functionality

Our main screen for the United Way Community Resources Page has 12 categories of services offered. The pictures are intended to help people who may not be able to read English well navigate the webiste. There is also a translation option for Spanish and Mandrian. 

![MainScreen](https://github.com/SandersKM/SandersKM.github.io/blob/master/images/CommunityResourcesScreenshots/screencapture-localhost-53661-2018-07-08-21_23_58.png)
![MainScreenSpanish](https://github.com/SandersKM/SandersKM.github.io/blob/master/images/CommunityResourcesScreenshots/screencapture-localhost-53661-2018-07-08-21_31_38.png)

Once a user clicks on a type of resource, they can filter the organizations that offer that resource by date, day of the week, and/or time. This is an important feature because some orgainzations are just open twice a month at different times. 

![ResultsScreen](https://github.com/SandersKM/SandersKM.github.io/blob/master/images/CommunityResourcesScreenshots/screencapture-localhost-53661-Home-InitialResults-2-2018-07-08-21_25_48.png)

We also wanted to make this site easily manageable by the United Way staff. Our main admin page is automatically filtered by date last updated, but the admin can also find specific orgainzations by name.

![AdminResults](https://github.com/SandersKM/SandersKM.github.io/blob/master/images/CommunityResourcesScreenshots/screencapture-localhost-53661-Organizations-2018-07-08-21_26_50.png)

When an admin wants to create a new resource, they are directed to a series of pages for filling out orgainzation information. The first page asks for the name and service requirements. The second page asks for types of resources offered. The final page allows the admin to add in times that the organization is open. The data structure was designed to hold information such as "open the 3rd Thursday of the Month from 9:00-11:00 AM and 1:00-5:00 PM". All of this information can be updated by the admin at a later date as well. 

![NewResourceName](https://github.com/SandersKM/SandersKM.github.io/blob/master/images/CommunityResourcesScreenshots/screencapture-localhost-53661-Organizations-Create-2018-07-08-21_27_42.png)
![NewResourceResources](https://github.com/SandersKM/SandersKM.github.io/blob/master/CommunityResourcesScreenshots/images/screencapture-localhost-53661-Resources-Create-116-2018-07-08-21_29_09.png)
![NewResourceTimeScreen](https://github.com/SandersKM/SandersKM.github.io/blob/master/CommunityResourcesScreenshots/images/screencapture-localhost-53661-Times-AddTimes-116-2018-07-08-21_30_40.png)
![NewResourceTimeAdding](https://github.com/SandersKM/SandersKM.github.io/blob/master/CommunityResourcesScreenshots/images/screencapture-localhost-53661-Times-Create-116-2018-07-08-21_31_16.png)
