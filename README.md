# Ex09 Event Registration Web Application
## Date:23-12-25

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
page 1
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
      <img class="rectangle" src="img/rectangle-1.png" />
      <div class="frame"></div>
      <img class="sec-logo" src="img/sec-logo-1.png" />
      <img class="img" src="img/rectangle-2.svg" />
      <div class="text-wrapper">REGISTER</div>
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="SPORTS" src="img/SPORTS.svg" />
      <div class="div"></div>
      <div class="text-wrapper-2">LOGIN</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #cfd81c;
  width: 100%;
  min-width: 452px;
  min-height: 1184px;
  position: relative;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 67px;
  left: 17px;
  width: 435px;
  height: 54px;
  object-fit: cover;
}

.iphone-pro-max .frame {
  position: absolute;
  top: 111px;
  left: 8px;
  width: 386px;
  height: 20px;
}

.iphone-pro-max .sec-logo {
  position: absolute;
  top: 192px;
  left: 147px;
  width: 119px;
  height: 109px;
  aspect-ratio: 1.09;
  object-fit: cover;
}

.iphone-pro-max .img {
  position: absolute;
  top: 564px;
  left: 83px;
  width: 271px;
  height: 90px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 587px;
  left: 121px;
  width: 236px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #0e081a;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 556px;
  left: 23px;
  width: 271px;
  height: 79px;
}

.iphone-pro-max .SPORTS {
  position: absolute;
  top: 448px;
  left: 117px;
  width: 143px;
  height: 27px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 441px;
  left: 83px;
  width: 274px;
  height: 86px;
  background-color: #ee1515;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 462px;
  left: 135px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #171414;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

page 2
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
      <img class="element-bg" src="img/2nd-bg-1.png" />
      <div class="text-wrapper">SPORTS DAY EVENT</div>
      <div class="CRICKET-CHESS">CRICKET<br />CHESS<br />THROUGH BALL<br />100MTS<br />VOLLEY BALL<br />BADMINTON</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #e3eae3;
  width: 100%;
  min-width: 445px;
  min-height: 1184px;
  position: relative;
}

.iphone-pro-max .element-bg {
  position: absolute;
  top: 0;
  left: 0;
  width: 445px;
  height: 1184px;
  aspect-ratio: 0.42;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 100px;
  left: 40px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .CRICKET-CHESS {
  position: absolute;
  top: 261px;
  left: 67px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

page 3
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
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <img class="text-on-a-path" src="img/text-on-a-path-4.svg" />
      <img class="img" src="img/image.svg" />
      <div class="rectangle"></div>
      <img class="text-on-a-path-2" src="img/text-on-a-path-2.svg" />
      <img class="text-on-a-path-3" src="img/text-on-a-path-5.svg" />
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <img class="text-on-a-path-4" src="img/text-on-a-path.svg" />
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="text-wrapper-2">FULL NAME</div>
      <div class="text-wrapper-3">GENDER</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-4">AGE</div>
      <div class="text-wrapper-5">REGISTER NO.</div>
      <div class="text-wrapper-6">DEPARTMENT</div>
      <img class="text-on-a-path-5" src="img/text-on-a-path-6.svg" />
      <img class="text-on-a-path-6" src="img/text-on-a-path-3.svg" />
      <div class="rectangle-8"></div>
      <div class="text-wrapper-7">EMAIL ID</div>
      <div class="text-wrapper-8">MOBILE NO.</div>
      <div class="text-wrapper-9">EVENT TO REGISTER</div>
      <div class="text-wrapper-10">REGISTER</div>
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #4c1ee5;
  overflow: hidden;
  width: 100%;
  min-width: 442px;
  min-height: 1141px;
  position: relative;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 38px;
  left: 47px;
  width: 533px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 164px;
  left: -975px;
  width: 291px;
  height: 49px;
}

.iphone-pro-max .img {
  position: absolute;
  top: 176px;
  left: -969px;
  width: 291px;
  height: 60px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 234px;
  left: 37px;
  width: 291px;
  height: 52px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-on-a-path-2 {
  position: absolute;
  top: 306px;
  left: -975px;
  width: 291px;
  height: 55px;
}

.iphone-pro-max .text-on-a-path-3 {
  position: absolute;
  top: 306px;
  left: -980px;
  width: 296px;
  height: 55px;
}

.iphone-pro-max .div {
  position: absolute;
  top: 379px;
  left: 37px;
  width: 291px;
  height: 52px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 456px;
  left: 37px;
  width: 291px;
  height: 57px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-on-a-path-4 {
  position: absolute;
  top: 540px;
  left: -970px;
  width: 292px;
  height: 59px;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 622px;
  left: 33px;
  width: 305px;
  height: 65px;
  background-color: #d9d9d9;
  transform: rotate(0.61deg);
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 725px;
  left: 37px;
  width: 302px;
  height: 58px;
  background-color: #d9d9d9;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 840px;
  left: 172px;
  width: 238px;
  height: 96px;
  background-color: #ff1c1c;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 152px;
  left: 37px;
  width: 295px;
  height: 61px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 166px;
  left: 69px;
  width: 227px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 241px;
  left: 74px;
  width: 212px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle-7 {
  position: absolute;
  top: 306px;
  left: 37px;
  width: 291px;
  height: 55px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 314px;
  left: 78px;
  width: 179px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 385px;
  left: 74px;
  width: 177px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 478px;
  left: 78px;
  width: 236px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-on-a-path-5 {
  position: absolute;
  top: 599px;
  left: -975px;
  width: 294px;
  height: 64px;
}

.iphone-pro-max .text-on-a-path-6 {
  position: absolute;
  top: 540px;
  left: -979px;
  width: 301px;
  height: 59px;
}

.iphone-pro-max .rectangle-8 {
  position: absolute;
  top: 536px;
  left: 37px;
  width: 291px;
  height: 63px;
  background-color: #d9d9d9;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 552px;
  left: 81px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 639px;
  left: 81px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-9 {
  position: absolute;
  top: 736px;
  left: 66px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-10 {
  position: absolute;
  top: 861px;
  left: 210px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #1b1010;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

page 4
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
      <img class="whatsapp-image" src="img/whatsapp-image-2025-10-08-at-19-20-21-9073de9d-1.png" />
    </div>
  </body>
</html>

.iphone-pro-max {
  background-color: #d5e1e1;
  overflow: hidden;
  width: 100%;
  min-width: 560.71px;
  min-height: 1183.86px;
  display: flex;
}

.iphone-pro-max .whatsapp-image {
  margin-top: -1.3px;
  width: 560.71px;
  height: 1183.86px;
  margin-left: -2.7px;
  transform: rotate(0.26deg);
  aspect-ratio: 0.67;
  object-fit: cover;
}
```


## OUTPUT:
<img width="1920" height="1080" alt="528955975-70c118b4-9449-4e0b-b774-f4e7731b0557" src="https://github.com/user-attachments/assets/5c93e893-b3e1-4278-81c1-ef332bf5d5f5" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
