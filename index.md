---
layout: project_page
permalink: /

title: "Glovity: Learning Dexterous Contact-Rich Manipulation via Spatial Wrench Feedback Teleoperation System"
authors:
  - name: "Yuyang Gao"
    link: ""  # 示例：替换为实际链接（如个人主页）
  - name: "Haofei Ma"
    link: "https://academic.mahaofei.com/"         # 示例：替换为实际链接
  - name: "Pai Zheng"
    link: "https://www.polyu.edu.hk/ise/people/academic-staff/pai-zheng/"  # 示例：替换为实际链接
affiliations:
    The Hong Kong Polytechnic University
paper: https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf
video: https://www.youtube.com/results?search_query=glovity+teleoperation
code: https://github.com/topics/glovity
data: https://huggingface.co/docs/datasets
---

<!-- Main Project Image -->
<div class="columns is-centered has-text-centered">
    <div class="column is-full">
        <img width="80%" src="/static/image/Glovity_head.png" alt="Glovity Project Overview Image" style="width:100%; height:auto;">
        <p><em>System Overview</em></p>
    </div>
</div>

<!-- Main Project Video -->
<div class="columns is-centered has-text-centered">
    <div class="column is-full">
        <video width="100%" autoplay controls muted loop playsinline height="auto" controls>
            <source src="/static/video/BMS.mp4" type="video/mp4">
            您的浏览器不支持视频标签。
        </video>
        <p><em>Blindfold Mouse Swinging</em></p>
    </div>
</div>

---
<!-- Abstract Section -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
We present <b>Glovity</b>, a novel, low-cost wearable teleoperation system that integrates a spatial wrench (force-torque) feedback device with a haptic glove featuring fingertip Hall sensor calibration, enabling feedback-rich dexterous manipulation. Glovity addresses key challenges in contact-rich tasks by providing intuitive wrench and tactile feedback, while overcoming embodiment gaps through precise retargeting. User studies demonstrate significant improvements: wrench feedback boosts success rates in book-flipping tasks from 48% to 78% and reduces completion time by 25%, while fingertip calibration enhances thin-object grasping success significantly compared to commercial gloves. Furthermore, incorporating wrench signals into imitation learning (via DP-R3M) achieves high success rates in novel contact-rich scenarios, such as adaptive page flipping and force-aware handovers. All hardware designs, software, and datasets will be <b>open-sourced</b> to facilitate community advancements in robotic learning.
        </div>
    </div>
</div>
---


<!-- Main Project Videos Grid (4-column) -->

<div class="columns is-centered has-text-centered">
    <div class="column is-half">
        <video width="100%" autoplay controls muted loop playsinline height="auto">
            <source src="/static/video/WF.mp4" type="video/mp4">
            您的浏览器不支持视频标签。
        </video>
        <p><em>Wrench Feedback System</em></p>
    </div>
    <div class="column is-half">
        <video width="100%" autoplay controls muted loop playsinline height="auto">
            <source src="/static/video/FR.mp4" type="video/mp4">
            您的浏览器不支持视频标签。
        </video>
        <p><em>Finnger Retargeting</em></p>
    </div>
</div>
<div class="columns is-centered has-text-centered">
    <div class="column is-half">
        <video width="100%" autoplay controls muted loop playsinline height="auto">
            <source src="/static/video/FHC.mp4" type="video/mp4">
            您的浏览器不支持视频标签。
        </video>
        <p><em>Finger Hall Calibration</em></p>
    </div>
    <div class="column is-half">
        <video width="100%" autoplay controls muted loop playsinline height="auto">
            <source src="/static/video/HF.mp4" type="video/mp4">
            您的浏览器不支持视频标签。
        </video>
        <p><em>Haptic Feedback</em></p>
    </div>
</div>




# Design Philosophy

Glovity\'s development is guided by three core principles that ensure both accessibility and high performance:

**High Cost-Performance**: The system achieves remarkable functionality at an unprecedented price point of approximately **$300** ($230 for wrench feedback system, $70 for haptic glove). This affordability is achieved through strategic use of minimal high-quality commercial components combined with 3D-printed parts, making advanced teleoperation technology accessible to researchers and developers worldwide.

**Ease of Replication**: All components can be easily obtained online or manufactured via 3D printing. The system adopts a modular, Lego-style design philosophy, enabling complete assembly in just a few hours with basic tools. This approach democratizes access to sophisticated teleoperation capabilities.

**Versatility and Modularity**: Glovity accommodates various hand sizes and integrates with diverse robotic platforms. The system operates at high frequencies (up to 100Hz) for wrench feedback, retargeting, and tactile feedback, ensuring responsive control across different manipulation tasks.


## Wearable Spatial Wrench Feedback System

<div class="columns is-centered has-text-centered">
    <div class="column is-full">
        <img width="80%" src="/static/image/Wrench.png" alt="Glovity Project Overview Image" style="width:100%; height:auto;">
        <p><em>Four base feedback modes of the wrench feedback system</em></p>
    </div>
</div>

---

## Imitation Learning

**Adaptive Page Flipping**: The system successfully handles variable page thicknesses and positions, demonstrating robust adaptation to changing contact conditions.

**Force-Aware Handovers**: Integration of wrench signals enables smooth object transfers between human and robot, with appropriate force modulation throughout the interaction.

<div class="columns is-centered has-text-centered">
    <div class="column is-half">
        <video width="100%" autoplay controls muted loop playsinline height="auto" controls>
            <source src="/static/video/IL_BF.mp4" type="video/mp4">
            您的浏览器不支持视频标签。
        </video>
        <p><em>Page Flipping</em></p>
    </div>
    <div class="column is-half">
        <video width="100%" autoplay controls muted loop playsinline height="auto" controls>
            <source src="/static/video/IL_HO.mp4" type="video/mp4">
            您的浏览器不支持视频标签。
        </video>
        <p><em>Force-Aware Handovers</em></p>
    </div>
</div>

---

## Citation

```bibtex
@article{gao2024glovity,
  title={Glovity: Learning Dexterous Contact-Rich Manipulation via Spatial Wrench Feedback Teleoperation System},
  author={Gao, Yuyang and Ma, Haofei and Zheng, Pai},
  year={2025},
}
```

---

*This project represents a collaborative effort to advance the state of robotic teleoperation through innovative hardware design, sophisticated algorithms, and open-source principles. For more information, access to code repositories, or collaboration opportunities, please visit our project resources linked above.*
