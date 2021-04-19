**Day 1: 6th April 2021**
I started on the next FCC project, which is a calculator. I passed all the simple tests, which involved having the things exist. And then when it came to do the calculations that got more complicated. I thought I'd worked out how to do it, but it's not doing what I think it should. So I'm going to come back to that another day and hopefully it will be obvious.

**Day 2: 7th April 2021**
Continued to work on the calculator. At one point I had nearly all the tests passing, updated it to pass another test, but then it passed fewer. It doesn't help that you can't see much code at a time in Codepen.

**Day 3: 8th April 2021**
Finally finished the calculator! After ages fixing things and breaking other things, I finally got it sorted out. It helped when I copied the code into VS Code so I could see more of it and Codepen didn't update every time I typed something. Streamlining it was the way to go in the end.

**Day 4: 9th April 2021**
I started the last project, the 25+5 timer. Which has 29 tests! I put the elements in and some state and functionality and formatting and it passes 18 of them. I still have the timer to go. But I went mad trying to get the time-left ID into the right format - I tried a couple of things then ended up converting everything to seconds and then having to deal with 1 hour needing to be changed to 60 minutes. I got there in the end.

**Day 5: 10th April 2021**
The 25+5 timer was such a pain. I did learn a lot - like how state updates asynchronously, so I put all of my initial states into an object, which helped. And then I found that I needed the timer to only change once the state had updated. Which worked, but then the tests failed because they expected it to work sooner. I didn't want to re-write the whole thing as a class component, so I had to leave it with some of the timer tests failing (they all worked at some point, just not all at the same time). It was enough to get me the certification! I just need to go back and do the Redux bits at some point.

**Day 6: 11th April 2021**
I started today looking at GitHub Actions to test your code automatically on the main branch. Which didn't work - from the error messages I suspected it was because it wanted to be building it and using those dependencies. A tutorial video on doing this with Cypress confirmed it. I'm not building The Newport Group in Github, but in the course of this I found that you can get GitHub Actions to do that for you. So I think this is something to come back to on my next project (and do some tutorials first).
I then started looking at the RP Thread Tracker. After a while of puzzling through it, I eventually discovered it uses Styled Components (as well as SASS and Bootstrap). So I have started learning that, so it will help me understand more of what's going on with the Thread Tracker.

**Day 7: 12th April 2021**
I discovered yesterday that PluralSight is free for the month. So I signed up for a couple of React courses. And then today ended up doing a React Hooks course on Scrimba, since it was also free. And it covered the basics I knew about hooks, but also things I'd done but didn't know why I was doing them, so that was helpful.

**Day 8: 14th April 2021**
I finally started one of the PluralSight courses - this one on using APIs in React. I've done the first lesson, which was mostly about explaining the code. And then adding in the API without explaining it. I don't really understand what's going on with the code. But I'm hoping that I'll learn something - there is some stuff later about React Query, which I've heard of, but that's it. And some testing and error handling, which are the bits I'm a lot less sure about when it comes to APIs.

**Day 9: 15th April 2021**
Today I did a tutorial on the FreeCodeCamp news page about creating a book management app using React Router and React Context. I did sort of understand what's going on, but I definitely need to learn more about React Router and React Context. The custom hook for using local storage was really useful - I can definitely imagine using that in the future.

**Day 10: 16th April 2021**
I did a tutorial on React Router. Most of it I knew, then when it came on to the bits I didn't it stopped being a tutorial and ended up being more of something to read. Based on what I know so far it's not something I immediately need to know, so it might just be a case of knowing it exists and then reading more about it when I come to use it.

**Day 11: 17th April 2021**
I went back to the PluralSight course. Although it looks like there are some useful things coming up I'm not learning anything from it. I'm just finding that nothing he's doing is really explained - I'm just typing some things and I don't know why. So I'm going to give up on that.

**Day 12: 19th April 2021**
I pointed GitHub Pages to my domain name. Which worried me for a bit, because there was a period of time when going to my GitHub Pages page sent me to my domain name... which then gave a blank page. It turned out I had to add some A records and give it some time. But while doing it I found something not looking quite right in Chrome. So I fixed that - and found that something had gone mad in my folder and some of my images in the old folder had been copied in the main folder. So I fixed all that. But the update hasn't (yet) shown up on the web. And GitHub is complaining that I haven't done the CNAME bit. It does say that it can take 48 hours, so I will give it some time and see if it works. And wait to move anything else. 
