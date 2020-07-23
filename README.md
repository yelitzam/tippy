# Tippy
# Pre-work - Tippy

*Tippy is a tip calculator application for iOS.

Submitted by: Yelitza Mendez

Time spent: 9 hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [ ] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] A slider option in case you plan on splitting the bill with others.

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='https://media.giphy.com/media/LrL7uXYpbUIylzJ1p6/giphy.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Giphy](https://giphy.com/).

## Notes

I had trouble getting the slider to work correctly. It's still a bit buggy as it doesnt update the split value when the slider is changed. I was having trouble
figuring out what setting I had to add in order to have calculateTip() called whenever the slider was changed but I wasn't able to figure that out. 

## License

    Copyright [2020] [Yelitza M]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
