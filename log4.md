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

**Day 27: 20th August 2021**
Now I've properly learnt Drupal - I broke it. I was following the tutorial for a theme, but should have copied the file from GitHub rather than typing it in because that went wrong. And I had to modify a file just so it would tell me what was wrong. But I got it fixed and finished the tutorial. What I need is to find a more detailed tutorial on creating a theme. I could work things out by inspecting them and changing things, but I need a decent overview of what goes where, what you can do and how you tell it what you've done.

**Day 28: 21st August 2021**
Today I did a Fortran tutorial, which was fun. Right at the start when it talked about compiling it, I remembered that. I remember later coming to languages that you don't need to compile which felt strange to me. I remembered subroutines being a thing. But the rest I had no memory of at all.

**Day 29: 2nd August 2021**
I started a tutorial series on Drupal theming. Mostly I just learnt how themes work in Drupal - I didn't need to know so much about how they need to be responsive... Next up in the tutorial is creating a theme, so that'll be interesting.
