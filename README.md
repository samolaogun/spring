# Spring

## Viewing
Clone the repo to view the simulation locally.
```bash
git clone https://github.com/samolaogun/spring.git
```
To view the spring simulation open `spring.html`. The actual spring logic and explanation is location in `spring.js`. I've already included a build to test the simulation `bundle.js`. In order to build the project yourself if you make any edits, install webpack `npm i --save-dev webpack` and run the build script `npm run build`.

## Background
The way that a spring animation works no different than physical oscillation. In both real life and in the digital world, springs can be represented by a function called a "damped oscillation". For a function to be damped simply means that as the function progresses, or as the x value of the function increases, the y value, or the function output approches a single value, which in this case is 0. I chose to create this animation using javascript because CSS animations are clamped to a specific range, which means that they do not support elastic behaviors such as this. Keep in mind that this is a true spring animation (a spring is never truly stable), but more just a visual illusion (the limit can never be reached).

## License
Read it [here](https://github.com/samolaogun/spring/blob/master/LICENSE).
