# Process Writeup

## Name: Farzona K
## Course: SEP10 Web Design
## Period: 8
## Concept: CSS

### Section: Context 
Though a little advanced, we are still in the basic web design class, where we may chage the colors, add borders, change backgrounds,change fonts, use hex and rbg codes, and more. It is an overview of coding style. I was somewhat familiar with CSS since we learned about it last year as well, but the new kinds of styles that were new to us confused me a little. 

#### Basics I learned: 
* `color: red;`changes color to red 
* `font-size: 16px;` gives a font size of 16 px.
* `font-family: monospace;`changed the font to monospace
* `border-color: green;` gives a border with the color green.
* `border-width: 10px;` changes the width of the border to 10px.
* `border-style: solid;` gives a solid border (there could be dotted and dashed borders). 
* `border-radius: 10px;` changes the shape of the border and makes it more round (like a circle).
* `margin: 20px;` the space around an element's border, so for this the margin is 20px (space outside) 
* `padding: 20px;` the space between an element's border and the element's content, the padding is 20px (space inside) 
* `background-color: #000000;` hex codes are for specific colors, #000000 is the color black ( letters and numbers in hex codes) 
* `background-color: rgb(0, 0, 0);`rbg is another way for specific colors using red, green and blue ( only numbers ) rgb(0, 0, 0) = black rgb(255, 255, 255) = white
   

#### Process: 
Similar to how I learned about HTML, I learnt CSS by first going over the first few [Free Code Camp](https://freecodecamp.org/) lessons.The first few lessons covered the basics, including `colors`, `fonts`, `boders`, `sizes`, and other elements. We were required to create a [CSS Make Something](https://app.pickcode.io/project/cm2m6o8x07znlpuunw5afu306) similar to the "HTML Make Something" in order to further our understanding and practice of the essentials. All I did was add CSS to my HTML project becasue we were allowed to do that, I also didnt want to do more work. After that, we spent the entire class period learning about selectors and how to use them to make the selection process easier. For example, rather than selecting each item individually, we have to use particular selectors to choose the items that we want to be a specific color,font etc. 

After that, we returned to FCC to learn the remaining CSS, such as the box outline, which includes margins and padding. We discovered how to use the `paddings` and `margins` to align items and make them appear more neater. Thats where I struggled a bit with. Hex codes and RGB were the last things we learned in the FCC. They were used to represent particular color types. In basic terms, we were using letters and numbers rather than the actual names of the colors. After that, we took a quiz, and I received a 9 out of 10. The question about margins and paddings was the only one I answered incorrectly. We were expected to complete a CSS challenge with our partners on the same day. Because my partner and I didn't want it to be too easy or too hard, we chose the tougher level out of the three that were available to us: tough, tougher, and toughest. 

### Challenge 1
The  `paddings` and `margins` were what really caught me off guard, although CSS wasn't that difficult to start with. At first, I couldn't figure out what these were. Before the teacher showed us the box and gave us an explanation, I had no idea what we were doing. I continued to struggle with it since I kept confusing the  `paddings` and `margins`. The only challenging aspects of the coding were trying to figure out the location of the  `paddings` and `margins`

I received a 9 out of 10 on the quiz, and the question I answered incorrectly was about `paddings` and `margins`.

The question of the quiz was "What is `margin`?"

The choices were: 

```HTML
* The space between a declaration and the associated border 
* The space between a class and an element's border
* The space between an element's border and the surrounding elements
* The space between an element and its border
```
I chose ```* The space between a declaration and the associated border ``` but the correct answer was ``` * The space between an element's border and the surrounding elements ```

When I saw the question, my mind truly went blank, and I was at a loss for what to do, so I went with that response. Though I didn't recall it being the space between the border and the other elements, I did recall that the margin had something to do with the border while I was thinking. Since the answer I chose was the only response that appeared different from the others, I became so trapped that I simply chose the one I believed it to be. 

### Challenge 2
Although it wasn't primarily centered around CSS, I had another challenge. Since I had gone over all of this the previous year, I found it quite difficult to concentrate and quickly became bored when we began learning CSS. This continued until we reached the topics we still didn't understand, at which time I became genuinely perplexed and lost motivation to accomplish things. 

The notes I took were the only thing that got me through my difficulties. My notes were the main resource that helped me comprehend and remember what was taught, despite the fact that I kept zoning out.  

### Challenge 3
`classes` and `ids` were the last things I had trouble with. I had trouble understanding this in HTML, and even after learning how to utilize it and its purpose, I was still unsure of the difference between `classes` and `ids`.  I seem to recall learning this once, but I was unsure of the exact lesson and didn't give it much thought until I was in need of it. When I was doing the [CSS Chocolate Challenge](https://app.pickcode.io/project/cm2w6obbyjpkzxvnyod1dzgjx), I needed it.

Although I was aware that it required the class attributes, I used `classes` for the challenge alone since I believed that `classes` and `ids` were identical and performed the same function. 

When I used `classes` for the challnege: 

```HTML
<div class="white">
 <h2> White Chocolate </h2>
<img src="https://raw.githubusercontent.com/hstatsep-wd/other/refs/heads/main/chocolate/img/white.jpg" img class="below-image">
```
```CSS
.white { 
    background-color:wheat;
    margin: 25px;
  padding: 10px;
}
```

and 

```HTML
<div class="milk">
<h2> Milk Chocolate </h2>
 <img src="https://raw.githubusercontent.com/hstatsep-wd/other/refs/heads/main/chocolate/img/milk.jpg" img class="below-image">>
```
```CSS
.milk { 
    background-color:chocolate;
    margin: 25px;
  padding: 10px;
}
```
Not a single `id` that I can recall using in the code. However, I was reviewing the FCC classes to check if I had missed anything after completing the entire challenge and submitting. I discovered that every property served a different purpose. For instance, if I add a `id` attribute, it takes over  the `class` attribute that was the initial one. 

```HTML
<h1 class="pink-text blue-text" id="orange-text">Hello World!</h1>
```

Here the color of ``` <h1> Hello World!</h1> ``` would've been organge becasue it takes over the class. If there was no `id` The `class` would've been the main atrributee and the color of ``` <h1> Hello World!</h1> ``` would've been blue. 

The order of the atrributee: **CLASS, ID, INLINE, IMPORTANT**

### Takeaways
The things I really need to remember are: 
* 

