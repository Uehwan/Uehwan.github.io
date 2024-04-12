---
layout: post
title:  Research Statement
date:   2024-04-12
description: Robot AI and Human-robot-interaction
---

We design and build autonomous robot systems that process various types of sensor data **to realize meaningful services for humans**. With an unprecedented scale of available data and computational resources, robotics systems could better understand the surrounding environments and improve user experience in human-robot interaction (HRI) scenarios. In various domains, our research aims to design robotics systems that 1) extract both semantic and physical information from sensor data for understanding the surrounding environments (perception), 2) safely reach the goal point in unstructured environments (navigation) and 3) elicit user behavior, intention or message from sensor data for promoting natural HRI experiences. Our research attempts to take a step toward the long-dreamed goal of replacing repetitive and dangerous tasks with robotics systems and natural interaction between human and robotics systems.

Specifically, our research has focused on making robotics systems for three crucial components of **robot-in-the-loop research scenarios**:

- multi-modal perception and navigation
- service robots
- intelligent interaction design

First of all, robotics systems must be able to perceive the semantic entities inherent in the environments as well as the geometry of the environments in order to perform high-level tasks such as errands, cleaning, cooking, and answering questions in addition to navigation. If the systems collect just one type of information among the physical information and semantics of the surrounding environment, they can merely perform simple tasks and cannot provide meaningful services to humans.

Next, versatile manipulation, and recognition of human behavior, intention or message are the very starting point of providing appropriate services to humans. Failing to equip the systems with these capabilities results in irrelevant services---leading to user dissatisfaction. Robootics systems gather information regarding the environment or human through various sensor devices; computationally process the information; detect human behavior, intention, or message; and perform manipulation to realize services.

Further, the natural interaction between humans and robots is becoming more and more important as service robots have started to get deployed in our daily lives. Without natural interaction, robotics systems cannot maximize user satisfaction---missing the very goal of service robots. Natural HRI requires the investigation of human expectation and the reaction of humans, and the process of appropriate designs for intelligent interaction systems in robot-in-the-loop scenarios.

---

## Multi-modal perception and navigation
### SimVODIS: Simultaneous Visual Odometry, Object Detection and Instance Segmentation<sup>[1]</sup>
<table class="demo_tb" style="width:45%; float: left; margin: 5px 15px 0px 0px;">
<tr>
<td style="text-align: center">
<img src="/assets/img/demo_simvodis.png" alt="SimVODIS Overview" style="width:100%;">
</td>
</tr>

<tr>
<td width="45%">
Figure 1. Overview of the proposed SimVODIS. SimVODIS receives a set of three consecutive images and then estimates semantics (object classes, bounding boxes and object masks), relative poses between input images, and the depth map of the center image.
</td>
</tr>
</table>

<strong>[Research Goal]</strong> Design a computationally-efficient network architecture to recognize both semantic and geometric information of the surrounding environments. <br/>
<strong>[Limitations of Convention]</strong> Conventional approaches combine two techniques to associate geometric and semantic information elicited from the surrounding environments. However, running both algorithms simultaneously requires a lot of computation resources and complicates the software structure. <br/>
<strong>[Contribution]</strong> First, we defined a fully data-driven semantic VO algorithm, SimVODIS, for the first time. We expect SimVODIS would provoke the evolution of data-driven VO towards semantic VO/SLAM. Second, we designed the SimVODIS network which simultaneously performs both geometric and semantic tasks. The network conducts multiple tasks utilizing shared feature maps and runs in one thread. Third, we made the source code of the proposed SimVODIS network and the pretrained network parameters open-source.

### 3-D Scene Graph: A Sparse and Semantic Representation of Physical Environments for Intelligent Agents<sup>[2]</sup>
<table class="demo_tb" style="width:50%; float: left; margin: 5px 15px 0px 0px;">
<tr>
<td style="text-align: center">
<iframe style="width:100%; height:300px;"
src="https://www.youtube.com/embed/GXNQAMYU-yQ">
</iframe>
</td>
</tr>
</table>

<strong>[Research Goal]</strong> Design an accurate, applicable, usable and scalable environment model for intelligent agents to store observed and perceived environmental information. <br/>
<strong>[Limitations of Convention]</strong> Raw and dense representations representing environments with minimum distortion require massive memory space, take much time for processing and lack any semantic information. Moreover, the coverage of abstractive and descriptive representations is confined to the field of view (FoV) of the cameras and the output is in the form of natural language, which makes it difficult for other AI applications to utilize. <br/>
<strong>[Contribution]</strong> First, we defined the concept of the 3-D scene graph which represents the environments in an accurate, applicable, usable, and scalable way. Second, we designed the 3-D scene graph construction framework which generates 3-D scene graphs for environments upon receiving a sequence of observations. Third, we provided two application examples of the 3-D scene graph: a) VQA and b) task planning. Fourth, we made the source code of the algorithms open-source.

