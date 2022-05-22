---
layout: ml
title:
tag: Geophysics
share: true
permalink: /geophysics/

---

<style>

.icon-fig{
    width: 250px;
    height: 200px;
    }
.description-title{
    width: 220px;
    text-align: left;
    margin-bottom: -0.5em;
    color: black;
    font-size: 22px;
    font-family: Calibri;
}

.description-text{
    width: 220px;
    text-align: left;
    margin-bottom: -0.5em;
    color: black;
    font-size: 18px;
    font-family: Georgia;
}
.paragraph{
    text-align: justify;
    font-size: 18px;
    margin-bottom: 1.0em;
    width: 800px;
    color: black;
    font-family: Georgia;
}    

@media screen and (max-width: 1000px) and (min-width: 700px){
    .icon-fig{
        width: 150px;
        height: 120px;
        }

    .description-title{
        width: 150px;
        text-align: center;
        margin-bottom: -0.5em;
        color: black;
        font-size: 18px;
        font-family: Calibri;
    }

    .description-text{
        width: 150px;
        text-align: left;
        margin-bottom: -0.5em;
        color: black;
        font-size: 18px;
    }            
    .paragraph{
        text-align:justify;
        font-size: 18px;
        margin-bottom: 0.5em;
        width: 600px;
        color: black;
    }
}

@media screen and (max-width: 700px){
    .icon-fig{
        width: 150px;
        height: 120px;
        }

    .description-title{
        width: 150px;
        text-align: center;
        margin-bottom: -0.5em;
        color: black;
        font-size: 18px;
        font-family: Calibri;
    }

    .description-text{
        width: 150px;
        text-align: left;
        margin-bottom: -0.5em;
        color: black;
        font-size: 18px;
    }            
    .paragraph{
        text-align: left;

        font-size: 18px;
        margin-bottom: 0.5em;
        width: 300px;
        color: black;
    }
}
</style>

<h3>Imaging the Earth with sound waves</h3>
<p class="paragraph">

    <span style="font-size: 10px">🟦</span> I am a Ph.D. candidate in the Stanford Exploration Project (<a href="/sep" target="_blank">SEP</a>) group at Stanford University, and I work on a non-invasive geophyiscal method called <a href="/seismic-imaging"><b>seismic imaging</b></a>, in which sound waves are employed to produce maps of the Earth's subsurface. This method is useful at detecting high-resolution geological features within the ground, and helps energy companies conduct hydrocarbon exploration and production in a safer, more efficient, and more environmental-friendly manner.<br/><br/>

    <span style="font-size: 10px">🟦</span> My <a href="/fwime"><b>thesis</b></a> work revolves around finding novel optimization algorithms to enhance the accuracy and resolution of suchs maps. To do so, it requires building strong skills and knowledge in physics of wave-propagation, mathematical/numerical optimization, and the ability to write and implement fast and efficient code with the use of GPUs. Thanks to SEP's ties with with the oil industry through its affiliate companies, I had the opportunity to interact with experts, receive insightful guidance/feedback, and design a research topic with a strong business impact. <br/><br/>

      <span style="font-size: 10px">🟦</span> Download my <b>Ph.D. <a href="http://sepwww.stanford.edu/data/media/public/sep/gbarnier/Guillaume_thesis_sep_website.pdf" target="_blank">thesis</a></b> and watch my <a href="https://www.youtube.com/watch?v=vv9krmVRkMo&t=3051s" target="_blank"><b>defense</b></a><br/><br/>. 
  
    <span style="font-size: 10px">🟦</span> Finally, most of the work presented in this website is the product of a 6-year <a href="/eg">joint effort</a> with my friend and colleague <a href="https://www.linkedin.com/in/ettore-biondi/">Ettore Biondi</a>, now a postdoctoral researcher at <a href="http://seismolab.caltech.edu/biondi_e.html" target="_blank">Caltech</a>. Our collaboration has been the most fruitful, stimulating, and efficient period in my life in terms of research. In 2019, Ettore and I won the award for <a href="https://sep.sites.stanford.edu/guillaume-barnier-receives-award-best-student-paper-presented-seg-2019-annual-meeting"><b>Best Student Paper</b></a> Presented at <a href="https://seg.org/About-SEG/Governance/Honors-and-Awards">SEG</a> Annual Meeting for our <a href="/papers/seg19.pdf" style="font-weight: normal" target="_blank">work</a> on seismic velocity model building.
</p>

<h3 style="margin-top: 2.0em;color: blue">Click on the icons below!<br/>
⬇⬇⬇</h3>
<body style="background-color: #F2F3F4; ">
    <br>
    <div class="tiles">
        {% for post in site.categories.geophysics %}
            {% include post-grid.html %}
        {% endfor %}
    </div>
</body>
