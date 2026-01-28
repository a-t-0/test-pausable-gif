# test-pausable-gif

<!--
Source - https://stackoverflow.com/q/72508378
Posted by Md. Yeasin Sheikh
Retrieved 2026-01-28, License - CC BY-SA 4.0
-->

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)
<br>
<img src="https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif" width="40" height="40" />


<details>
  <summary><b>Click to preview animation (GIF)</b></summary>
  <br>
  <img src="https://path-to-your-animation.gif" alt="Demo Animation">
</details>


# Generates: [![Demo](thumb.png)](demo.gif)
print(generate_pausable_gif_link(
    thumbnail_url="https://example.com/static-frame.png", 
    gif_url="https://example.com/animated.gif", 
    alt_text="Click to play demo"
))
