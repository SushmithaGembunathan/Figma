# Ex09 Event Registration Web Application
## Date:21.12.24

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
Home Page 

<div class="container--0-">
  <img
    src="data:image/png;"
  /><svg
    width="248"
    height="74"
    viewBox="0 0 248 74"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_d_22_2)">
      <rect x="4" width="240" height="66" fill="#1DADCA"></rect>
      <rect x="4.5" y="0.5" width="239" height="65" stroke="black"></rect>
    </g>
    <defs>
      <filter
        id="filter0_d_22_2"
        x="0"
        y="0"
        width="248"
        height="74"
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
          result="effect1_dropShadow_22_2"
        ></feBlend>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="effect1_dropShadow_22_2"
          result="shape"
        ></feBlend>
      </filter>
    </defs></svg
  ><svg
    width="248"
    height="64"
    viewBox="0 0 248 64"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_d_22_3)">
      <rect x="4" width="240" height="56" fill="#1DBFCA"></rect>
      <rect x="4.5" y="0.5" width="239" height="55" stroke="black"></rect>
    </g>
    <defs>
      <filter
        id="filter0_d_22_3"
        x="0"
        y="0"
        width="248"
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
          result="effect1_dropShadow_22_3"
        ></feBlend>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="effect1_dropShadow_22_3"
          result="shape"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-3">Register</div>
  <div class="text-0-1-4">Login</div>
</div>

