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