### Dual Task Learning by Leveraging Both Dense Correspondence and Mis-Correspondence for Robust Change Detection With Imperfect Matches<sup>[3]</sup>
<table class="demo_tb" style="width:45%; float: left; margin: 5px 15px 0px 0px;">
<tr>
<td style="text-align: center">
<img src="/assets/img/demo_simsac.gif" alt="SimSaC Demo" style="width:100%;">
</td>
</tr>

<tr>
<td width="45%">
Figure 2. The proposed SimSaC displays robust performance even given imperfect matches of reference and query images with which conventional methods fail.
</td>
</tr>
</table>

<strong>[Research Goal]</strong> Design a robust scene change detection algorithm given imperfect mathches which are more plausible in the real-world scenarios. <br/>
<strong>[Limitations of Convention]</strong> Contemporary approaches for SCD, however, assumes an ideal match of the scene between the current and
the past time steps although observing the same scene with a perfect match hardly occurs in real-world applications. Thus, contemporary approaches would not display the reported performance when deployed to practical systems. <br/>
<strong>[Contribution]</strong> First, we carefully formulated a change detection task that reflects performance in realworld settings for the first time. Second, we proposed the SimSaC network for robust change detection which leverages both dense correspondence (scene flow) and miscorrespondence (change). Third, we designed a training scheme that enhances the robustness of change detection without requiring additional annotations. Fourth, we collected a new benchmark dataset consisting of imperfect matches for measuring change detection performance in real-world scenarios. Fifth, we made the source code of the algorithms open-source.

---

## Service robots
### A Stabilized Feedback Episodic Memory (SF-EM) and Home Service Provision Framework for Robot and IoT Collaboration<sup>[4]<sup>
<table class="demo_tb" style="width:50%; float: left; margin: 5px 15px 0px 0px;">
<tr>
<td style="text-align: center">
<iframe style="width:100%; height:300px;"
src="https://www.youtube.com/embed/7ES-n5MLqmY">
</iframe>
</td>
</tr>
</table>

<strong>[Research Goal]</strong> Design a computational episodic memory that learns human behaviors and reasons human intentions. <br/>
<strong>[Limitations of Convention]</strong> Conventional learning and reasoning algorithms such as hidden Markov model (HMM) or reinforcement learning (RL) either learn in an off-line setting or suffer from the curse of dimensionality. Adaptive theory resonance (ART) networks display instability in long-term scenarios and lack a feedback mechanism. <br/>
<strong>[Contribution]</strong> First, we designed a stabilized memory system with a feedback mechanism for incremental learning of human behaviors and reasoning human intentions. Second, we proposed a home service provision framework for robot and IoT collaboration using the proposed SF-ART architecture. Third, we set up a Smart Home environment and verify the effectiveness of both the proposed memory architecture and the service framework.

---

## Intelligent interaction design
### I-Keyboard: Fully Imaginary Keyboard on Touch Devices Empowered by Deep Neural Decoder<sup>[5]<sup>
<table class="demo_tb" style="width:45%; float: left; margin: 5px 15px 0px 0px;">
<tr>
<td style="text-align: center">
<img src="/assets/img/demo_I-Keyboard.gif" alt="I-Keyboard Demo" style="width:100%;">
</td>
</tr>

<tr>
<td width="45%">
Figure 3. Users could type on an empty touch screen with ten fingers imagining a keyboard layout. Since users could follow their own typing habit, the usability enhances.
</td>
</tr>
</table>

<strong>[Research Goal]</strong> Design a natural text-entry method for humans to deliver messages through touch screens (users can start typing using ten fingers on any position at any angle on touch screens without worrying about the keyboard position and shape). <br/>
<strong>[Limitations of Convention]</strong> Soft keyboards’ lack of tactile feedback increases the rate of typos and soft keyboards hinder mobile devices from presenting enough content because they occupy a relatively large portion on displays. <br/>
<strong>[Contribution]</strong> First, we defined an advanced typing scenario where both a predefined typing area and a calibration step are omitted. Second, we collected user data in an unconstrained environment and comprehensively analyzed user behaviors in such an environment. Third, we designed a deep learning architecture for a shape, position, and angle-independent decoding and formulated the auxiliary loss for training the architecture.

### Type Anywhere You Want: An Introduction to Invisible Mobile Keyboard<sup>[6]<sup>
<table class="demo_tb" style="width:45%; float: left; margin: 5px 15px 0px 0px;">
<tr>
<td style="text-align: center">
<img src="/assets/img/demo_IMK.gif" alt="IMK Demo" style="width:100%;">
</td>
</tr>

<tr>
<td width="45%">
Figure 4. IMK decodes both current and past inputs. As an user writes more text, IMK utilizes more context and the accuracy improves.
</td>
</tr>
</table>

