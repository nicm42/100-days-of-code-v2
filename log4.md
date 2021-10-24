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

**Day 53: 15th September 2021**
I discovered Svelte's docs have a pausable tween, so I added that in, so now the shape stops growing on a second click. I then made the helper show, which took a little while to work out how to do. I ended up adding a class to change it from display none to display block. And then used the same idea to take the hand shaped cursor off the shape once it's stopped.

**Day 54: 16th September 2021**
I spent a while today trying to work out how to get the contact form on the same page as the rest of the about elements. In the end I found a module that turned the contact form into a block, so it's on the same page, if not where I want it. But I'm going to style them with a grid anyway, so I can rearrange them. Then I installed a module that does carousels. There were no instructions on how to use it, but I found a tutorial. However, it's still got them one below the other, just with the addition of previous and next buttons. There are a lot of options, so it could take a while to find the solution. But that's for another day.

**Day 55: 17th September 2021**
Back on Click the Shape today. I realised I needed to do all the finishing bits when the tween finished. I found a mention of being able to do something when it's complete, but nothing that actually told me how to do that. So I ended up doing it with a timer. I may try looking that up again another day because I don't like that solution. I then added the text to the results section and made it show at the end. And added the closest scores to local storage and display them on page load.

**Day 56: 18th September 2021**
Forgot to fill this in again, but I learnt some Swift. Just the basics of how to write it, because doing anything requires more exciting requires a Mac.

**Day 57: 19th September 2021**
Fought with the Slick carousel in Drupal. After trying lots of things I discovered all the errors in the console. For some reason it couldn't find the CSS and complained about Blazy. I changed the theme back to Bartik and now it's complaining that it doesn't like the CSS and complained about Blazy even more. So that's sort of progress...
Later: I had a bit of time so I looked into the carousel some more. I found that the error message in Bartik was because it couldn't find the CSS. I found something that told me I'd put it in the wrong place - I put it in the right place and magically, it worked! It's still complaining about Blazy, even though I don't think I'm using it, so I'll need to look into that. It also looks terrible, which I need to use a combination of options and CSS to fix.

**Day 58: 20th September 2021**
I deleted some of the crap hanging around from trying to get the Slick carousel to work. Then decided to start on the ships page. For some reason, setting Grid in the views made my columns all really narrow. So I turned that off and just went with CSS Grid instead, which works much better. It was pretty cool that in the view I could stop the title from being a link, but then add one to to the bottom. The CSS is at least easier since I know it, although using CSS rather than SASS takes a bit of thought. And it all takes a while because I have to look at the class names, try it in the browser, then do it, then wait ages for drush to clear the cache.

**Day 59: 21st September 2021**
I finished the ships page! Including adding media queries to the grid so it shows an even number based on the space the ships take up. I know you still need a breakpoints file (maybe?) but I can't remember what it does, so I will have to look that up. I discovered that it does pick up the changed CSS without needing to clear the cache every time, so that will save a lot of time when I come to do the other pages.

**Day 60: 22nd September 2021**
A frustrating day today. I discovered some of the changes I'd made to the ships page affected the other pages too. The solution is to use twig, which I am all for because I haven't done a lot with it. However, none of the options for showing the twig files used worked. Not in Firefox or in Chrome. I have no idea why. I ended up finding a class that was unique to the page and adding that to the beginning of all the classes. And then I started on the about page, but I think that's going to be a problem because the contact block is in a separate div from the rest, so I can't just put a display flex on the page.

**Day 61: 23rd September 2021**
Another search for styling a specific page in Drupal told me that there's a body class that tells you what the page is. I could have saved so much time last night. I've now got that all over the place in each file. I finished styling the About page. I couldn't get it in the same order as the original, but I could at least get them all in a row when there was enough space. I started on the carousel, which is hard to do anything on because it keeps moving!

**Day 62: 24th September 2021**
I did Saturday's language learning today, so that I could spend the whole weekend on a Frontend Mentor project. Which I'm hoping I can fit into a weekend. I learnt the basics of Perl, which was pretty similar to JavaScript and other languages. But when it was different it was really different.

**Day 63: 25th September 2021**
The answer to the question of whether I can program a Frontend Mentor project in a weekend is yes, because I've nearly finished it in a day. I just have to do some more testing and refine the SCSS a bit, then it's done. Now I've written that down that could well take a day, depending on what I find, but it should be done tomorrow anyway.

**Day 64: 26th September 2021**
I finished the Frontend Mentor project. When uploading it I found all the HTML and accessibility issues. I'd just been thinking about getting it done and got a bit div-happy. So that was some fun last-minute fixes... It is all done now, though, and tomorrow I need to give some feedback, since I've been meaning to for ages.

**Day 65: 27th September 2021**
I finally did some Frontend Mentor feedback. I started off with challenges I'd done, but then went to anyone who had a query I could answer. Every time I do it I think how rewarding it is and how I should do it more often and then end up putting it off. I also went back to Click the Shape. It took me a while to think about how to reset the shape, but I got that done eventually. And then just a couple of randomisations and it's up to where the previous version was (albeit with layout problems and a strange bug, but they are for another day).

