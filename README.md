# Paper List of Interactive Labeling Algorithm

Interactive Labeling Algorithm is a very interesting research field, which aims to help annotate large-scale datasets with less effort for computer vision community. The annotator iteratively provides corrective annotations for the current machine annotations.

This is a collection of research papers of Interactive Labeling Algorithm. The papers are sorted by time. Any suggestions and pull requests are welcome.

The sharing principle of these references here is for research. If any authors do not want their paper to be listed here, please feel free to contact Kaiwen Zha (Email: kaiwenzha [AT] gmail.com).

## Overview

  - [Popular Annotation Tools](#popular-annotation-tools)
  - [Interactive Segmentation Algorithms](#interactive-segmentation-algorithms)
    - [Optimization Methods](#optimization-methods)
    - [Geodesic Methods](#geodesic-methods)
    - [FCN-Based Semantic Segmentation Methods](#fcn-based-semantic-segmentation-methods)
    - [Vertex Prediction Methods](#vertex-prediction-methods)
    - [Full Image Segmentation Methods](#full-image-segmentation-methods)
    - [Others](#others)
  - [Interactive Bounding-box Labeling Algorithms](#interactive-bounding-box-labeling-algorithms)
  - [Interactive Active Learning via Relative Attributes](#interactive-active-learning-via-relative-attributes)
  - [Other Interesting Explorations](#other-interesting-explorations)

## Popular Annotation Tools

- [LabelMe: a database and web-based tool for image annotation](https://people.csail.mit.edu/brussell/research/AIM-2005-025-new.pdf) by Russell et al. IJCV 2008
- [Efficiently Scaling Up Crowdsourced Video Annotation](http://101.96.10.64/www.cs.columbia.edu/~vondrick/vatic/ijcv.pdf) by Vondrick et al. IJCV 2012
- [Microsoft COCO: Common Objects in Context](https://arxiv.org/pdf/1405.0312.pdf) by Lin et al. ECCV 2014
- [BDD100K: A Diverse Driving Video Database with Scalable Annotation Tooling](https://arxiv.org/pdf/1805.04687.pdf) by Yu et al. arXiv 2018

## Interactive Segmentation Algorithms

### Optimization Methods

- [Interactive graph cuts for optimal boundary and region segmentation of objects in N-D images](http://www.csd.uwo.ca/~yuri/Papers/iccv01.pdf) by Boykov et al. ICCV 2001
- [Grabcut: Interactive foreground extraction using iterated graph cuts](https://cvg.ethz.ch/teaching/cvl/2012/grabcut-siggraph04.pdf) by Rother et al. SIGGRAPH 2004
- [Densecut: Densely connected crfs for realtime grabcut](http://mftp.mmcheng.net/Papers/DenseCut.pdf) by Cheng et al. CGF 2015
- [Deep extreme cut: From extreme points to object segmentation](https://arxiv.org/abs/1711.09081) by Maninis et al. CVPR 2018

### Geodesic Methods

- [Geodesic matting: A framework for fast interactive image and video segmentation and matting](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.695.658&rep=rep1&type=pdf) by Bai et al. IJCV 2009
- [Geodesic image and video editing](http://wwwpub.zih.tu-dresden.de/~cvweb/publications/papers/2011/ACriminisi_ACM_TOG2010.pdf) by Criminisi et al. TOG 2010
- [Geodesic star convexity for interactive image segmentation](http://www.robots.ox.ac.uk/~vgg/publications/papers/gulshan10.pdf) by Gulshan et al. CVPR 2010

### FCN-Based Semantic Segmentation Methods

- [Deep interactive object selection](https://arxiv.org/abs/1603.04042) by Xu et al. CVPR 2016
- [Regional interactive image segmentation networks](https://ieeexplore.ieee.org/document/8237559/) by Liew et al. ICCV 2017
- [Interactive boundary prediction for object selection](http://openaccess.thecvf.com/content_ECCV_2018/papers/Hoang_Le_Interactive_Boundary_Prediction_ECCV_2018_paper.pdf) by Le et al. ECCV 2018
- [Interactive image segmentation with latent diversity](https://cqf.io/papers/Interactive_Image_Segmentation_CVPR2018.pdf) by Li et al. CVPR 2018
- [Iteratively trained interactive segmentation](https://arxiv.org/abs/1805.04398) by Mahadevan et al. BMVC 2018
- [A fully convolutional two-stream fusion network for interactive image segmentation](https://arxiv.org/abs/1807.02480) by Hu et al. Neural Networks 2019

### Vertex Prediction Methods

- [Annotating Object Instances with a Polygon-RNN](https://arxiv.org/abs/1704.05548) by Castrejon et al. CVPR 2017
- [Efficient Interactive Annotation of Segmentation Datasets with Polygon-RNN++](https://arxiv.org/abs/1803.09693) by Acuna et al. CVPR 2018

### Full Image Segmentation Methods

- [Fluid Annotation: A Human-Machine Collaboration Interface for Full Image Annotation](https://arxiv.org/abs/1806.07527) by Andriluka et al. ACM MM 2018
- [Interactive Full Image Segmentation](https://arxiv.org/abs/1812.01888) by Agustsson et al. arXiv 2018

### Others

- [Random walks for image segmentation](http://vision.cse.psu.edu/people/chenpingY/paper/grady2006random.pdf) by Grady et al. TPAMI 2006
- [Predicting sufficient annotation strength for interactive foreground segmentation](http://www.cs.utexas.edu/~grauman/papers/suyog-jain-iccv2013.pdf) by Jain et al. ICCV 2013
- [Video segmentation with just a few strokes](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Nagaraja_Video_Segmentation_With_ICCV_2015_paper.pdf) by Nagaraja et al. ICCV 2015

## Interactive Bounding-box Labeling Algorithms

- [Training object class detectors from eye tracking data](http://calvin.inf.ed.ac.uk/wp-content/uploads/Publications/papadopouloseccv14.pdf) by Papadopoulos et al. ECCV 2014
- [We don’t need no bounding-boxes: Training object class detectors using only human verification](https://arxiv.org/abs/1602.08405) by Papadopoulos et al. CVPR 2016
- [Extreme clicking for efficient object annotation](https://arxiv.org/abs/1708.02750) by Papadopoulos et al. ICCV 2017
- [Training object class detectors with click supervision](https://arxiv.org/abs/1704.06189) by Papadopoulos et al. CVPR 2017
- [Learning intelligent dialogs for bounding box annotation](https://arxiv.org/abs/1712.08087) by Konyushkova et al. CVPR 2018

## Interactive Active Learning via Relative Attributes

- [Visual recognition with humans in the loop](https://vision.cornell.edu/se3/wp-content/uploads/2014/09/Visipedia20q.pdf) by Branson et al. ECCV 2010
- [Relative attributes](https://www.cc.gatech.edu/~parikh/relative.html) by Parikh et al. ICCV 2011
- [Attributes for classifier feedback](https://www.cc.gatech.edu/~parikh/Publications/ParkashParikh_ECCV_2012_attributes_feedback.pdf) by Parkash et al. ECCV 2012
- [Simultaneous active learning of classifiers & attributes via relative feedback](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Biswas_Simultaneous_Active_Learning_2013_CVPR_paper.pdf) by Biswas et al. CVPR 2013
- [Similarity comparisons for interactive finegrained categorization](https://ttic.uchicago.edu/~smaji/papers/similarity-cvpr14.pdf) by Wah et al. CVPR 2014

## Other Interesting Explorations

- [What’s it going to cost you?: Predicting effort vs. informativeness for multilabel image annotations](http://www.cs.utexas.edu/~grauman/papers/vijayanarasimhan_cvpr2009.pdf) by Vijayanarasimhan et al. CVPR 2009
- [Active annotation translation](https://ieeexplore.ieee.org/document/6909868/) by Branson et al. CVPR 2014
- [Best of both worlds: human-machine collaboration for object annotation](http://ai.stanford.edu/~olga/papers/RussakovskyCVPR15.pdf) by Russakovsky et al. CVPR 2015
- [Guide me: Interacting with deep networks](https://arxiv.org/abs/1803.11544) by Rupprecht et al. CVPR 2018

