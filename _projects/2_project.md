---
layout: page
title: Safe Vision Language Navigation
description: Fine-tuning vision language navigation with Control Barrier Functions
img: Safe_VLN/img/vlnce-setting.png
importance: 2
category: Safe Multimodal Foundation Models
giscus_comments: true
---

Vision and Language Navigation in Continuous Environments is an instruction-guided navigation task with crowdsourced instructions, realistic environments, and unconstrained agent navigation. 

Safe VLN (Safe Vision-and-Language Navigation) is the “do VLN, but don’t do dumb/dangerous stuff while doing it” version of instruction-following navigation. In standard VLN / VLN-CE, success is mostly about reaching the language goal efficiently. In Safe VLN, the agent is additionally evaluated (and often trained) to satisfy safety constraints while following the instruction—so it must navigate like a careful robot, not just an optimal path planner.



<div class="row">
    <div class="col-sm-12 mt-3">
        {% include video.liquid path="Safe_VLN/video1.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="row">
    <div class="col-sm-12 mt-3">
        {% include video.liquid path="Safe_VLN/video2.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="row">
    <div class="col-sm-12 mt-3">
        {% include video.liquid path="Safe_VLN/video3.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>



