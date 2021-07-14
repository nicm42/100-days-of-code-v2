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

**Day 45: 23rd May 2021**
I realised I wasn't showing a message if no books were found, so I added that. I had to keysmash to get no results from the API! I then did some stuff with searching the API x times, so you can get all of the books. Currently it just searches 10, then you can search the next 10 etc, but can't go back or skip 10. That requires more thought (not least about whether it's worth doing). I did a couple of Weekly Web Dev challenges. I watched a video where they mentioned leetcode, which I thought I'd done before, but either I haven't, or it's changed a lot since then. I did a couple of easy challenges, and it took me a while to see exactly what was being tested - codewars is a lot easier to see in that respect.

**Day 46: 24th May 2021**
I got the bookfine project to go back 10 books. Which was tricky because it seemed like the only way to do it was to update states based on other states, but only if going backwards... I managed to find a way round it. And then discovered I needed to add more books to the tests, so it could test what happened if there were 10 books on a page going both forwards and backwards. I did another easy leetcode thing and an easy Weekly Web Dev Challenge.

**Day 47: 25th May 2021**
I abandoned leetcode because I just got annoyed with it - it's just so hard to tell what's going on in your code. I did a CSS-y Weekly Web Dev challenge and then did some CSS on the bookfinder project. Which involved choosing some colours and then checking how to do global styles. At some point I need to decide what everything should actually look like.

**Day 48: 26th May 2021**
I did a load of CSS today, so it's all done for the mobile view. Just the desktop/tablet etc view to go. Which I need to look up how to do. I also need to do some more looking up about how to do it more efficiently and not just have the same code in different place. I'm really missing classes to be able to style all similar things at once!
I then did the Weekly Web Dev challenge. After thinking about no classes and SCSS like CSS, it was hard to get used to plain CSS again! The challenge was to create a clone of a Netflix film card. Everything that was on the picture was fine, but the stretch goal was to have more information pop up when you click the drop down. All I could really add was 'more information goes here' because I have no idea what it might say on Netflix.

**Day 49: 27th May 2021**
I did a Weekly Web Dev challenge that was about CSS. I then did the media queries part of the CSS for the bookfinder project, which was all fine. But then testing it with real data I found a whole load of JS things I need to fix...

**Day 50: 28th May 2021**
I did a couple of bits from my list, which were simple. But for one of them, the tests should tell me if it worked. But when I discovered that duplicating the previous and next buttons broke all the tests involving them. I fixed those bits, but now it's gone a bit weird with the API calling - I think I need to change the dummy data and tests, but I need to look at all those with a fresh eye.

**Day 51: 29th May 2021**
Another Weekly Web Dev challenge, doing animations on button hover. I fixed a few things on the bookfinder project - I'm down to one error on the app test that I can't see why it's erroring, but hopefully a bit of time and it will become obvious.

**Day 52: 30th May 2021**
Decided to do some CSS today. So I added my own dropdown arrow to the select, so it looks the same in Firefox as it does in Chrome. I then fixed the CSS to improve it, so there weren't the same things all over the place. And installed React Helmet, so I could link the Google Font, and I can then use it to do the SEO, once I get to that.

**Day 53: 31st May 2021**
Fixed this to get the results from the array rather than the API, if you press next. And then I discovered I hadn't set up Helmet quite right - once I moved it from App to index it was better. It fits better on there too. I then discovered, upon googling, that Google Books totalItems isn't always correct, which explains a lot. So I removed the total book count and then found a new way to work out the end number of books.

**Day 54: 3rd June 2021**
I took a couple of days to catch up with videos and reading and discovered a few things. So it turns out I don't need Helmet, that's only for dynamic stuff and I only have one page. There's an index.html in the public, which Webpack uses as a base. So that simplified a lot. I also found why you might not want to use state on the input and select and the alternative without using ref. Which then took a long time to get both TypeScript and Jest/React Testing Library to be happy with. I then investigated props in Styled Components, so I could style disabled buttons. And then I made a start on this week's Weekly Web Dev Challenge.

**Day 55: 4th June 2021**
I finished off the Weekly Web Dev challenge. I just had the tricky bits to do, so I'm very glad I chose a course with circles in the background, rather than strange shapes that would have been more of a pain to create.

**Day 56: 5th June 2021**
I was watching something in React that was interesting, but then they used props in Styled Components in the way I want to use them, rather than the way they use them in the docs. So I updated the Previous and Next buttons in the bookfinder project and now it's much easier to read.

**Day 57: 6th June 2021**
I'd been putting off a Lighthouse review of my portfolio for a while. I noticed the favicon wasn't working, so I fixed that and then worked through the Lighthouse bits. I've gone from a score of 89 to 94, which is a improvement (it's in the green now). The bits that are left either make such a small difference and/or are related to the server, which I don't think I can do anything about.

