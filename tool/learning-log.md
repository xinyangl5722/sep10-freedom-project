# Tool Learning Log

Tool: **Tailwind and Aframe**

3/3/2024:  
* I started to install Tailwind using the Tailwind tutorial.
  * I was confused on how to install it so I watched a [7 minute YouTube tutorial](https://www.youtube.com/watch?v=arftp8kFBBg)


3/4/2024:  
* I started to tinker and test out random stuff by trying to make a navbar
  * I watched an 8 minute [YouTube tutorial](https://www.youtube.com/watch?v=X6CsbhSVUEc) on how to make one
    * I copied some of the code in my html and I also tried to figure out what the class codes mean.
    * `<nav class="p-6 border-8 border-black bg-red-500">` was the code to make the rectangle of my navbar. I tried to find out what does `p-5` stand for in the [Tailwind CSS Cheat Sheet](https://tailwindcomponents.com/cheatsheet/) I found.
    * `img class="h-20 inline"`-> The class to make the image smaller and make an inline
    * What happens if I make the `h-20` to `h-6`? -> The image turned smaller
* Next Steps
  * Finish [8 minute YouTube tutorial](https://www.youtube.com/watch?v=X6CsbhSVUEc)
  * Start learning Aframe
    

3/9/2024:
* I later started to learn Aframe
* First I did an installation from the Aframe docs
  * I copy and pasted the script in my IDE
  * Then I tried to make a cone by following the order of the other [Aframe tutorial](https://aframe.io/docs/1.5.0/guides/building-a-basic-scene.html) in the document.
   * `<a-cone position="-0.5 1 -1" height="0.5" radius-bottom="0.25" rotation="90 45 90" color="#4CC3D9"></a-cone>` was the code I did
   * I also used the `<a-scene` element
 * I later made the Aframe in a different html page and learned how to put it together using a past freedom project example
   * That project already has a code link so I went and see what they did
   * I found something called an iframe and looked it up
   * I tried it out on my html and the Aframe was now in the html
 * Next Steps
   * Find out more about what I could do with Aframe

3/16/2024:
* I started to learn animation on [Aframe](https://aframe.io/docs/1.5.0/components/animation.html)
* I started to look closely at a code that was displayed in the website and tried to understand it.
  * It was about orbiting a sphere
  ```html
  <a-entity rotation="0 0 0" animation="property: rotation; to: 0 360 0; loop: true; dur: 10000">
      <a-sphere position="5 0 0" color="mediumseagreen"></a-sphere>
  </a-entity>
  ```
  * I learned that you add the property first, and then the direction of the animation. Then it is if it's a loop or not and then the speed
* Next Step
  * Go back to learning Tailwind
 
3/17/2024
* I later started to learn about the grid system
  * I went to a YouTube tutorial but that really didn't help me at all
  * I later went back to the website [right here](https://tailwindcss.com/docs/grid-template-columns)
  * So I did this code
  ```css
  <div class="grid-rows-1	">
    <div class="grid grid-cols-3 text-center">
      <div class="bg-yellow-400 m-8 w-8">01</div>
      <div class="m-8">02</div>
      <div class="m-8">03</div>
    </div>
  ```
  * I did `grid grid-cols-3` as for three items in one row
  * I also made them text center
  * And now, the three divs are side-by-side

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
