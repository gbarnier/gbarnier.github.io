---
layout: about
tag: About
title: About
permalink: /about/
---

<html>
    <head>
        <!-- <title>Guillaume</title> -->
        <!-- <link type="text/css" rel="stylesheet" href="/css/about_style.css"/> -->

        <style>
        .paragraph-fig{
            width: 550px;
            text-align: justify;
            font-family: Georgia;
            font-size: 18px;
        }
        .paragraph-wide{
            width: 800px;
            text-align: justify;
            font-family: Georgia;
            font-size: 18px;
            word-spacing: -1.0px;
        }        
        .fig-wide{
            margin-left: 20px;
          width: 250px;
          float: right;
          border: 2px solid black;
        }         
        @media screen and (max-width: 1000px) and (min-width: 400px){
            .paragraph-fig{
              width: 370px;
              text-align: justify;
              word-spacing: -1.5px;                            
              margin-left: 0px;
              color: black;
              font-size: 17px;

            }
            .paragraph-wide{
              width: 600px;
              text-align: justify;
              text-justify: distribute;
              word-spacing: -1.25px;
              font-size: 17px;

            }  
            .fig-wide{
              width: 200px;
              float: right;
              border: 2px solid black;
            }
        }    
        @media screen and (max-width: 400px){
            .paragraph-fig{
              width: 300px;
              text-align: left;
              margin-left: 0px;
              color: black;
              font-size: 17px;
            }
            .paragraph-wide{
              width: 300px;
              text-align: left;   
              color: black;
              font-size: 17px;
            }  
            .fig-wide{
              width: 100px;
              float: right;
              border: 2px solid black;
              margin-left: 70px;
            }                                        
        }
        </style>

    </head>


    <body style="background-color: #F2F3F4;">

        <!-- <img src="{{ site.url }}/images/stairs_rio_c.png" alt="Guillaume's photo" style="width: 200px; float: right; border: 2px solid black;"/> -->
        <h5><span style="font-size: 20px">🌎</span> Geophysics</h5>
        <!-- <img src="{{ site.url }}/images/stairs_rio_c.png" alt="Guillaume's photo" style="width: 200px; float: right; border: 2px solid black;"/> -->
        <img src="{{ site.url }}/images/stairs_rio_c.png" alt="Guillaume's photo" class="fig-wide"/>

        <div class="paragraph-fig">
        <!-- <div style="display: inline; font-weight: normal;text-align: left;" > -->
            <p>
                <ul>
                <li class="paragraph-fig">I am Guillaume Barnier, a French Ph.D. candidate in the Stanford Exploration Project (<a href="/sep">SEP</a>) group, within the Department of Geophysics at Stanford University.</li>
                <li class="paragraph-fig">Under the supervision of Prof. <a href="https://wiki.seg.org/wiki/Biondo_Biondi">Biondo Biondi</a>, I design new
                seismic imaging algorithms to produce accurate maps the Earth's subsurface using sound waves. Have a look at the <a href="/geophysics">Geophysics</a> tab!</li>
                <li class="paragraph-fig">In 2019, my friend and fellow student <a href="https://www.linkedin.com/in/ettore-biondi/">Ettore Biondi</a> and I won the award for <a href="https://sep.sites.stanford.edu/guillaume-barnier-receives-award-best-student-paper-presented-seg-2019-annual-meeting"><b>Best Student Paper</b></a> Presented at <a href="https://seg.org">SEG</a> 2019 Annual Meeting for our work on <a href="https://library.seg.org/doi/10.1190/segam2019-3216866.1">seismic velocity model building</a>.</li>
                <li class="paragraph-fig">Before joining the Ph.D. program at Stanford, I obtained my MSc from the <a href="https://geophysics.mines.edu">Geophysics Department</a> at the <a href="https://www.mines.edu">Colorado School of Mines</a> where I used seismoelectric waves (electromagnetic waves induced by sound waves) to characterize petrophysical properties of hydrocarbon reservoirs (check out my <a href="https://mountainscholar.org/bitstream/handle/11124/79570/Barnier_mines_0052N_10305.pdf?sequence=1" target="_blank"> thesis</a>).</li>
                </ul>
            </p>
        </div>

        <h5><span style="font-size: 20px">🕹️</span> Machine Learning</h5>
        <div class="paragraph-wide">
            <p>
                <ul>
                    <li class="paragraph-wide">In the last couple of years, I have become passionate about machine learning, especially <b>reinforcement learning</b> algorithms.</li>
                    <li class="paragraph-wide">I initiated and led a project with the Stanford School of Medicine to predict brain tissue damage for stroke patients using <b>deep supervised learning</b> and <b>computed tomography</b> (CT). You can check out all the details <a href="/ctp-project">here</a>.</li>
                    <li class="paragraph-wide">Recently, I have truly enjoyed some of Stanford's AI courses, which include reinforcement learning (<a href="http://web.stanford.edu/class/cs234/index.html">CS 234</a>), deep learning (<a href="https://cs230.stanford.edu">CS 230</a>), and machine learning (<a href="http://cs229.stanford.edu">CS 229</a>).</li>
                    <li class="paragraph-wide">I am currently trying to define a project on reinforcement learning and will soon post my progress <a href="/rl-project">here</a>, bear with me!</li>
                </ul>
            </p>
        </div>

        <h5><span style="font-size: 20px">📈</span> Financial Markets</h5>
        <div class="paragraph-wide">
            <p>
                <ul>
                    <li class="paragraph-wide">Prior to my Geophysics career, I was an investement banker and I worked for J.P. Morgan Global Markets in London from 2007 to 2010, selling and buying interest rate derivative products for hedge funds.</li>
                </ul>
            </p>
        </div>
        <h5><span style="font-size: 25px">⛰️</span> Outside of Work</h5>
        <div class="paragraph-wide">
            <p>
                <ul>
                    <li class="paragraph-wide">In my free time, I enjoy trail running, riding my road bike, doing CrossFit, and bascially anything that allows me to stay active! Surfing and traveling have always been an important part of my life, and allowed me to spend time in some amazing countries such as Indonesia, Morocco, Peru, Australia, and Mexico. </li>
                    <li class="paragraph-wide">And if you are wondering, I took the above picture on the <a href="https://en.wikipedia.org/wiki/Escadaria_Selarón"> Escadaria Selarón</a> in Rio de Janeiro, <span style="font-size: 25px">🇧🇷</span>.</li>
                </ul>
            </p>
        </div>

    </body>
</html>
