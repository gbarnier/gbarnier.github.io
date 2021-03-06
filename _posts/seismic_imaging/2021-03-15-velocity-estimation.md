---
layout: media
title: "Seismic Velocity Estimation"
categories: geophysics
tag: Velocity Estimation
excerpt: " "
ads: false
modified: " "
share: true
permalink: velocity-estimation
image:
  teaser: fwi_marmousi_final_good_a.png
---
<style>

.paragraph{
    text-align: justify;
    font-size: 18px;
    <!-- margin-bottom: 1.0em; -->
    font-family: Georgia;
    width: 800px;
    color: black;

}  
.fig-data{
    width: 600px;
    margin-left: 80px;
}

.fig-label{
    height: 1.0em;
    text-align: center;
    font-size: 18px;
    font-family: Georgia;
    color: black;
    margin-left: -40px;
}

@media screen and (max-width: 1000px) and (min-width: 700px){

    .paragraph{
        text-align: justify;
        font-size: 18px;
        width: 600px;
        color: red;    
    }

}
@media screen and (max-width: 700px){

    .paragraph{
        text-align: justify;
        font-size: 18px;
        width: 300px;
        color: blue;    
    }
    .fig{
        width: 400px;
        margin-left: 0px;
    }
    .fig-label{
        height: 1.0em;
        text-align: left;
        font-size: 18px;
        font-family: Georgia;
        color: black;
        margin-left: 50px;
    }          
}

</style>


<h3>STEP 2: Velocity model estimation</h3>

<p class="paragraph">
Seismic velocity estimation (also referred to as seismic velocity model building, or even <a href="https://en.wikipedia.org/wiki/Seismic_tomography" target="_blank">tomography</a>) is usually the most challenging step of the seismic imaging workflow, and the focus of my <b><a href="/fwime">dissertation work</a></b>. It is the process of estimating the speed at which the waves travel through the ground, referred to as a seismic velocity model. The wave speed highly depends on the type of rocks in which sound propagates, and typically ranges from 1.5 km/s for water to 7 km/s for volcanic rocks within the subsurface (compared to 0.3 km/s in the air).
</p>

<h4>Full waveform inversion (FWI): the industry standard</h4>
<p class="paragraph">
In the last decade, one particular tomogaphic algorithm referred to as full waveform inversion (<a href="https://jean-virieux.obs.ujf-grenoble.fr/IMG/pdf/GPY_2009_VIRIEUX.pdf?" target="_blank">FWI</a>) has become the industry standard for velocity model building (largely due to the increased computational power) and many case studies have shown its potential at recovering accurate and high-resolution solutions. This algorithm requires two inputs: <a href="/acquisition">seismic data</a>, and an approximate initial guess of the solution (referred to as the initial model), and is then applied in an iterative manner as follows:

<ul clas>
    <li class="paragraph">Using the initial velocity model, a seismic survey (similar to the one acquired on the field) is simulated on a computer</li>
    <li class="paragraph">The simulated seismic data is compared to the field data </li>
    <li class="paragraph">If the two datasets are not "similar" enough (according to a pre-defined metric), this lack of similarity (also called error, misfit or residual) is translated into an update of the velocity model, gradually improving its accuracy</li>
    <li class="paragraph">This iterative procedure is performed until the simulated seismic data becomes "similar" enough to the field data. And hopefully, at this point, the estimated velocity model has become accurate</li>
</ul>
</p>

<p class="paragraph">
The animated figure below shows a synthetic example of a FWI workflow on the well-known <a href="/papers/marmousi2.pdf">Marmousi 2</a> model (Martin et al., 2006). In the seismic imaging community, synthetic models/tests are a very common and remain an efficient way to test, benchmark, and assess the performance of tomographic algorithms. Here, the goal is to recover a model as similar to the true Earth as possible (assumed to be known). Each frame corresponds to the velocity model estimation at a given iteration during the process. As you can see, the initial model is quite smooth (i.e., low resolution) and lacks many details from the true Earth. After applying FWI, the final recovered model has greatly improved and captures the high-resolution features from the true Earth.
</p>
<br/>

<figure>
<img src="/images/fwi-marmousi.gif" class="fig"/>
<figcaption class="fig-label">Example of a successful application of FWI on a synthetic model.</figcaption>
</figure>

<p class="paragraph">
<b>Disclaimer</b>: the figure above (especially the boat) is <b>not drawn to scale</b>! The vertical extent of each panel images is approximately 3.5 km in depth by 18 km in width.<br/><br/>
Finally, once the velocity model estimation step has been successfully conducted, it can be used (along with the seismic data) as an input to produce higher-resolution images of the subsurface. This is the last step of the imaging process, referred to as <b>migration</b>.
</p>
<br/>

<p>
<span style="float:left; font-size: 15px"><a href="/acquisition"><b><span style="color: red"><-- PREVIOUS</span></b></a></span>
<span style="float:right; font-size: 15px"><a href="/migration"><b><span style="color: green">NEXT --></span></b> </a></span>
</p>
<br/>
<br/>
