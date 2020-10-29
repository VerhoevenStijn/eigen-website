---
title: 'Homepage'
layout: 'layouts/home.html'
custom_css: "
#lijnen{
  border-bottom: 1rem solid white;
  }
  .lijn{
    width: 50px;
    border-bottom: 1rem solid white;
    animation: lijn 7s infinite;
    position: relative;
    z-index: -1;
  }
  @keyframes lijn{
    0%   {width: 200px; border-bottom: 1rem solid red;left:800px; top:300px;}
    25%  {width: 250px; border-bottom: 1rem solid green; left:100px; top:500px;}
    50%  {width: 100px; border-bottom: 1rem solid orange; transform: rotate(720deg); left:200px; top:10px;}
    75%  {width: 200px; left:200px; top:400px;}
    100% {width: 500px; left:800px; top:200px;}
  }
  .cirkel {
    border-radius: 50%;
  	width: 60px;
  	height: 60px;
    position: relative;
    border: 2px solid red;
    animation: cirkel 7s infinite;
  }

  @keyframes cirkel {
      0%   {border: 0.3rem solid yellow; left:0px; top:0px;}
      25%  {border: 0.3rem solid red; left:1000px; top:200px;}
      50%  {border: 0.3rem solid purple; left:800px; top:60px;}
      75%  {border: 0.3rem solid green; left:400px; top:200px;}
      100% {border: 0.3rem solid blue; left:0px; top:0px;}
  }

  .vierkant {
  	width: 50px;
  	height: 50px;
    border: 2px solid white;
    position: relative;
    animation: vierkantAnimatie 7s infinite;
  }

  @keyframes vierkantAnimatie {
      0%   {border: 2px solid blue; left:450px; top:700px;}
      25%  {border: 2px solid green; left:60px; top:60px;}
      50%  {border: 2px solid red; left:300px; top:60px;}
      75%  {border: 2px solid yellow; left:900px; top:100px;}
      100% {border: 2px solid orange; left:400px; top:500px;}
  }

  .vierkantTwee {
  	width: 0;
  	height: 0;
  	border-left: 2px solid yellow;
  	border-right: 2px solid yellow;
  	border-bottom: 20px solid yellow;
    position: relative;
    animation: vierkantTwee 7s infinite;
  }

  @keyframes vierkantTwee {
      0%   {border: 30px solid green; left:800px; top:300px;}
      25%  {border: 40px solid red; left:500px; top:100px;}
      50%  {border: 60px solid yellow; left:200px; top:10px;}
      75%  {border: 30px solid orange; left:900px; top:300px;}
      100% {border: 50px solid orange; left:200px; top:500px;}
  }"
---

### shapes - zweef mee door deze portfoliowebsite
