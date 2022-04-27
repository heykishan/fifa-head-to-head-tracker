# FIFA match score tracker

This is a minimal score tracker app built on Salesforce to track game scores and maintain some basic stats among friends.
It is currently built with FIFA in mind, but can be repurposed to support any similar game with some effort.

## Features

- Create matches, add players and scores.
- Match status and Player Stats are auto calculated
- Essential reports on the homepage

## Usage

Create a Salesforce dev org, if you dont have one already. You can do so from your trailhead account (its free).
Download or clone this repo and open this directory on VSCode. Confugure your dev org on the directory and push the content to your org. You should now be able to use the features inside the FIFA app (from the app launcher).

The app is supported on the Salesforce Mobile app too.

## Roadmap

Some things Im looking to add are,
- Ways to add penalty results (and create, make penalty score fields conditionally required)
- Ways to track bookings (could be a cool report on Homepage for most red/yellow cards received by players)
- A Salesforce Screen Flow to add multiple matches at once

## Contributing
Be it typo fixes or feature additions - all pull requests are welcome, just make sure it does not break SFDX structure in any way. Feel free to open an issue to discuss bugs or feature requests.

## License
[Creative Commons Zero v1.0 Universal](https://github.com/heykishan/fifa-head-to-head-tracker/blob/main/LICENSE). Some rights reserved.