<strong>[Research Goal]</strong> Design a natural text-entry method for humans to deliver messages through mobile touch screens. <br/>
<strong>[Limitations of Convention]</strong> The limitations of soft keyboards for mobile devices include high rate of typos, lack of tactile feedback, inconsideration of users’ different keyboard mental model, and large screen occupation. <br/>
<strong>[Contribution]</strong> First, we collected a large-scale, richly annotated IMK dataset which contains approximately 2M pairs of touch points and text. Second, we analyzed the characteristics of user behavior on the new proposed task in-depth. Third, we designed a novel deep neural architecture, Self-Attention Neural Character Decoder (SA-NCD) as a baseline decoder.

<div id="line_breaker" style="clear: both;">
<br/>
</div>

### Writing in The Air: Unconstrained Text Recognition from Finger Movement Using Spatio-Temporal Convolution<sup>[7]<sup>

<table class="demo_tb" style="width:45%; float: left; margin: 5px 15px 0px 0px;">
<tr>
<td style="text-align: center">
<img src="/assets/img/demo_WiTA.gif" alt="WiTA Demo" style="width:100%;">
</td>
</tr>

<tr>
<td width="45%">
Figure 5. An example instance of the dataset collected in this work. The person in the example is writing "re" from the word "recognized".
</td>
</tr>
</table>

<strong>[Research Goal]</strong> Design a computational model that interprets the text written in the air with the index finger using an RGB camera. <br/>
<strong>[Limitations of Convention]</strong> Conventional WiTA systems hardly achieve satisfactory performance for practical deployment into real-world applications. Moreover, there is no available benchmark dataset suitable for development and evaluation of WiTA systems. <br/>
<strong>[Contribution]</strong> First, we explicitly defined the task of WiTA and collect five types of the dataset in two languages (Korean and English) for the development and evaluation of WiTA systems. Second, we designed baseline methods for the WiTA task and proposed spatio-temporal residual network architectures which translate an input video sequence into a sequence of characters written in the air. Third, we  made the data collection tool, the WiTA dataset, the proposed WiTA baseline networks and the pretrained network parameters open-source.

---

<sup> [1] **U.-H. Kim**, S.-H. Kim and J.-H Kim, “SimVODIS: Simultaneous Visual Odometry, Object Detection, and Instance Segmentation,” IEEE Trans. on Pattern Analysis and Machine Intelligence, vol. 44, no. 1, pp. 428-441, Jan. 2022. [SCIE, IF: 16.390] </sup><br/>
<sup> [2] **U.-H. Kim**, J.-M. Park, T.-J. Song and J.-H Kim, “3-D Scene Graph: A Sparse and Semantic Representation of Physical Environments for Intelligent Agents,” IEEE Trans. on Cybernetics, vol. 50, no. 12, pp. 4921-4933, Dec. 2020. [SCIE, IF: 11.079] </sup><br/>
<sup> [3] J.-M. Park\*, **U.-H. Kim\***, S.-H. Lee and J.-H Kim, “Dual Task Learning by Leveraging Both Dense Correspondence and Mis-Correspondence for Robust Change Detection With Imperfect Matches,” IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), pp. 13749-13759, Jun. 2022 [Oral Presentation] </sup><br/>
<sup> [4] **U.-H. Kim** and J.-H Kim, “A Stabilized Feedback Episodic Memory (SF-EM) and Home Service Provision Framework for Robot and IoT Collaboration,” IEEE Trans. on Cybernetics, vol.  50, no.5, pp.  2110-2123, May 2020. [SCIE, IF: 11.079] </sup><br/>
<sup> [5] **U.-H. Kim**, S.-M. Yoo and J.-H Kim, “I-Keyboard: Fully Imaginary Keyboard on Touch Devices Empowered by Deep Neural Decoder,” IEEE Trans. on Cybernetics, Early Access, Sep. 2019. [SCIE, IF: 11.079] </sup><br/>
<sup> [6] S.-M. Yoo\*, **U.-H. Kim\***, Y.-W. Hwang and J.-H. Kim (* equal contribution), “Type Anywhere You Want: An Introduction to Invisible Mobile Keyboard,” in Proceedings of the 30-th International Joint Conference on Artificial Intelligence (IJCAI), 2021. (13.9% acceptance rate) </sup><br/>
<sup> [7] **U.-H. Kim\***, Y.-W. Hwang\*, S.-K. Lee and J.-H. Kim (* equal contribution), “Writing in The Air: Unconstrained Text Recognition from Finger Movement Using Spatio-Temporal Convolution,” IEEE Trans. on AI, vol. 4, no. 6, pp. 1386-1398, 2023. </sup><br/>



<script>
  if ((window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth) < 600) {
    document.getElementById("line_breaker").innerHTML = "";
    var tables = document.getElementsByClassName("demo_tb");
    for( var i = 0; i < tables.length; i++ ){
        var single_table = tables.item(i);
        single_table.style.width = "100%";
        single_table.style.margin = "0px; 0px; 0px; 0px";
    }
  }
</script>