**Day 58: 7th June 2021**
I played about with adding an image. I tried a background image below the form, which looked fine as a form background, but odd looking at the whole page. I tried adding it as an image next to the form if there's enough space, but I'm not sure about that either.

**Day 59: 8th June 2021**
I finally made a decision about the image, but then I had to fiddle around with ways of adding it to get it to do what I wanted. It looks good now though.

**Day 60: 9th June 2021**
Did this week's Weekly Web Dev Challenge. Once I remembered what I was doing (you have to tell the eventlistener that you want to listen for a click...) it was easy. So I did the stretch goal. It's annoying that you can't style the radio buttons, but it turns out that creating your own in CSS is really easy.

**Day 61: 10th June 2021**
I discovered at codebar that if you do a search and press Next, then do another search, it gets confused about the buttons being disabled. I fixed that - it's because it's all looking at state hooks, so they definitely need looking at, although I have sorted it using constants. I also moved the buttons into their own component, so they're not in App twice. I put Loading in its own component and made it bigger.

**Day 62: 12th June 2021**
I did a lot of little things today. I centred the logo vertically in the space remaining, moved the error and books messages to their own files. I looked at the HTML structure that improved that (I had a lot of divs, I realised). And then since I was on a11y I did some wave and aXe testing. Next up is some Cypress testing, I think, which requires me not to be listening to the tennis at the same time, so a job for tomorrow morning.

**Day 63: 13th June 2021**
I installed Cypress and then it turned into a pain, giving me errors. I eventually tracked it down to my babel file - I just needed to delete targets. Which I don't think I needed in there anyway. Lots of time spent installing stuff, but I now have it basically working. I just need to write some tests.

**Day 64: 14th June 2021**
I discovered Cypress Testing Library. So there's one Testing Library which works for different languages and allows you to use eg getByRole. I installed that, at which point TypeScript was unhappy with both Jest and Cypress. I did some playing and then understood what was going on, so fixed that. I then updated my ternary operators in Card to make them variables, so it's all easier to read (hopefully). I then started on my Cypress tests. It took me a little while to understand how the API mocking worked, but it turns out it's really simple.

**Day 65: 15th June 2021**
Added all the Cypress tests. They were pretty quick because I'd already thought about what to test when doing the Jest testing. Annoyingly I don't quite have 100% coverage on the Cypress tests because it thinks I'm not testing the book end count when going back, but I am, so not quite sure how to convince it.

**Day 66: 16th June 2021**
I added keyboard and accessibility tests in Jest and Cypress. Which took a while, trying to establish what worked in which testing software... I also fixed the card's link alternative text so it was at the bottom of the card, made the page background lighter and added snapshot tests in Jest.

**Day 67: 17th June 2021**
I finally solved the Cypress problem of it erroring when pressing enter on the Previous button. Then discovered the loading spinner wasn't vertically centred any more, so I fixed that. I did some SEO, although it includes the site address, so I have to gt that right when I upload it! I tested on some other browsers and devices, found iOS really rounds the input, so it looks terrible. When I googled it the links were purple, so I've encountered that before. So I fixed that. I watched some videos on React useReducer, Context and Query. I now understand what they're for and how they work, so I just need to see if they are of any use in making this the bookfinder app easier to read.

