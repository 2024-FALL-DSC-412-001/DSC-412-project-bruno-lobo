# DSC412-project

## Dead By Daylight Predictive Killer Tier List Placement Model

This project aims to analyze the power levels of the killer characters in the game Dead By Daylight (a.k.a DBD), and attempt to produce a model that is able to predict the placement of a killer in a [tier list](https://en.wikipedia.org/wiki/Tier_list) based solely on descriptive and quantifiable information about said killer.
Should this model be successful, it would be possible to more easily determine if a killer will create concerns in terms of balance in the game before it comes out, skipping a lot of play test that is usually required to make such a claim.
The tier list used in the analysis is included as a picture in this project, named TierList.png, for reference. The data used comes from KillerData.xlsx and KillerDatav2.xlsx.

## Running the code

Open up VSCode or Jupyter Notebook, and clone this repo

Make sure your terminal is in this directory. You can confirm that is true by typing `pwd` in terminal.

Make sure pip is at least version 24.2

`python -m pip install --upgrade pip`

Create a virtual environment with

`python -m venv ./.venv`

Then activate it in terminal:

Windows: `.\.venv\Scripts\activate`

Mac: `source ./.venv/bin/activate`

Linux: `source ./.venv/bin/activate`

You should see `.venv` appear in the terminal on the left side of the command line

Install the requirements using:
`python -m pip install -r ./requirements.txt`

The code should now be ready to be executed in your environment.

## References

- Kill rate data gathered from over 770,000 games that took place between Nov 2021 and October 2024, submitted by the community to BritishBoop's [nightlight.gg](https://nightlight.gg/) website
- Speed related numbers taken from the official [Dead By Daylight wiki](https://deadbydaylight.fandom.com/wiki/Movement_Speeds)
- Skill related data, power components and tier list placements taken from multiple content creators that play the game, as well as my own experience. Opinions may differ.