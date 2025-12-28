# Ex08 Event Registration Web Application
## Date:24-12-2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:

```
html

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
      <div class="rectangle"></div>
      <div class="text-wrapper">Annual day</div>
      <div class="div"></div>
      <div class="text-wrapper-2">Login</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Register</div>
      <img class="logos" src="img/idwahcuod7-logos-1.png" />
    </div>
  </body>
</html>

style

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  top: 419px;
  left: 33px;
  width: 379px;
  height: 59px;
  position: absolute;
  background-color: #a11f6b;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 419px;
  left: 66px;
  width: 440px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .div {
  top: 532px;
  left: 102px;
  width: 211px;
  height: 64px;
  position: absolute;
  background-color: #a11f6b;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 532px;
  left: 133px;
  width: 357px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 638px;
  left: 102px;
  width: 211px;
  height: 58px;
  background-color: #a11f6b;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 636px;
  left: 105px;
  width: 209px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 50px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .logos {
  position: absolute;
  top: 183px;
  left: 129px;
  width: 182px;
  height: 182px;
  aspect-ratio: 1;
  object-fit: cover;
}

html

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
      <div class="rectangle"></div>
      <div class="text-wrapper">Annual days events</div>
      <img class="polygon" src="img/polygon-1.svg" />
      <img class="polygon" src="img/polygon-2.svg" />
      <img class="img" src="img/polygon-3.svg" />
      <img class="polygon-2" src="img/polygon-4.svg" />
      <img class="polygon-3" src="img/polygon-5.svg" />
      <img class="polygon-4" src="img/polygon-6.svg" />
      <div class="div">Dance</div>
      <div class="text-wrapper-2">Singing</div>
      <div class="text-wrapper-3">Mime show</div>
      <div class="text-wrapper-4">Solo performance</div>
      <div class="text-wrapper-5">Prize distribution</div>
    </div>
  </body>
</html>

style

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 440px;
  height: 65px;
  background-color: #a11f6b;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 6px;
  left: 19px;
  width: 440px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #363334;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .polygon {
  position: absolute;
  top: 160px;
  left: 65px;
  width: 28px;
  height: 29px;
}

.iphone-pro-max .img {
  top: 288px;
  position: absolute;
  left: 65px;
  width: 28px;
  height: 29px;
}

.iphone-pro-max .polygon-2 {
  top: 422px;
  position: absolute;
  left: 65px;
  width: 28px;
  height: 29px;
}

.iphone-pro-max .polygon-3 {
  top: 550px;
  position: absolute;
  left: 65px;
  width: 28px;
  height: 29px;
}

.iphone-pro-max .polygon-4 {
  top: 709px;
  position: absolute;
  left: 65px;
  width: 28px;
  height: 29px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 154px;
  left: 117px;
  width: 319px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 277px;
  left: 117px;
  width: 305px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 417px;
  left: 117px;
  width: 299px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 537px;
  left: 127px;
  width: 292px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 700px;
  left: 127px;
  width: 299px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

html

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
      <div class="rectangle"></div>
      <div class="text-wrapper">Event resgistration form</div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-2">Full name</div>
      <div class="text-wrapper-3">Gender</div>
      <div class="text-wrapper-4">Age</div>
      <div class="text-wrapper-5">Mobile no</div>
      <div class="text-wrapper-6">Register no</div>
      <div class="text-wrapper-7">Email id</div>
      <div class="text-wrapper-8">Department</div>
      <div class="text-wrapper-9">Events registered</div>
      <div class="rectangle-9"></div>
      <div class="text-wrapper-10">Submit</div>
    </div>
  </body>
</html>


style

.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 440px;
  min-height: 956px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 0;
  left: -11px;
  width: 451px;
  height: 96px;
  background-color: #a11f6b;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 1px;
  left: 27px;
  width: 423px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .div {
  position: absolute;
  top: 127px;
  left: 21px;
  width: 279px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 193px;
  left: 21px;
  width: 279px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 261px;
  left: 21px;
  width: 279px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 327px;
  left: 21px;
  width: 279px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 392px;
  left: 21px;
  width: 279px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 458px;
  left: 21px;
  width: 279px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-7 {
  position: absolute;
  top: 526px;
  left: 21px;
  width: 279px;
  height: 54px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-8 {
  position: absolute;
  top: 606px;
  left: 21px;
  width: 279px;
  height: 103px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 129px;
  left: 21px;
  width: 341px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 199px;
  left: 21px;
  width: 310px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 256px;
  left: 21px;
  width: 294px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 327px;
  left: 21px;
  width: 280px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 394px;
  left: 21px;
  width: 365px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 464px;
  left: 21px;
  width: 302px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 526px;
  left: 21px;
  width: 291px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-9 {
  position: absolute;
  top: 610px;
  left: 21px;
  width: 342px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-9 {
  position: absolute;
  top: 764px;
  left: 117px;
  width: 175px;
  height: 64px;
  background-color: #1dc79c;
}

.iphone-pro-max .text-wrapper-10 {
  position: absolute;
  top: 773px;
  left: 137px;
  width: 267px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:

![alt text](<Screenshot (25).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
