# Series Tracker

A simple script to parse html files from TVRage.com and get a list of episodes
for a given TV Show.

## Usage

As of this version, the series title is hardcoded on the main function, but
it's must be easy extend the code and create a list of series names and
episodes.

## Long delays

It takes a html fetch action to get each episode synopsis, so for long running
series, the fetching process might take a while. To avoid synopsis fetching,
it's only necessary to set SYNOPSIS to False.
