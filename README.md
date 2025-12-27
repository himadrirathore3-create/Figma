# Ex08 Event Registration Web Application
# Date:16/12/2025
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
1.index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="download" src="img/download-2-1.png" />
      <div class="rectangle"></div>
      <div class="HELLO-WORLD-TICKET">HELLO WORLD!!!!!!<br /><br />TICKET BOOKING FORM</div>
    </div>
  </body>
</html>

```
```
1.global.css

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

```
```
1.style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .download {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 310px;
  left: 48px;
  width: 345px;
  height: 302px;
  background-color: #8fd2e4d4;
}

.iphone-pro-max .HELLO-WORLD-TICKET {
  position: absolute;
  top: 310px;
  left: 84px;
  width: 256px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

```
```
2.index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="div">
        <img class="download" src="img/download-2-1.png" />
        <img class="download" src="img/download-2-2.png" />
        <img class="download" src="img/download-2-3.png" />
        <img class="text-on-a-path" src="img/text-on-a-path.svg" />
        <div class="rectangle"></div>
        <div class="text-wrapper">TICKETS AVAILABLE</div>
        <div class="rectangle-2"></div>
        <div class="DUBAI">
          DUBAI&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~$200
          - $280
        </div>
        <div class="rectangle-3"></div>
        <div class="GREECE">
          GREECE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~$1,400
          - $3,400
        </div>
        <div class="rectangle-4"></div>
        <div class="EGYPT">
          EGYPT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~$350
          - $700
        </div>
        <div class="text-wrapper-2">0-$1,500</div>
        <div class="rectangle-5"></div>
        <div class="FRANCE">
          FRANCE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;~$370
          - $600
        </div>
        <div class="rectangle-6"></div>
        <div class="rectangle-7"></div>
        <div class="KENYA">
          KENYA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          ~$350 - $800
        </div>
        <img class="slice" src="img/slice-1.svg" />
        <div class="JAPAN">
          JAPAN&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          ~$1,200 - $1,500
        </div>
      </div>
    </div>
  </body>
</html>

```
```
2.global.css

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

```
```
2.style.css

.iphone-pro-max {
  background-color: #ffffff;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .download {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 956px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 310px;
  left: 48px;
  width: 345px;
  height: 302px;
  background-color: #8fd2e4d4;
}

.iphone-pro-max .HELLO-WORLD-TICKET {
  position: absolute;
  top: 310px;
  left: 84px;
  width: 256px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

```
```
3.index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="div">
        <img class="download" src="img/download-2-1.png" />
        <div class="ellipse"></div>
        <div class="text-wrapper">PROCEDURE FOR BOOKING</div>
        <div class="rectangle"></div>
        <p class="p">
          The process of reserving seats on an aircraft by selecting the destination, date, airline, and passenger
          details, then making payment online or offline.
        </p>
      </div>
    </div>
  </body>
</html>

```
```
3.global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.cs")

*{
    -webkit-font-smoothing: antialiased;
    box-sizing: border-box;
}

html,
body {
    margin: 0px;
    height: 100%;
}

button: focus-visible {
    outline: 2px solid #4a90e2 limportant;
    outline: -webkit-focus-ring-color auto 5px !important;

} 
a {
    text-decoration: none;
}
```
```
3.style.css

.iphone-pro-max {
    background-color: #7a78e7;
    width: 100%;
    min-width: 440px;
    min-height: 956px;
    display: flex;
}

.iphone-pro-max .div {
    width: 440px;
    height: 956px;
    position: relative;
    background-color: #ffffff;
}

.iphone-pro-max download {
    position: absolute;
    top: 0;
    left: 0;
    width: 440px; 
    height: 956px; 
    aspect-ratio: 0.56;
    object-fit: cover;
}

.iphone-pro-max ellipse {
    top: 76px;
    position: absolute;
    left: 95px;
    width: 216px;
    height: 279px;
    background-color: #Bfd1e4d9;
    border-radius: 108px/139.5px;
}

.iphone-pro-max text-wrapper {
    position: absolute;
    top: 173px;
    left: 120px;
    width: 165px;
    font-family: "Itim-Regular", Helvetica;
    font-weight: 400;
    color: #eeeeee;
    font-size: 24px;
    letter-spacing: 0;
    line-height: normal;
}

.iphone-pro-max rectangle {
    position: absolute;
    τορ: 494px;
    left: 41px;
    width: 339px;
    height: 306px;
    background-color: #8fd2e4d9;
}

.iphone-pro-max. {
    position: absolute;
    top: 524px;
    left: 84px;
    width: 254px;
    font-family: "Itin-Regular", Helvetica:
    font-weight: 400;
    color: #00000; font-size: 24px,
    letter-spacing:
    1ine-height: normal;

```
```
4.index.html

<!DOCTYPE html>

<html>

<head>

<meta name="viewport" content="width=device-width, initial-sca

<meta charset="utf-8" />

<link rel="stylesheet" href="globals.css" /> <link rel=stylesheet" href="style.css" />

</head>

<body>

<div class="iphone-pro-max">

<img class="download" src="img/download-2-4.png" />

<div class="rectangle"></div>

<div class="text-wrapper">BOOKING SERVICE</div>

<div class="div"></div>

<div class="EMAIL-gmail">EMAIL:<br />tourisme@gmail.com</div 6

<div class="rectangle-2"></div>

<div class="PHN-NO">PHN.NO:<br />6383955587</div>

</div>

</body>

</html>

```
```
4.global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.cs")

*
{ -webkit-font-smoothing: antialiased;

box-sizing: border-box;

html,

body {

margin: 8px;

height: 100%;
}

button: focus-visible {
    outline: 2px solid #4a90e2 !important;
    outline: -webkit-focus-ring-color auto 5px !important;
}

a{
    text-decoration: none;

}
```
```
4.style.css

.iphone-pro-max {
    background-color: #ffffff;
    width: 100%;
    min-width: 440px;
    min-height: 956px;
    position: relative;
}

.iphone-pro-max.download {
    position: absolute;
    top: 0;
    left: 0;
    width: 440px;
    height: 956px;
    aspect-ratio: 0.56;
    object-fit: cover;
}

.iphone-pro-max rectangle {
    position: absolute;
    top: 100px;
    left: 62px;
    width: 319px;
    height: 192px;
    background-color: #8fd2e4e3;
}

.iphone-pro-max text-wrapper {
    position: absolute;
    top: 139px;
    left: 112px;
    width: 233px;
    font-family: "Itim-Regular", Helvetica;
    font-weight: 400;
    color: #000000;
    font-size: 48px;
    letter-spacing: 0;
    line-height: normal;
    white-space: nowrap;
}

.iphone-pro-max .div {
    position: absolute;
    top: 687px;
    left: 44px;
    width: 355px;
    height: 101px;
    background-color: #8fd2e4e0;
}

.iphone-pro-max EMAIL-gmail {
    position: absolute;
    top: 695px;
    left: 71px;
    width: 298px;
    transform: rotate(0.88deg);
    font-family: "Itim-Regular", Helvetica;
    font-weight: 400;
    color: #000000;
    font-size: 32px;
    letter-spacing: 0;
    line-height: normal;
    white-space: nowгар;
}

.iphone-pro-max.rectangle-2 {
    position: absolute;
    top: 524px;
    left: 44px;
    width: 337px;
    height: 96px;
    background-color: #8fd2e4e6;
}

.iphone-pro-max.PHN-NO {
    position: absolute;
    top: 531px;
    left: 62px;
    width: 319px;
    font-family: "Itim-Regular", Helvetica;
    font-weight: 400;
    color: #000000;
    font-size: 32px;
    letter-spacing: 0;
    line-height: normal;
}
```

# OUTPUT:
![alt text](<Screenshot 2025-12-23 085741.png>)
![alt text](<Screenshot 2025-12-23 085755.png>)
![alt text](<Screenshot 2025-12-23 085707.png>)
![alt text](<Screenshot 2025-12-23 085728.png>)
# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
