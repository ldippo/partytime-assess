# Assessment Requirements

## Forward Notes

Do not spend over 3 hours on this assessment, not including the time it takes to review these requirements. Please try to complete all the passing criteria. If you complete passing criteria in under 2 hours, please attempt one or more of the bonus tasks. I will assume the task took a full 3 hours in the absence of a bonus feature. Try to allocate at most 1 hour to the bonus feature, it is acceptable to exceed 3 hours if you make it to the bonus.

## Purpose

The purpose of this assessment is to gauge your abilities and preferences with the creation of a small visually interesting application. I am looking for assistance with visual polish which is why there should be a focus on animation, performance & responsive layout. I also expect competency with concepts such as the component lifecycle, state management & quality abstraction. Please don't invest time in testing this particular app.

## Passing Criteria

A visual mockup is provided for reference [here](./assessment-mockup.webm) - as to how this app should generally look. Though you may deviate from the visual I present and make enhancements if you think it will better represent your skills & abilities. Please remember I am primarily indexing on performance, responsivity and animation ability.

- Present the string "DISCOTECA" on the screen
- Your component should take at least two properties
  - `interval: number // time in ms`: The number of ms which determines the frequency each animation frame is triggered and for one 'tick' of the timer to occur
  - `duration: number`: how many 'ticks' should occur before the timer will complete
- The border of the app window will represent a timer
- While the timer ticks forward the border fills in clockwise, proportional to the number of ticks / duration (percent completion)
- After the duration determined by the prop `duration` has elasped, the border should be completely filled in
- After the value of time determined by prop `interval` has elapsed, the border of the app will tick forward
- With every tick of the timer
  - The border will cycle through the colors
  - The characters will cycle through the colors
  - Every other character will have an alternating animation (ex Scale, Rotate, Scale)
- No two characters will ever be the same color at once
- This app should be completely responsive with regard to layout
- Each character should be centered within its allocated section of the layout
- Upon completing the timer, a visual indicator should replace the screen giving you the option to restart

## Bonus Features

- Add a hotkey that shuffles the characters around the grid
  - Animate the shuffling process
- Make the grid rotate in 3D
  - Conform the grid to a spherical geometry like a discoball
- Scale the size of the characters with window size
  - Animate the scaling after a layout resize

## Resources

These are the colors used in the video mockup  
#4BBFE6  
#266CDD  
#2B20BC  
#FFCC33  
#A01CA3  
#FA1085  
#F30F58  
#F8A26D  
#F3E479
