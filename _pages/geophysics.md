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
.description-text{
    width: 220px;
    text-align:left;
    margin-bottom: -0.5em;
    color: black;
    font-size: 18px;
}
.paragraph{
    text-align:justify;
    font-size: 18px;
    margin-bottom: 1.0em;
    width: 800px;
}    

@media screen and (max-width: 1500px) {
    .icon-fig{
        width: 150px;
        height: 120px;
        }
    .description-text{
        width: 150px;
        text-align:left;
        margin-bottom: -0.5em;
        color: black;
        font-size: 18px;
    }            
    .paragraph{
        text-align:justify;
        font-size: 18px;
        margin-bottom: 0.5em;
        width: 400px;
    }
}
</style>

<h3>Imaging the Earth with sound waves</h3>
<!-- <p style="text-align:justify;font-size: 18px; margin-bottom: 1.0em; width: 800px;"> -->
<p class="paragraph">

    I am a Ph.D. candidate in the Stanford Exploration Project (<a href="/sep" target="_blank">SEP</a>) group at Stanford University, which is the the first ever geophysical research consortium funded by the oil and gas industry, founded by seismologist <a href="https://en.wikipedia.org/wiki/Jon_Claerbout" target="_blank">Jon F. Claerbout</a> in 1973. Have a look <a href="/sep">here</a> to learn more about the history of our group!<br/><br/>

    I work on a non-invasive geophyiscal method called <a href="/seismic-imaging">seismic imaging</a>, in which sound waves are employed to produce maps of the Earth's subsurface. This method is useful at detecting high-resolution geological features within the ground, and helps energy companies conduct hydrocarbon exploration and production in a safer, more efficient, and more environmental-friendly manner. Click <a href="/seismic-imaging">here</a> to learn more about this technique!<br/><br/>

    My <a href="/fwime">thesis</a> work revolves around finding novel optimization algorithms to enhance the accuracy and resolution of suchs maps. To do so, it requires building strong skills and knowledge in physics of wave-propagation, mathematical/numerical optimization, and the ability to write and implement fast and efficient code with the use of GPUs. Thanks to SEP's ties with with the oil industry through its affiliate companies, I had the opportunity to interact with experts, receive insightful guidance/feedback, and design a research topic with a strong business impact. <br/><br/>

    Finally, most of the work presented in this website is the product of a 6-year <a href="/eg">joint effort</a> with my friend and colleague <a href="https://www.linkedin.com/in/ettore-biondi/">Ettore Biondi</a>, now a postdoctoral researcher at <a href="http://seismolab.caltech.edu/biondi_e.html" target="_blank">Caltech</a>. Our collaboration has been the most fruitful, stimulating, and efficient period in my life in terms of research. In 2019, Ettore and I won the award for <a href="https://sep.sites.stanford.edu/guillaume-barnier-receives-award-best-student-paper-presented-seg-2019-annual-meeting"><b>Best Student Paper</b></a> Presented at <a href="https://seg.org/About-SEG/Governance/Honors-and-Awards">SEG</a> Annual Meeting for our work on <a href="/papers/seg19.pdf" style="font-weight: normal" target="_blank">seismic velocity model building</a>. Additionally, we created our own <b>youtube channel</b> called <b><a href="https://www.youtube.com/channel/UCjloQO0H6JnddXoB017mcog" target="_blank">eg-optimization</a></b>, where we post technical videos explaining in more details our thesis work. Come check it out, and hit the subscribe button.
</p>

<h3 style="margin-top: 2.0em;>Links">Click on the icons below!</h3>
<body style="background-color: #F2F3F4; ">
    <br>
    <div class="tiles">
        {% for post in site.categories.geophysics %}
            {% include post-grid.html %}
        {% endfor %}
    </div>
</body>

