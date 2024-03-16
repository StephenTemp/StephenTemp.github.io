---
title: "Robust Frame-to-Frame Camera Rotation Estimation in Crowded Scenes"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2015-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

![Image of Hough transform on S O 3 to efficiently find the camera rotation most compatible with optical flow](/images/rotation-estimation.jpg)

<p style="text-align: center;">Abstract</p>
====
We present an approach to estimating camera rotation in crowded, real-world scenes from handheld monocular video.

While camera rotation estimation is a well-studied problem, no previous methods exhibit both high accuracy and acceptable speed in this setting. Because the setting is not addressed well by other datasets, we provide a new dataset and benchmark, with high-accuracy, rigorously verified ground truth, on 17 video sequences. We introduce a novel generalization of the Hough transform on S O 3 to efficiently find the camera rotation most compatible with optical flow. Methods developed for wide baseline stereo (e.g., 5-point methods) perform poorly on monocular video. On the other hand, methods used in autonomous driving (e.g., SLAM) leverage specific sensor setups, specific motion models, or local optimization strategies (lagging batch processing) and do not generalize well to handheld video. Finally, for dynamic scenes, commonly used robustification techniques like RANSAC require large numbers of iterations, and become prohibitively slow. Among comparably fast methods, ours reduces error by almost 50% over the next best, and is more accurate than any method, irrespective of speed.

This represents a strong new performance point for crowded scenes, an important setting for computer vision.
