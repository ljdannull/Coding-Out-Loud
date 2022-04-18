# Coding-Out-Loud
![alt text](https://github.com/ljdannull/Coding-Out-Loud/blob/master/keyboard.png)
![alt text](https://github.com/ljdannull/Coding-Out-Loud/blob/master/color_scale.png)

Watched https://www.youtube.com/watch?v=9ld-9fLiv4E, and added to the visualization created.
The original video covered the creation of a heatmap over the keyboard where the frequencies of a letter first in the words of a given dictionary were the heats of all the letters, and these were displayed on a keyboard, based on a tweet the participant of the video brought up.
My changes include a custom continuous color scale, which maps straight from the frequency of a letter to rgb values, as opposed to the video, which used discrete cut-off thresholds. It also lowers alpha as frequencies increase, so that higher frequencies appear brighter, because the underlying plot is white. I also added the frequencies of the non alphabetic characters as 0, which the video specifically identified as a challenge for the viewer. Additionally, I attempted to add a bar visualizing the color scale onto the keyboard plot, but was unable to do so, so I created the color scale as a separate plot. It was fun using this to visualize different mappings, such as using squared trig functions. Labels also did not work for me.
