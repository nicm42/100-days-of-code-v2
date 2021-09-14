**Day 1: 23rd July 2021**
I started on the Jest testing. Which was fine until I came to mock the APIs. I thought I had it sorted in the previous project, but that used Axios, although I thought this should be broadly the same. At least I solved the problem with the App test not rendering App - it should be called .tsx, not .ts.

**Day 2: 24th July 2021**
I spent some time today going through every possible way of mocking my APIs, without it working at any point. In the end I wrote a simplified version in CodeSandbox, which also didn't work. And I found that the tests don't run in Firefox, you have to open it in Chrome.
But I also got to spend some of my day having fun with PHP. I did a tutorial on creating what is effectively a blog using MySQL. As always Linux is a bit different, and although the instructor wrote to the database with the root user and no password, that apparently doesn't work on Linux unless you're logged in as root. Which I didn't know was possible - unless it means you have your browser open as root. But I created a new user and that solved it. But it was fun to see it all come together, even if I didn't 100% understand all of it. I did a quick tutorial on cookies too, which are very easy to set and use (in PHP).

**Day 3: 26th July 2021**
I finally got the API mocking sorted by using Axios. I then got most of the testing done in Jest, I just have a few errors I can't fix that will hopefully become obvious, and the Express bits to test.

**Day 4: 27th July 2021**
I finally got all the Jest tests working! It says I'm not covering a couple of lines in one of the files, but I am. I split the Express bits into separate files, then got stuck in a loop with node-ts and it was only happy when it was all in one file. So it's staying like that, because getting errors every time I ran the server was annoying. And all I could find online was other people who were also stuck in the loop.

**Day 5: 28th July 2021**
I got loads done today. I was planning to do the Cypress testing, which I did, and it was a bit of a pain before I worked out what was going on. But not too much to do because there's not much going on and I already thought about what to test when doing the Jest testing. I then dealt with the deploying parts.
For the server I just had to add a couple of lines so it would load the React app from there. The most useful instruction I found is about copying everything into a new folder so I could have both a GitHub git, and a Heroku git. It then took me a while to relate the instructions to my app to get it on Heroku, but it worked in the end! And I had time to update my Portfolio with it.

**Day 6: 29th July 2021**
I had a quiet day today, catching up on the Weekly Web Dev challenges and then doing a few CSS Battles.

**Day 7: 30th July 2021**
I updated my Portfolio and Github Profile to make my Frontend Mentor projects more clear. I gave some Frontend Mentor feedback. I also did a couple of CSS Battles.

**Day 8: 31st July 2021**
Today I did a Flutter tutorial. I liked it - I can see how it would be easy to learn, since it's a lot like React. Although technically what I learnt was Dart. I think. I'm not 100% clear on which is which and what does what.

**Day 9: 1st August 2021**
I started a Frontend Mentor project. I picked a newbie one and than plan is to do it all normally, using CSS logical properties. Then do an RTL version and if I've done the CSS right, it will look the same, just backwards. I also decided to try out another bundler, and chose Rollup. There was some useful posts on dev.to about it, and some Stack Overflow stuff, so although it took a while, I got it doing what I needed to do in the end.

**Day 10: 2nd August 2021**
I started on the CSS and I've done the mobile view, not exactly and minus the active states. Although I thought this would be a good one to test out logical properties in RTL, so far I've not used a lot.

**Day 11: 3rd August 2021**
I did the desktop view, which didn't involve changing too much. And added the box shadow, which is such a pain to work out if it looks the same, just from looking at an image. And then I started on the active state, which is a pain. I got it mostly done for the mobile view, but it's totally different on the desktop view.

**Day 12: 4th August 2021**
I did the active desktop state, which was a bit of a pain. I feel like I've hacked it to get it in the right position and it might need a re-think - once I've thought about how best to get it to work for both mobile and desktop. I think I also need to get the pro subscription, even if just for a month, because looking at things based on the jpg is driving me a bit mad and it would be so useful to see the exact sizes of things.

**Day 13: 5th August 2021**
I added some JavaScript to make the active state show and hide on button click, and added transitions. I realised that since it gives images for sharing, that in a real app they would be buttons, so I made them buttons.

