# TACHYONS-BUTTONS

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-buttons
```
or download the css on github and include in your project.

## The Code
```

/*
 *
 * btns.css
 * ```Simple css utilities for building responsive buttons

 * Author: mrmrs
 * License: MIT
 *
 *                */

/*

  Base .btn class

  Code:
  <a href="#" class="btn">Default button</a>

*/

.btn,
.btn:link,
.btn:visited {
  border-radius: .3em;
  border-style: solid;
  border-width: 1px;
  color: #111;
  display: inline-block;
  letter-spacing: .15em;
  margin-bottom: .5em;
  padding: 1em .75em;
  text-decoration: none;
  text-transform: uppercase;
  transition: color .4s, background-color .4s, border .4s;
}

.btn:hover {
  color: #7FDBFF;
  border: 1px solid #7FDBFF;
  transition: background-color .3s, color .3s, border .3s;
}

.btn:active {
  color: #0074D9;
  border: 1px solid #0074D9;
  transition: background-color .3s, color .3s, border .3s;
}


/*

  Sizes

  Small  = .btn--s
  Medium = .btn--m
  Large  = .btn--l

  Code:
  <a href="#" class="btn btn--s">
  <a href="#" class="btn btn--m">
  <a href="#" class="btn btn--l">

*/

.btn--s { font-size: 12px; }
.btn--m { font-size: 14px; }
.btn--l { font-size: 20px; border-radius: .25em!important; }


/*

  Layout utility for responsive buttons

  Code:
  <a href="#" class="btn btn--full">

*/

.btn--full,
.btn--full:link {
  border-radius: .25em;
  display: block;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
  width: 100%;
}


/*

  Skins

  * Black & White
  * Grays
  * Colors

  Code:
  <a href="#" class="btn btn--black">
  <a href="#" class="btn btn--white">
  <a href="#" class="btn btn--gray">
  <a href="#" class="btn btn--gray-dark">
  <a href="#" class="btn btn--gray-border">
  <a href="#" class="btn btn--blue">

*/

/* BLACK & WHITE */

.btn--black,
.btn--black:link,
.btn--black:visited {
  color: #fff;
  background-color: #000;
}

.btn--black:hover {
  color: #fff;
  background-color: #777;
  border-color: #777;
}

.btn--black:active {
  color: #fff;
  background-color: #999;
  border-color: #999;
}

.btn--black:hover {
  background-color: #444;
}

.btn--black {
  background-color: #000;
}

.btn--gray:link,
.btn--gray:visited, {
  background-color: #f0f0f0;
  border-color: #f0f0f0;
  color: #555;
}

.btn--gray:hover {
  background-color: #ddd;
  border-color: #ddd;
  color: #444;
}

.btn--gray:active {
  background-color: #ccc;
  border-color: #ccc;
  color: #444;
}

.btn--gray-border:link,
.btn--gray-border:visited, {
  background-color: #fff;
  border-color: #555;
  border-width: 2px;
  color: #555;
}

.btn--gray-border:hover {
  background-color: #fff;
  border-color: #ddd;
  color: #777;
}

.btn--gray-border:active {
  background-color: #ccc;
  border-color: #ccc;
  color: #444;
}

.btn--gray-dark:link,
.btn--gray-dark:visited {
  background-color: #555;
  color: #eee;
}

.btn--gray-dark:hover {
  background-color: #333;
  border-color: #333;
  color: #eee;
}

.btn--gray-dark:active {
  background-color: #777;
  border-color: #777;
  color: #eee;
}


/* BLUES */

.btn--blue:link,
.btn--blue:visited {
  color: #fff;
  background-color: #0074D9;
}

.btn--blue:hover {
  color: #fff!important;
  background-color: #0063aa;
  border-color: #0063aa;
}

.btn--blue:active {
  color: #fff;
  background-color: #001F3F;
  border-color: #001F3F;
}

/* Keep it mobile-first and responsive */

@media screen and (min-width: 32em) {
  .btn--full {
    max-width: 16em!important;
  }
}
## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

