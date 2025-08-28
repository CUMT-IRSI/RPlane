# Rethinking The Value of Dynamic and Static Feature Planes in 4D Reconstruction of Deformable Tissues
4D dynamic reconstruction of internal cavity tissues

> [Rethinking The Value of Dynamic and Static Feature Planes in 4D Reconstruction of Deformable Tissues]() \
> Ran Bu, Chenwei Xu, Ruiyi Liu, Yanzi Miao

![image](https://github.com/CUMT-IRSI/RPlane/blob/master/rplane.png)

## Introduction
Reconstructing deformable tissues is crucial for medical image computing and robotic surgery, as it enhances the safety and efficacy of surgical procedures. However, current methods face significant challenges, including errors in tissue reconstruction at occluded regions and limitations in realtime accurate observation of complex structures. In this paper, we present a novel method called Rethink Plane (RPlane), an efficient framework based on Neural Radiance Fields (NeRF), designed to reconstruct global high-fidelity deformable tissues from binocular endoscopic videos efficiently. Our main contribution lies in rethinking the value of dynamic and static features that existing methods often overlook, and developing a Depth Uncertainty Filter. Throughout this work, the dynamic filter is an extremely important foundational component. Based on this, a Dynamic Feature Enhancement module is proposed to address the depth distortion problem caused by the occlusion of surgical instruments. Additionally, a Color Recurrent Refinement strategy is proposed to reduce dynamic blurring caused by instrument contact or tissue self-motion. We validate the effectiveness of RPlane on two datasets (ENDONERF and StereoMIS). In all cases, RPlane achieves state-of-the-art (SOTA) performance in terms of tissue reconstruction quality and detail clarity (with a PSNR of 40.527 in ENDONERF and 36.267 in StereoMIS). Furthermore, RPlane demonstrates a 53.3% improvement in robustness without increasing training time or computational resources. This significant performance improvement promises to be an innovative solution for intraoperative applications.
## RPlane VS ForPlane in terms of rendering quality
https://github.com/user-attachments/assets/d217406a-452f-47b1-8cf1-72cff32ac8e3

## Acknowledgments
The authors would like to express their sincere gratitude to Dr. Tong Lu for his valuable contributions in addressing the reviewers’ comments and improving the manuscript.
