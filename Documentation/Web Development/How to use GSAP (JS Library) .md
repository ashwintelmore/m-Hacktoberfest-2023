## Description

- Problem stament:- How to use GSAP (JS Library) 

## Domain
- Web Development

## Solution

Before directly jumping on "How to use GSAP?" first we need to know what GSAP actually is. so,

> What is GSAP and what it is used for?
> 
> GSAP (JavaScript library) stands for GreenSock Animation Platform, created by the Greensock team. It’s one of the best web animation libraries 


>Why GSAP ?
>
> If you are looking for :
> 
> - a crazy fast and performant animation library.
> - a library that is armed with a tremendous amount of features to help you achieve beautiful animation no matter how complex it could be.
> - a library that is compatible with every browser and with various frameworks and libraries.
> - a library that can almost animate every single property of an element.
> - a lightweight and expandable library and not dependent on any other 3rd party tools like Jquery.
> 
Following are the steps that you have to follow in order to use GSAP :-

- Create 3 file: index.html, style.css and index.js (You can give any name to files)
- Link both HTML and CSS file in HTML file
- To use GSAP, you have to paste the cdn link of the GSAP above your main script tag so that your gsap load first.
  - visit : https://cdnjs.com/libraries/gsap , copy first script tag and Paste that script tag just above the main script tag.
  - Now GSAP has so many features and in order to use those features you have to copy those script tag from the website that I mentioned earlier and paste it above the main script tag.

example:- 
``` 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.11.2/gsap.min.js" integrity="sha512-gsEItzcNkWxfxHjr4BaEZAd9YuRWYjxnj7c/yukcZ0/nWehUb5TjJNyyv1ApCU2DFH/qgw+stFZHPOKnoQnIuQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script src="index.js"></script>
</body>
</html> 
```

After this you are good to go to use GSAP in your js flie.
