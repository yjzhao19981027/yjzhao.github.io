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

<div class="b-accordion__item panel b-js-accordion-item" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_3_heading">
            <h4 class="b-accordion__title">
                <a title="VPU-Net: A Video-based Point Cloud Upsampling Framework" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button
                        js-analytics-accordian-wide-button js-analytics-accordian-wide
                        collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_3_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_3_panel">
                    VPU-Net: A Video-based Point Cloud Upsampling Framework
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_3_panel" class="collapse " aria-labelledby="uniqueId_NFvw7rQq_3_heading">
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

#### 3D Object Detection

3D object detection is the process of detecting and categorizing objects of interest from 3D point cloud data, as well as estimating the position of their 3D bounding boxes.

<div class="b-accordion__item panel b-js-accordion-item" id="ulxsuokf" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_4_heading">
            <h4 class="b-accordion__title">
                <a title="SRDAN: Scale-aware and Range-aware Domain Adaptation Network for Cross-dataset 3D Object Detection" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button
                        js-analytics-accordian-wide-button js-analytics-accordian-wide
                        collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_4_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_4_panel">
                    SRDAN: Scale-aware and Range-aware Domain Adaptation Network for Cross-dataset 3D Object Detection
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_4_panel" class="collapse " aria-labelledby="uniqueId_NFvw7rQq_4_heading">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule">
                <p><strong>Authors:</strong>&nbsp;
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Weichen Zhang</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Wen Li</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Dong Xu</a>
                    </p>
                    <p><strong>Abstract:</strong>Geometric characteristic plays an important role in the representation of an object in 3D point clouds. For example, large objects often contain more points, while small ones contain fewer points. The point clouds of objects near the capture device are denser, while those of distant objects are sparser. These issues bring new challenges to 3D object detection, especially under the domain adaptation scenarios. In this work, we propose a new cross-dataset 3D object detection method named Scale-aware and Range-aware Domain Adaptation Network (SRDAN). We take advantage of the geometric characteristics of 3D data (i.e., size and distance), and propose the scale-aware domain alignment and the range-aware domain alignment strategies to guide the distribution alignment between two domains. For scale-aware domain alignment, we design a 3D voxel-based feature pyramid network to extract multi-scale semantic voxel features, and align the features and instances with similar scales between two domains. For range-aware domain alignment, we introduce a range-guided domain alignment module to align the features of objects according to their distance to the capture device. Extensive experiments under three different scenarios demonstrate the effectiveness of our SRDAN approach, and comprehensive ablation study also validates the importance of geometric characteristics for cross-dataset 3D object detection. </p>
                    <p><strong>Our Method:</strong></p>
                    <div align="center">
                        <img src="/images/method/method5.png" height="100px">
                    </div>
                    <p><strong>Reference:</strong> W. Zhang*, W. Li and D. Xu, “SRDAN: Scale-aware and Range-aware Domain Adaptation Network for Cross-dataset 3D Object Detection,” CVPR, June 2021.
 </p>
</div>
            </div>
        </div>
    </div>

<div class="b-accordion__item panel b-js-accordion-item" id="hjldio5f" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_5_heading">
            <h4 class="b-accordion__title">
                <a title="Back-tracing Representative Points for Voting-based 3D Object Detection in Point Clouds" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button
                        js-analytics-accordian-wide-button js-analytics-accordian-wide
                        collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_5_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_5_panel">
                    Back-tracing Representative Points for Voting-based 3D Object Detection in Point Clouds
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_5_panel" class="collapse " aria-labelledby="uniqueId_NFvw7rQq_5_heading">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule">
                <p><strong>Authors:</strong>&nbsp;
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Bowen Cheng</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Lu Sheng</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Shaoshuai Shi</a>,
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Ming Yang</a>,
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Dong Xu</a>
                    </p>
                    <p><strong>Abstract:</strong>3D object detection in point clouds is a challenging vision task that benefits various applications for understanding the 3D visual world. Lots of recent research focuses on how to exploit end-to-end trainable Hough voting for generating object proposals. However, the current voting strategy can only receive partial votes from the surfaces of potential objects together with severe outlier votes from the cluttered backgrounds, which hampers full utilization of the information from the input point clouds. Inspired by the back-tracing strategy in the conventional Hough voting methods, in this work, we introduce a new 3D object detection method, named as Back-tracing Representative Points Network (BRNet), which generatively back-traces the representative points from the vote centers and also revisits complementary seed points around these generated points, so as to better capture the fine local structural features surrounding the potential objects from the raw point clouds. Therefore, this bottom-up and then top-down strategy in our BRNet enforces mutual consistency between the predicted vote centers and the raw surface points and thus achieves more reliable and flexible object localization and class prediction results. Our BRNet is simple but effective, which significantly outperforms the state-of-the-art methods on two large-scale point cloud datasets, ScanNet V2 (+7.5% in terms of mAP@0.50) and SUN RGB-D (+4.7% in terms of mAP@0.50), while it is still lightweight and efficient.  </p>
                    <p><strong>Our Method:</strong></p>
                    <div align="center">
                        <img src="/images/method/method6.png" height="100px">
                    </div>
                    <p><strong>Reference:</strong> B. Chen, L. Sheng, M. Yang, S. Shi and D. Xu, “Back-tracing Representative Points for Voting-based 3D Object Detection in Point Clouds,” CVPR, June 2021. 

 </p>