**Day 66: 28th September 2021**
Back to Drupal today, before I forget what I'm doing. The carousel is now nearly done, it's just moving the title and body fields on top of the image that's left. When I tried using a position absolute, like I did with the arrows and dots it just made the image small. Investigating that will be for another day. I got as far as stopping the carousel from autoplaying because it was driving me mad trying to see anything when I inspected it.

**Day 67: 29th September 2021**
I finished off the carousel, which involved going into Views and putting an HTML tag around the title, so then I could absolutely position it. I then did the nav, which was pretty simple, and added a favicon. And the realised that some of the text on the carousel isn't visible against some of the images, so I'll have to darken them tomorrow.

**Day 68: 30th September 2021**
Very nearly finished off the Drupal site! Just a couple of small things to look at (at least I think they're small) and sort out the readme and it's done. Since I'm not putting it online, it will need a lot of screenshots.

**Day 69: 1st October 2021**
I Investigated the breakpoints file and I don't think I need it, but I added one anyway for the sake of completeness. I then spent ages taking screenshots of every page, since I'm not uploading it anywhere. And the Drupal Spaceship Store is done!

**Day 70: 2nd October 2021**
Today was F#, which looked simple to get it to work on Linux, but it just wouldn't install .NET. Or at least it didn't look like it did, but VS Code now thinks it did. I ended up in Replit, which made things a lot easier. I looked at the languages they supported and there's loads in there I've never heard of, so I'm not going to run out of languages to try for a while.

**Day 71: 3rd October 2021**
I started testing Click the Shape. It started slowly as I worked out what was going on, but now I've got the hang of it I've done some simple tests - mostly just that text is there. A lot of it changes things in other components, so I'll stick to checking the text for now, and then check that one thing changes when you change another thing. I imagine the testing will take a while, because it always does, just working out what's going on.

**Day 72: 4th October 2021**
More testing. I've pretty much done all the simple bits and got onto some local storage testing. I still have most of the interactivity to go, but it's taking ages because the tests just took ages to run. If they fail they take longer.

**Day 73: 5th October 2021**
I have nearly done all the unit tests. Except through them I found a bug. And then found two more... And can't see how to fix them, but there was something weird going on where it also wouldn't live reload, so I don't know if that has something to do with it. Hopefully it'll be more obvious tomorrow...

**Day 74: 6th October 2021**
I discovered what I was doing wrong yesterday was running npm start, when I should have run npm run dev. Running the right thing helped a lot... It then turned out that my fix for clearing the scores did work, so that was something. I then finished the Jest tests! My coverage is not 100%, but as always, the bits it says I haven't covered, I have in fact in the tests. So I won't worry about that. I just have an annoying bug that doesn't always happen to fix now...

**Day 75: 7th October 2021**
I had an idea about the bug and it turned out to be right - I think. It's hard to be sure because it didn't happen all the time. But it was because I was running the finished growing function on a timer, and I changed it to watch for grow becoming a 3 (pretty cool that you can do that!). I then did some styling - I removed a load of divs and elements that had classes that weren't used anywhere.

**Day 76: 8th October 2021**
I finished off the SCSS. After fiddling with the closest scores, I found the easiest option was to just put them in a table, that way they'll always be lined up. I did the layout for desktop, although I'm not sure about it. It makes sense to use more horizontal space, but there's not much going on. I can't think of anything I'd like better, so I might have to live with it for a while and then see if I come up with a better idea. I then played with the clear scores button, making sure it's disabled when there are no scores to clear. A reactive variable came in very handy to do it with. It just took me a while to realise it was working and you couldn't click it, because it still changed colour on hover and had a hand cursor.

**Day 77: 9th October 2021**
Last week when I decided to try Lua, found tutorials making games with Lua/Love2D I thought it would be fun. And I was right, I loved it. I followed a tutorial to make a really simple game, and loved it so much I extended it once I'd finished the tutorial. I am definitely going to learn more about Lua and Love2D. I like the idea of making games as a side project, since it'll be different to what I do at work. And since I like making websites, which I'll be doing at work, and like making games, I can do that at home.

**Day 78: 10th October 2021**
I got loads done today. I did all the Cypress testing and updated my Jest tests to TypeScript (which wasn't too bad). I then added in the functionality to use spacebar rather than clicking, so then needed to update the text and all the tests. I felt guilt about using a load of awaits in my Jest testing, so I changed them to waitFor, which all worked perfectly. I then did a bit of aXe and Wave testing and fixed a few things those brought up that I had forgotten about/hadn't considered. After all the fuss I had with the closest scores and making it a table, it works perfectly well as a grid. I'm not sure why I hadn't done that in the first place.

**Day 79: 11th October 2021**
I added three more shapes, which I thought would be simple, but finding them was hard. Once I had them I discovered that the closest grid wants to fill everything in in order, so if there's a ratio missing, it'll fill that space with an icon. Which is probably why I didn't use a grid in the first place. And also, for some of the shapes the helper doesn't look centred. I thought this was true for the triangle before, but assumed it was just a trick of the shape, but it's not, it's because the shape doesn't completely fill the viewbox in all directions. I think. Anyway those are tomorrow's problems.

**Day 80: 12th October 2021**
I got more done than I thought today. I realised last night how to fix the closest grid - so instead of only rendering the scores if it's there, make it invisible if the score isn't there. I then played about with shapes - once they're centred within the box, they're fine. And updating all the tests was quick and easy. I then started on adding a count of the number of tries at clicking on a shape to get 2.0. I thought it was easy, tested it and found I'd not thought it through. So that's something for tomorrow.

**Day 81: 13th October 2021**
I fixed the number of tries problem easily. And then started on MongoDB. I found a tutorial on NetNinja, which was good and although I found some websites that say what to put in, he explained why it was there and what was going on. So I am all set up with connecting to the database, I just need to work out how to connect it to my Svelte files, which the tutorial doesn't cover, since it's all back end. But looking at the project I did before using Express, I should be able to figure it out, with some Googling for tutorials. At least knowing React means I can look up React tutorials and understand how to apply them to Svelte.

**Day 82: 14th October 2021**
I thought connecting up the front and back end would be easy, but it wasn't. I added a proxy, but it needs Webpack (or CRA) so I ended up putting the whole link in there. And it turned out it didn't like Axios. So I took that out and just fetched it instead, and it finally worked. So that was pretty much all of my time. I did add routes and models for each shape, but now I'm thinking that I should just have one database and pick out the shape that's needed from the data, as otherwise adding new shapes involves a lot of work.

**Day 83: 15th October 2021**
I changed the database to include scores. And realised when I did it that I'd set it up wrong before anyway, with my dummy data, as I had name as the key, not a key-value pair. I then filtered the data to get the data just for the current shape. Then added a new component which pops up a div with the names and scores in it. I just need to add more text to it and make it look nice. And then go onto posting data.

**Day 84: 16th October 2021**
Got a load done with the high scores component. I made it look good, which took a while. Then I realised I needed a button to open it. And also a message if there's no scores or an error or when it's loading. So I found out Svelte's way of doing that an added that in. But now it's all done, it just needs changing to only open when the ratio is 2.0, but it's easier to keep it doing it when you click a shape for testing.

**Day 85: 17th October 2021**
Today was about posting scores to the database. I spent a while on the form and figuring out the Svelte way of doing things. Then wasn't at all sure about posting, but it turns out that you just change get to post and find to save in Express, then in JS tell it the method is post and it's done. So that was easy. It then took me a while to work out how to close the component and update the highscores table. I had to get the data back from the database again, but I can't see how to do it without changing from the Svelte way of doing things. Which I want to do, for the sake of learning how things are different in Svelte.

**Day 86: 18th October 2021**
I updated the code so the highscores only showed when you got a 2.0 ratio. And then found that whenever you click the button to view scores, the opportunity comes to post the scores. Having thought about ways round it, the only thing I could think of was to remove the button. No one will notice it's absence since they'll never know it was there in the first place. I tried it in a couple of browsers and then fiddled with the CSS a bit with the focus states. And then found it can't connect to the database on my phone. I don't know why.

**Day 87: 19th October 2021**
I fixed a couple of tests that were failing because I'd updated the props on those components. And then started on testing everything I'd added to interact with the database. I added some bits to mock the server, then realised I wasn't sure where to add that or how to test the await block. I ended up doing some testing of the text on the new bits, because I at least knew how to do that. The rest I can look into again tomorrow.

**Day 88: 20th October 2021**
Brad Traversy put out a video with an Express backend and through that I realised that connecting both doesn't require a proxy, you just tell Express to serve up the index file. Obviously with Svelte that is only going to work once you've built it, so there are some things to change before building, but it works perfectly, no Webpack required. I then uploaded it to Heroku which would have been simple if I'd copied the package.json into the right place and updated it to the right command for start. Of course once I got it working I realised there was a bug, but I am feeling closer to getting it done, now I've at least got the server/front end connection and deployment sorted.

**Day 89: 21st October 2021**
I though the bug I found yesterday was going to be complicated to fix and involve a lot of of re-writing. Turned out I just had the wrong variable name in one place. So I tidied up some stuff and re-uploaded it and I think it's ready to send round. I still have some automated testing to do - but some of it I can't work out how to do because it's based on having a ratio of 2.0. But I can continue to look at that.

**Day 90: 22nd October 2021**
I didn't feel like I had a brain today, so I caught up on some videos and did enough katas on Codewars in Lua to get to 7kyu! Which was really hard to start with as I tried to get my head around how to do write in Lua and what the error messages meant (often that I'd missed the return statement or an end statement). But it was really useful for getting used to writing some very simple code in Lua

**Day 91: 23rd October 2021**
I did a C# tutorial, which was interesting. Visual Studio has a lot going on. And it felt like it complaining at the lack of semi-colons at the end of lines was a bit much while I was writing that line. But you could build and run your program with one click, which was pretty cool.

**Day 92: 24th October 2021**
I updated a bit of wording on the postscores and fixed the tests. Then I declared Click the Shape done. 
