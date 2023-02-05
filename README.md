
# Professional Portfolio using Advanced CSS
![License Badge](https://img.shields.io/badge/License-MIT-green)

## Table of Contents
* [Description](#description)
* [Examples](#examples)
* [Technologies](#technologies)
* [License](#license)


## Description
The purpose of this cahllenge was to construct a Portfoli website from scratch.Since I don't have any actual projects yet, I used placeholder images with links to exsiting sites that I want to emulate.

## Examples
Created a header with links that when clicked, moves browser to that section. 
```html
    <header>
        <h1>Matt Fleming</h1>
        <img class="avatar" src=".\assets\images\avatar.jpg" alt="Avatar">
            <nav>
              <a href="#about">About</a>
              <a href="#work">Work</a>
              <a href="#contact">Contact</a>
            </nav>
    </header>
```

Added a hover feature to the image links that I stumpled upon using google.
```css

  .app:hover {
    box-shadow: 0 0 10px rgba(0,0,0,0.5);
    transform: scale(1.1);
    transition: all 0.3s ease-in-out;
  }


```
## Technologies
* ![HTML Badge](https://img.shields.io/badge/Language-HTML-blue)
* ![CSS Badge](https://img.shields.io/badge/Language-CSS-yellow)

## License
Copyright 2023 Matt Fleming

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.