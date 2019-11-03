# Heuristic Evaluation
## Part 1: Findings

![design_1!](/img/HeuristicTable.PNG)


### Offending Portion For Comments: 1,3,4,8,9

![design_1!](/img/paper-proto-profile.JPG)


### Offending Portion For Comments: 6

![design_1!](/img/paper-proto-record.JPG)


### Offending Portion For Comments: 1,2,7,10

![design_1!](/img/paper-proto-match.JPG)


### Offending Portion For Comments: 12

![design_1!](/img/paper-proto-band.JPG)


### Offending Portion For Comments: 5

![design_1!](/img/paper-proto-prep.JPG)


## Part 2: Revisions

### Profile Revisions
After compiling our heuristic evaluations, we noticed that the profile page was the source of most of our broken heuristics. To start, we changed our instrument and genre selctors to be drop-down menus that show instruments based off of the characters typed in the filter box. This was done in response to several people pointing out that we should have users select their instruments rather than typing them out (see comment 3). We also included an option to sync Harmonee to the user's prefered calendar application so that the band matching "Jam Events" can be informed by the user's actual availability (see comment 1) multiple people pointed this out and ranked the lack of something like this as relatively high in severity.
![design_1!](/img/Heuristic-Instrument-Edit.JPG)
![design_1!](/img/Heuristic-Genre-Edit.JPG)
![design_1!](/img/Heuristic-Schedule-Edit.JPG)

### Recording Feature Revisions
We also noticed that during our evaluation, our evaluators had a lot of questions about how to use the recording feature, and it quickly became apparent that we did not included enough features. They mentioned that it should definitely be able to import recordings from outside the app (see comment 6), so we added a button to allow users to take audio from other sources. While it was not mentioned by evaluators, we later found that it was a big problem that we did not have a submit button, so this was also added.
![design_1!](/img/Heuristic-Record-Edit.JPG)

### Multiple Match Revisions:
Lastly, we had multiple evaluators comment that we lacked an organized way to show the user that they have multiple matches (see comment 2), so we decided to include an entirely new page in which all matches are shown and can be sorted by match percentage or date of matching. We also decided to include some of the metrics that were used to compute the percentage in response to one of the evaluators suggeting that we do so (see comment 7).


