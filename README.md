This is a simple timer written in Node.JS with a simple functionality. It  grow trees as the timer progresses. Oh, and the sun changes position and the its color, along with the color of the sky, changes too.

##Inspiration

I have always liked hourglasses, water clocks, sundials and similar antique time keeping devices. I think there is something very profound in the way that the passing of time is displayed so very physically in these devices.

It is often difficult to keep track of time and realize the true weight of time, the true power that time exhibit onto the world. We only realize that time had passed when we look at the children who had matured, at the sun that had set and indeed, at the tree that had grown.

This application not only provides a beautiful timer that people can use for anything, but also tries to invoke that feeling in people and encourages them to think more deeply about the effect of time.

##What it does

At the beginning, the user is greeted with an empty Savannah baking under the scorching sun at the top and three buttons at the bottom: start, stop and reset. Pressing start will start the timer, and the the first tree will start to grow.

It will be fully grown after 1 minute, after which another tree will start to grow at a random place, and mature in 1 minutes. Every minute, another tree grows during which the sun will continues to move across the sky. A day lasts 10 minutes. Pressing stop will temporarily stop the timer along with the growing process while reset will reset the timer but not the grown trees.

##How I built it

It's built with React on Node.JS.

##Challenges I ran into

I had to learn React and Node.JS from Scratch. I am not yet proficient enough in React or Node.JS to leverage their full potential and instead simply used a lot of pure JavaScript and HTML Canvas.

##Accomplishments that I'm proud of

Conceiving the project and putting the project together into a somewhat presentable form with React on Node.JS, a library and run time I have never used before.

##What I learned

The basics of React and NodeJS. Proficiency in manipulating HTML Canvas.

##What's next for Savannah Timer

Savannah Timer still needs a lot of improvements, sorted from most urgent to least:

1. Revising the Timer: currently the timer of Savannah Timer is not nearly accurate, lagging behind real time seconds the longer it is run. It will have to be reworked into a new more accurate form.
2. Adding more features to the Savannah: birds, grass and clouds. These should make the Savannah greatly more lively and beautiful.
3. Implementing a night cycle: currently Savannah Timer only have a day cycle. Implementing a night cycle would greatly improve beauty and realism.
4. Overhauling the way things are animated: currently, everything is animated by repeatedly redrawing a single HTML canvas. This makes performance extremely poor and the animation quality low. A potential route is storing the file of an animated growing tree and simply playing that when the tree is growing.
