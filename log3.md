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

**Day 13: 20th April 2021**
I worked out what GitHub's problem was and got rid of the error message for my domain. I still can't get it to show the latest change, but I will save it for tomorrow, in case it works it out in the meantime. I've tried a load of things from StackOverflow and none of it worked.
I started on a Styled Components tutorial, but he didn't explain anything and I could barely see what he was typing. So I started on a longer one instead, which looks like it will be better. But I've only got as far as doing the set up - create react app takes so long to install.

**Day 14: 21st April 2021**
I did the Styled Components tutorial and I get the basics. Which is enough for now - I'll learn anything more complicated as I do it. Especially as it'll make more sense when I'm doing my own things and transferring my thinking from SCSS to Styled Components.
I looked at my portfolio and realised the problem was that for some for reason the CSS hadn't updated. I'm sure that when I changed it I ran Gulp and checked it offline, but maybe I didn't. But it is fixed now.

**Day 15: 22nd April 2021**
I looked at the thread tracker (with a proper fork this time) and now I've learnt Styled Components it all made so much more sense. It was so quick to make the change that I couldn't help thinking I'd done something wrong! It took me longer to fill in the details on the pull request.
And then I found a new issue, so that might be a job for tomorrow!

**Day 16: 23rd April 2021**
I made a requested change on the thread tracker, that was simple. I spent quite a bit of time investigating the issue I opened to try and narrow down if the problem is Linux, Linux Mint or just my computer. I then set up everything for the Bookfinder project. I thought Create React App took ages to install everything when I did it for tutorials. But when I timed it it only took 7 minutes, which isn't bad when my computer is getting old and slow.

**Day 17: 24th April 2021**
I did the fix on the thread tracker - it turned out to be simpler than I thought. It took less time to fix than it did to test in all the browsers on Linux and Windows! I then pointed my Hashnode blog to my domain and the projects I have on Netlify in my portfolio. I had second thoughts about my avatar on my portfolio, so I changed it to my logo - which took a while because I didn't have one big enough or in the right shade of red, and then I discovered I didn't have the font either, so I had to find it and re-download it.

**Day 18: 25th April 2021**
I went through SEO stuff and added some meta tags, robots.txt and sitemap to my portfolio. Some of that is overkill, but some of that should mean that the featured bit in LinkedIn should now pick up a decent image (or any image at all, in the case of The Newport Group).

**Day 19: 26th April 2021**
I started the bookfinder project. It's so going as I thought I knew this stuff, but it's harder, starting from scratch! I'm trying to do TDD at the same time, so trying to think about what to do, then write the test, then write something that will pass it. And at least set things up in styled components, even if I'm not doing any of the CSS yet.

**Day 20: 27th April 2021**
It still feels like slow progress on the bookfinder project. I set it up to have space for the information and set up the function to do something when the button is clicked. Next I need to sort out the API so I can make a call to it.

**Day 21: 28th April 2021**
I looked up how to hide your API key and places said you need to put in Node in the backend. So I went through FreeCodeCamp's basic Node and Express module, but I only vaguely understood it and it didn't help me work out how to integrate it into my project. So I went looking for videos and found one about using Netlify functions and how to have your APi key on your Netlify project, but still hidden. So I will try following that.

**Day 22: 29th April 2021**
I didn't have the brain for the bookfinder project today, but on my to do list is finishing Scrimba courses I've started. So I did the coding part of the Web Dev tips. It started with things I knew, but then there was an introduction to TypeScript. It has been on my list of things to learn, but having seen that bit I'm thinking that the best way to learn it would be to take something I've already created in JS and convert it to TS. That might be (optimistically) a weekend project. There was also a lesson on optional function execution using &&. Which I've never quite got the hang of, so haven't used - although if I tried using it I'd probably get the hang of it. It was good to have a lesson on and try using a bit of it.

