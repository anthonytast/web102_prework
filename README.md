# WEB102 Prework - *Tropic Support*

Submitted by: Anthony Tast

**Tropic Support** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **6** hours spent in total

## Required Features

The following **required** functionality is completed:

* [✓] The introduction section explains the background of the company and how many games remain unfunded.
* [✓] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [✓] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [✓] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [✓] Added Tropic Support colors and branding
* [✓] Added *temperature* feature to highlight which games need the most help (based on the remaining goal and the average donation amount per backer)

## Video Walkthrough

Here's a walkthrough of implemented features:

![Tropic Support Demo](assets/TropicSupportWeb.gif)

<!-- Replace this with whatever GIF tool you used! -->
GIF created with LICEcap  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

I had a lot of fun building this app. My main challenge came with adding a custom feature to the site.

* I wanted to add something that would encourage users to donate to struggling games. I found the tropical branding to be a great addition because it added some theming and lively colors to the user interface, while encouraging the user to donate to games that require the most funding.
* Once I decided to go with the tropical theme, I wasn't sure how to determine the *temperature*. The feature is somewhat abstract, simply meant to indicate which games are struggling the most. My formula was successful because it indicates how many more donations are required based on the average donation amount per backer. I set a boiling temperature as the maximum to keep the temperature within reason. I also set freezing as a minimum so that users don't feel discouraged from donating to games with proper funding.

## License

    Copyright 2025 Anthony Tast

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
