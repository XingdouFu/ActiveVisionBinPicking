# The web pages of active vision bin picking project
Check details at https://xingdoufu.github.io/ActiveVisionBinPicking/

# Title
The first high-speed "Active Vision Bin Picking" in the world
(A Low-Cost, High-Speed, and Robust Bin Picking System for Factory Automation Enabled by a Non-stop, Multi-View, and Active Vision Scheme)
# Authors
Xingdou Fu*, Lin Miao Yasuhiro Ohnishi Yuki Hasegawa Masaki Suwa
# Abstract
Bin picking systems in factory automation usually face robustness issues caused by sparse and noisy 3D data of metallic objects. Utilizing multiple views, especially with a oneshot 3D sensor and “sensor on hand” configuration is getting more popularity due to its effectiveness, flexibility, and low cost. While moving the 3D sensor to acquire multiple views for 3D fusion, joint optimization, or active vision suffers from lowspeed issues. That is because sensing is taken as a decoupled module from motion tasks and is not intentionally designed for a bin picking system. To address the problems, we designed a bin picking system, which tightly couples a multi-view, active vision scheme with motion tasks in a “sensor on hand” configuration. It not only speeds up the system by parallelizing the high-speed sensing scheme to the robot place action but also decides the next sensing path to maintain the continuity of the whole picking process. Unlike others focusing only on sensing evaluation, we also evaluated our design by picking experiments on 5 different types of objects without human intervention. Our experiments show the whole sensing scheme can be finished within 1.682 seconds (maximum) on CPU and the average picking complete rate is over 97.75% . Due to the parallelization with robot motion, the sensing scheme accounts for only 0.635 seconds in takt time on average.

To our best knowledge, our solution differs from any existing ones and is the first try to build a high-speed active vision bin picking system.


## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