.container--0- {
  position: absolute;
  left: -524px;
  top: -578px;
  width: 412px;
  height: 917px;
  background-color: #ffdd00c4;
  justify-content: start;
  align-items: start;
}
.text-0-1-3 {
  width: 227px;
  height: 53px;
  color: #000000;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 32px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 193px;
  height: 25px;
  color: #000000;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 32px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

Page 2

<div class="container--0-">
  <div class="text-0-1-0">
    Talent Fest <br />
    Events
  </div>
  <div class="text-0-1-1">*Solo Singing</div>
  <div class="text-0-1-2">*Group Singing</div>
  <div class="text-0-1-3">*Solo Dance</div>
  <div class="text-0-1-4">*Group Dance</div>
  <div class="text-0-1-5">*BeatBoxing</div>
  <div class="text-0-1-6">*Mime Act</div>
  <div class="text-0-1-7">*Mono Act</div>
  <div class="text-0-1-8">*ShipWreck</div>
</div>

.container--0- {
  position: absolute;
  left: -80px;
  top: -578px;
  width: 412px;
  height: 917px;
  background-color: #13d5af;
  justify-content: start;
  align-items: start;
}
.text-0-1-0 {
  width: 380px;
  height: 140px;
  color: #ffffff;
  border-width: 1px;
  border-style: solid;
  border-color: #a22224;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 40px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-1 {
  width: 386px;
  height: 39px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 242px;
  height: 37px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-3 {
  width: 238px;
  height: 28px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-4 {
  width: 247px;
  height: 29px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-5 {
  width: 231px;
  height: 36px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-6 {
  width: 202px;
  height: 35px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 233px;
  height: 39px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-8 {
  width: 239px;
  height: 37px;
  color: #ffffff;
  font-size: 24px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

Page 3

<div class="container--0-">
  <div class="text-0-1-0">Register Now</div>
  <svg
    width="278"
    height="35"
    viewBox="0 0 278 35"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="278" height="35" fill="#D9D9D9"></rect></svg
  ><svg
    width="278"
    height="37"
    viewBox="0 0 278 37"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="278" height="37" fill="#D9D9D9"></rect></svg
  ><svg
    width="278"
    height="37"
    viewBox="0 0 278 37"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="278" height="37" fill="#D9D9D9"></rect></svg
  ><svg
    width="278"
    height="36"
    viewBox="0 0 278 36"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="278" height="36" fill="#D9D9D9"></rect></svg
  ><svg
    width="278"
    height="37"
    viewBox="0 0 278 37"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="278" height="37" fill="#D9D9D9"></rect></svg
  ><svg
    width="189"
    height="59"
    viewBox="0 0 189 59"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g filter="url(#filter0_d_23_33)">
      <ellipse
        cx="94.5"
        cy="25.5"
        rx="90.5"
        ry="25.5"
        fill="#FFDD00"
        fill-opacity="0.77"
        shape-rendering="crispEdges"
      ></ellipse>
      <path
        d="M184.5 25.5C184.5 28.7638 182.148 31.9872 177.611 35.0096C173.093 38.0195 166.522 40.7495 158.358 43.05C142.036 47.6489 119.458 50.5 94.5 50.5C69.5415 50.5 46.9643 47.6489 30.6424 43.05C22.4781 40.7495 15.9073 38.0195 11.3891 35.0096C6.85217 31.9872 4.5 28.7638 4.5 25.5C4.5 22.2362 6.85217 19.0128 11.3891 15.9904C15.9073 12.9805 22.4781 10.2505 30.6424 7.95004C46.9643 3.35106 69.5415 0.5 94.5 0.5C119.458 0.5 142.036 3.35106 158.358 7.95004C166.522 10.2505 173.093 12.9805 177.611 15.9904C182.148 19.0128 184.5 22.2362 184.5 25.5Z"
        stroke="black"
        shape-rendering="crispEdges"
      ></path>
    </g>
    <defs>
      <filter
        id="filter0_d_23_33"
        x="0"
        y="0"
        width="189"
        height="59"
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
          result="effect1_dropShadow_23_33"
        ></feBlend>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="effect1_dropShadow_23_33"
          result="shape"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-7">Full Name</div>
  <div class="text-0-1-8">Department</div>
  <div class="text-0-1-9">Email ID</div>
  <div class="text-0-1-10">Contact Number</div>
  <div class="text-0-1-11">Events To Register</div>
  <div class="text-0-1-12">SUBMIT</div>
</div>

.container--0- {
  position: absolute;
  left: 364px;
  top: -578px;
  width: 412px;
  height: 917px;
  background-color: #df8cc7;
  justify-content: start;
  align-items: start;
}
.text-0-1-0 {
  width: 317px;
  height: 57px;
  color: #ffffff;
  border-width: 1px;
  border-style: solid;
  border-color: #000000;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 64px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 254px;
  height: 14px;
  color: #000000;
  font-size: 20px;
  font-family: Inika, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-8 {
  width: 236px;
  height: 14px;
  color: #000000;
  font-size: 20px;
  font-family: Inika, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-9 {
  width: 178px;
  height: 19px;
  color: #000000;
  font-size: 20px;
  font-family: Inika, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-10 {
  width: 190px;
  height: 24px;
  color: #000000;
  font-size: 20px;
  font-family: Inika, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-11 {
  width: 227px;
  height: 16px;
  color: #000000;
  font-size: 20px;
  font-family: Inika, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}
.text-0-1-12 {
  width: 92px;
  height: 18px;
  color: #000000;
  box-shadow: 0px 4px 4px 0 #000000;
  font-size: 20px;
  font-family: Inika, "Bold";
  font-weight: 700;
  text-align: left;
  vertical-align: top;
}

Page 4

<div class="container--0-">
  <div class="text-0-1-0">
    Thank You <br />
    For <br />Registering
  </div>
</div>

.container--0- {
  position: absolute;
  left: 808px;
  top: -578px;
  width: 412px;
  height: 917px;
  background-color: #e09842;
  justify-content: start;
  align-items: start;
}
.text-0-1-0 {
  width: 297px;
  height: 283px;
  color: #000000;
  border-width: 1px;
  border-style: solid;
  border-color: #ffffff;
  box-shadow: 0px 4px 8px 0 #000000;
  font-size: 40px;
  font-family: Inknut Antiqua, "ExtraBold";
  font-weight: 800;
  text-align: left;
  vertical-align: top;
}

```

## OUTPUT:

![alt text](<Screenshot 2024-12-21 132453.png>)
![alt text](<Screenshot 2024-12-21 133116.png>)
![alt text](<Screenshot 2024-12-21 133130.png>)
![alt text](<Screenshot 2024-12-21 133143.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
