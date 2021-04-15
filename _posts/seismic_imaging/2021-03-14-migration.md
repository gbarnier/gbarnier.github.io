---
layout: media
title: "Step 3: Seismic Migration"
categories: geophysics
tag: Migration
excerpt: " "
ads: false
modified: " "
share: true
permalink: migration
image:
  teaser: migration_uncommented.png
---

<h3>STEP 3: The migration process</h3>

<p style="text-align:justify; font-size: 18px">
In this last step, the seismic image is produced with an algorithm called <a href="https://en.wikipedia.org/wiki/Seismic_migration" target="_blank">migration</a>, which is the process by which seismic recordings (seismograms) are "geometrically re-located in space to the location the event occurred in the subsurface" (according to wikipedia).<br/><br/>

Now let's try to understand migration more intuitively on a simple case with the help of the schematic diagram shown in the figure below. A wave is sent into the ground at <b>t<sub>0</sub></b>, propagates through a first layer of <b>unknown thickness</b> <span style="font-size: 18px;color: red"><b>L<sub>1</sub></b></span>, reflects off an interface, and gets recorded at the surface at <b>t<sub>1</sub>=t<sub>0</sub>+<span style="font-size: 18px;color: blue">&tau;</span></b>, where <b><span style="font-size: 18px;color: blue">&tau;</span></b> corresponds to the time it took for the wave to travel from the source to the interface, and from the interface to the sensor.<br/><br/>
If the source-sensor distance <span style="font-size: 18px;color: black"><b>D<sub>SR</sub></b></span> and the propagation speed (i.e., the velocity model) <span style="font-size: 18px;color: green"><b>v<sub>1</sub></b></span> in the first layer are known, it is possible (using Pythagorean theorem) to infer the position of the interface (i.e., the thickness <span style="font-size: 18px;color: red"><b>L<sub>1</sub></b></span> of the first layer) that gave rise to the reflection, as shown by the equation at the bottom of the figure. Indeed, for more complex geological settings, this equation does not hold, and numerical methods must be employed, such as reverse time migration (<a href="https://library.seg.org/doi/abs/10.1190/1.1441434?casa_token=0MVJchZLwssAAAAA:HRVpYxmbHB-pQqc5vtOaWmdz8KyxNkcUjluSthoo7FK5ZJA4HgL-9HeKdEVySm5ucas7_mDcFA" target="_blank">RTM</a>).<br/><br/>
</p>

<figure>
<img src="/images/migration_hyperbolic.png" width="500" style="margin-left:150px"/>
<figcaption style="height: 1.0em; text-align:center; font-size: 18px; font-family: Calibri; color: black; margin-left: 0px">Schematic diagram of a migration process</figcaption>
</figure>

<p style="text-align:justify; font-size: 18px">
The <b>take-away message</b> here is that migration is simply the process of using the reflected energy present in the recorded signal and mapping it back - or migrating it - to the position of the interface between rock layers that generated the reflection. <br/><br/>

The inputs for the migration step are the <a href="/acquisition">seismic data</a> acquired in the field (step 1 of the imaging process) and the seismic <a href="/velocity-estimation">velocity model</a> obtained in step 2. The figure below illustrates these inputs for the same synthetic numerical example used in the previous sections (the Marmousi 2 model). The left panel shows the seismic data as if it had been acquired with an offshore survey, and the right panel is the velocity model obtained after 100 iterations of FWI.
</p>
<img src="/images/mig-input.png" width="2000" style="margin-left:0px"/>


<p style="text-align:justify; font-size: 18px">
The output of migration is a map (referred to as a migrated image) displaying sharp boundaries between rock layers of different types (e.g., sandstone, shales, basalt, etc.). The figure below displays an example of such image. The black/white pixels indicate the presence of an interface, while the gray color corresponds to homogenous regions. The resolution of this map is higher than the one of the velocity model (right panel in the figure above) and more details about the Earth can be observed.
</p>
<img src="/images/migration_commented.gif" width="2000" style="margin-left:0px"/>

<p style="text-align:justify; font-size: 18px">
Finally, a team of experts will interpret the geological features of the subsurface by examininig this map (as shown by the colored annotations on the figure above), and use this additional information to infer the presence/location of hydrocarbon reservoirs. Hence, the accuracy and quality of the final migrated image will greatly impact the planning of the hydrocarbon reservoir identification, production phases, and the business-decision process.
<p>
<h3>This is where my thesis starts</h3>
<p style="text-align:justify; font-size: 18px">
In complex geological scenarios, seismic images are highly sensitive to the accuracy of the velocity model obtained by tomography, and even a small error will easily deteriorate the image quality. Unfortunately, the velocity model estimation step is extremely challenging and remains the main bottleneck of the imaging workflow. The success of conventional methods (such as FWI) is contingent on having a good initial guess, which is not always available. Therefore, a lot of research has been conducted to invent new tomography techniques robust enough to bypass the need for an accurate initial model. And this is where my thesis starts! But first, let's see why conventional methods can fail in certain scenarios
</p>
<br/>
<p>
<span style="text-align:right; font-size: 18px"><a href="/velocity-estimation"><-- <b><span style="color: red">PREVIOUS</span></b>: Velocity estimation</a></span>
<span style="text-align:right; margin-left:170px; font-size: 18px"><a href="/bottleneck"><b><span style="color: green">NEXT</span></b>: When conventional methods fail --> </a></span>
</p>
