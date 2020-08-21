---
title: "CSS :before pseudo element animation "
image: /uploads/animation.gif
date: 2020-08-21T06:53:59.067Z
draft: false
showonlyimage: false
weight: 0
description: "CSS animation & note on how I centered a :before pseudo element  🖼 "
---
I really like websites with great animations and transitions. When animations are used right, they direct the users to the right information. Also, they give the website and content a "personality"! This is something I will spend more time learning and working on in future projects. 

For my current project, the design has a highlight graphics at the end. I want to make an animation based on the graphic. I did a prototype in codepen before added it to the project. By doing the prototype, I realized there are at least 2 concepts I did not understand:

1. [Radical gradient](https://developer.mozilla.org/en-US/docs/Web/CSS/radial-gradient): I did not understand how the colors' position would manifest visually. I had four colors. I gave them about the same percentage, but they showed up very differently than what I expected. I still have questions. 👀🤔
2. [Transform: translate](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate): translate is pretty self-explanatory: it repositions an element in the horizontal and/or vertical directions. But I did not understand when you use % as the unit how it is being calculated. After looking into it, it is based on the element's width and height. I got confused with parent element's width and height. 

![animation prototype](/uploads/initial.gif "Animation prototype: off center")

I initially align the center at the end of the animation. That's not what we want. Then I changed the top and left to 50% to align center. After that, the pseudo element's top-left top corner was placed at the parent element's center. That's halfway there. I still needed to adjust the pseudo element's position to the center, so use translate(-50%, -50%). 

I want to document this process! Because I realized there is a lot of CSS properties that I have seen and think I know, I don't really understand! This is a good reminder. It's all in the details. Learn your tools!🧰

See the[ code here](https://codepen.io/linzhang/pen/BaKLzmO)

![centered animation](/uploads/animation.gif "centered animation")