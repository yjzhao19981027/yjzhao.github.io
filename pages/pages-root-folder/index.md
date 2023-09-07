---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth:
title: "JC STEM Lab of MediaML @ HKU"

#slider:
#text_color: white
#shadow_color: black
#slides: 
#  - image: gallery-example-1.jpg
#    slide_html:
#  - image: gallery-example-2.jpg
#    slide_html: "<h2>Yes, this carousel supports html texting</h2>"
#  - image: gallery-example-3.jpg
#    slide_html: "<h2>Yes, this carousel supports html texting</h2>"

sidebar: right

# widget1:
#   title: "GradNet ICCV2019 Demo"
#   url: 'https://youtu.be/tWDbs3VrnbU'
#   video: '<iframe width="360" height="240" src="https://www.youtube.com/embed/tWDbs3VrnbU" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width: 100%; max-height: 150pt;"></iframe>'
#   text: 'Check out our demo for Visual Object Tracking'
# widget2:
#   title: "Video Tracking"
#   url: 'https://www.youtube.com/watch?v=M1LqUV4jLbM'
#   text: 'Implementation of MDNet, KCF and SiamFC.'
#   video: '<iframe src="https://www.youtube.com/embed/M1LqUV4jLbM" width="360" height="240" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width: 100%; max-height: 150pt;"></iframe>'
# widget3:
#   title: "Pose Tracking"
#   url: 'https://youtu.be/CiKJuAH2U8I'
#   video: '<iframe src="https://www.youtube.com/embed/AL-8XCzRFo0" width="360" height="240" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="max-width: 100%; max-height: 150pt;"></iframe>'
#   text: 'Our team won the 2nd place in the pose-track challenge.'

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

## Introduction

TBD

## Our Aim

Research on humanoid visual perception algorithms and technologies for service robots.

## Our Research

Professor Dong Xu's team at the University of Hong Kong will conduct research in the field of point cloud processing and analysis. Specifically, they will focus on one or more of the following research directions:

#### Point Cloud Compression

Efficient and high-quality compression techniques are developed for point cloud data, significantly reducing storage and bandwidth costs. This includes Geometry-based Point Cloud Compression (G-PCC) and Video-based Point Cloud Compression (V-PCC), which are specifically designed for compressing point cloud data.


<div class="b-accordion__item panel b-js-accordion-item" id="sqmr030u" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_0_heading">
            <h4 class="b-accordion__title">
                <a title="VoxelContext-Net: An Octree based Framework for Point Cloud Compression" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button                         
                  js-analytics-accordian-wide-button js-analytics-accordian-wide collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_0_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_0_panel">
                    VoxelContext-Net: An Octree based Framework for Point Cloud Compression
                </a>
            </h4>
        </div>
        
        <div id="uniqueId_NFvw7rQq_0_panel" class="collapse" aria-labelledby="uniqueId_NFvw7rQq_0_heading" aria-expanded="false" style="height: 0px;">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule">
                <p><strong>Authors:</strong>&nbsp;
                    <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Zizheng Que</a>, 
                    <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Lu Guo</a>, 
                    <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Dong Xu</a>
                </p>
                <p><strong>Abstract:</strong>In this paper, we propose a two-stage deep learning framework called VoxelContext-Net for both static and dynamic point cloud compression. Taking advantages of both octree based methods and voxel based schemes, our approach employs the voxel context to compress the octree structured data. Specifically, we first extract the local voxel representation that encodes the spatial neighbouring context information for each node in the constructed octree. Then, in the entropy coding stage, we propose a voxel context based deep entropy model to compress the symbols of non-leaf nodes in a lossless way. Furthermore, for dynamic point cloud compression, we additionally introduce the local voxel representations from the temporal neighbouring point clouds to exploit temporal dependency. More importantly, to alleviate the distortion from the octree construction procedure, we propose a voxel context based 3D coordinate refinement method to produce more accurate reconstructed point cloud at the decoder side, which is applicable to both static and dynamic point cloud compression. The comprehensive experiments on both static and dynamic point cloud benchmark datasets(e.g., ScanNet and Semantic KITTI) clearly demonstrate the effectiveness of our newly proposed method VoxelContext-Net for 3D point cloud geometry compression. </p>
                <p><strong>Our Method:</strong></p>
                <div align="center">
                    <img src="/images/method/method1.png" height="100px">
                    <img src="/images/method/method2.png" height="100px">
                </div>
                <p><strong>Reference:</strong> Z. Que*, G. Lu and D. Xu, “VoxelContext-Net: An Octree based Framework for Point Cloud Compression,” CVPR 2021</p>

</div>
            </div>
        </div>
    </div>

#### Point Cloud Upsampling

Generate denser point clouds from sparse point clouds, including static point cloud upsampling and video-based point cloud upsampling.

