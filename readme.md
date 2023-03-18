> # This Templete from Elzero web school (the third templete of Html&Css)

>## What I learned or Rememberd from this templetes :

>### HTML Notes :
>- when we need to go to any section or page home we put the content in ```<a>```
>>#### Video Div
>- we use holder div inside container - that is used like container in other divs - to avoid the lack of space in mobile response 

>### CSS Notes :
>>#### Header Div
>- we make the effect in links div with ```::before```
>- we use ``` overflow : hidden ``` in (links a) to make the effect in hover
>- to make effect smooth we use ```transition: .3s```
>- mega menu styling
>>#### Landing Div
>- we make the background of it using ```::before```
>- the shape of background made with ```transform: skewY()```
>- arrow animation (bouncing)
>~~~
>@keyframes bouncing{
>    0%,10%,20%,50%,70%,80%,100%{
>       transform: translateY(0);
>    }
>    40%,60%{
>       transform: translateY(-15px);
>    }
> }
>~~~
>>#### Gallary Div
>- main-title animation
>- image flashing effect (animation)
>~~~
>@keyframes flashing{
>  0%,40%{
>    opacity:1 ;
>  }
>  100%{
>    opacity: 0;
>    width:200%;
>    height:200%;
> }
>}
>~~~
>>#### Features Div
>- image effect with before and after(Technique after)
>- fill (more word) when hover with linear-gradient:
>~~~
>.features .container .quality a{
> background-position:right bottom;
> background-size:200% 100%;
> background-image:linear-gradient(to right, rgb(245, 63, 54) 50%, white 50%) ;
>}
>.features .container .quality:hover a{
>  background-position:left bottom;
>  }
>~~~
>>#### Team Member Div
>- to make color shift -for example to gray- to an element we use ```filter:grayscale(100%);```
>- effect box when hover
>>#### OurSkills Div
>- put width of the progress span inline in html to make it easy to accses with js later
>>#### global sperator 
>- to make the separator we add empty div in html and make the shape with css code:
>~~~
> background-image: linear-gradient(135deg, white 25%,transparent 25%), linear-gradient(225deg, white 25%,transparent 25%);
>background-size: 30px 30px;
>~~~