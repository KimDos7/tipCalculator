
# Pre-work - *Tip Calculator*

**Tip Calculator** is a tip calculator application for iOS.

Submitted by: **Alex Kim**

Time spent: **10** hours spent in total

## User Stories

The following **required** functionality is complete:

* [X] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [X] User can select between tip percentages by tapping different values on the segmented control and the tip value is updated accordingly

The following **optional** features are implemented:

* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [X] Using locale-specific currency and currency thousands separators.
* [X] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [X] Dark Mode
- [X] Total immediatley updating while the bill is updating
- [X] Settings Page

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/ZDOK3mxypC0HRFvuRu/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [GIPHY](http://giphy.com/).

## Notes

Describe any challenges encountered while building the app:

This is my first time diving into swift and IOS development in general so the entire project was a great but challenging experience. The first biggest conflict was realizing what "!" actually did in my code and why it was so necessary thorughout the entire project. This solved my big issue in the error CArgV threw at me when I wanted to format my numbers by the thousand marker. Then, with events, I found that I could do the project based on event changed, rather than end, helping me resolve several issues like updating total the moment bill amount has changed. 
The keyboard would not show up what so ever and I thought this was a coding issue, but after looking through online, it turned out that I needed to use Command + K to use the software keyboard instead of my mac. 


## License

    Copyright 2021 Alex Kim

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
