---
layout: page
title: Digital Double
description: Automatic Generation and Stylization of 3D Facial Rigs
img: /assets/img/dd.jpg
---

We present a fully automatic pipeline for generating and stylizing high geometric and textural quality facial rigs. They are automatically rigged with facial blendshapes for animation, and can be used across platforms for applications including virtual reality, augmented reality, remote collaboration, gaming and more. From a set of input facial photos, our approach is to be able to create a photorealistic, fully rigged character in less than seven minutes. The facial mesh reconstruction is based on state-of-the art photogrammetry approaches. Automatic landmarking coupled with ICP registration with regularization provide direct correspondence and registration from a given generic mesh to the acquired facial mesh. Then, using deformation transfer, existing blendshapes are transferred from the generic to the reconstructed facial mesh. The reconstructed face is then fit to the full body generic mesh. Extra geometry such as jaws, teeth and nostrils are retargeted and transferred to the character. An automatic iris color extraction algorithm is performed to colorize a separate eye texture, animated with dynamic UVs. Finally, an extra step applies a style to the photorealis-tic face to enable blending of personalized facial features into any other character. The user's face can then be adapted to any human or non-human generic mesh. A pilot user study was performed to evaluate the utility of our approach. Up to 65% of the participants were successfully able to discern the presence of one's unique facial features when the style was not too far from a humanoid shape.

#### Paper

{% reference danieau2019automatic -f conference.bib %}

#### Videos 
<div class="video_row">
    <object type="text/html" data="http://www.dailymotion.com/embed/video/x72iin7" style="width:700px;height:394px;"></object>
</div>
<div class="video_row">
    <object type="text/html" data="http://www.youtube.com/embed/NRnCYlXJSQc" style="width:700px;height:394px;"></object>
</div>

#### Award

The Digital Double demonstration was presented at IBC 2019 and won the IBC Best Show Award presented by [TVB Europe](https://www.tvbeurope.com/business/best-of-show-at-ibc-2019-winners-announced).

#### Press

Hardisk. October 2019. [On m'a cloné](https://www.youtube.com/watch?v=kDSI132lqEU) (Fr)<br />
InterDigital. September 2019. [InterDigital R&I Recognized for Immersive Video Technology at Inaugural IBC Showcase](https://www.interdigital.com/post/interdigital-ri-recognized-for-immersive-video-technology-at-inaugural-ibc-showcase) (En) <br />
Ranch Computing. July 2019. [Back from Siggraph 2019 Announcements, exhibitors, keynotes...](https://blog.ranchcomputing.com/back-from-siggraph-2019) (En)