**Day 14: 6th August 2021**
I realised I needed to do some hover states for the buttons - focus was provided by the browser and actually is really visible in both Firefox and Chrome, for once. So I did the hover states. And changed the images to be inline svg so I could change the fill colour. Then I added some radio buttons and script to change the text direction to test the logical properties and it worked! Everything was mirrored. I just need to make them into a toggle and then it's just a case of finishing off the layout to get it looking closer to the design.

**Day 15: 7th August 2021**
Forgot to fill this in! Today I did a Java tutorial. I was a bit put off at the start by putting everything in classed and all the public static void stuff. But once you've done those bits, you don't have to worry about it if everything is in main. Which it probably wouldn't be normally, but when doing a beginner's tutorial it's fine. I found one for making a text adventure game, which I really enjoyed - it was fun to play and easy to see how it all worked.

**Day 16: 9th August 2021**
I did the styling on the radio buttons. Everytime they were in RTL they confused me, but putting the label below the buttons really helped with that. Now I just need to refine the CSS so it's closer to the design and test it on all the browsers.

**Day 17: 10th August 2021**
I played Knights of the Flexbox table. Although it's about Flexbox, it's mostly about Tailwind classes, and I'm not that sold on Tailwind. As I played it I kept thinking it would just be much easier to write it in CSS... I also did this week's Scrimba Weekly Web Dev Challenge, which was really simple. Some of them are but then I end up not sure if I've missed something.

**Day 18: 11th August 2021**
Today's coding time was while I was mostly waiting for things after I'd supposedly finished work, so I decided to install Drupal locally. I knew it would be a pain and things would go wrong because that's always what happens and I was right. But I got there in the end and have a working local installation of Drupal! Very exciting.

**Day 19: 12th August 2021**
I went back to Drupal and spent a while trying to work out how to get Docker to run. I knew yesterday that not following every single installation step would come back to bite me. Once I got into Drupal I read some of the user guide, but decided I'm not sure it's going to help much and following a tutorial will be better. But I did find it needed updating (already) so I had to look up how to do that. And that was pretty much my coding time.

**Day 20: 13th August 2021**
Added Cypress tests to the Frontend Mentor project, so it's testing clicking the button to open and close the share menu, and also the radio buttons for text direction. That's all the JS that's going on in there.

**Day 21: 14th August 2021**
I did Traversy Media's crash course on Ruby on Rails. As with everything, it was installing it that took the time. I generally found it complicated with all the folders going on and where you put everything. But I can see how it's quite English, with added colons.

**Day 22: 15th August 2021**
I finally bought a Pro membership to Frontend Mentor, so I could finish the design from the Figma files. Which was sometimes annoying because I could see mine matched but didn't quite look the same, so still took a bit of fiddling. But overall, much easier than trying to match to an image.

**Day 23: 16th August 2021**
Getting the Frontend Mentor project on Vercel was a complete nightmare. It just kept giving me errors, which I don't get on my computer, but the only fixes I could find were related to my computer (and didn't help). Netlify was just as bad, so there's something going on there. In the end I just took the dist folder out of gitignore so it didn't have to do the build step, but I don't know what it's problem was. After spending all that time on it, adding it to Frontend Mentor and updating the readme will have to wait until tomorrow.

**Day 24: 17th August 2021**
I updated the readme for the FEM project. But couldn't submit the solution. The page either refreshed to give me the filling in option or just thought about it for ages. Having tried in two browsers, I gave up. Something is obviously wrong at their end. I'll try again tomorrow, but if it doesn't work then, then it'll just have to remain unsubmitted.

**Day 25: 18th August 2021**
I started the Drupal tutorial. I'm glad I did because there's a lot going on in Drupal that I had no idea about it, so this is a good introduction. But he installed it a different way, so when I'm done, I'll have to go back and try his installation to see how it works.

**Day 26: 19th August 2021**
More of the Drupal tutorial today. It's slow going because he chats abut various Drupal things while doing something related, so I have to keep pausing it. I am enjoying it and I can see how it's a really useful tool.

**Day 27: 20th August 2021**2929
Now I've properly learnt Drupal - I broke it. I was following the tutorial for a theme, but should have copied the file from GitHub rather than typing it in because that went wrong. And I had to modify a file just so it would tell me what was wrong. But I got it fixed and finished the tutorial. What I need is to find a more detailed tutorial on creating a theme. I could work things out by inspecting them and changing things, but I need a decent overview of what goes where, what you can do and how you tell it what you've done.

