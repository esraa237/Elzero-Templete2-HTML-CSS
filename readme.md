> # This Templete from Elzero web school (the third templete of Html&Css)

>## What I learned from this templetes :

>### HTML Notes :
>- when we need to go to any section or page home we put the content in ```<a>```
>- 

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
