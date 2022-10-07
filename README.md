# Awesome Object SLAM
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Object SLAM papers and resources

This repo is mainitained by [Ziqi Lu](https://github.com/520xyxyzq) and [Akash Sharma](https://github.com/akashsharma02).

You are very welcome to contribute to this repo. Please feel free to [submit](https://github.com/520xyxyzq/awesome-object-SLAM/pulls) a PR or contact the maintainers.

## Table of Contents

## Papers

[TODO] Is it better to list them in the order of category->year->paper? But still not sure what's the best way to categorize them... (object representation? sensors?) Or maybe there is a smarter way to label papers with different categories (like a paper can be RGB + using Quadrics + ...)?

[TODO] I think we need a more explicit decision boundary for what can be considered as object SLAM. Object SLAM, loosely speaking, is _the process of building a 3D object-level global environment map from local object-centric observations_. But there are some grey areas like multi-object tracking (3D) or object-centric multi-view stereo. Also does semantic mapping count, or we have to jointly optimize camera and object states? I personally don't want this list to be super long. It's going to be difficult to maintain and won't be very helpful.

[NOTE] Format for now: All-caps title, after which we add PDF/Code/Video/ProjPage. (No Video if ProjPage exists) In each year, papers are sorted in alphabetic order. For non-opensource papers (like ICRA), I was using non-offical links (like ArXiv).

### Object representation

#### Parametric representation (Sparse)

#### 2022

- SO-SLAM: Semantic Object SLAM with Scale Proportional and Symmetrical Texture Constraints. [\[PDF\]](https://arxiv.org/pdf/2109.04884.pdf) [\[Code\]](https://github.com/XunshanMan/SoSLAM)
- Symmetry and Uncertainty-Aware Object SLAM for 6DoF Object Pose Estimation. [\[PDF\]](https://openaccess.thecvf.com/content/CVPR2022/papers/Merrill_Symmetry_and_Uncertainty-Aware_Object_SLAM_for_6DoF_Object_Pose_Estimation_CVPR_2022_paper.pdf) [\[Code\]](https://github.com/rpng/suo_slam)

#### 2020

- EAO-SLAM: Monocular Semi-Dense Object SLAM Based on Ensemble Data Association. [\[PDF\]](https://arxiv.org/pdf/2004.12730.pdf) [\[Code\]](https://github.com/yanmin-wu/EAO-SLAM) [\[Project Page\]](https://yanmin-wu.github.io/project/eaoslam/)
- OrcVIO: Object Residual Constrained Visual-Inertial Odometry.  [\[PDF\]](https://arxiv.org/pdf/2007.15107.pdf) [\[Code\]](https://github.com/shanmo/OrcVIO-Stereo-Mapping) [\[Project Page\]](https://moshan.cf/orcvio_githubpage/)

#### 2019

- CubeSLAM: Monocular 3D Object SLAM. [\[PDF\]](https://arxiv.org/pdf/1806.00557.pdf) [\[Code\]](https://github.com/shichaoy/cube_slam) [\[Video\]](https://www.youtube.com/watch?v=QnVlexXi9_c&ab_channel=ShichaoYang)
- QuadricSLAM: Dual Quadrics from Object Detections as Landmarks in Object-Oriented SLAM. [\[PDF\]](https://natanaso.github.io/rcw-icra18/assets/ref/ICRA-MRP18_paper_14.pdf) [\[Code\]](https://github.com/qcr/quadricslam) [\[Video\]](https://www.youtube.com/watch?v=n-j0DFDFSKU&ab_channel=LachlanNicholson)
- Robust Object-based SLAM for High-Speed Autonomous Navigation. [\[PDF\]](https://groups.csail.mit.edu/rrg/papers/OkLiu19icra.pdf)

#### 2013
- SLAM++: Simultaneous Localisation and Mapping at the Level of Objects. [\[PDF\]](https://www.doc.ic.ac.uk/~ajd/Publications/salas-moreno_etal_cvpr2013.pdf) [\[Video\]](https://www.youtube.com/watch?v=tmrAh1CqCRo&ab_channel=imperialrobotvision)

#### Field representation (Dense 3D Grids)

#### 2022

- Learning to Complete Object Shapes for Object-level Mapping in Dynamic Scenes. [\[PDF\]](https://arxiv.org/pdf/2208.05067.pdf) [\[Project Page\]](https://mlr.in.tum.de/research/projects/cosom)

#### 2021

- Compositional and Scalable Object SLAM. [\[PDF\]](https://akashsharma02.github.io/assets/pdf/Sharma21icra.pdf) [\[Code\]](https://github.com/rpl-cmu/object-slam)
- DSP-SLAM: Object Oriented SLAM with Deep Shape Priors. [\[PDF\]](https://arxiv.org/abs/2108.09481) [\[Code\]](https://github.com/JingwenWang95/DSP-SLAM) [\[Project Page\]](https://jingwenwang95.github.io/dsp-slam/)

#### 2020

- NodeSLAM: Neural Object Descriptors for Multi-View Shape Reconstruction. [\[PDF\]](https://arxiv.org/pdf/2004.04485.pdf) [\[Project Page\]](https://edgarsucar.github.io/NodeSLAM/)

#### 2019

- Deep-SLAM++: Object-level RGBD SLAM based on class-specific deep shape priors. [\[PDF\]](https://arxiv.org/pdf/1907.09691.pdf)

#### 2018

- Fusion++: Volumetric Object-Level SLAM. [\[PDF\]](https://arxiv.org/pdf/1808.08378.pdf) [\[Video\]](https://www.youtube.com/watch?v=2luKNC03x4k)
- MaskFusion: Real-Time Recognition, Tracking and Reconstruction of Multiple Moving Objects. [\[PDF\]](https://arxiv.org/pdf/1804.09194.pdf) [\[Code\]](https://github.com/martinruenz/maskfusion) [\[Project Page\]](http://visual.cs.ucl.ac.uk/pubs/maskfusion/index.html)

### Inference methods for Object SLAM
#### 2021

- Consensus-Informed Optimization Over Mixtures for Ambiguity-Aware Object SLAM. [\[PDF\]](https://arxiv.org/pdf/2107.09265.pdf) [\[Video\]](https://www.youtube.com/watch?v=506VSt0tq4o&ab_channel=MITMarineRoboticsGroup)

#### 2020

- Probabilistic Data Association via Mixture Models for Robust Semantic SLAM. [\[PDF\]](https://arxiv.org/pdf/1909.11213.pdf) [\[Video\]](https://www.youtube.com/watch?v=Eq_w8zOXCF4&ab_channel=MITMarineRoboticsGroup)

#### 2019

- Multimodal Semantic SLAM with Probabilistic Data Association. [\[PDF\]](https://www.researchgate.net/profile/Kevin-Doherty-14/publication/335142963_Multimodal_Semantic_SLAM_with_Probabilistic_Data_Association/links/607cdef3881fa114b411050e/Multimodal-Semantic-SLAM-with-Probabilistic-Data-Association.pdf) [\[Video\]](https://www.youtube.com/watch?v=9hEonD8KDrs&ab_channel=MITMarineRoboticsGroup)

#### 2018

- A Unifying View of Geometry, Semantics, and Data Association in SLAM. [\[PDF\]](https://existentialrobotics.org/ref/Atanasov_SemanticSLAM_IJCAI18.pdf) [\[Video\]](https://existentialrobotics.org/vid/Bowman_SemanticSLAM_ICRA17.mp4#t=145)


#### 2017

- Probabilistic Data Association for Semantic SLAM. [\[PDF\]](https://www.cis.upenn.edu/~kostas/mypub.dir/bowman17icra.pdf)

----------------------

## Resources

- Add Datasets here

