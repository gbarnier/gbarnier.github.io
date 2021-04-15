---
layout: ml
title:
share: true
permalink: /geophysics/

---

<h3>Imaging the Earth with sound waves</h3>
<p style="text-align:justify;font-size: 18px; margin-bottom: 1.0em; width: 800px;">

    I am a Ph.D. candidate in the Stanford Exploration Project (<a href="/sep" target="_blank">SEP</a>) group at Stanford University, which is the the first ever geophysical research consortium funded by the oil and gas industry, and founded by seismologist <a href="https://en.wikipedia.org/wiki/Jon_Claerbout" target="_blank">Jon F. Claerbout</a> in 1973. Have a look <a href="/sep">here</a> to learn more about the history of our group!<br/><br/>

    I work on a non-invasive geophyiscal method called <a href="/seismic-imaging">seismic imaging</a>, in which sound waves are employed to produce maps of the Earth's subsurface. This method is useful at detecting high-resolution geological features within the ground, and helps energy companies conduct hydrocarbon exploration and production in a safer, more efficient, and more environmental-friendly manner. Click <a href="/seismic-imaging">here</a> to learn more about this technique!<br/><br/>

    My <a href="/fwime">thesis</a> work revolves around finding novel optimization algorithms to enhance the accuracy and resolution of suchs maps. To do so, it requires building strong skills and knowledge in physics of wave-propagation, mathematical/numerical optimization, and the ability to write and implement fast and efficient code with the use of GPUs. Thanks to SEP's ties with with the oil industry through its affiliate companies, I had the opportunity to interact with experts, receive insightful guidance/feedback, and design a research topic with a strong business impact. <br/><br/>

    Finally, most of the work presented in this website is the product of a 6-year <a href="/eg">joint effort</a> with my friend and colleague <a href="https://www.linkedin.com/in/ettore-biondi/">Ettore Biondi</a>, now a postdoctoral researcher at <a href="http://seismolab.caltech.edu/biondi_e.html" target="_blank">Caltech</a>. Our collaboration has been the most fruitful, stimulating, and efficient period in my life in terms of research. In 2019, Ettore and I won the award for <a href="https://sep.sites.stanford.edu/guillaume-barnier-receives-award-best-student-paper-presented-seg-2019-annual-meeting"><b>Best Student Paper</b></a> Presented at <a href="https://seg.org/About-SEG/Governance/Honors-and-Awards">SEG</a> Annual Meeting for our work on <a href="/papers/seg19.pdf" style="font-weight: normal" target="_blank">seismic velocity model building</a>.
</p>

<h3 style="margin-top: 2.0em;>Links">Links</h3>
<body style="background-color: #F2F3F4; ">
    <br>
    <div class="tiles">
        {% for post in site.categories.geophysics %}
            {% include post-grid.html %}
        {% endfor %}
    </div>
</body>





<!-- Seismology is the scientific study of earthquakes and the propagation of elastic waves through the Earth
Seismic imaging, or more formally reflection seismology - is

ses the principles of seismology to estimate the properties of the Earth's subsurface from reflected seismic waves. The method requires a controlled seismic source of energy, such as dynamite or Tovex blast, a specialized air gun or a seismic vibrator. Reflection seismology is similar to sonar and echolocation.

Because seismic waves commonly propagate efficiently as they interact with the internal structure of the Earth, they provide high-resolution noninvasive methods for studying the planet's interior. One of the earliest important discoveries (suggested by Richard Dixon Oldham in 1906 and definitively shown by Harold Jeffreys in 1926) was that the outer core of the earth is liquid. Since S-waves do not pass through liquids, the liquid core causes a "shadow" on the side of the planet opposite the earthquake where no direct S-waves are observed. In addition, P-waves travel much slower through the outer core than the mantle.

Seismic waves produced by explosions or vibrating controlled sources are one of the primary methods of underground exploration in geophysics (in addition to many different electromagnetic methods such as induced polarization and magnetotellurics). Controlled-source seismology has been used to map salt domes, anticlines and other geologic traps in petroleum-bearing rocks, faults, rock types, and long-buried giant meteor craters. For example, the Chicxulub Crater, which was caused by an impact that has been implicated in the extinction of the dinosaurs, was localized to Central America by analyzing ejecta in the Cretaceous–Paleogene boundary, and then physically proven to exist using seismic maps from oil exploration.[18]

Processing readings from many seismometers using seismic tomography, seismologists have mapped the mantle of the earth to a resolution of several hundred kilometers. This has enabled scientists to identify convection cells and other large-scale features such as the large low-shear-velocity provinces near the core–mantle boundary.[20 -->

<!-- So far, no one has managed to find an ultimate solution

As first described by Claerbout (1985), an information gap be- tween the low and high wavenumbers of the subsurface model is present when dealing with seismic velocity estimation using surface data. Many velocity estimation techniques have been proposed to close this gap and create an ultimate inversion technique that could bridge these low- and high-wavenumber contents. One of the proposed ideas is to combine a MVA approach, heuristically found more robust to initial velocity errors, with a more accurate waveform method, such as FWI, but more prone to fall into non-useful solutions (Symes, 2008). Following this philosophy, many authors have proposed differ- ent methods (Fleury and Perrone, 2012; Biondi and Almomin, 2014; Huang and Symes, 2015; Barnier et al., 2018a).
Barnier et al. (2018a) showed the potential of FWIME at suc- cessfully pairing both techniques into a robust workflow. It relies on an extended Born modeling operator to correct for substantial mismatches between observed and predicted data. By using the variable projection method (Golub and Pereyra, 1973; Rickett, 2013), it handles the coupling between the MVA and the FWI regimes in a consistent and automatic way. In this paper, we combine FWIME with the model-space multi-scale approach described in Barnier et al. (2019), which enables us to control the wavenumber content of the model updates, thereby improving the convergence properties of FWIME.

Note that when the subsurface is made of horizontal layers, a low-resolution model is sufficient to produce accurate results. -->
