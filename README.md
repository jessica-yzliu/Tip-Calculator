
# Pre-work - *Tip Calculator*

**Tip Calculator** is a tip calculator application for iOS.

Submitted by: **Jessica Liu(Yanze)**

Time spent: **10** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [x] Settings page to change the default tip percentage.
* [ ] UI animations
* [x] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] User can send a text message via the app to remind people to pay back.
- [x] In-App Bug Report feature (INSTABUG Framework)
- [x] Animated colors when user changes tip percentage

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='https://github.com/Yanze/codepath-project/blob/master/demo.gif' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

1. Passing data between controllers: I used prepareForSegue function to pass data, but this is not very convenient for passing data back forth. So I decided to use a model to share data between viewControllers.
2. Animation: I don't feel very comfortable with animations, need to spent some time on this topic.

## License

    Copyright @2017 Jessica Liu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
