# SubFinder Documentation
Documentation relating to the subfinder project.

[![Twitter](https://img.shields.io/badge/twitter-@Ice3man543-blue.svg)](https://twitter.com/Ice3man543)
[![Twitter](https://img.shields.io/badge/twitter-@codingo__-blue.svg)](https://twitter.com/codingo_)
[![Twitter](https://img.shields.io/badge/Twitter-Mzack9999-blue.svg)](https://twitter.com/Mzack9999)

# Project History

This project began it's life as a Bug Bounty World slack channel discussion. @Ice3Man and @codingo_ were talking about how the cornerstone subdomain tool at the time, sublist3r, appeared to have been abandoned. The goal of this project was to make a low dependancy, manageable project in Go that would continue to be maintained over time. @Ice3man decided to rewrite the sublist3r project and posted about it. @codingo_ offered to contribute to the project and subfinder was born. 

# Frequently Asked Questions (FAQ)
## How do I move settings between machines?
Configuration for subfinder is saved at ```~/.config/subfinder/config.json``` which can be copied between machines.

## Do I need to use API keys?
No. The majority of sources for subfinder don't require API keys, you just won't see as many results. Check the post installation instructions for which sources require API keys.

## I wish SubFinder did x...
We're extremely open to pull requests, if you wish to have a feature feel free to develop it and push it to here for review and inclusion in the main project. If you're unable to code something, please raise it as an issue and if we think it has benefit to the community we'll look into developing it for you.

## Why is this a better tool than xyz tool?
There are a number of subdomain tools, and we beleive you should try each of them to find the one that works well with how you like to approach subdomain discovery. We've developed subfinder to solve subdomain finding in a way that we felt worked best for the way we work, and was easily maintainable to allow us and others to add as many sources and features as possible.
