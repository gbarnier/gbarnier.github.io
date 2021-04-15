---
layout: media
title: "Step 2: Seismic Velocity Estimation"
categories: geophysics
excerpt: " "
ads: false
modified: " "
share: true
permalink: velocity-estimation
image:
  teaser: fwi_marmousi_final_good_a.png
---

<h3>STEP 2: Velocity model estimation</h3>

<p style="text-align:justify; font-size: 18px">
Seismic velocity estimation (also referred to as seismic velocity model building, or even <a href="https://en.wikipedia.org/wiki/Seismic_tomography" target="_blank">tomography</a>) is usually the most challenging step of the seismic imaging workflow, and the focus of my <b><a href="/fwime">dissertation work</a></b>. It is the process of estimating the speed at which the waves travel through the ground, referred to as a seismic velocity model. The wave speed highly depends on the type of rocks in which sound propagates, and typically ranges from 1.5 km/s for water to 7 km/s for volcanic rocks within the subsurface (compared to 0.3 km/s in the air).
</p>

<h4>Full waveform inversion (FWI): the industry standard</h4>
<p style="text-align:justify; font-size: 18px">
In the last decade, one particular tomogaphic algorithm referred to as full waveform inversion (<a href="https://jean-virieux.obs.ujf-grenoble.fr/IMG/pdf/GPY_2009_VIRIEUX.pdf?" target="_blank">FWI</a>) has become the industry standard for velocity model building (largely due to the increased computational power) and many case studies have shown its potential at recovering accurate and high-resolution solutions. This algorithm requires two inputs: <a href="/acquisition">seismic data</a>, and an approximate initial guess of the solution (referred to as the initial model), and is then applied in an iterative manner as follows:

<ul style="font-size: 18px;">
    <li style="font-size: 18px;">Using the initial velocity model, a seismic survey (similar to the one acquired on the field) is simulated on a computer</li>
    <li style="font-size: 18px;">The simulated seismic data is compared to the field data </li>
    <li style="font-size: 18px;">If the two datasets are not "similar" enough (according to a pre-defined metric), this lack of similarity (also called error, misfit or residual) is translated into an update of the velocity model, gradually improving its accuracy</li>
    <li style="font-size: 18px;">This iterative procedure is performed until the simulated seismic data becomes "similar" enough to the field data. And hopefully, at this point, the estimated velocity model has become accurate</li>
</ul>
</p>

<p style="text-align:justify; font-size: 18px">
The animated figure below shows a synthetic example of a FWI workflow on the <a href="/papers/marmousi2.pdf">Marmousi 2</a> model (Martin et al., 2006). In the seismic imaging community, synthetic models/tests remain a very common and efficient way to test, benchmark, and assess the performance of tomographic algorithms. Here, the goal is to recover a model as similar to the true Earth as possible (assumed to be known). Each frame corresponds to the velocity model estimation at a given iteration during the process. As you can see, the initial model is quite smooth (i.e., low resolution) and lacks many details from the true Earth. After applying FWI, the final recovered model has greatly improved and captures the high-resolution features from the true Earth.
</p><br/>

<figure>
<img src="/images/fwi-marmousi.gif" width="600" style="margin-left:130px"/>
<figcaption style="height: 1.0em; text-align:center; font-size: 18px; font-family: Calibri; color: black; margin-left: 40px">Example of a successful application of FWI on a synthetic model.</figcaption>
</figure>

<p style="text-align:justify; font-size: 18px">
Finally, once the velocity model estimation step has been successfully conducted, it can be used (along with the seismic data) as an input to produce higher-resolution images of the subsurface. This is the last step of the imaging process, referred to as <b>migration</b>.
</p>
<br/>
<p>
<span style="text-align:left; font-size: 18px"><a href="/acquisition"><-- <b><span style="color: red">PREVIOUS</span></b>: Seismic Data Acquisition</a></span>
<span style="text-align:right; margin-left:300px; font-size: 18px"><a href="/migration"><b><span style="color: green">NEXT</span></b>: Migration --> </a></span>
</p>
