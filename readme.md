# Artist Portfolio Project

## Overview
Another project! This one will be pretty simple, again mainly to practice my CSS skills, nothing too fancy. This project is a relatively simple Ceramics Artist portfolio website, I'll be using my name as alias, althought I have actually done simple ceramics when I was in grade school.. So I guess its somewhat fractionally legitimate. 

I thought to my self, the more I practice, the better. Familiarising myself with Git as well is important. I also noticed that these readme's act as a journal entry of my progress, process and understanding throughout.

### Commit 1 (19/03/23)
Added initial markup for the header section including nav.

### Commit 2 (19/03/23)
I added the font I want to use and overall during this commit styled the navbar, I noticed that its much easier tackling the website one section at a time, rather than adding markup for the entire website and then styling it that way. I feel like it would get too crowded. 

But essentially I changed the display property to inline-block to add all the elements in one line together, I also get to practice using classes and descendant combinators. 

I've also noticed the default margins that some elements such as the h1 and the li, I know that you can apply a reset before styling css. However it's good to know here that regardless you have to set the value to 0, otherwise it will stack on top of the default.

### Commit (20/03/23)
Added images in the body that will display as a gallery of ceramics works, images are not mine and are loyalty free. I simply added width relative unit for now. 

### Commit 4 (20/03/23)
It's extremely clear how powerful and incerdibly useful  CSS flexbox and grid can be when laying out different elements or items. During this commit all I'm trying to do is figure out how to layout the images in a gallery grid layout. 

I placed each image inside a div with a class of card, wrapping the h2 and the image together. I had to set the display to inline block, so they are able to sit next to each other, in this case I set the width enough so that 2 images takes up the row. Again, this is not responsive, I'm just practicing some fundamental CSS, otherwise I would definitely have just used flexbox or grid. 

The width that I set for the card div is just a little bit under 50%, because at 50% it overflows and pushes the image to the next line. So that's why I set it at 49.75%.

I also set the images itself to have a width of 100% so that it takes up 100% of the parent, which in this case is the card div container.

One last thing to note, is that I used box sixing border box to contain the sizing even more, otherwise it overflows and pushes the images to the next line. I did this so I'm able to use padding to create space between each images.

Again, probably the most inefficient way to create this layout.