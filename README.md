# Ex09 Event Registration Web Application
## Date:17/12/2024

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
1. Registration page
```
(HTML-CODE)
<div class="container--0-">
  <img
    src="data:image/jpeg;base64,/9j/4AAQSkZJ"
  /><svg
    width="230"
    height="64"
    viewBox="0 0 230 64"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_d_2_3)">
      <rect x="4" width="222" height="56" fill="#3138FF"></rect>
    </g>
    <defs>
      <filter
        id="filter0_d_2_3"
        x="0"
        y="0"
        width="230"
        height="64"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite in2="hardAlpha" operator="out"></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="BackgroundImageFix"
          result="effect1_dropShadow_2_3"
        ></feBlend>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="effect1_dropShadow_2_3"
          result="shape"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-2">REGISTER</div>
  <div class="text-0-1-3">Grand International Conference</div>
</div>

(CSS-CODE)
.container--0- {
  position: absolute;
  left: -206px;
  top: -459px;
  width: 360px;
  height: 640px;
  background-color: #c1e096;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 187px;
  height: 29px;
  color: #ffffff;
  font-size: 32px;
  font-family: Italiana, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-3 {
  width: 214px;
  height: 67px;
  color: #000000;
  font-size: 32px;
  font-family: IM FELL Great Primer, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
```
2. SELECTION PAGE
```
(HTML-CODE)
<div class="container--0-">
  <img
    src="data:image/jpeg;base64,/9j/4AAQSkZJ"
  /><svg
    width="189"
    height="41"
    viewBox="0 0 189 41"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="189" height="41" fill="#FF0101"></rect>
  </svg>
  <div class="text-0-1-2">SELECT VENUE</div>
  <div class="text-0-1-3">
    Singapore<br />Dubai<br />Kuala Lumpur<br />Sri Lanka
  </div>
  <div class="text-0-1-4">Fill your option in the above box</div>
  <svg
    width="157"
    height="45"
    viewBox="0 0 157 45"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="157" height="45" fill="#B65DED"></rect>
  </svg>
</div>

(CSS-CODE)
.container--0- {
  position: absolute;
  left: 179px;
  top: -459px;
  width: 360px;
  height: 640px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-2 {
  width: 254px;
  height: 35px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inria Sans, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-3 {
  width: 298px;
  height: 354px;
  color: #000000;
  font-size: 32px;
  font-family: Imprima, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-4 {
  width: 167px;
  height: 14px;
  color: #000000;
  border-width: 1px;
  border-style: solid;
  border-color: #c89494;
  font-size: 12px;
  font-family: Imprima, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
```

3. END PAGE
```
(HTML-CODE)
<div class="container--0-">
  <img
    src="data:image/jpeg;base64,/9j/4AAQSkZJ"
  />
  <div class="text-0-1-1">
    Thank You for your co-operation.<br />You will be soon announced about your
    conference trip.
  </div>
  <div class="text-0-1-2">
    For contact<br />Phone : +91 54678 89764<br />Email : saveetha@gmail.com
  </div>
</div>

(CSS-CODE)
.container--0- {
  position: absolute;
  left: 564px;
  top: -459px;
  width: 360px;
  height: 640px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 286px;
  height: 163px;
  color: #000000;
  font-size: 32px;
  font-family: Just Me Again Down Here, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
.text-0-1-2 {
  width: 294px;
  height: 49px;
  color: #000000;
  font-size: 15px;
  font-family: Kaisei Opti, "Regular";
  font-weight: 400;
  text-align: center;
  vertical-align: top;
}
```

## OUTPUT:
![alt text](<Screenshot (65).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
