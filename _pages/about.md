---

permalink: /

title: ""

excerpt: ""

author_profile: true

redirect_from: 

  - /about/

  - /about.html

---



{% if site.google_scholar_stats_use_cdn %}

{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}

{% else %}

{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}

{% endif %}

{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👨‍🎓 About Me

I am a Professor at the School of Information Science and Engineering, Hangzhou Normal University, where I lead the Intelligent Video Coding (IVC) Lab. My research primarily focuses on the cutting-edge fields of visual data compression and multimedia communication.



Specifically, my work explores next-generation visual compression technologies, including AV2 and MPEG AI-based point cloud/3DGS compression, as well as their real-time system implementations on NPU and FPGA platforms. Since 2018, I have been continuously supported by Google’s Chrome University Relationship Program to advance the development of the AV2 standard.



I am an IEEE Senior Member and currently serve as an Associate Editor for IEEE Signal Processing Letters. Over the years, I have actively contributed to international standardization, notably receiving the ISO/IEC Appreciation Prize in 2011 for my leadership in MPEG activities.



# 🔥 News

- *2026.01*: &nbsp;📢 Serving as **Area Chair** for **ICASSP 2026** and **ICME 2026**.

- *2025.10*: &nbsp;📄 Paper on "GeoQE" (Point Cloud Streaming) accepted by **ACM MM 2025**.

- *2025.07*: &nbsp;🎉 One paper on LiDAR reflectance compression accepted by **ICML 2025**.

- *2025.06*: &nbsp;🚀 Presented "Reno" (Real-time Neural Compression) at **CVPR 2025**.

- *2025.01*: &nbsp;📑 Research on Multiscale Point Cloud Compressor published in **IEEE TPAMI**.

- *2024.12*: &nbsp;📢 Serving as **Area Chair** for **MMSP 2025**.

- *2024.06*: &nbsp;🏆 Paper "ELIM" nominated as **Best Paper Award Finalist** at **IEEE PCS 2024**.

- *2023.10*: &nbsp;📄 Two papers on G-PCC++ and YOGA accepted by **ACM MM 2023**.

- *2020.12*: &nbsp;🏫 Promoted to **Professor** and lead the **IVC Lab** at Hangzhou Normal University.

  

<span class='anchor' id='publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2023</div><img src='images/Neural Adaptive Loop Filtering for Video Coding.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Neural Adaptive Loop Filtering for Video Coding: Exploring Multi-Hypothesis Sample Refinement](https://ieeexplore.ieee.org/abstract/document/10078282)


**Dandan Ding**, Junjie Wang, Guangkun Zhen, Debargha Mukherjee, Urvang Joshi, Zhan Ma

- We reformulate ALF as a Multi-Hypothesis Sample Refinement (MSR) problem, using a DNN model to generate multiple distortion hypotheses that are linearly superimposed to approximate the final reconstruction.

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023</div><img src='images/Sparse Tensor-based Multiscale Representation for Point Cloud Geometry Compression.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Sparse Tensor-based Multiscale Representation for Point Cloud Geometry Compression](https://ieeexplore.ieee.org/abstract/document/9968173)

Jianqiang Wang, **Dandan Ding**, Zhu Li, Xiaoxing Feng, Chuntong Cao, Zhan Ma

- We propose SparsePCGC, a low-complexity multiscale representation that performs sparse convolutions only on most-probable positively-occupied voxels to characterize spatial correlations efficiently.

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Proc. IEEE 2021</div><img src='images/Advances In Video Compression System Using Deep Neural Network.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Advances In Video Compression System Using Deep Neural Network: A Review And Case Studies](https://ieeexplore.ieee.org/abstract/document/9369668)

**Dandan Ding**, Zhan Ma, Di Chen, Qingshuang Chen, Zoe Liu, Fengqing Zhu

- This article extensively reviews technical advances in video compression using deep neural networks, presenting case studies on semantic pre-processing, end-to-end neural coding, and neural adaptive post-processing.

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2021</div><img src='images/Neural Reference Synthesis for Inter Frame Coding.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Neural Reference Synthesis for Inter Frame Coding](https://ieeexplore.ieee.org/abstract/document/9658260)

**Dandan Ding**, Xiang Gao, Chenran Tang, Zhan Ma

- We propose a Neural Reference Synthesis (NRS) framework with joint optimization of reconstruction enhancement and reference synthesis modules to improve both in-ring filtering and inter-frame prediction.

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCyb 2022</div><img src='images/Biprediction-Based Video Quality Enhancement via Learning.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Biprediction-Based Video Quality Enhancement via Learning](https://ieeexplore.ieee.org/abstract/document/9119800)

**Dandan Ding**, Wenyu Wang, Junchao Tong, Xinbo Gao, Zoe Liu, Yong Fang

- We develop a biprediction-based multiframe video enhancement (PMVE) framework that synthesizes virtual frames to extract cross-correlations between successive frames for high-accuracy quality restoration.

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2021</div><img src='images/Point Cloud Upsampling via Perturbation Learning.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Point Cloud Upsampling via Perturbation Learning](https://ieeexplore.ieee.org/abstract/document/9493165)

**Dandan Ding**, Chi Qiu, Fuchang Liu, Zhigeng Pan

- We propose learning 2D perturbations through MLPs to estimate coordinate shifts from sparse input points to upsampled dense points, outperforming state-of-the-art methods in geometric uniformity.

</div>

</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/exploit contextual clustering in learned image coding.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

[Another way to the top: exploit contextual clustering in learned image coding](https://ojs.aaai.org/index.php/AAAI/article/view/28791)

Yichi Zhang, Zhihao Duan, Ming Lu, **Dandan Ding**, Fengqing Zhu, Zhan Ma

- We propose Contextual Clustering based LIC (CLIC), which relies on clustering operations and local attention instead of traditional convolutions to generate compact representations for image compression.

</div>

</div>





- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**





# 🎖 Honors and Awards

- *2024.06* Best Paper Award Finalist, IEEE PCS 2024.

- *2011.06* ISO/IEC Appreciation Prize, for leadership in MPEG standardization.



# 📖 Educations

- *2006.09 - 2011.06*, **Zhejiang University**, China. Ph.D. in Communication and Information System.

- *2007.07 - 2008.05*, **EPFL**, Switzerland. Joint Ph.D. program in GR-LSM.

- *2002.09 - 2006.06*, **Zhejiang University**, China. B.S. in Communication Engineering.

  

<span class='anchor' id='professional-experience'></span>

# 💻 Professional Experience

- *2020.12 - Present*, **Professor**, Hangzhou Normal University. Lead IVC lab.

- *2015.12 - 2020.11*, **Assistant Professor**, Hangzhou Normal University.

- *2013.07 - 2015.11*, **Assistant Professor**, Zhejiang University.

