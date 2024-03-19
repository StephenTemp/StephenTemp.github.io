---
title: "Robust Frame-to-Frame Camera Rotation Estimation in Crowded Scenes"
excerpt: "Energy Consumption Prediction for Climate Planning"
excerpt: "We characterize social polls online and leverage machine learning models to describe the demographics, political leanings, and other characteristics of the users who author and interact with social polls. We study the relationship between social poll results, their attributes, and the characteristics of users interacting with them.<br/><img src='/images/rotation-estimation.jpg' width='551' height='377'>"
collection: portfolio
---


![Image of Hough transform on SO3 to efficiently find the camera rotation most compatible with optical flow](/images/rotation-estimation.jpg)

Abstract
=====

We present an approach to estimating camera rotation in crowded, real-world scenes from handheld monocular video.

While camera rotation estimation is a well-studied problem, no previous methods exhibit both high accuracy and acceptable speed in this setting. Because the setting is not addressed well by other datasets, we provide a new dataset and benchmark, with high-accuracy, rigorously verified ground truth, on 17 video sequences. We introduce a novel generalization of the Hough transform on SO3 to efficiently find the camera rotation most compatible with optical flow. Methods developed for wide baseline stereo (e.g., 5-point methods) perform poorly on monocular video. On the other hand, methods used in autonomous driving (e.g., SLAM) leverage specific sensor setups, specific motion models, or local optimization strategies (lagging batch processing) and do not generalize well to handheld video. Finally, for dynamic scenes, commonly used robustification techniques like RANSAC require large numbers of iterations, and become prohibitively slow. Among comparably fast methods, ours reduces error by almost 50% over the next best, and is more accurate than any method, irrespective of speed.

This represents a strong new performance point for crowded scenes, an important setting for computer vision.