**Day 23: 30th April 2021**
I went through Scrimba's TypeScript course, which was basically all about types. I guess that's where the name comes from. I then had a look at a couple of videos about installing it and using it on your project. had a look at Guess the Number and it's not long, so I think it shouldn't take too long to translate to TypeScript. Although it is a bit old, so I'll need to split the JS files and update the SASS splitting. And probably update some of the stuff I've got installed too. And, since it's the first thing I wrote with TDD, have a look at the testing to see if there's anything I can add/improve. So all that might take longer than the TypeScript part!

**Day 24: 1st May 2021**
I started on converting Guess the Number to TypeScript. By which I mean I opened it, realised my Jest tests were terrible, so spent the day splitting the JavaScript into separate files and then trying to get the tests all working. I eventually managed to sort it out and get 100% coverage. I was so used to testing React that testing JavaScript was suddenly quite weird. Having looked at the game quite a bit I can find some other things to improve, but one thing at a time!

**Day 25: 2nd May 2021**
Converting to TypeScript didn't take long. Although I discovered there's things you have to do to deal with DOM elements, which weren't mentioned in the Scrimba course. I then tidied up the HTML and JS, and updated SASS to use @use instead of @import. And added some tests in Cypress. I think it's done now, I just need to come back to it with a fresh brain tomorrow to double check and see if I can build it in Netlify, rather than including the dist folder on GitHub.

**Day 26: 3rd May 2021**
Checked Guess the Number, and it was fine, but it didn't build. I had to update a dependency. That took longer than I thought it would. But I then gave some feedback on a couple of Frontend Mentor projects. Going back to the Bookfinder project, I thought I'd better look at Google Books API. And I found that it doesn't need a key. All that research on how to hide it will come in useful, just not yet.

**Day 27: 4th May 2021**
I added the API call - which took a little while because I first put it in a separate function, which then ran when the page was rendered. I then got the relevant bits of info so I can at least mock up some cards. I realised that the input and button need to be in a form, so you can submit by typing then pressing enter. I installed TypeScript and then discovered the whole thing is more complicated than I thought, so I need to read some stuff on writing TypeScript in React.

**Day 28: 5th May 2021**
I converted everything to TypeScript and it all went ok. And then I updated ESLint and spent the rest of the time sorting that out. And now Prettier is being a pain and the API call isn't working any more. So not the most productive day ever. Hopefully it won't take long to sort out tomorrow.

**Day 29: 6th May 2021**
I finally discovered that ESLint was using CRA's rules and not mine and it would have been better all round if I hadn't touched anything. But now I have, I have got it to use my rules (on top of its own). At the moment I have things on warn so I can decide what I want to do with that rule later. And I'd managed to delete the = out of the API call, which is why it wasn't working. I then updated the tests to use dummy card data. Hopefully I've finished fiddling with TypeScript and ESLint and can work on getting the API's results into the cards.

**Day 30: 7th May 2021**
I realised that rather than mapping through my card data and adding the information into Card, I instead need to have one Card component and I map through, adding that however many times it's needed. Which sounds simple, but I realised I didn't know how to pass the props down, and I definitely didn't know how to do it in TypeScript! I got there in the end and now I understand how to do it. I ran out of time to fix the tests accordingly, since I moved things and renamed things, but sorting those out will have to wait for another day - I couldn't do them first, as you should in TDD, as I wasn't sure what I was doing!

**Day 31: 8th May 2021**
I was going to sort out the tests today, so I did the card one and then struggled dealing with dummy data. And then realised that the real thing will use API data, rather than dummy data, so I would need to do it a different way anyway. So I instead sorted out how to get the API data from the Search component to the Card component - I went via a state hook on the parent component and passed it down. Which took a while to work out how to do in TypeScript. After spending ages trying to get the data to update all the relevant bits, I realised I can just shove the data array in there and pick out the bits I need in the Card.

