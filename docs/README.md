<div align="center">
<h1><p><strong>The first high-speed "Active Vision Bin Picking" in the world </strong></p></h2>
<h2><p><strong>(A Low-Cost, High-Speed, and Robust Bin Picking System for Factory Automation Enabled by a Non-stop, Multi-View, and Active Vision Scheme)</strong></p></h2>
<p><strong>Xingdou Fu*, Lin Miao, Yasuhiro Ohnishi, Yuki Hadegawa, Masaki Suwa</strong></p>
<p><strong>OMRON corporation</strong></p>
</div>
        
<div>
  <small>The 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2024)</small>
</div>
<div>
  <small>*Corresponding author: Xingdou Fu（付 星斗） 
    <a href="mailto:write2fxd@gmail.com">write2fxd@gmail.com</a>
  </small>
</div>

# Webpage of the project
<h4>Check more details(Paper/Video/Poster...) at <a href="https://xingdoufu.github.io/ActiveVisionBinPicking/">https://xingdoufu.github.io/ActiveVisionBinPicking/</a></h4>

# Abstract
Bin picking systems in factory automation usually face robustness issues caused by sparse and noisy 3D data of metallic objects. Utilizing multiple views, especially with a oneshot 3D sensor and “sensor on hand” configuration is getting more popularity due to its effectiveness, flexibility, and low cost. While moving the 3D sensor to acquire multiple views for 3D fusion, joint optimization, or active vision suffers from lowspeed issues. That is because sensing is taken as a decoupled module from motion tasks and is not intentionally designed for a bin picking system. To address the problems, we designed a bin picking system, which tightly couples a multi-view, active vision scheme with motion tasks in a “sensor on hand” configuration. It not only speeds up the system by parallelizing the high-speed sensing scheme to the robot place action but also decides the next sensing path to maintain the continuity of the whole picking process. Unlike others focusing only on sensing evaluation, we also evaluated our design by picking experiments on 5 different types of objects without human intervention. Our experiments show the whole sensing scheme can be finished within 1.682 seconds (maximum) on CPU and the average picking complete rate is over 97.75% . Due to the parallelization with robot motion, the sensing scheme accounts for only 0.635 seconds in takt time on average.

To our best knowledge, our solution differs from any existing ones and is the first try to build a high-speed active vision bin picking system.

# Overview

<div align="center">
        <p><img src="static/images/carousel3.jpg" alt="Conventional approaches versus ours"/></p> 
        <p><img src="static/images/carousel4.jpg" alt=" Our approach"></p> 
        <p><img src="static/images/carousel5.jpg" alt="Experiment device"></p> 
        <p><img src="static/images/carousel6.jpg" alt="Experiment (target objects)"></p> 
</div>

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