**Day 68: 18th June 2021**
I started off thinking I'd use React Query, but then I found that a custom hook would be simpler. I wrote one and it works to fetch books. I also used used the Context API to update state there, rather than passing it down to components. Those all worked well, but then I found that updating the state that's on the context from the custom hook doesn't work. Not even when I came up with a far simpler example. Hopefully I'll be able to find a solution after a break.

**Day 69: 19th June 2021**
I had an idea, tried it, it didn't work. I read some React articles and they were interesting and helpful for my general refactoring, but not for this specific problem. I had a break today to do a video on Python crash course. It was all about the basics of Python you need in order to write anything in it. I liked it and I can see why it's suggested for newbies because it feels very English.

**Day 70: 20th June 2021**
I finally solved the problem I was having. And discovered how useful CodeSandbox is. Of course now I have a new problem: my state hooks not using context are not updating in the custom hook. Hopefully a break and some more playing around in Code Sandbox will help fix that. Although I haven't done everything yet, it's looking so much better from my refactoring.

**Day 71: 21st June 2021**
I solved the problem - you need to declare everything from the custom hook in one place, then pass it down. So I fixed that. I then went onto sort out the buttons, but of course I now have a problem on those. But that was right at the end, so I haven't had much time to look at it. Hopefully it won't be too hard to fix.

**Day 72: 22nd June 2021**
I now have the bookfinder refactored and working as before! At least when I try it in the browser. I need to update all the tests since I'm passing different things in different places, but hopefully they'll pass...

**Day 73: 23rd June 2021**
I thought adapting the tests to the refactoring would be simpler than I thought. Most of it was ok - I learnt that if you're using context you have to wrap your component with it in the render, which makes sense. It's just the integration tests where it's using it in the child that's proving trickier. I haven't even looked at the Cypress tests yet, but they should be ok since it's just going to the page, same as a person does.

