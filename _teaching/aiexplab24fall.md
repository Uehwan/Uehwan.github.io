---
layout: course
title: AI Experience Laboratory
description: Fall 2024
---

**Schedule**: Mon/Wed 4:00pm-6:30pm<br/>
**Location**: GIST College Building A (N4), Room 227 ([Zoom Online](https://us06web.zoom.us/j/87925937140?pwd=Qm1XTmU4MENybXVEeWJ5eVh2Z0dKdz09)) / [Class Colab](https://colab.research.google.com/drive/1O_T4HQpGv2-UCYz4JiTD27FqluxMmOZA?usp=sharing)<br/>


**Instructor**: Ue-Hwan, Kim (uehwan@gist.ac.kr)<br/>
**Office**: GIST Central Research Facilities (C11) 407<br/>
**Office Hour**: Tue 4pm-5pm or by appointment

**TAs**:<br/>
Jae-Woo, Kim (kjw01124@gm.gist.ac.kr) <br/>
Won-Sic, Jang (wonsicjang@gm.gist.ac.kr) <br/>
<br/>

### Notice
* Review report format available [here](https://docs.google.com/document/d/1iyHUFjtQCoM6bj0vhg6PyvUN8eVsiZBmKXKEiK5E26E/edit?usp=sharing)
* *Recitations* start from **September 11** :)
* We do not have recitation on **October 9** (we will cover the material on October 16).
* **[Midterm]** Date: Oct. 28, 4pm-6pm / Location: GIST Oryong Hall (W1) Room 203
  * The exam is closed book, closed notes, closed computer, and closed calculator
  * Just need to bring your pen, pencil and erasers in addition to *your student ID card*
  * Coverage: Session 00 ~ Session 05 (including recitations)
  * Result released! Check [this document](https://docs.google.com/spreadsheets/d/1Fy7-t4L2PusdKW-AqKlXuELfJGXpczh96AxLTJAc9ow/edit?usp=sharing)
    * Claim during Dec. 3, 7pm-8pm C11 Room 410
* We do not have recitation on **November 6**
* **RR Result (~midterm)**
  * Check the result [here](https://docs.google.com/spreadsheets/d/1GGiZGXJzFa8pUXFsQ07OFX5HHT6AYJZ1RDNzKAhGOmU/edit?usp=sharing)
  * The meaning of scores
    * 0.50: not sufficient amount of content
    * 0.25: link is broken
  * RR claim will be on Nov. 20 after the recitation
    * You can claim for the broken link showing the edit history
* **[Final Exam]** Date: Dec. 16, 4pm-6pm / Location: GIST College Building C (N6) Room 104
  * The exam is closed book, closed notes, closed computer, and closed calculator
  * Just need to bring your pen, pencil and erasers in addition to *your student ID card*
  * Coverage: Session 06 ~ Session 10 (including recitations)


### Introduction
This course will showcase various methods in machine learning and deep learning. Throughout the semester, emphasis will be put on practical use cases. Examples of specific methods this course covers includes convolutional neural networks, recurrent neural networks, transformers and generative adversarial networks. Further, we will use Google Colab as our development environment.
<br/>
<br/>

### References
* Introduction to Deep Learning @ CMU [Link](https://deeplearning.cs.cmu.edu/S23/index.html)
* Deep Learning @ Eberhard Karls Universität Tübingen [Link](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/deep-learning/)
* Introduction to Deep Learning @ UW [Link](https://sebastianraschka.com/blog/2021/dl-course.html)
* Deep Learning for Computer Vision @ Stanford [Link](http://cs231n.stanford.edu/)
* Natural Language Processing with Deep Learning @ Stanford [Link](https://web.stanford.edu/class/cs224n/)
* Learn PyTorch for Deep Learning @ ZTM [Link](https://github.com/mrdbourke/pytorch-deep-learning)
* Deep Learning from Scratch [Link](https://github.com/WegraLee/deep-learning-from-scratch)
* Dive into Deep Learning (Aston Zhang et al., 2019) [Link](https://d2l.ai/)
<br/>
<br/>

### Schedule
<div class="table-responsive">
<table class="table table-hover table-sm text-center">
  <thead>
    <tr>
      <th class="col-sm-1" scope="col">Date</th>
      <th class="col-sm-4" scope="col">Topic</th>
      <th class="col-sm-3" scope="col">Materials</th>
      <th class="col-sm-2" scope="col">Recitations</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">09-02</th>
      <td class="text-left"><b>[Session 00.0]</b> &nbsp;Introduction</td>
      <td>
        <a href="https://youtu.be/qR2q4jwN-Rs" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1Rqgy6Gc--kJjimmnf_W5UISFkl5qR20v-7fZMrF3RG4/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/fqDqLDriX9yEfi1h6" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1s96owmnLZEP80VeFA1TFRC8z5c7-M_HCPLV1VuQ8syA/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">09-04</th>
      <td class="text-left"><b>[Session 01.0]</b> &nbsp;Preliminary</td>
      <td>
        <a href="https://colab.research.google.com/drive/11xa-72fRJqgc4YKwdErVbBGiTWgsMGX1" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1MO4dvhBOHOfsBw7Yl3L_05sUALzTfU7baD4AvStQ_tQ/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/q26uR2X8DfJy5pVq5" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1fD4ZhBcIylpWy_Y-yj4FDNnVevCnQXDI8ujb8mFpni0/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr>
      <th scope="row">09-09</th>
      <td class="text-left"><b>[Session 01.1]</b> &nbsp;Preliminary (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1dvseRqqGWX2OB-fJpSq_02GV-FeHuKRk" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1MO4dvhBOHOfsBw7Yl3L_05sUALzTfU7baD4AvStQ_tQ/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/2qR8VtAQaQEFUbV97" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/15GY_OMrLgcNqIsaa92_ewkbyMJ99VRumjqCliXeLawk/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">09-11</th>
      <td class="text-left"><b>[Session 02.0]</b> &nbsp;Perceptrons</td>
      <td>
        <a href="https://colab.research.google.com/drive/1HJShFKJd3AvPFDfysvMZFqqPijOxEA6s?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/12fvxbsmoRLGDkiP0JzHuabd2GPgJMZwEONq8obJLF_U/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/tK2odweZZCKoKmxd6" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1HeWaRTHYV6iJYfHST_XiKBXzKBkIyfmJRZEuv5Hl8xY/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/11QTYpsUovdqSJgwLIs50Xj5Ho7G9eia1?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/168DeDqEqYvMp8o7IhNoiamqbGnm6_SzH?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">09-16</th>
      <td colspan="3">No Lecture (National Holiday)</td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">09-18</th>
      <td colspan="3">No Lecture (National Holiday)</td>
    </tr>
    <tr>
      <th scope="row">09-23</th>
      <td class="text-left"><b>[Session 02.1]</b> &nbsp;Perceptrons (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1lS-ERfqrf5SFJbUGolfbaD4d0m7wi4gG?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/12fvxbsmoRLGDkiP0JzHuabd2GPgJMZwEONq8obJLF_U/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/9QWGaUjFq58WBAYw5" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/12pVXJjYJhXFX1GpUiaZL35x_KS4R1EEfi9YRRZ_sGiM/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">09-25</th>
      <td class="text-left"><b>[Session 03.0]</b> &nbsp;Loss functions</td>
      <td>
        <a href="https://colab.research.google.com/drive/1ThuWyO7TZmRl4wD_TJY_Dnem3xLnNgpw?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1xLUu3kGdvxGTZBd51gaOsqBJSFsE8dfC3e3KCKdkYMo/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/Ma75f5sMGwLpj93x8" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1ZoEnjbaZYBfV4wJLrmtm7OPXny858YrmjgAAg6ijpGQ/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1UmuQnx_6ZLEF0TBO5xepHiMrE1ZoKAUb?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1OkBCRgn--iL3Luk1y8tTk5huiothhZfc?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">09-30</th>
      <td class="text-left"><b>[Session 03.1]</b> &nbsp;Loss functions (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1pN1HXWxU8vVtMqVBk31R3Gb5wDlboh2t?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1xLUu3kGdvxGTZBd51gaOsqBJSFsE8dfC3e3KCKdkYMo/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/QQRxLa92muLEqt1i7" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/16luHFR1HuEaNxTn6_jnysclmCrQcXkH6mX289A1zpyA/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">10-02</th>
      <td class="text-left"><b>[Session 04.0]</b> &nbsp;Backpropagation</td>
      <td>
        <a href="https://colab.research.google.com/drive/1O-abi_Y3x42n3kgZaGVnlhcVPuL9wQYv?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1bmpGS7Q6nd-DQinUH2N31J8KVd-4s8mDk5aSBnVBmLU/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/NRFSZjgACGyL1iF77" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1lPB1KvVId07Ia4c-jro8JkTqXDDu7rpg70wbN_P_2eM/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1-1nnBfSplxgUZx904l9vwQ7VIThYfTzy?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1UqCoNw2_JL50U0t5ZeF5oY6PBJbQHVvB?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">10-07</th>
      <td class="text-left"><b>[Session 04.1]</b> &nbsp;Backpropagation (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1X3czzJ83BgDolNvUpbBGNTBSiv8RrB51?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1bmpGS7Q6nd-DQinUH2N31J8KVd-4s8mDk5aSBnVBmLU/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/x7MPGYWPV9SWS3W69" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/19lCaz4mHyzcDBZhukDq6_Kb1qFzCLUNbgizRlxKMxUw/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">10-09</th>
      <td colspan="2">No Lecture (National Holiday)</td>
      <td>
        <a href="https://colab.research.google.com/drive/11lF4_s4SwzMcmK2mjYYghx7rE59MCmhb?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1Jd_xswFdWDLFDZi4SH0FMaImDQCpVppp?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">10-14</th>
      <td class="text-left"><b>[Session 04.2]</b> &nbsp;Backpropagation (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1W5ckuB696gzqjTvy1wgJE05UznWAIYjw?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1bmpGS7Q6nd-DQinUH2N31J8KVd-4s8mDk5aSBnVBmLU/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/nEcbtQTwKES5b26i7" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1-k1Yq44tTwFltu2zRs7FrT0UoyWkceBKVg0a_okwU5w/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
      <!--td>
        <a href="https://colab.research.google.com/drive/1AKGwvkCDZnnOMbhvqO5D17iSYIqcsCNf?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1Jd_xswFdWDLFDZi4SH0FMaImDQCpVppp?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td-->
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">10-16</th>
      <td class="text-left"><b>[Session 05.0]</b> &nbsp;Optimization</td>
      <td>
        <a href="https://colab.research.google.com/drive/1bry1OIQ2fMgyVHoxxuf-lW8LiEMzuRLg?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1rjXN0Pudol0DoaEIm-Am8cjFGsFNoSBstGxcKL60P_I/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/KuCdq1SbMY6YwBtR8" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1hg5NxRXYUR4JeaCAizJqUV-A01AdDbC_IMFYZE7HzOU/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1vndkdUFAsGYEAswZLK4Gf1wKrwzpkxK5?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1pe4udBEDOxRZiPVBG5wYV1QuJjOW6Lkz?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">10-21</th>
      <td class="text-left"><b>[Session 05.1]</b> &nbsp;Optimization (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1bJXyiWSTCExPD7I1e-uDtN3iVbXRVopS?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1rjXN0Pudol0DoaEIm-Am8cjFGsFNoSBstGxcKL60P_I/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/11FrmzgjgPryCKLi8" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1Ov0ip7Pb7nTTe_lzpPv1mWK7kBRpZWmAWFqvw8pi5Ro/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">10-23</th>
      <td class="text-left"><b>[Session 99.0]</b> &nbsp;Midterm review (Q&A)</td>
      <td>
        <!--a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a-->
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1K1g5qyxa3c_7vlQIXEUwWOwY5bDr6ymZ?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1RtxmMv1vGrCXuURFr3BEG2rCeKkd-c1U?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">10-28</th>
      <td class="text-left"><b>[Session 99.1]</b> &nbsp;Midterm</td>
      <td>
        <!--a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Solution</a-->
        <!--a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Scores</a-->
        <!--a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Claim</a-->
        <!--a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a-->
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">10-30</th>
      <td colspan="3">No Lecture (Midterm Period)</td>
    </tr>
    <tr>
      <th scope="row">11-04</th>
      <td class="text-left"><b>[Session 06.0]</b> &nbsp;CNNs</td>
      <td>
        <a href="https://colab.research.google.com/drive/1f6M1-ruBS_UjtOMS4VP3MrVTJd7T4lWJ?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://drive.google.com/file/d/1sKFwZ070ZPL49k4UYlWdVgAAysEQuyx-/view?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/mdoNCAf3TwVin5LK9" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1kr5kWL8q3e1ya-O52WTE2zwZPUwEex1dQ4ApOlBdh38/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">11-06</th>
      <td class="text-left"><b>[Session 00.1]</b> &nbsp;AI Days</td>
      <td>
        <a href="https://docs.google.com/presentation/d/1loU8AcLZklx_JRnW_SieXEln5mYWFeQu_U-HEdx9RmE/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1loU8AcLZklx_JRnW_SieXEln5mYWFeQu_U-HEdx9RmE/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/CK23RDyVnFydJj5s5" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1RkDNsDMXePnJ-I3iGFQY48Pz2IYdQNCxNeuNDog77D8/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr>
      <th scope="row">11-11</th>
      <td class="text-left"><b>[Session 06.1]</b> &nbsp;CNNs (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1HXTeZphZG0_5x2D6FQDUJFBU-EqCAH8A?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://drive.google.com/file/d/1sKFwZ070ZPL49k4UYlWdVgAAysEQuyx-/view?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/Kjm4Ea5yJ5jbvypr7" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1r3R3N9jk1dlZqxNQM73fIKVeVIvngc2o88pXdipB-pc/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">11-13</th>
      <td class="text-left"><b>[Session 07.0]</b> &nbsp;Word vectors</td>
      <td>
        <a href="https://colab.research.google.com/drive/1eeUmClkL56StX372Y2WXquEM1Ng8XFWa?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1WRa8JOF4fmZ4lDCF-xiV8oL4EejH1_uSNJUgLQh1lp0/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/P9rJQdKRwCgXr2dh7" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1GtVwFcN7F0eX9SRnVVqfHQDml1pLRIQEyx7uA59Bggk/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1--QDJCzQdx4Eba-GmzLqjDyc32lL24wO?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1U4q2pdhsgzPa2gB4kMhL_pMTEpGXuKQV?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">11-18</th>
      <td class="text-left"><b>[Session 07.1]</b> &nbsp;Word vectors (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/14fSaaRG61glCHxj6zuaV8gxo0cymSvwA?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1WRa8JOF4fmZ4lDCF-xiV8oL4EejH1_uSNJUgLQh1lp0/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/MLnhdU3NcZQeAoAeA" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1e0OGv15IlyP1PJWBD-gw4b0DZDH-Vc0T1lWLduivdaI/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">11-20</th>
      <td class="text-left"><b>[Session 08.0]</b> &nbsp;RNNs</td>
      <td>
        <a href="https://colab.research.google.com/drive/1kmCln5bKaf8-_qRsldD9KhO0pT-mckH2?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/128aF0HxGAfOTM8nyb5nZlBVAMIjLamqQIdhk2fMhqbc/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/hG83A1k6zG63RNZM9" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/10z0DuHY4-rO-XzteesVtS757zfgYMu9xIAwyqy0B9vQ/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1Kmzta_ybXUEl5MFdHYsQmVQj0hJ2b7KS?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1nu78D6IY9rxvPYpUMd4pvUgJntN1k5j2?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">11-25</th>
      <td class="text-left"><b>[Session 08.1]</b> &nbsp;RNNs (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1hvPwv9xoyuJ9eYQP5wlFkE1-hWyk28We?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/128aF0HxGAfOTM8nyb5nZlBVAMIjLamqQIdhk2fMhqbc/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/Epj1nRH1YgZnAsNQA" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1xSjalcGVCreIU0M6fPpiRkScAVsfbPKy1tWStOvDdHI/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">11-27</th>
      <td class="text-left"><b>[Session 09.0]</b> &nbsp;Seq2Seq</td>
      <td>
        <a href="https://colab.research.google.com/drive/1W-pqVCcmkHwZ79o2yD1lt5--eQBqmpmx?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1LFctT_P6HgXu6x01Sr7Ml1jFYPzC_Hb1xZIXJK1BoK8/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/616zw7L5GETuzQqZ9" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1XdjeanKwCekFvbEQe6OsGuaGIyxjI8LQrPxDelwcu4w/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1LvevQ516fvHllF61Y1zkaRXG5cYesFmW?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1jaSDPJBnQfcGu7gOjIK78WrgiwY4RqRf?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">12-02</th>
      <td class="text-left"><b>[Session 09.1]</b> &nbsp;Seq2Seq (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1XaraUJE0_MOIOW8Mdt160ZIhwkyGTAWf?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1LFctT_P6HgXu6x01Sr7Ml1jFYPzC_Hb1xZIXJK1BoK8/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/U5zwkw1Bx94yhWb47" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1E4JfQn7l59TeTwhAfXNDFzNpAsYOWgeg1WqQIlGVrpU/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">12-04</th>
      <td class="text-left"><b>[Session 10.0]</b> &nbsp;Transformers</td>
      <td>
        <a href="https://colab.research.google.com/drive/1HUXrxl6GB7lrIv6_HkegFIT-QSzmMuoQ?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1cLbQQyoWu1rHiIZPGIsl54meQgFmqiUATzo3N_xBKMg/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/Kt86kDNdTt8gX3sP8" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1B9IMKcSsQ8zh_nmHu6qDvHN0tCAvc76Ca2okURP6SsA/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1x_HxKKVAVD5YtJEn7zhd-S1dtvy-NY2n?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/1QcglxFnjO7Qd8H1Re6RUFnxWfU1mIp9l?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">12-09</th>
      <td class="text-left"><b>[Session 10.1]</b> &nbsp;Transformers (cont'd)</td>
      <td>
        <a href="https://colab.research.google.com/drive/1BtUYrn_x-OpXX1_hPCKzSfFOBZJPDtVC?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="https://docs.google.com/presentation/d/1cLbQQyoWu1rHiIZPGIsl54meQgFmqiUATzo3N_xBKMg/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="https://forms.gle/kmSSDrsobxfSwxX8A" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="https://docs.google.com/spreadsheets/d/1LOFUEyVNle8fANlqSAILmo6YkgWlsalWX2fue_o__js/edit?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a>
      </td>
      <td></td>
    </tr>
    <tr style="border-bottom: 1.5px solid lightgrey;">
      <th scope="row">12-11</th>
      <td class="text-left"><b>[Session 99.2]</b> &nbsp;Final exam review (Q&A) </td>
      <td>
        <!--a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Lecture</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Slides</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Submit</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a-->
      </td>
      <td>
        <a href="https://colab.research.google.com/drive/1xhfM7-JYNzEuMbpXlg8-xYphh_5cwSb4?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Exercises</a>
        <a href="https://colab.research.google.com/drive/16kJBYCO94pm_DVq7A1TSkeC46gzf7q1J?usp=sharing" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">solution</a>
      </td>
    </tr>
    <tr>
      <th scope="row">12-16</th>
      <td class="text-left"><b>[Session 99.3]</b> &nbsp;Final exam</td>
      <td>
        <!--a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Solution</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Scores</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Claim</a>
        <a href="" target="_blank" class="badge badge-pill" style="background-color:#B509AC;">Result</a-->
      </td>
      <td></td>
    </tr>
    <tr>
      <th scope="row">12-18</th>
      <td colspan="3">No Lecture (Final Exam Period)</td>
    </tr>
  </tbody>
</table>
</div>

