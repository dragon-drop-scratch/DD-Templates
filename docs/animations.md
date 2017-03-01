# Animations
<b>Table of Contents</b>
- <a href="#premade">Premade</a>
- <a href="#making-your-own">Make Your Own</a>

## Premade
animated-gradient
  Adds the ability to have a mulicolor gradient background.


## Making Your Own
Creating your own animation is very simple.
1. Fork the repo

2. Be sure to name it (in settings)

3. Open `fork/animation.css`

4. Create a new animation in CSS

5. Inside the animation add `title: <i>Name of Animation</i>;` and `description: <i>Description</i>;`

6. Comit Changes

7. <a>Import the Theme</a>

<b>Example</b>
`@keyframes name {
    0%   {background-color:red; left:0px; top:0px;}
    25%  {background-color:yellow; left:200px; top:0px;}
    50%  {background-color:blue; left:200px; top:200px;}
    75%  {background-color:green; left:0px; top:200px;}
    100% {background-color:red; left:0px; top:0px;}
    
    title: Example;
    description: My own special animation!;
}`