**Day 28: 21st August 2021**
Today I did a Fortran tutorial, which was fun. Right at the start when it talked about compiling it, I remembered that. I remember later coming to languages that you don't need to compile which felt strange to me. I remembered subroutines being a thing. But the rest I had no memory of at all.

**Day 29: 22nd August 2021**
I started a tutorial series on Drupal theming. Mostly I just learnt how themes work in Drupal - I didn't need to know so much about how they need to be responsive... Next up in the tutorial is creating a theme, so that'll be interesting.

**Day 30: 23rd August 2021**
I did the part of the tutorial that involved creating a theme. Not so much the CSS, as those files were provided, but how to tell Drupal about them. Which has made sense of the yml files I saw before. But I can tell there's so much going on. And after the tutorial I will have to go and look up more because at the moment I've only seen themes with css and js (and haven't looked at the js yet).

**Day 31: 24th August 2021**
Today was some stuff about twig and regions - a basic introduction. I've got the idea, it's going to be a case of reading the documentation and looking at what other themes have done.

**Day 32: 25th August 2021**
The tutorial finally go to the point where we're creating a sub-theme based on a design. I was wondering how you had more than one thing on a page and this will answer the question. When I get to that part of the tutorial (the end, presumably). But I've left myself something to look forward to tomorrow.

**Day 33: 26th August 2021**
Finished the Drupal theming tutorial! Most of it was about blocks and views, the CSS just make it look pretty and moved some things around. Although one bit wasn't in the right place, but it turns out that's due to the CSS. And it's all floats and I didn't want to go there. I can see all the possibilities, but there's so much in there you can do. Next I need to read some documentation and try making a simple site myself.

**Day 34: 27th August 2021**
I took a break from Drupal to do Traversy Media's Svelte Crash Course, which was only 30 minutes long. And I can see why everyone loves Svelte. It is really simple. It uses Rollup for a bundler, so it's handy I just tried it out on my last project! It's so fast - running create react app takes 7 minutes (I timed it once); I'm not sure this even took as long as 7 seconds.

**Day 35: 28th August 2021**
Today I learnt Rust. Which is hard. Most of the languages I've done on my Saturday series I've liked or loved. But this one I would happily never use again. I'm sure if I learnt it properly and used it a lot I'd get used to it, but given a choice, I'd rather not.

**Day 36: 29th August 2021**
I set up Click the Dot with Svelte and included TypeScript in it. I need to look up how to include Sass in it. I then tried installing Drupal not using ddev, but I think it needs to be in var/www/html, which is a crazy place to put it because I need to be root to change any files in there. Maybe ddev installation is better, I don't know. I need to look into it more tomorrow.

**Day 37: 30th August 2021**
It turned out all I needed to do was to run the server and then I had a Drupal site. So it's all working now and on Git, I just need to work out how best to add the content - once that's in it'll be easier to see how to theme it. I also set up Click the Shape in Svelte. Hopefully it won't be too much work to convert it from jQuery, then make changes and add things. I also set up a Frontend Mentor project in Snowpack, so I can try that out. It took me a little while to work out what I was doing with Snowpack, but I got there in the end - and it was simple to set up.

**Day 38: 31st August 2021**
I did the header part of the Frontend Mentor project for mobile. It took me a while to work out where to put all the scss files and still have Snowpack be able to find the css file. I haven't done this for a bit, so it was hard to start, but I was all right once I got into it. There are quite a few complex things in each section, which is why I chose this layout, so it is going to take me a while. But there's plenty of days of Paralympics left to work to.

**Day 39: 1st September 2021**
I did the header for desktop - which involved fixing the things it turned out I broke when doing mobile... The next section was pretty short. But for some reason Figma said that the text was black and font-weight 400 - the font only has 400 so that's fine. But it didn't look black, I don't know why. I changed it to be a grey and it was more like the design - although I then made it a darker grey so it's actually contrasting against the white background.

**Day 40: 2nd September 2021**
I finished off the creations section. I had to re-do the way I'd done the images gradient with a before element, so that it could have a white overlay on hover. It took me a little while to work out why it wouldn't work with after - because a elements have an after and all the images are as. Once I got that sorted, then the desktop version of the grid wasn't too bad. I had to change my flex to a grid to position the button in different places in each. I then started on the footer section - just sorting out the HTML and inserting the images and doing a few CSS bits to make it all visible.

**Day 41: 3rd September 2021**
I finished off the footer, which didn't take long. And then needed to work out at what point to change everything from mobile to desktop and how it should look in between. Which took longer. I still have a few things that aren't quite right, but they'll be easier to fix tomorrow

**Day 42: 4th September 2021**
They were easier to fix today! I got it done and uploaded. I found when I built it that the background images didn't show up. I changed the links to them to match the build folder and they still work in dev, which is confusing. I got it built in Vercel in two tries (I realised the first time I hadn't told it the name of the build folder). And then all uploaded onto Frontend Mentor, so now it's all done and I can't put off Drupal any longer...