**Day 32: 9th May 2021**
I managed to add a test for axios running on button click, but couldn't get it to work for axios failing, even though it definitely works in the real thing. I spent a lot of time trying things, and have had a lot of different error messages, but nothing that worked.
I thought I was done for the day, feeling terrible that I didn't achieve much. I went back to this, immediately found the answer, and realised I had another couple of things I needed to test. I now have 100% coverage (in Jest) for the Search component! It feels like I'm getting somewhere now.

**Day 33: 10th May 2021**
I looked up how to exclude index from the test coverage report, so it looks a little better. I spent ages on the app test. I realised that I don't need to mock my card component because it's either not there if there's no data yet, or is there if there is. But I've yet to work out how to get it to mock having some data to map through without getting errors.

**Day 34: 11th May 2021**
I didn't have much time today, plus I've been stressing out over getting that test to work (although I have some ideas now, just not enough time to test them). So I did three of the Weekly Web Dev Challenges on Scrimba. It was good to do something simple and try and remember how to write JavaScript, after spending time with React!

**Day 35: 12th May 2021**
Today really exemplified the idea of stopping when you're stuck. I implemented my solution to the problem I was stuck on on Monday and it was all sorted in about five minutes. And then finished off the rest of the testing. Annoyingly, the code coverage says I'm not covering one line, but I am so I don't know why. I have got some notes of other functionality I need to add in, so it's not something to worry about now because that could change.

**Day 36: 14th May 2021**
A day's break really helped, plus setting myself a deadline. I converted my tests to TypeScript. One was fine, which I didn't expect. One of the errors I found a solution for easily. I had two other errors that I searched for alternately, which helped. They were both obvious when I found the answer, I was just overcomplicating things!

**Day 37: 15th May 2021**
I got loads done today. I added a PropTypes check - it needed everything that I was using, so that took a while just to type out! I then added testing for if any information is missing (apart from the book ID, which I assume it must have) and added a way to test it in the browser without needing to use the API. And added a loading element. Which is more complicated than any tutorials, as they assume the API will be loaded when you load the page. So I had to do some more state passing.

**Day 38: 16th May 2021**
I added an element if there's an error. Which all works ok, but the test thinks it worked even before I added it and it complains about me updating a state in the catch. I think I need to mock the Search component when doing App tests. Which is a problem for another day.

**Day 39: 17th May 2021**
I went on the Scrimba discord to ask about whether it was a good idea to move getData to App and there was an answer to someone else asking something similar! So I moved it and then played with httpstat.us to test out error messages when the API errors. Despite adding more tests for those, Jest coverage still says a I have a few lines not tested - even though I'm definitely testing them, in one case I'm finding it based on the text, so it's definitely covered!

**Day 40: 18th May 2021**
Some googling and playing with the API meant I found how to search by title or author (but you can't search by both). I added that into the app, and also a dropdown so you can say which you're searching by. A load of tests need adding to test the API is including them, but that's for another day.

**Day 41: 19th May 2021**
I had a load of error messages on my axios tests, so I started one from scratch and managed to get rid of the error. And the other one that came up complaining about act(). But my tests are passing when they shouldn't be and going to the catch, which is probably related. But that will be a problem for another day.

**Day 42: 20th May 2021**
Not much time today, so I did the Scrimba Weekly Web Dev challenge. This week's one as well! I just have a whole load of older ones to catch up on some time.

**Day 43: 21st May 2021**
I was so stuck on the axios testing again, until I came across someone saying that you have to mock the test before you render. And all of a sudden it worked! I did then get some errors because I realised I set my dummy data up wrong and it wasn't quite like what you get back from the API. But once I fixed that I could then test other things. Which I will be saving for tomorrow.

**Day 44: 22nd May 2021**
I finally have 100% code coverage! The reason I didn't before is that the axios testing that I thought was working, wasn't. I have sorted out the rest of the axios testing, made the dropdown required and cleared it on submit, and formatted the authors, if there's more than one. The main thing left to do that's not CSS is adding pages and getting more data, which I haven't decided how to do yet.
