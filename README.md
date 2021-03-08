# Eleventy Blog From Scratch

## Introduction

This project was started as a way for me to better understand the Eleventy Static Site Generator. I had to deploy an Eleventy site to Netlify as part of part of [The Coders Guild](https://thecodersguild.org.uk/) JAMStack Web and App Development Course using the [Eleventy Base Blog](https://github.com/11ty/eleventy-base-blog) starter template. I wanted to understand how the site generator worked but the source code was difficult to understand so I decided I should start from scratch and build it from the ground up. To focus on the building of the site rather than the aesthetics, I decided to use Bootstrap to add a basic layout to it quickly and added based the styling on a bootstrap example blog. You can view the theme at the [live example](https://startbootstrap.com/previews/clean-blog) or on the [GitHub repository](https://github.com/StartBootstrap/startbootstrap-clean-blog).

Check out my live site: https://eleventy-blog-from-scratch.netlify.app/

## What did I learn?

I think the biggest things I learnt from this were understanding how front matter and different templating languages work. With so many files linking to one another it can be very difficult to work out what is going on and building this myself was a great way to really understand it. Eleventy works with multiple template languages but I opted to work with Nunjucks since it popular and has plenty of supported functionality. It seems there are a number of ways that code can be set up to reuse templates, but here I used the `layout` key in the front matter and used partials and `include` for the header, footer and navbar. I found the Eleventy documentation was actually really good for this and it helped understanding immensely.

## Resources

Here are some of the resources I used during the building of this project:

* [Eleventy Documentation](https://www.11ty.dev/docs/)
* [Build your own Blog from Scratch using Eleventy](https://www.filamentgroup.com/lab/build-a-blog/)
* [Let’s Learn Eleventy! Boost your Jamstack skills with 11ty](https://www.netlify.com/blog/2020/04/09/lets-learn-eleventy-boost-your-jamstack-skills-with-11ty/)
* [Making a Simple Web Site with the Simplest Static Site Generator](https://medium.com/@11ty/making-a-simple-web-site-with-the-simplest-static-site-generator-level-1-7fc6febca1)
* [Learn JAMstack with a free 3.5 hour video of demos and examples](https://www.netlify.com/blog/2020/03/12/learn-jamstack-with-a-free-3.5-hour-video-of-demos-and-examples/)
* [Video Series: Create an 11ty Theme from a free set of HTML templates](https://www.youtube.com/playlist?list=PLOSLUtJ_J3rrJ1R1qEf8CCEpV3GgbJGNr)

