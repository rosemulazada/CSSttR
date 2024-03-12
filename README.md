# CSS to the Rescue

My repository for the final assignment for CSS to the Rescue, Web Design and Development 2024.

## Table of Contents

-   [Introduction to the assignment](#introduction-to-the-assignment)
-   [Installation](#installation)
-   [My project](#my-project)
    -   [Before any code: what are my thoughts/plans?](#before-any-code-what-are-my-thoughtsplans)
    -   [CSS features I want to use](#css-features-i-want-to-use)
-   [Takeaway from feedback](#takeaway-from-feedback)
    -   [March 1st: Presenting our ideas](#march-1st-presenting-our-ideas)
    -   [March 8th: The first intake](#march-8th-the-first-intake)
    -   [March 15th: TBA](#march-15th-tba)
-   [Usage and Features](#usage-and-features)
-   [Reflection](#Reflection)
-   [Version log](#versionchange-log)
-   [External Sources](#external-sources)

## Introduction to the assignment

The point of this class is that JavaScript is illegal to use; you should rely solely on CSS to get the job done. You could choose between four projects to create:

1. Modular control panel
2. Fireworks show
3. Rubix cube
4. Fold a paper plane

The requirement for 3. and 4. was to solve a math equation handed out by the teacher Sanne 't Hooft, and while I gave my best shot at one just for funs sake to see if I could do it, I didn't and didn't expect to get far. So I've stuck it to 1 or 2.

I liked both a lot, but when I started exploring the possibilities of what I could make for the modular control panel I became excited about the idea of making a game device from my youth in pure CSS. The Nintendo (3)DS was taken at the time and I didn't want to do what someone else was doing, and besides, I hold a special value in my heart for the PSP, so it came to me naturally. This is what I've decided to make for this assignment.

## Installation

Here are the steps to install my project.

1. Under the `Code` tab at the top (the big green button).
2. Download this repository as a `.zip` file and unpack it.
3. Locate the folder `CSSttR`
    - If you have `VS Code`: From here, all you need to do is open the folder in your editor and use the `Live Server` extension to start a local host. This allows you to also view the code and work more hands-on, should you desire.
    - If not, you can find the document on your device, navigate to the `index.html` file (this should be visible just by opening up `CSSttR`), right-click it and open in a browser of your choosing. I've used Arc and Google Chrome to test this project, so I can recommend these two.

## My project

Inspired by the module option of this assignment, I quickly found myself grasping for devices from my youth to play with. Not wanting to go with the generic items like the Nintendo Switch, I opted for the Playstation Portable, or the PSP as it's better known by. For those unfamiliar, or just for a visual refresher, this is that module.

![PSP device](https://images.versus.io/objects/sony-psp-3000.front.variety.1591878256408.jpg)

### Before any code: what are my thoughts/plans?

The PSP has a few things to note.

1. Its unique shape.
2. The buttons, which there are at least eight of excluding the power button.
3. The screen.

4. I tried to think a lot about how I could achieve the shape of the device but eventually decided to settle for a SVG I made because I didn't want to put too much valuable time into this over getting to the main layout and its functionality, as that by itself will take up a lot of time.
   2/3. I struggled settling on what I wanted the buttons to do in relation to the screen. The screen needs to turn on, for one, but there is so much that the device could do. I thought of mapping through the PSP menu first, something I'm still kind of considering.. but there was also the option of making a mini Mario game where you can make him walk around, jump, pose, etcetera. Mario was never for the PSP, but this is CSS, so I've chosen not to care about that.. However, I'm still slightly on the fence about which one of these two options I'll choose. I think the Mario one allows for more of the buttons to be used, which might be a valuable reason to choose it over the menu, but I'll have to map this out and weigh out what I've got. For now, I just want to make sure I can get the layout right.

### CSS features I want to use

`:has()` is one that I'm fascinated by, and one that I know will be the feature every other student names too but it comes with good reason. It's like a little slice of JavaScript in CSS, which to me is fascinating and I'm excited to learn about what other possibilities will be implemented from `:has()` in the future. But I plan to use `:has(input:checked)` to toggle an animation on the PSP screen, when the input is checked: the input being the PSP buttons which I've styled.

## Takeaway from feedback

Every friday, we have a feedback session with four students total and the teacher for the class, where we show our work, what we're struggling with, what we'd like to do and help eachother progress. Here's a log of each session.

### March 1st: Presenting our ideas

### March 8th: The first intake

### March 15th: TBA

TBA

## Usage and Features

TBA.

## Reflection

TBA.

## Version/Change log

### CSSttR V0.1.0

**March 9th**

I ended up starting over on this day because my layout was unclear and my code was messy. There wasn't much to do over, and it's a good thing I did do it, because it made the code so much easier to follow and work with, less conflicting properties, etc.

-   Set up a grid for the d-pad, the screen, the analog pad and the bottom bar of the device.
-   Set up the styling for the input buttons of the analog pad, but have not positioned these yet, only moved them into the correct side of the grid.

### CSSttR V0.2.0

**March 11th**

-   Set up the grid for the four analog buttons on the right
-   Positioned power/hold buttons. When you click on the power button, it lights up green, and the hold button light turns orange. For now, it also makes the screen get a `display: none;` which of course is not what we want but it's just to illustrate that I can make something happen when you turn the screen on: and this can be toggled, meaning you can turn the PSP off and on.

### CSSttR V0.3.0

**March 12th**

-   Set up the grid for the four D-PAD buttons on the right
-   I styled the D-PAD to resemble their buttons on the original device.

TBA.

## External Sources

1. ['Pressed button' styling (used for default state)](https://stackoverflow.com/questions/38377062/how-to-make-html-button-look-pressed-in-using-css)
2. [Display: grid explained by CSS-tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
3. [Clippy: used to make the d-pad clip-path](https://bennettfeely.com/clippy/)