<div class="b-accordion__item panel b-js-accordion-item" id="rh223j2g" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_1_heading">
            <h4 class="b-accordion__title">
                <a title="Sequential Point Cloud Upsampling by Exploiting Multi-scale Temporal Dependency" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button                         js-analytics-accordian-wide-button js-analytics-accordian-wide collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_1_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_1_panel">
                    Sequential Point Cloud Upsampling by Exploiting Multi-scale Temporal Dependency
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_1_panel" class="collapse" aria-labelledby="uniqueId_NFvw7rQq_1_heading" aria-expanded="false" style="height: 0px;">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule">
                <p><strong>Authors:</strong>&nbsp;
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Kaisiyuan Wang</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Lu Sheng</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Shuhang Gu</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Dong Xu</a>
                    </p>
                    <p><strong>Abstract:</strong>In this work, we propose a new sequential point cloud upsampling method called SPU, which aims to upsample sparse, non-uniform, and orderless point cloud sequences by effectively exploiting rich and complementary temporal dependency from multiple inputs. Specifically, these inputs include a set of multi-scale short-term features from the 3D points in three consecutive frames (i.e., the previous/current/subsequent frame) and a long-term latent representation accumulated throughout the point cloud sequence. Considering that these temporal clues are not well aligned in the coordinate space, we propose a new temporal alignment module (TAM) based on the cross-attention mechanism to transform each individual feature into the feature space of the current frame. We also propose a new gating mechanism to learn the optimal weights for these transformed features, based on which the transformed features can be effectively aggregated as the final fused feature. The fused feature can be readily fed into the existing single frame-based point cloud upsampling methods (e.g., PU-Net, MPU and PU-GAN) to generate the dense point cloud for the current frame. Comprehensive experiments on three benchmark datasets DYNA, COMA, and MSR Action3D demonstrate the effectiveness of our method for upsampling point cloud sequences. </p>
                    <p><strong>Our Method:</strong></p>
                    <div align="center">
                        <img src="/images/method/method3.png" height="100px">
                    </div>
                    <p><strong>Reference:</strong> K. Wang*, L. Sheng, S. Gu and D. Xu, “Sequential Point Cloud Upsampling by Exploiting Multi-scale Temporal Dependency,” IEEE T-CSVT, 31(12), pp. 4686-4696, December 2021.</p>
</div>
            </div>
        </div>
    </div>



#### 3D Object Detection

3D object detection is the process of detecting and categorizing objects of interest from 3D point cloud data, as well as estimating the position of their 3D bounding boxes.

<div class="b-accordion__item panel b-js-accordion-item" id="59ok6c07" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_0_heading">
            <h4 class="b-accordion__title">
                <a title="VPU-Net: A Video-based Point Cloud Upsampling Framework" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button                         
                  js-analytics-accordian-wide-button js-analytics-accordian-wide collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_0_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_0_panel">
                    VPU-Net: A Video-based Point Cloud Upsampling Framework
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_0_panel" class="collapse" aria-labelledby="uniqueId_NFvw7rQq_0_heading" aria-expanded="false" style="height: 0px;">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule">
                <p><strong>Authors:</strong>&nbsp;
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Kaisiyuan Wang</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Lu Sheng</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Shuhang Gu</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Dong Xu</a>
                    </p>
                    <p><strong>Abstract:</strong>In this work, we propose a new patch-based framework called VPU for the video-based point cloud upsampling task by effectively exploiting temporal dependency among multiple consecutive point cloud frames, in which each frame consists of a set of unordered, sparse and irregular 3D points. Rather than adopting the sophisticated motion estimation strategy in video analysis, we propose a new spatio-temporal aggregation (STA) module to effectively extract , align and aggregate rich local geometric clues from consecutive frames at the feature level. By more reliably summarizing spatio-temporally consistent and complementary knowledge from multiple frames in the resultant local structural features, our method better infers the local geometry distributions at the current frame. In addition, our STA module can be readily incorporated with various existing single frame-based point upsampling methods ( e.g. , PU-Net, MPU, PU-GAN and PU-GCN). Comprehensive experiments on multiple point cloud sequence datasets demonstrate our video-based point cloud upsampling framework achieves substantial performance improvement over its single frame-based counterparts. </p>
                    <p><strong>Our Method:</strong></p>
                    <div align="center">
                        <img src="/images/method/method4.png" height="100px">
                    </div>
                    <p><strong>Reference:</strong> K. Wang*, L. Sheng, S. Gu and D. Xu, “VPU-Net: A Video-based Point Cloud Upsampling Framework,” IEEE T-IP, 31, pp. 4062-4075, 2022. </p>
</div>
            </div>
        </div>
    </div>

#### 3D Action Recognition

3D action recognition is the process of identifying various human actions from sequences of 3D point cloud data.

