# User Experience Design Overview

### 2.) Roles
Geoff Salmon - Researcher, Designer

Edwin Lantigua - Researcher, Designer


### The Problem. Our Solution
Currently, there are a wealth of resources for learning new instruments and uploading music online on an individual basis. While this is certainly something to be celebrated, there are no resources for musicians to connect with, learn from, inspire, and motivate each other. There are thousands of artists that want to collaborate with others but don’t know where to find people who share similar interests and have the same vision. Even then, people who happen to be in groups feel like they are stuck or stagnating as artists: they don’t know what the next step is. The process of moving from noodling in jam sessions to recording in the studio or performing at gigs is may present a significant challenge. There is plenty of latent potential that is locked away and, as a result, hundreds of songs and musical project not being made. Harmonee’s mission is to unlock this potential, making the logistics of band formation and maintenance from something that is a burden into something that is exciting and painless. Our use of a mobile app format lead to the two tasks we found most important: establishing a network of musicians, and thoughtful preparation for events.


### 4.) Paper Prototype
In order to make our design ideas as iterable as possible, we started by drafting a lo-fi paper prototype that intends to present the genreal aesthetics of our application, as well as to show a more concrete example of how our users might be able to complete the two tasks of interest. This prototype started as a base on which many improvements were made based on later user testing. Below is an overview of the prototype as well as a detailed walk-through of how a user would be able to complete their two primary tasks.

#### Overview

![paper-proto!](/img/whole_proto.jpeg)

#### Task 1, Building a Musical Network
This is the starting point for the app, which is intended to orient the user's experience closer to whichever task they are looking to complete. Because we are interested in accomplishing the task of building a musical network, we will select "Looking For a Band."

![paper-proto!](/img/paper-proto-start.JPG)

This page allows the user to insert information about themselves that is relevant to finding other musicians that are compatible with them. THey are able to edit each section by tapping on them and typing their desired input. Most notably, the user is told that the matching system will begin after they submit a musical sample that they can record right from the app by pressing "Record Sample."

![paper-proto!](/img/paper-proto-profile.JPG)

This is the part of the application where users record their music right into their device. It includes the standard audio recording tools, including playback, stop, and of course, record.

![paper-proto!](/img/paper-proto-record.JPG)

Some time after users have filled out their profile and provided a sample recording of their music, they will receive this notification about a new band matching. From here, they can simply open the notification to see the matching.

![paper-proto!](/img/paper-proto-match-notification.JPG)

This screen shows the user a potential band matching. The page includes information on each of the potential band members, as well as some of the information that was used to make the matching. This screen also notifies the user of a "Test Jam Event" that they have the option of accepting so that they may meet these other musicians, and later potentially start a band.

![paper-proto!](/img/paper-proto-match.JPG)

#### Task 2, Thoughtful Preparation

In addition to one’s individual profile, bands have a band profile shared by the whole group. This page features a picture of the group, the band’s name, a short description, some song links and, importantly, a preparation list for groups to plan for the uncertain.

![paper-proto!](/img/paper-proto-band.JPG)



The first section of the preparation list features missing items. These are items that they missed in their previous performance or considerations that they need to take into account for next time. The Commonly Forgotten section showcases items that are commonly listed across the app as missing. Finally, the goals section shows things that band members want to see in their band.

![paper-proto!](/img/paper-proto-prep.JPG)

The calendar section lists upcoming events as specified by users as well as suggested events based on band member schedules.

![paper-proto!](/img/paper-proto-calendar.JPG)

### 5.) Usability Testing Process
Our testing process began with a brief explanation of what the purpose of our app was and the goal of the test itself. While we did not provide our users with a formal consent form, we did make sure to communicate to them that 1.) his participation is completely voluntary and he can leave at any point, 2.) we are testing how well the prototype intuitively helps the user complete certain tasks, 3.) this is in no way an evaluation of Steve’s ability. After this, we introduced the paper prototype to the user and explained that it is intended to mimic the interface of a mobile application where the user has the ability to tap on elements to select, as well as swiping and typing as appropriate. We informed the user that he is encouraged to talk out his actions, and that no observation is too trivial to mention, as we are interested in the unique insights he might have, especially those about confusing parts of our application flow. We especially encouraged him to ask questions, but to be mindful of the fact that we will likely not be able to answer them unless they are critical to the continuance of the test.


### 6.) Usability Testing Results
Our tests illuminated many oversights that were made while designing our paper prototype that we were able to later use to iterably improve our design. Throughout our testing we noticed the trend that many of the issues that came up either had to do with some sort of lack of intermediate functions that help get the user to complete the main task, or misconceptions of the affordances of an element allowed to the user because of insufficient signifiers.

