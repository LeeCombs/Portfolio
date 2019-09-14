---
layout: post
title: "Front End Derust"
date: 2019-09-13
categories: projects
permalink: /projects/front_end_derust
technologies: HTML, CSS, JavaScript
short_description: Derusting work for my front end development skills
description: |
    This will cover my experience with trying to derust and get back up to speed with my front-end development skills. I'll be using Codecademy's tutorials since they cover the basics really well, then move onto small personal projects to get proper practise with it. I'll be going over HTML, CSS, and JavaScript basics.
thumbnail_link: /assets/fed_thumb.png

---

# Overview
I've been working on a quick derust to re-familiarize myself with front-end development. In the past I used Codecademy to brush up and learn the basics of a few skills, so I decided to check them out again and see what they offer for CSS, HTML, and JavaScript. While the free stuff is pretty surface level, I believe that it'll be helpful regardless.

As I haven't had the opportunity to dive deep into front-end development, and it's been a couple years since I've taken it in school, I'll mention, briefly, the things I've touched upon, and the things that I've actually learned proper.

After completing the Codecademy derust, I'll move onto doing more site layout recreations so that I may actually put some of this knowledge to use, instead of just reading it and forgetting it a week later.

# What Was covered

## HTML
Basic structure, attributes, styling, lists, images, videos, etc.

I learned a few good things to do that not only impact code quality, but also increase SEO performance. I knew that the alt text on images was used in the case that images didn't load correctly, but didn't know that it helped improve SEO, and can be helpful for impaired users. Got to use the **video** tag for the first time too.

Semantic HTML was a big get for me. My default strategy was to initially through everything into a div, and sort it out from there. I saw the **header**, **article**, **nav**, **section**, and **footer** tags before, but never read into why the were used, and what they offered over simply using **div** tags. In hindsight, of course they improve readability and accessibility when working on the site, but they also impact SEO performance, which makes sense. Knowing this now, I look forward to going back to previous projects and refactoring the HTML to fix these issues. Other neat tags I saw were **figure**, **figcaption**, and **aside**.

It also covered tables, which is something I haven't touched since school. **thead**, **tbody, and **tfoot** were important additions that I never knew about, it was also just rows, cols, data, and so on. thead was a tag that always stuck out to me, as I read it as thead instead of tHead, but never knew what it was for.

For forms, client-side validation was good to touch on again, but the biggest takeaway was the **datalist** input, which I'm familiar with as a user, but have not coded it into any forms I've made. It's a very user-friendly input that I just like.

## CSS
Basics, attributes, selectors, display and positioning, Bootstrap.

The biggest takeaway from this was finally understanding positioning. It was briefly covered in school, and since then I've relied on either flex boxes or hoping the site's layout is simple. 

**Position** (relative, absolute, and fixed) was something that I've changes before, didn't notice much impact, and immediately changed back to try something else. The exception is fixed for sticky headers or whatever. One interview asked me to place a button at the bottom right of the page; again I had no clue where to start. It's really simple though, with **position: fixed**, **bottom: 0**, and **right: 0**, that's it. I attempted to use floats and margins to achieve this, which is probably possible, but this is much more intuitive.

**Z-index** is really basic as I'm familiar with it through many other means. 

**Inline displays**, the differences between inline, block, and inline block, and that it amounts to how an element shares its horizontal space, was nice to properly read about. During one interview, I was asked to create a simple navigation header using CSS. Up until then, I relied on solutions that were in the box already to achieve it, and thus was unable to recreate the layout. All that I had to to was create a list, add a couple items to it, and set those items with **display: inline-block;**, and give its container div a border. Really kicking myself on that one.

**Floats**. Float and clear has always alluded me. The second I saw float added anywhere I sighed, but it's straight-forward concept. While I still don't have anything practical done with them, it's good to know where to start.

Margins! **margin: auto** was something I previously read but didn't grasp. It requires a width to be set, which is why I couldn't understand why it sometimes would and wouldn't work. **Margin collapsing** I found interesting, where when top/bottom margins collide, they're not added, simply the biggest one wins.

**Bootstrap** was briefly covered in school. The project I worked on, however, I was in charge of page content, and not layout, so when it came time to utilize Bootstrap, someone else had taken care of it. I'm looking forward to learning and practising it for future layouts!

## JavaScript
Lots covered here, and I only did so briefly. I'm strong with OOP principles, so I decided to dedicate more time to CSS and HTML. I did learn the actual definitions of methods and properties, which is always nice.

JavaScript is really alien to me. I always use strongly typed languages, so trying to deal with type coercion is really awful to me. It's something that would become second nature with experience I'm sure, but at this time seems like one huge potential headache after another.

The differences between **ES5** and **ES6** were touched upon. A big thing was string interpolation. Up until now I've always preferred string concatenation, but going through the interpolation here really makes it an obvious choice. Not only does readability increase, but maintenance seems much easier too.

Function expressions, anonymous functions, and arrow function syntax are really interesting too. I had always seen **=>** thrown around, and **function(param, param) => {}**, but never knew what they were about. I like the ways you can restructure those expressions too.

Privacy not being built in is bizarre to me, but at least I know the underscore naming convention, and can be mindful of what I access and how.

**Babel** and **caniuse.com** were tools covered in the lessons. Babel is great for backwards comparability, but isn't something I've ever had to deal with. caniuse.com was really helpful in pointing out browser comparability, and it something I can see myself using in the future.

# What's Up Next
I'm looking forward to putting these skills to use when I recreate more layouts on CodePen. I also am interested in going back to previous projects and applying this knowledge to refactor some of the rookie work I've done. Even those SEO improvement won't really do me much good personally, the knowledge will help a whole ton.

I'm planning on focusing on learning Bootstrap, some other quirks like **em**? rem? sizing, and diving deeper into JavaScript and learning more web-specific uses for it, instead of the surface explanation Codecademy gave it.