</div>
            </div>
        </div>
    </div>

<div class="b-accordion__item panel b-js-accordion-item" id="uwdba4zj" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQq_6_heading">
            <h4 class="b-accordion__title">
                <a title="Transformer3D-Det: Improving 3D Object Detection by Vote Refinement" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button
                        js-analytics-accordian-wide-button js-analytics-accordian-wide
                        collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQq_6_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQq_6_panel">
                    Transformer3D-Det: Improving 3D Object Detection by Vote Refinement
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_6_panel" class="collapse " aria-labelledby="uniqueId_NFvw7rQq_6_heading">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule">
                <p><strong>Authors:</strong>&nbsp;
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Lichen Zhao</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Jinyang Guo</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Dong Xu</a>,
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Lu Sheng</a>
                    </p>
                    <p><strong>Abstract:</strong>Voting-based methods (e.g., VoteNet) have achieved promising results for 3D object detection. However, the simple voting operation in VoteNet may lead to less accurate voting results that are far away from the true object centers. In this work, we propose a simple but effective 3D object detection method called Transformer3D-Det (T3D), in which we additionally introduce a transformer based vote refinement module to refine the voting results of VoteNet and can thus significantly improve the 3D object detection performance. Specifically, our T3D framework consists of three modules: a vote generation module, a vote refinement module, and a bounding box generation module. Given an input point cloud, we first utilize the vote generation module to generate multiple coarse vote clusters. Then, the clustered coarse votes will be refined by using our transformer based vote refinement module to produce more accurate and meaningful votes. Finally, the bounding box generation module takes the refined vote clusters as the input and generates the final detection result for the input point cloud. To alleviate the impact of inaccurate votes, we also propose a new non-vote loss function to train our T3D. As a result, our T3D framework can achieve better 3D object detection performance. Comprehensive experiments on two benchmark datasets ScanNetV2 and SUN RGB-D demonstrate the effectiveness of our T3D framework for 3D object detection.  </p>
                    <p><strong>Our Method:</strong></p>
                    <div align="center">
                        <img src="/images/method/method7.png" height="100px">
                    </div>
                    <p><strong>Reference:</strong> L. Zhao*, J. Guo*, D. Xu and L. Sheng, “Transformer3D-Det: Improving 3D Object Detection by Vote Refinement,” IEEE T-CSVT, 31(12), pp. 4735-4746, December 2021. 


 </p>
</div>
            </div>
        </div>
    </div>

#### 3D Action Recognition

3D action recognition is the process of identifying various human actions from sequences of 3D point cloud data.

<div class="b-accordion__item panel b-js-accordion-item" id="uwdba4zj" style="background-color: transparent;">
        <div id="uniqueId_NFvw7rQbq_6_heading">
            <h4 class="b-accordion__title">
                <a title="APSNet: Towards Adaptive Point Sampling for Efficient 3D Action Recognition" href="javascript:void(0)" class="b-accordion__link b-accordion__link--size-corporate b-js-accordion-button
                        js-analytics-accordian-wide-button js-analytics-accordian-wide
                        collapsed" role="button" data-toggle="collapse" data-target="#uniqueId_NFvw7rQbq_6_panel" aria-expanded="false" aria-controls="uniqueId_NFvw7rQbq_6_panel">
                    APSNet: Towards Adaptive Point Sampling for Efficient 3D Action Recognition
                </a>
            </h4>
        </div>

        <div id="uniqueId_NFvw7rQq_6_panel" class="collapse " aria-labelledby="uniqueId_NFvw7rQq_6_heading">
            <div class="b-accordion__content b-accordion__content--corporate">
                <div class="content richTextModule">
                <p><strong>Authors:</strong>&nbsp;
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Jiaheng Liu</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Jinyang Guo</a>, 
                        <a href="https://www.sydney.edu.au/engineering/about/our-people/academic-staff/shuaiwen-song.html">Dong Xu</a>
                    </p>
                    <p><strong>Abstract:</strong>Observing that it is still a challenging task to deploy 3D action recognition methods in real-world scenarios, in this work, we investigate the accuracy-efficiency trade-off for 3D action recognition. We first introduce a simple and efficient backbone network structure for 3D action recognition, in which we directly extract the geometry and motion representations from the raw point cloud videos through a set of simple operations ( i.e., coordinate offset generation and mini-PoinNet). Based on the backbone network, we propose an end-to-end optimized network called adaptive point sampling network (APSNet) to achieve the accuracy-efficiency trade-off, which mainly consists of three stages: the coarse feature extraction stage, the decision making stage, and the fine feature extraction stage. In APSNet, we adaptively decide the optimal resolutions ( i.e., the optimal number of points) for each pair of frames based on any input point cloud video under the given computational complexity constraint. Comprehensive experiments on multiple benchmark datasets demonstrate the effectiveness and efficiency of our newly proposed APSNet for 3D action recognition.  </p>
                    <p><strong>Our Method:</strong></p>
                    <div align="center">
                        <img src="/images/method/method8.png" height="100px">
                    </div>
                    <p><strong>Reference:</strong> J. Liu*, J. Guo* and D. Xu, “APSNet: Towards Adaptive Point Sampling for Efficient 3D Action Recognition,” T-IP, 31, pp. 5287-5302, 2022. 



 </p>
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