**Day 43: 5th September 2021**
I added content to the Drupal site. Which wasn't as complicated as I thought it would be. It's going to be organising and CSSing it that's going to take longer, I think.

**Day 44: 6th September 2021**
I started on Click the Shape in Svelte. I spent some time remembering what I was doing and reading the docs and getting Prettier to work with Svelte files. But I also added in the select with a list from an array and when one is selected the instructions text updates. Which is pretty cool. And pretty simple in the end.

**Day 45: 7th September 2021**
It was too hot today and I didn't have a lot of time, so I did two week's ago's Weekly Web Dev. That was simple. I tried last week's, but got stuck. I think I need to re-think the way I've done it, but I don't have the energy, so will come back to that another day.

**Day 46: 8th September 2021**
Another hot day, so I did a bit on Click the Shape, adding the shapes and the closest scores. I'm still setting up the shapes twice (which is at least an improvement on three  times) but fixing that will be for another (less hot) day.

**Day 47: 9th September 2021**
I started on the Drupal theme by creating the yml file. And finding the theming documentation. I at am now reassured that I know how to start and what I need to do next.

**Day 48: 10th September 2021**
I thought I'd add the SCSS file from the previous Click the Shape into this one and it would just all work. Wrong! I ended up having to add the bits into the components, which I haven't decided is what I want to do yet. And it's currently ignoring the media queries. I think I will need to find a repo or tutorial using SCSS to see how they've done it.

**Day 49: 11th September 2021**
Forgot to fill this in yesterday, but wrote the blog post. I did Traversy Media's crash course on MySQL. Which all made sense, and I'm glad it included how to use it in Node, as it turns out to be easy. The hard part was re-setting my root password because I didn't know it, and every step I took I got errors. At least I gave the Spaceship Store's database its own user, so it's not been affected by any of that.

**Day 50: 12th September 2021**
Halfway through! I worked out what Drupal regions I wanted by trial and error (very much error when things disappeared...). And then added a Google Font, which took a while as I hadn't considered that I needed to tell it I wanted to use said font. I think I need to do some CSS now to get it looking how I want. And then remind myself how to use the breakpoints.

**Day 51: 13th September 2021**
Back on Click the Shape, I added the results section. I wondered why it wasn't showing, was convinced it wasn't using the mixins and then eventually discovered it was because the button was hidden. For some reason the layout is all messed up on bigger than mobile screens, but since the CSS all needs re-writing anyway, I'll save that for later. As long as it all shows up that's good enough to get it working.
I then looked at growing the shape when you click on it. I did it the old-fashioned way, then discovered Svelte has some stuff to help. I used transition but it's for making things visible and invisible (which I'll have use for later). Tween turned out to be the one I wanted. And it works well. Next up will be working out how to stop it on another click.

**Day 52: 14th September 2021**
I didn't like the five ships in a row grid, so I added a new one, so it can be two rows of three ships. Since I used a website to remove the background on the new one, I did the same on the other images, so they look better than with my previous dodgy background removal. I then set it to re-size the images so they're not too big. And realised that the grid layout in the View is crap - there's tables in there and it's not responsive, so I unticked the box for the default classes and added a grid myself. It still needs some formatting - and it will need some breakpoints, but at least everything's not right up against each other.
