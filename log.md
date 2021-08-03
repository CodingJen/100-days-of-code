# 100 Days Of Code - Log

### Day 1: July 1, 2021

**Today's Progress**: Been working through <https://freecodecamp.org> . This was logged from the future.

**Thoughts** I've coded for most of my life, on and off though. Always enjoyed it but never stuck with it enough to get good. Now my life is at a crossroads and I want to try pursuing that which I've always loved.

**Link(s) to work**

- [freeCodeCamp Responsive Web Design Certificate](https://www.freecodecamp.org/certification/codingjen/responsive-web-design)
- [freeCodeCamp JavaScript Algorithms and Data Structures Certificate](https://www.freecodecamp.org/certification/codingjen/javascript-algorithms-and-data-structures)
- [freeCodeCamp Front End Libraries Certificate](https://www.freecodecamp.org/certification/codingjen/front-end-libraries)

---

### Day 16: July 16, 2021

**Today's Progress**:

- Today I turned my [freeCodeCamp](https://www.freecodecamp.org/) 25+5 Clock into an actual project instead of just being on [codepen](https://codepen.io) it's now a real and hosted react app!
- Github is setup with this document and my 25+5 project!
- I also got this document started and updated my log with my previous daily (almost) tweets, with links.

**Thoughts** I'm thinking of trying my hand at React Native with the 25+5 Clock for a start. Just want to keep it simple before I start a bigger project. I should probably also keep tweaking the clock. Always room to improve.

**Link(s) to work**

- [Github](https://github.com/CodingJen)
- [25 + 5 Clock](https://vibrant-bartik-bf8769.netlify.app/)

---

### Day 17: July 17, 2021

**Today's Progress**:

- Fixed some more bugs in my 25+5 Clock.
- Added local storage for the session and break times, now they are remembered and set when the page loads.
- Started work on the volume control.
- Trying to figure out if I can make a vertical range slider.

**Thoughts** Should I just make a custome control for the volume? Thinking a vertical thumbwheel looking control, maybe I can pull it off. Also looking into drag and drop, want people to be able to add their own sound
files. I don't want to store it in a server or anything though so maybe I can encode them and put in local storage? Maybe a base64 encoding of the file?

**Link(s) to work**

- See day 16

---

### Day 18: July 18, 2021

**Today's Progress:**

- Added volume slider, had to figure out how to make a range slider vertical.
- Started styling the slider. Needs a few more tweaks.

**Thoughts** Trying to do the vertical range input is weird. Having to transform: rotate() has some problems. Takes the width but then uses that for the height after it gets turned 90deg.
I want the container narrow but then the range slider is really short. Workaround seems to be to manually set the height but then I lose responsiveness.

**Link(s) to work**

- https://github.com/CodingJen/25-5-clock-web/commit/be0e398e25f3e82057baa191908d24e1fa8ccfa1

---

### Day 19: July 19, 2021

**Today's Progress:**

- Refactored my app's styles to styled components, long process even for a simple little app.
- Finally got VSCode and github to work together on my laptop as seamlessly as it's working on my desktop. Not sure what was happening there.
- More research into drag and dropping of files, still have some prep to do before i'm ready to start implementing that though.

**Thoughts**
Liking the styled components. Think it'll work easier than having a 500+ line css file for my app.

**Link(s) to work**

- [Today's big commit](https://github.com/CodingJen/25-5-clock-web/commit/6e88dced5e9dfaaaaf3d57f6e43ba770494763e4) - Sure looks colorful in the diff log!

---

### Day 20: July 20, 2021

**Today's Progress:**

- Working on refactor to react hooks. Switched over what I though would work but was seriously disappointed.

**Thoughts**
Wish I had just learned the hooks system from the get go, maybe it's better this way, it is forcing me to learn it. I had hoped it would be
easy to convert but after I did things i thought would still work didnt. I will perservere for a while but I hope I don't have to start over
and do it a small step at a time.

**Link(s) to work**

- Nothing today, I'll show it when something is there. It's just a complete mess right now.

---

### Day 21: July 21, 2021

**Today's Progress:**

- Wow it's been a couple days of trying to get the hooks to work, way more hours than I would have liked. I did finally get them to work, had warnings, and had to figure those out too.
- Some minor tweaks to naming and used an emoji for a favicon!
- Re updated the demo site on netlify

**Thoughts**
I wish i had someone to bounce these problems off of, but at the same time trying to google and figure it out on my own might be best, I just wish I had someone to point me in the right direction so I don't spend 20 hours getting something done that should have taken 1!

**Link(s) to work**

- [Git repo at the point of this writing](https://github.com/CodingJen/25-5-clock-web/tree/4a900bc7089824eb36691e87b7768657b687b763)
- [Demo site](https://vibrant-bartik-bf8769.netlify.app/)

---

### Day 22: July 22, 2021

**Today's Progress:**

- Started planning my next project. It will be fun to see it come together.
- Hopefully set up the git repo in a better way.
- Got some boilerplate code setup.
- Project name is 😎 Emoji Invaders. 👽 Like space invader but Smileyer! 😊

**Thoughts**
Still want to work on the last project but I think I need to move on to something else. Maybe I'll come back and add some more features later but for now it's good (enough).

**Link(s) to work** -[Emoji Invaders](https://github.com/CodingJen/emoji-invaders)

---

### Day 23: July 23, 2021

**Today's Progress:**

- Worked on the Emoji Invaders game. Started having a bit of trouble figureing through it in React alone so I went on codepen.io and started prototyping it in vanilla js there
- Got the player to move back and forth along the bottom of the screen, adding stopping at the edges, and got it to shoot flames when hitting the space bar!
- Moved from codepen to a local project because the internet was giving me issues.
- Upped project to Github.
- Writing this all from the future because it was a long day of coding.

**Thoughts**
Still having trouble with react. Went to vanilla js and was able to really hammer off some code. I guess I'm just not completely understanding the react system yet.

---

### Day 24: July 24, 2021

**Today's Progress:**

- More Emoji Invaders! 😁 Emoji's are going through the loops, getting shot down.

**Thoughts**
Having lots of fun working on a game. I do need to get to a more 'professional' project though.

**Link(s) to work**

- https://github.com/CodingJen/emoji-invaders-vanillajs

---

### Day 25: July 25, 2021

**Today's Progress:**

- 🔈 Boom, buh, dum duh SOUND!!
- If above isn't clear there is sound and it speeds up as needed! Getting more fun.
- Starting to figure how to drop bombs (randomly?) either way I think the sprites need a refactor.

**Thoughts**
Still wonderful seeing this come together. Got to figure out how to randomly choose from the active invader sprites which one will drop a bomb... Starting to feel like I need to render each one seperatly myself instead of using the grid.
I need to know it's position, although I think I can still calculate that from the getBoundingClientRect(). ⚙ Hmm gears are turning.

**Link(s) to work**

- https://github.com/CodingJen/emoji-invaders-vanillajs

---

### Day 26: July 26, 2021

**Today's Progress:**

- Added another sound, pew pew 🔫
- started on getting the emojis to fight back, dropping bombs 💣
- Started on logo, trying to style it properly, put font on backblaze.

**Thoughts**
Few things done today although it was a slow day for code to come to me. Needed more of a self care day today anyway. Mental health is important. Got some things cleaned up around me.

**Link(s) to work**

- https://github.com/CodingJen/emoji-invaders-vanillajs

---

### Day 27: July 27, 2021

**Today's Progress**

- Added boom emoji when they blow up 💥
- Added one more sound, now emojis sound like they're exploding! 🙄
- Happy enough with title text now!
- New branch and a teardown and rebuild for responsive design.

**Thoughts**
Lots of weird bugs keep getting in there. Guess thats half the battle right? Squash bug, add feature, squash bug. Rinse and repeat until done! 😉
I think my refactor will also help there, I think a lot of the bugs have to do with they way it was implemnented with HTML to begin with, might be
fixable in the css but it won't help some other things. Still have to loop through elements that are hidden right now, they should get removed from
the DOM when they are killed.

**Link(s) to work**

- https://github.com/CodingJen/emoji-invaders-vanillajs

---

### Day 28: July 28, 2021

**Today's Progress**

- Reworked the emoji grid, they are no longer created in the html, now just in the DOM
- Bombs are dropping
- Worked on resize, and starting to move away from hard coded size, now responding to the window size - some parts still a work in progress however
- Got jenniferfix.ca domain a couple days ago, linked it to linode and started to get my cloud server setup

**Thoughts**

So much work, I hope all this will pay off. Really going to work on presenting things to the public instead of just hiding and no one sees anything.
I think that's my life in a nutshell however. With coming out and starting to let people know who I really am -- it's been so liberating!
Also love that I get some positive love from the Emoji Invaders name! ❤ I want to get it out there. I really hope I can polish it enough to be a
very fun version of Space Invaders.

**Link(s) to work**

- [Emoji Invaders Github](https://github.com/CodingJen/emoji-invaders-vanillajs)

---

### Day 29: July 29, 2021

**Today's Progress**

- Cleaned up a bit of code in Emoji Invaders
- Prototyping to enforce an aspect ratio while keeping it responsive
- Working on setting up the web host. Researching a continous integration method
- Learning about the Twitter API, applied for a Dev account.
- Started a node tutorial with the API stuff

**Thoughts**

Keeping way to busy. Hope I don't burn myself out with this stuff. It's a good thing I don't have a lot going on in my life right now, lol. At least I'm not working full
time so I have a chance to do this.

**Links to work**

- [Emoji Invaders Github](https://github.com/CodingJen/emoji-invaders-vanillajs)
- [Twitter Talker](https://github.com/CodingJen/twitter-talker)

---

### Day 30: July 30, 2021

**Today's Progress**

- Learned about 'slow' animations with CSS. Refactor how all the sprites are moved. Now using the transorm: translate(x,y); of CSS styles.
- 🧡Levels!
- Yes thats right, it gets harder, well it would if I felt like setting up the player damage which i'm purposly avoiding right now lol.

**Thoughts**
Wow okay, so the transform thing is definitly the big lesson I've learned over the last couple days. Was listening to the Syntax podcast and they we're talking about slow
css transitions. I didn't realize that some would cause the whole page to restart the layout process. There are 4 steps in the layout and that's at the start. Transform only
works on the last step added as a layer so the whole page doesn't have to re render. Ok TIL! Use transform more often for CSS animations! And still no key to the twitter API so
I can't progress any on that front yet.

**Links to work**

- [Emoji Invaders Github](https://github.com/CodingJen/emoji-invaders-vanillajs)

---

### Day 31: July 31, 2021

**Today's Progress**

- Added ESLint with the airbnb style guide. Started with over 100 problems, well besides the wrong line ending type, they just want an LF, not a CRLF. CRLF is just windows version i thought the other systems smart enough to figure out what to do with it.. oh well. down to under 20, some I'm not sure what to do about as you're not supposed to do things like setting a dom element transform.. not sure why, maybe some googling will tell me..
- I have the bunkers displaying, not perfect yet but they are there, half the battle. Easy enough to implemnent a collision detection algo. Now how to make it look like the damage spreads out a bit. Maybe each cell should fade a bit first. Can I store that it's a bit faded in a dataset element?

**Thoughts**
Still progressing. Thought I would be there by now. So much to deal with. Thought I had this under control by now. Guess I really don't have that many real projects under my belt yet, but this one I intend to get to a finished state. I can think of so many parts that I will have to deal with though. Mind just keeps on racing on whats to do. Just focus on one part, get it done then move on. Of course there are lots of moving parts in any project.

**Links to work**

- [Emoji Invaders Github](https://github.com/CodingJen/emoji-invaders-vanillajs)

---

### Day 32: August 1, 2021

**Today's Progress**

- Worked a bit on trying to figure out an effecient way to to the collision testing and destruction of the bunkers
- Worked on setting up a google cloud compute engine.
- Not as much code today, need a break it is Sunday after all.

**Thoughts**
I think my biggest problem right now is there is no real model with they way i'm coding this. Which part of the code has control over which other parts. It's starting to become I mess and I know it. Thought I could just 'hack' it together but maybe not. We shall see, hopefully it all works out.
Not sure what the proper way to architect this would be. I feel my big global game object containing all the state should be ok, but just throwing a check for something just anywhere feels wrong.

**Links to work**

- [Emoji Invaders Github](https://github.com/CodingJen/emoji-invaders-vanillajs)

---

### Day 33: August 2, 2021

**Today's Progress**

- All in on the bunkers. Took some pen and paper figuring of math, using pythagoras to get distance between points and testing if the distance is less than the radius of my bomb emoji if so, bye bye.

**Thoughts**
Wish I knew if what i'm doing for collision testing is best. Seems like a lot of checks to do, but then again the computer is super fast. Should do some reading. Really want to refactor my code into classes or something. This just writing function after function thing isn't working _anymore._ I am almost to a functional game though so I should just push through, get it working, then refine. Why refine what doesn't work. Next time I'll should be able to start out a bit more organized. Or maybe use a game engine. Still have lots of code to write I'm sure but at least I don't have to deal with input or the timestep. Funny focusing on the bombs dropping, pause and play over and over and the bombs disappear when you hit play again. Timestep issue.

**Links to work**

- [Emoji Invaders Github](https://github.com/CodingJen/emoji-invaders-vanillajs)

---
