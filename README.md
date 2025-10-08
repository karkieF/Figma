# Ex09 Event Registration Web Application
## Date:08/10/25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
for page 1:
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="sec-logo" src="img/sec-logo-01as-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">EVENT DAY</div>
      <div class="div"></div>
      <div class="text-wrapper-2">username</div>
      <div class="text-wrapper-3">pa</div>
      <div class="rectangle-2"></div>
      <img class="img" src="img/rectangle-3.svg" />
      <div class="text-wrapper-4">password</div>
      <img class="rectangle-3" src="img/rectangle-5.svg" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">REGISTER</div>
      <img class="SEC-logo" src="img/SEC-logo-1-1.png" />
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}



style.css

.android-compact {
  background-color: #00f2ffde;
  overflow: hidden;
  width: 100%;
  min-width: 412px;
  min-height: 917px;
  position: relative;
}

.android-compact .sec-logo {
  position: absolute;
  top: 33px;
  left: 0;
  width: 412px;
  height: 86px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-compact .text-on-a-path {
  position: absolute;
  top: 145px;
  left: 554px;
  width: 226px;
  height: 218px;
  object-fit: cover;
}

.android-compact .rectangle {
  position: absolute;
  top: 403px;
  left: 48px;
  width: 295px;
  height: 74px;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 415px;
  left: 99px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .div {
  position: absolute;
  top: 573px;
  left: 52px;
  width: 300px;
  height: 63px;
  background-color: #ff494c;
  border: 1px solid;
  border-color: #000000;
  box-shadow: inset 0px 4px 4px #00000040;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 585px;
  left: 85px;
  width: 212px;
  font-family: "Inter-ExtraLight", Helvetica;
  font-weight: 200;
  color: #ffffffa8;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 698px;
  left: 122px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 668px;
  left: 57px;
  width: 295px;
  height: 68px;
  background-color: #ff0000;
  border: 1px solid;
  border-color: #000000;
  box-shadow: inset 0px 4px 4px #00000040;
}

.android-compact .img {
  position: absolute;
  top: 675px;
  left: 476px;
  width: 100px;
  height: 100px;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 680px;
  left: 82px;
  font-family: "Inter-ExtraLight Italic", Helvetica;
  font-weight: 200;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .rectangle-3 {
  position: absolute;
  top: 812px;
  left: 56px;
  width: 296px;
  height: 82px;
}

.android-compact .rectangle-4 {
  position: absolute;
  top: 892px;
  left: 344px;
  width: 2px;
  height: 2px;
  background-color: #d9d9d9;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 831px;
  left: 114px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .SEC-logo {
  position: absolute;
  top: 104px;
  left: 52px;
  width: 281px;
  height: 271px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

for page 2:
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENTS</div>
      <div class="div"></div>
      <div class="text-wrapper-2">CRICKET</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">BADMINTON</div>
      <img class="text-on-a-path" src="img/image.svg" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="rectangle-3"></div>
      <div class="text-wrapper-4">100 MTS</div>
      <img class="img" src="img/rectangle-12.svg" />
      <div class="rectangle-4"></div>
      <div class="text-wrapper-5">FOOT BALL</div>
      <img class="rectangle-5" src="img/rectangle-14.svg" />
      <div class="rectangle-6"></div>
      <div class="text-wrapper-6">VOLLEY BALL</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-compact {
  background-color: #ccff00;
  overflow: hidden;
  width: 100%;
  min-width: 411px;
  min-height: 917px;
  position: relative;
}

.android-compact .rectangle {
  position: absolute;
  top: 297px;
  left: 33px;
  width: 339px;
  height: 64px;
  background-color: #8e2bf8;
  box-shadow: inset 0px 4px 4px #00000040;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 310px;
  left: 99px;
  width: 187px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .div {
  position: absolute;
  top: 441px;
  left: 66px;
  width: 262px;
  height: 53px;
  background-color: #2600ff;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 446px;
  left: 99px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 538px;
  left: 66px;
  width: 262px;
  height: 49px;
  background-color: #0c00ff;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 541px;
  left: 85px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .text-on-a-path {
  position: absolute;
  top: 630px;
  left: -5px;
  width: 262px;
  height: 55px;
}

.android-compact .rectangle-3 {
  position: absolute;
  top: 719px;
  left: 66px;
  width: 262px;
  height: 51px;
  background-color: #130fff;
  box-shadow: inset 0px 4px 4px #00000040;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 723px;
  left: 102px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .img {
  position: absolute;
  top: 725px;
  left: -53px;
  width: 100px;
  height: 100px;
}

.android-compact .rectangle-4 {
  position: absolute;
  top: 814px;
  left: 66px;
  width: 262px;
  height: 55px;
  background-color: #180cff;
}

.android-compact .text-wrapper-5 {
  position: absolute;
  top: 821px;
  left: 93px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .rectangle-5 {
  position: absolute;
  top: 670px;
  left: 5px;
  width: 1px;
  height: 3px;
}

.android-compact .rectangle-6 {
  position: absolute;
  top: 630px;
  left: 66px;
  width: 262px;
  height: 55px;
  background-color: #2a00ff;
}

.android-compact .text-wrapper-6 {
  position: absolute;
  top: 638px;
  left: 77px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

for page 3:
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="img" src="img/92aa6b6e9cd30653c670080fa79bd7c5-1.png" />
      <div class="text-wrapper">REGISTRATION</div>
      <div class="rectangle"></div>
      <div class="div">FORM</div>
      <img class="rectangle-2" src="img/rectangle-17.svg" />
      <div class="rectangle-3"></div>
      <div class="text-wrapper-2">FULL NAME</div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-3">GENDER</div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-4">ID</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-5">DEPARTMENT</div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-6">REGISTER</div>
    </div>
  </body>
</html>

globals.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


style.css

.frame {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 411px;
  min-height: 917px;
  position: relative;
}

.frame .img {
  position: absolute;
  top: 0;
  left: 0;
  width: 411px;
  height: 917px;
  aspect-ratio: 0.67;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 56px;
  left: 82px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle {
  position: absolute;
  top: 199px;
  left: 80px;
  width: 2px;
  height: 7px;
  background-color: #d9d9d9;
}

.frame .div {
  position: absolute;
  top: 121px;
  left: 101px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-2 {
  position: absolute;
  top: 227px;
  left: -520px;
  width: 296px;
  height: 20px;
}

.frame .rectangle-3 {
  position: absolute;
  top: 238px;
  left: 49px;
  width: 286px;
  height: 58px;
  background-color: #d9d9d9;
  box-shadow: inset 0px 4px 4px #00000040;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 247px;
  left: 62px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-4 {
  position: absolute;
  top: 360px;
  left: 59px;
  width: 1px;
  height: 10px;
  background-color: #d9d9d9;
}

.frame .rectangle-5 {
  position: absolute;
  top: 337px;
  left: 49px;
  width: 286px;
  height: 56px;
  background-color: #d9d9d9;
  box-shadow: inset 0px 4px 4px #00000040;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 342px;
  left: 80px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-6 {
  position: absolute;
  top: 438px;
  left: 49px;
  width: 286px;
  height: 61px;
  background-color: #d9d9d9;
  box-shadow: inset 0px 4px 4px #00000040;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 447px;
  left: 101px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-7 {
  position: absolute;
  top: 563px;
  left: 49px;
  width: 286px;
  height: 64px;
  background-color: #d9d9d9;
  box-shadow: inset 0px 4px 4px #00000040;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 581px;
  left: 62px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-8 {
  position: absolute;
  top: 746px;
  left: 62px;
  width: 251px;
  height: 88px;
  background-color: #d9d9d9;
  box-shadow: 0px 4px 4px #00000040;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 769px;
  left: 98px;
  font-family: "Inter-BlackItalic", Helvetica;
  font-weight: 900;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

```


## OUTPUT:
![alt text](<Screenshot (53).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
