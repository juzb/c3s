# c3s
Communicating Climate Change in Style 🌍🌎🌏

# 

| Work in progress. This repo is based on a 48 h sciathon and therefore not perfect (yet) |
|---|

## Vision

We want to help communicate relevant science on climate change as efficient as possible.

Check out short video on the project: [![Project video](img/video_thumbnail.png)](https://youtu.be/3t5OFxMSSF0)


## What can I do?

**If you are working on communicating climate change** - let us know about your work, contribute your expertise to the project by commenting on the issues below 

**If you are a programmer** - help us improve the tool. Contribute ideas by raising issues and commenting on the potential projects. Get to work on the implementation of important features. 
<!-- # TODO: link issue here -->

**If you have questions or suggestions on the project** - reach out to us on twitter: [@juzb](https://twitter.com/juluzb), 
<!-- #TODO: add your handles, if you're fine with that -->

**If you want to jump right into it** - check out our [analysis notebook](https://colab.research.google.com/github/juzb/c3s/blob/master/code/sciathon_notebook.ipynb)


## What to communicate?

We'd  like to have a discussion about this and hear from you! 
Check out our [issue](https://github.com/juzb/c3s/issues/1#issue-650606111) 
Help us to figure out
- what are the most urgent messages to convey
- what is the scientific evidence


## How to communicate?

We'd  like to have a discussion about this and hear from you! 
Check out our [issue](https://github.com/juzb/c3s/issues/2#issue-650606682)
Help us to figure out
- who needs to hear the messages the most
- how the message should be conveyed to it reaches open ears


## Next Steps in Coding

[Discuss here](https://github.com/juzb/c3s/issues/3#issue-650607257)
- Improve modularity and reliability of the code
- Add a distinction between climate change sceptic and climate change positive tweets
- Write comprehensive records to a restorable format (when a colab notebook dies, a lot of pgoress is lost otherwise)

# Using the c3s tool

We want to make using our tool as simple as possible. In fact, you can start right now in a colab notebook or locally:
Though you will need keys to access the Twitter API - check [their documentation here](https://developer.twitter.com/en/docs/basics/authentication/overview).

## Colab:

Just open this [link to our analysis notebook in google colab](https://colab.research.google.com/github/juzb/c3s/blob/master/code/sciathon_notebook.ipynb).

You will have to overwrite the part where the keys are loaded and set them manually. 

## Locally:
<!-- Hyperlink all of these -->
1. clone this repository
2. install conda
3. create a conda environment with `tweepy` in `python3`: 
 ```
conda create -n c3s --file conda-env.yml
conda activate c3s
 ```
4. get credentials for the Twitter API
5. run the [notebook](code/sciathon_notebook.ipynb)

## Attributions

This project started off with team Bisztray in the Lindau Nobel Laureate Meetings [Online Sciathon 2020](http://sciathon.org/):

We are honored to have won the first prize in the sicathon's communicating climate change section amongst many great projects!

![Group picture](img/group_bisztray.png)

Many thanks to the fantastic team of the [Lindau Nobel Laureate Meetings](https://www.lindau-nobel.org/) for the organisation of the sciathon and the [Online Science Days 2020](http://science-days.org/).

 
