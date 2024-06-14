# Issues

In this post I will record the issues that appears across de blog development, the idea is to have a real walkthrough of issues and needs that appeared over time.

## Issue 01: Home page and navigation

The first post was commited in Index html page, because I wished to deploy and to see te results as soon as possible. However to deliver new posts was necessary to create a Home page to group posts and a mechanism to go back to home.

I used simple html links `a` to solve this. Although there are many ways to implement navigation, including routes libraries, we can always remember that simple links can be very useful and enough to this situation.

![Home Page image]()

## Issue 02: Maximum width and readability

On large screens it was difficult to read because of the line length, so I set the maximum width to 960px. In future posts I intend to talk more about readability.

## Issue 03: Images

In the sencond post the images starts to create problems, unlke of text, images are not responsive by default and start to break the edge of screens causing the appearence of scrolls. To fix this behavior was applied a `max-width` of 80%.

But other things are bothering, like borders and alignment, and this points will be solved in future releases.

## Issue 04: Code duplication and re-work

Some of fixes were added directly in HTML files, but issues solved with CSS Styles starts to be necessary in many files causing code duplication, and after some times I decided to create the first `.css` project file and concentrate the main styles. 


## Issue 05: Post rewriting

Actualy I'm writing posts in Markdown and after adapting to HTML, yes, I'm writing 2 times. To solve this, I will use 11ty (finally).