A great example of the former would be the lack of the following pages on our application. The first example came as a result of multiple users during heuristic evaluations asking about how one would typically handle viewing multiple matches. While this page is rather simple in terms of functionality, we felt the inclusion of this page to be critically important because we want our users to be able to match and compare their jam experiences with many different types of people. Our original research indicated that the best way to find compatible bandmates is through experiencing many musicians. Giving users the ability to see and compare all their matches at once is critical for this process. The second example is similar in structure to the last, but differs slightly in motivation. When conducting our tests one of our users was disapointed at the fact that the application seems to only allow for the managing of one band at a time. The existence of this page now clearly demonstrates that users can support multiple bands.

![paper-proto!](/img/page-additions.PNG)

The following pictures demonstrate some of the changes that were made in response to elements having insuficient signifiers or otherwise being confusing for our users. The first shows a drop-down input selector that has the functionality of allowing multiple entries (in the given case, instruments and genres). With the initial design, most testers either assumed that only one input was allowed, or were not able to easily figure out how to add multiple inputs. This result was of particular importance to us because the quality of the band matching is highly dependent on the amount of information the user is able to provide to Harmonee. Simple design oversights like this should not hinder the gathering of this data. These results informed our switch to a dropdown menu that more obviously shows this functionality through checkboxes. The second example shown on the right shows the events tab in edit mode where there is a lack of a way to add events! This was an observation that all participants made that severly impacted their ability to perform their second tasks, and caused them to question whether it was the app itself that made events on behalf of the band, or if it was indeed one of their responsibilities. Based on these complaints, we revised the prototype to include a green plus sign to indicate adding events. Their was also an observation made that removing events is a high-consequence action that could easily be done by accident with the original design. We decided to include a confirmation pop-up to prevent this from happening. 

![paper-proto!](/img/edits-overview.PNG)

Lastly, another major result we found was that users were consistently unsure about when Harmonee has submitted their profile for matching. This caused most of the users to be visibly confused about how to proceed. We acknowledge these results by now having the user choose to "edit" and "submit" their profiles, as well as including status messages at the bottom of the page that the user when they have successfully submitted their profile.

![paper-proto!](/img/edits2-overview.PNG)

These results are perhaps the most salient of our usability tests, but do not show the complete scope of the results gathered. To view all results collected please visit https://eddyngeoffy.github.io/2019-11-10-Usability-Testing-Review/

### 7.) Final Paper Prototype

The final paper prototype takese all of the most salient insights discussed above and incorporates it into one coherent application prototype. In the context of the two tasks, the revisions allow the user to 1.) effectively enter their user information that will be used to match them with other musicans, 2.) have a better underdstanding of the state of the application based on what they have accomplished, 3.) organize multiple matches, 4.) organize multiple bands, and 5.) effective read, update, and delete band events. 

#### Task 1: “find a group of musical peers to play music with in the near future.”
![task_1_overview!](/img/Task1-1.png)
![task_1_overview!](/img/Task1-2.png)

#### Task 2: "you currently part of a band and your task is to act as band manager for the group."
![task_1_overview!](/img/Task2.png)

### 8.) Digital Mockup
In all, the HiFi prototype faithfully captures all of the functionality captured in the LoFi prototype. Changes made mainly reflect stylistic decisions about color and spacing in order to make some functions more obvious or simply more attractive. A notable change was the inclusion of various "tip" cards that give some insight on how tasks might be useful to them. In addition, the profile page 
![HiFi_Prototype_Overview](/img/HiFi-Overview.png)


#### Task 1: Building a Network of Musicians
The below images shows the user progressing through the profile creation process, as well as what it might look like should they be successfully matched with several other individuals. They are able to set their instruments, genre, and availability in this prototype, but in theory they should be able to include a large number of other important metrics for band compatibility that are at the present beyond the scope of our prototype views. The task ends when the user successfully navigates to one of their match pages and accepts a "Test Jam Session."

![HiFi_Prototype_Overview](/img/HiFi-Task-1-1.png)
![HiFi_Prototype_Overview](/img/HiFi-Task-1-2.png)


#### Task 2: Mindful Preparation for Events
The below image follows the user as they view their band profile and manage several aspects from there. The user navigates to the preparation list to get a sense of the types of supplies they are lacking, or should have an extra of, as well as providing information on the types of supplies that other users commonly forget. After this, the user checks their calendar to view their upcoming events and is given the option to edit or remove existing events, add new events, as well as add events that the app suggests based on their existing band schedule. 

![HiFi_Prototype_Overview](/img/HiFi-Task-2-1.png)


### 10.) Appendix
Original Paper Prototype Page https://eddyngeoffy.github.io/2019-10-30-Paper-Prototype/

Usability Testing Page https://eddyngeoffy.github.io/2019-11-10-Usability-Testing-Review/

Digital Mockup https://eddyngeoffy.github.io/2019-11-13-Digital-Mockup/

