# User Experience Design Overview

### 2.) Roles
Geoff Salmon: Executive Designer
Edwin Lantigua: Executive Designer


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


### 6.) Usability Testing Results
Our tests illuminated many oversights that were made while designing our paper prototype that we were able to later use to iterably improve our design. Throughout our testing we noticed the trend that many of the issues that came up either had to do with some sort of lack of intermediate functions that help get the user to complete the main task, or misconceptions of the affordances of an element allowed to the user because of insufficient signifiers.

A great example of the former would be the lack of the following pages on our application. The first example came as a result of multiple users during heuristic evaluations asking about how one would typically handle viewing multiple matches. While this page is rather simple in terms of functionality, we felt the inclusion of this page to be critically important because we want our users to be able to match and compare their jam experiences with many different types of people. Our original research indicated that the best way to find compatible bandmates is through experiencing many musicians. Giving users the ability to see and compare all their matches at once is critical for this process. The second example is similar in structure to the last, but differs slightly in motivation. When conducting our tests one of our users was disapointed at the fact that the application seems to only allow for the managing of one band at a time. The existence of this page now clearly demonstrates that users can support multiple bands.

![paper-proto!](/img/page-additions.PNG)

The following pictures demonstrate some of the changes that were made in response to elements having insuficient signifiers or otherwise being confusing for our users. The first shows a drop-down input selector that has the functionality of allowing multiple entries (in the given case, instruments and genres). With the initial design, most testers either assumed that only one input was allowed, or were not able to easily figure out how to add multiple inputs. This result was of particular importance to us because the quality of the band matching is highly dependent on the amount of information the user is able to provide to Harmonee. Simple design oversights like this should not hinder the gathering of this data. These results informed our switch to a dropdown menu that more obviously shows this functionality through checkboxes.

![paper-proto!](/img/edits-overview.PNG)