**Day 74: 24th June 2021**
I finally sorted out the remaining App tests. It turns out that Context is a pain - you have to set the variables at the start of the test, which is fine for one little unit test, but a pain when you're trying a big integration test. I ended up having to split out my tests some more, so I could fix the constants. But actually, that was a good thing, as each tests does fewer things. The Cypress tests all still work, so it means I definitely didn't break anything, I just need to update the Jest tests. (just snapshot to go and hopefully that'll be a quick win tomorrow...)

**Day 75: 25th June 2021**
The snapshots turned out to be easy to fix. Annoyingly my Jest coverage report says that some lines aren't covered but they are. I don't know if there's some context-related reason why it can't. Even if those lines aren't being tested in Jest (which they are), they're (also) definitely being tested in Cypress.

**Day 76: 26th June 2021**
Forgot to fill this in on Saturday, but I did write a blog post about what I did instead! I did some Python tutorials: a Pong game (using Turtle), making an API (using Flask & SQL) and web scraping (using Beautiful Soup). Since the latter two were more of an introduction, I did enjoy the game more, because by the end I had a finished game, which was pretty cool. It has given me an idea of what Python can do, which was the point of the exercise.

**Day 77: 28th June 2021**
I built the app, which worked fine, then pushed to main and played about with GitHub Actions for running tests on push or PR. I'd tried this with Jest tests before and hadn't been able to get it to work. I intended to try the tutorial, to see if that works, but I couldn't find the one I'd used before. So I did Cypress first, since that had docs on it, but it didn't work. But I found the video I found on it before and discovered I just had to add a line to package.json and it worked. And then after some Googling I found that Jest was really simple to do. I could watch them run when I made a PR, which was very exciting! I still have to put the site somewhere and then add it to my portfolio, but that's for another day - I didn't expect to get that far today!

**Day 78: 29th June 2021**
I deployed the bookfinder to Netlify, submitted it to Chingu and added it to my portfolio. I might try and catch up on some coding videos and the Weekly Web Dev challenges before I start on a new project (just have to decide which to do next!)

**Day 79: 30th June 2021**
Watched some coding videos today. It feels like loads to get through, but if I can reduce that number to 0, then I should be able to keep up with newly released ones.

**Day 80: 1st July 2021**
I might well wait until the end of Wimbledon to start a new project, as by then I won't know what to do with myself, with no tennis on for around 12 hours a day. Today I watched some more videos - I am getting through the list, slowly.

**Day 81: 2nd July 2021**
More videos. I realised some of the ones on my list have been on there for such a long time because I don't really want to watch them, I just feel like I should because they might come in useful in the future. So I took them off the list, because if I need them in the future, I can go and find them then.

**Day 82: 3rd July 2021**
Today was my learning something different tutorial day. I ended up doing Go. Like with Python, the Traversy Media crash course was all about how to use the language, then next week I'll do a tutorial to make something. Overall I found it to be a bit like JS and a bit like Python. I think some things are just universal.

**Day 83: 4th July 2021**
Today I did Traversy Media's crash courses on Node and Express, which was a lot. I've done freeCodeCamp's basic Node & Express, but really didn't understand what was going on with them. Splitting them out helped, so now I see what was going on. I need to look back at the videos I saw using an API and creating an API with Node/Express and see if I now understand what is going on with them.

**Day 84: 5th July 2021**
I did a video and a half today, which came to an hour. But I added another half hour to the watch list, so it's not really gone down much...

**Day 85: 6th July 2021**
The watch list has now gone down a lot. I realised the one I started yesterday was just watching someone follow documentation and I got the idea. So I watched one about TypeScript with Node and Express. Which gave me the gist and I'll have to check specifics for what I want to do when I come to use it.

**Day 86: 7th July 2021**
I've finally finished my watch list! The final one was about testing in React, but I was pleased to find out that I knew all of that. So I think I am finally getting Jest and Testing Library after all! I also discovered that GitKraken doesn't work with private repos in the free version. Since I need to learn Git on command line anyway, I tried it in there. And got into trouble because it eventually turned out that my private SSH key had the wrong permissions. And when I fixed it I couldn't remember my password, so I had to set up new keys. The weird thing is that GitKraken says it's not using SSH, but GitHub says that GitKraken has used SSH recently. Although if it had, I'd have thought it would have complained about the permissions too. So I don't know. It works, so I'm not touching it.

**Day 87: 8th July 2021**
Having spent some time yesterday researching and installing things (and fighting with ssh) I started coding on an assignment. I realised I've done so much React lately that I forgot vanilla JS doesn't work quite the same way! It took me a little while to remember what I was doing. It says something about how much I've learnt React. (But I still can't answer Scrimba's poll from the other week as to whether I prefer JS or React). In the end I got it all working and loaded some data. I only have one thing to do and I've fulfilled the very basics of the brief, which is a good feeling.

**Day 88: 9th July 2021**
I did the one bit of the assignment I had left. And then decided to convert the js file to ts, which meant I then needed a build tool. And found Gulp wasn't happy with TypeScript or Dart Sass. Rather than messing around with it, I considered Webpack, since it would allow me to import things, but I remembered it had problems with Cypress. I didn't want to spend my time messing around with that either, so I ended up with Parcel. Which it turns out allows imports too! I should have just started with that.

**Day 89: 10th July 2021**
Today was Golang tutorial today and I ended up doing a Traversy Media one on creating an API. Which seemed a lot more complicated than in Express, but that's partly because Express is JS so already understand a lot of it, plus it used an external module and reading the docs for that might have helped. I also did a lot on the assignment, refining things, creating tests, doing all the CSS.

**Day 90: 11th July 2021**
I fixed some bugs on the assignment that I'd introduced. I added a caption, for accessibility, then spent ages playing around trying to get the keyboard to navigate on the chart and the screenreader to not read the things that are not useful for it to read, without succcess.

**Day 91: 12th July 2021**
I finished the assignment! I'm very glad I downloaded it from GitHub to follow the instructions I gave because I included some files in gitignore that were actually needed... Anyway, it's done now. Before starting a new project I'm going to do some Frontend Mentor feedback, as it's been a while since I've done any of that.

**Day 92: 14th July 2021**
I caught up on the Weekly Web Dev challenges, having missed last week's. And caught up on my to watch list (people keep putting more videos out...). I kind of miss having a project on, but I'm also liking the relaxed coding time spent on doing lots of little things.
