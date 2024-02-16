# Entry 4
##### 2/12/2024

## Findind a Tool
Lately, I have been finding tools for my freedom project to build a website in. First, I looked at [tailwind](https://tailwindcss.com/docs/installation/play-cdn) and tinkered with it. I followed the CDN. In the head, I typed up this code.
```
<script src="https://cdn.tailwindcss.com"></script>
```
Once I typed up that code in the head, I started to copy and paste another code and typed up the CSS.
```
  <style type="text/tailwindcss">
    @layer utilities {
      .content-auto {
        content-visibility: auto;
      }
    }
  </style>
  ```
  I later started to add an `h1` in the body, and went over to the CSS and typed the code.
  ```
  h1 {
    background-color: green;
  }
  ```
  I started tinkering more examples, which is how I decided to choose Tailwind as one of my tools.
  Later, I went over to Aframe and was fascinated by the 3d shapes I could create. So I went over to the [Aframe Guide](https://aframe.io/docs/1.5.0/introduction/) and tinkered with it. First, I copied the `script` and the whole shapes code
  ```
  <script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>
  ```
  ```
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  ```
  Later, I started to type up my own code trying to copy the format. I did a sphere that is pretty much on the left side of the screen. The code looks a lot like this.
  ```
  <a-sphere position= "-2.5 1.5 -5" radius= "1.25" color="#4CC3D9"></a-sphere>
  ```
  [This is what the result looks like.](https://jsbin.com/laripadiju/edit?html,css,output) Once I experimented it a little bit more, I also decided to stick with Aframe as well.

  ## EDP
  Honestly, I'm currently between the planning and making the prototype, but preparing to make the prototype. I found two tools to work on. I have tinkered with the two tools I have chosen by trying out the codes on an empty [jsbin](https://jsbin.com/?html,css,output).

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
