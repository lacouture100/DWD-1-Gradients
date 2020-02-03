# Dynamic Web Development 
## Assignment 1
***

This repository contains my first assignment for the Dynamic Web Development Class at ITP. The assignment contains a simple web page with experiments using only HTML, CSS, and media assets (images, videos, gifs, fonts, etc.).

## About
***

This proeject consists on making a webpage with only HTML and CSS in order to get a good idea on how to code, track, sync and deploy a website.

## Setup
***

 - To open the webpage you can download the files included in the repository and run the **index.html** file in the root folder.

### Prerequisites

 -  An internet browser.

### Installation

For this particular project, there are no specific installation requirements.

### Develop

To develop this document, you can follow the steps provided below:
1. Create a fork of this project on Github
2. Ping the author of this repo via Github Issues to see if they are looking for contributions on the specific feature you're looking to add
3. Open the file in VS Code and make updates 
4. Add and commit those changes in your forked github repo
5. Make a pull request specifying what additions and changes were made
6. Have a nice chat and communication with me about those changes. 
7. Celebrate the contribution! 

## Built with
***
* [VS Code](https://code.visualstudio.com/)
* [Github](https://github.com)

## Author
***
* [Alvaro Lacouture](https://alvarolacouture.com) 

## Acknowledgements
***
* [Joey Lee](https://jk-lee.com) -- adjunct professor -- [NYU ITP](https://itp.nyu.edu)
* [Cassie Tarakajian](https://cassietarakajian.com/) -- adjunct professor -- [NYU ITP](https://itp.nyu.edu)
* [The Good Project Readme Project](https://github.com/itp-dwd/2020-spring/blob/master/templates/readme-template.md)


***
# Notes & Process

My work primarily focused on experiments with gradients using CSS animations and grid layouts. I started playing around with gradient animations and color mixes around the whole background before deciding on a more "tiled" version. 

I decided to use a grid layout since it seemed simple enough to create the effect I wanted. For the home page I decided to go for a minimal look, with two rectangular containers each with it's own gradient. The top-most container has a vertical movement pattern and is the first experiment. The second rectangle contains a dynamic horizontal gradient which leads towards the second experiment.

In the first experiment's page, made entirely with vertical gradients,I used different time setting to create an animation that would only synce every six seconds. In the second experiment's page I used both horizontal gradients and text.


## Process & Documentation

At first I started with a gradient animation throughout the whole background. The gradient was between the vales of RGB: red, green, and blue.

![](GIFs/process_1.gif)

Later on I started playing with movement. First by moving the whole container. The movement didn't really accomplish what I wanted.

![](GIFs/process_2.gif)

After testing more I decided on animating the gradient background in each of the containers layed out with the grid. The grid gave it the perfect layout to generate an appealing visual effect.

![](GIFs/process_3.gif)

I later made another page with several horizontal gradient animations and a text element in the middle. The text uses the "Impact" font.

![](GIFs/process_5.gif)

By the end I settled on making the home page with two hyperlinked rectangles, each one with an animation similar to the page each of them linked to. 

![](GIFs/process_4.gif)



## Challenges & Struggles
 - I struggled with aligning objects to the center, managing their size and how much they would stretch or not according to the viewport.
  - I takes me some time to realize how to mix absolute, fixed, relative and other positions in combination with the grid and flex-box layout.

## Questions
 - When I created a <div> with `width : 100%` , it worked perfectly. However when I introduced the `vertical : 100%` parameter the <div> would no appear. Why does this happen?
  - Which is a better way to handle the layout, through grids or through flex-box?
  - When organizaing content in a webpage, what should be left to JS and what should be controlled with CSS?


## References

* Felipe Pantone. [Chromadynamica](https://www.felipepantone.com/chromadynamica)