<div class="b-accordion__item panel b-js-accordion-item" id="sqmr030u" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_0_heading">
            <h4 class="b-accordion__title">
                <a title="3D Action Recognition" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button                         
                  js-analytics-accordian-wide-button js-analytics-accordian-wide collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_0_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_0_panel">
                    3D Action Recognition
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_0_panel" class="collapse" aria-labelledby="uniqueId_NFvw7rQq_0_heading" aria-expanded="false" style="height: 0px;">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule"><p><strong>Our expert:</strong>&nbsp;Dr <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Shuaiwen Song</a></p>
<p><strong>Our partner:</strong>&nbsp;Google Brain, Microsoft, Alibaba Research, Facebook Reality Lab, University of Washington.</p>
<p>We are tackling the essential performance problems for both extreme large-scale and small-scale models on a diverse range of hardware platforms. </p>
<p>Along with our international collaborators, we aim to explore principles and key technologies of multi-scale multi-dimensional machine learning inference system optimisation through cross-stack co-design (compiler, runtime and hardware accelerators). </p>
<p>The scope of our MLSys research includes but not limited to ML compiler design and optimisations, software-hardware co-design, runtime optimisation techniques, and customised acceleration for novel deep learning models.</p>
<p><strong>Funding agency:</strong> Google Brain, Alibaba Global Faculty Award (AIR), Facebook Fair Faculty Award, USYD SOAR fellowship.</p>
</div>
            </div>
        </div>
    </div>

#### Model Compression

Model compression refers to the process of reducing the size and complexity of a pre-trained deep learning model to obtain a lightweight network with comparable accuracy. The compressed network has a smaller structure and fewer parameters, which effectively reduces computational and storage costs. This makes it easier to deploy the network in hardware-constrained environments.

<div class="b-accordion__item panel b-js-accordion-item" id="sqmr030u" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_0_heading">
            <h4 class="b-accordion__title">
                <a title="Model Compression" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button                         
                  js-analytics-accordian-wide-button js-analytics-accordian-wide collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_0_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_0_panel">
                    Model Compression
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_0_panel" class="collapse" aria-labelledby="uniqueId_NFvw7rQq_0_heading" aria-expanded="false" style="height: 0px;">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule"><p><strong>Our expert:</strong>&nbsp;Dr <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Shuaiwen Song</a></p>
<p><strong>Our partner:</strong>&nbsp;Google Brain, Microsoft, Alibaba Research, Facebook Reality Lab, University of Washington.</p>
<p>We are tackling the essential performance problems for both extreme large-scale and small-scale models on a diverse range of hardware platforms. </p>
<p>Along with our international collaborators, we aim to explore principles and key technologies of multi-scale multi-dimensional machine learning inference system optimisation through cross-stack co-design (compiler, runtime and hardware accelerators). </p>
<p>The scope of our MLSys research includes but not limited to ML compiler design and optimisations, software-hardware co-design, runtime optimisation techniques, and customised acceleration for novel deep learning models.</p>
<p><strong>Funding agency:</strong> Google Brain, Alibaba Global Faculty Award (AIR), Facebook Fair Faculty Award, USYD SOAR fellowship.</p>
</div>
            </div>
        </div>
    </div>

#### 3D Visual Grounding

The task of 3D visual grounding aims to address the following problem: determining the specific target object, including its category and the location of its 3D bounding box, through explicit and unambiguous language descriptions.

<div class="b-accordion__item panel b-js-accordion-item" id="sqmr030u" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_0_heading">
            <h4 class="b-accordion__title">
                <a title="3D Visual Grounding" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button                         
                  js-analytics-accordian-wide-button js-analytics-accordian-wide collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_0_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_0_panel">
                    3D Visual Grounding
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_0_panel" class="collapse" aria-labelledby="uniqueId_NFvw7rQq_0_heading" aria-expanded="false" style="height: 0px;">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule"><p><strong>Our expert:</strong>&nbsp;Dr <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Shuaiwen Song</a></p>
<p><strong>Our partner:</strong>&nbsp;Google Brain, Microsoft, Alibaba Research, Facebook Reality Lab, University of Washington.</p>
<p>We are tackling the essential performance problems for both extreme large-scale and small-scale models on a diverse range of hardware platforms. </p>
<p>Along with our international collaborators, we aim to explore principles and key technologies of multi-scale multi-dimensional machine learning inference system optimisation through cross-stack co-design (compiler, runtime and hardware accelerators). </p>
<p>The scope of our MLSys research includes but not limited to ML compiler design and optimisations, software-hardware co-design, runtime optimisation techniques, and customised acceleration for novel deep learning models.</p>
<p><strong>Funding agency:</strong> Google Brain, Alibaba Global Faculty Award (AIR), Facebook Fair Faculty Award, USYD SOAR fellowship.</p>
</div>
            </div>
        </div>
    </div>
