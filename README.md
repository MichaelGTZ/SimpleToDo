# Project 1 - *Simple Todo*

**Simple Todo** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Michael Gutierrez**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is completed:

* [X] User can **view a list of todo items**
* [X] User can **successfully add and remove items** from the todo list
* [X] User's **list of items persisted** upon modification and and retrieved properly on app restart

The following **stretch** features are implemented:

* [ ] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![App Demo Link](Screenshots/Simple_Todo_Demo.gif)

GIF created with [Kap](https://getkap.co/).

## Notes

Describe any challenges encountered while building the app.

My version of android studio's default view was ConstraintLayout, which I hadn't recognized until the video tutorial showed the activity_main.xml code and I was able to differentiate between my layout options and the video's. The RelativeLayout option was located in the "Legacy" section of my Android Studio. The provided written guide here https://hackmd.io/@slavkoder/H1P5E7QHU#RelativeLayout was a great help to this confusion.

Upon trying to confirm my installation as shown in the Android Studio Setup Slides https://docs.google.com/presentation/d/1Z0maWlx0t_bSKDV3XRYVnAJ9y0kUilc9f2f-wY2BX8k/edit#slide=id.g2301961c90_0_81, I needed to additionally update to API 29.0.4 after downloading API 29. This process was fairly straight forward after I looked through guides and the internet to understand that it, indeed, was this update, that had to be done.

## License

    Copyright [2020] [Michael Gutierrez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
