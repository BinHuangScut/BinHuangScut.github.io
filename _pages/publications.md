---
layout: page
title: Publications
permalink: /Publications/
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<!-- ==================== CSS ==================== -->
<style>
/* -------------------- Section Titles -------------------- */
.section-title {
    padding-bottom: 0.4em; /* Reduce space between title text and underline */
    border-bottom: 3px solid #007BFF; /* Blue thick underline */
    margin-bottom: 0.4em; /* Reduce space between underline and content */
    display: block; 
}

/* -------------------- Blue line under h4 -------------------- */
h4 {
    border-bottom: 1.5px solid #007BFF; /* Blue thick underline */
    padding-bottom: 0.4em; /* Reduce space between title text and underline */
    margin-bottom: 0.4em; /* Reduce space between underline and content */
    width: 100%; 
    display: block; 
}

/* -------------------- General publication list styling -------------------- */
.publications {
    list-style: none; /* Remove default bullets */
    padding-left: 0; /* Remove default padding */
    margin-bottom: 1.5em; /* Space below the list */
}

/* -------------------- Highlight author's name -------------------- */
.author-highlight {
    font-weight: normal; /* Remove bold */
    text-decoration: underline; /* Underline the name */
}

/* -------------------- Journal Papers Auto-numbering [J*] -------------------- */
.journal-publications {
    counter-reset: journal-counter;
}
.journal-publications li::before {
    counter-increment: journal-counter;
    content: "[J" counter(journal-counter) "] ";
    font-weight: bold;
}

/* -------------------- Conference Papers Auto-numbering [C*] -------------------- */
.conference-publications {
    counter-reset: conf-counter;
}
.conference-publications li::before {
    counter-increment: conf-counter;
    content: "[C" counter(conf-counter) "] ";
    font-weight: bold;
}

/* -------------------- Spacing between publication entries -------------------- */
.publications li {
    margin-bottom: 0.8em;
}

/* -------------------- Highlight Best Paper Award -------------------- */
.highlight {
    background-color: #FFFFE0; /* Light yellow background */
    color: #D32F2F; /* Red text */
    font-weight: bold;
    padding: 0.1em 0.3em; /* Padding around text */
    border-radius: 3px; /* Rounded corners */
}
</style>

<!-- ==================== HTML ==================== -->

For a complete list of publications, please refer to 
<a href="https://scholar.google.com/citations?user=FdEP8xgAAAAJ&hl=en">Google Scholar</a>.

<!-- -------------------- In-Progress Papers -------------------- -->

<div class="journal-publications publications">
    <h4>In-Progress Papers</h4>
    <li>
        Caoyang Cheng, <span class="author-highlight">Bendong Tan</span>, and Junbo Zhao, 
        "Nodal frequency security-constrained optimal power system virtual inertia and damping dispatch", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, 2026. (Under review)
    </li>
    <li>
        Tong Su, Junbo Zhao, <span class="author-highlight">Bendong Tan</span>, Daniel Adrian Maldonado, Xiaodong Liu, and Xiaochuan Luo, 
        "Analytic input convex neural networks enabled transient stability predictive control with wind generators", 
        <span class="journal-name">Applied Energy</span>, 2026. (Under review)
    </li>
</div>

<!-- -------------------- Journal Papers -------------------- -->

<div class="journal-publications publications">
    
    <h4>Journal Papers</h4>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Ketian Ye, Junbo Zhao, Mingguo Hong, Slava Maslennikov, and Xiaochuan Luo, 
        "<a href="https://doi.org/10.1038/s41467-025-68241-y">Computationally efficient tail distribution-aware large-scale power system overloading risk assessment</a>",
        <span class="journal-name">Nature Communications</span>, 2026. <span class="highlight">Featured Article-Top 50 Best Papers</span>
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Deepjyoti Deka, and Junbo Zhao,
        "<a href="https://ieeexplore.ieee.org/document/11303596">Spatial-temporal global sensitivity analysis for probabilistic transient stability assessment</a>",
        <span class="journal-name">IEEE Transactions on Power Systems</span>, 2025.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, 
        "Stochastic dynamic stability assessment with high penetration of uncertain sources: Uncertainty modeling, solutions and applications", 
        <span class="journal-name">Cyber-Physical Energy Systems</span>, 2025.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Tong Su, Yu Weng, Ketian Ye, Parikshit Pareek, 
        Petr Vorobev, Hung Nguyen, Junbo Zhao, and Deepjyoti Deka, 
        "<a href="https://arxiv.org/abs/2505.15950">Gaussian processes in power systems: Techniques, applications, and future Works</a>", 
        <span class="journal-name">Applied Energy</span>, 2025.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Naiyuan Chiang, and Nan Duan, 
        "<a href="https://ieeexplore.ieee.org/document/10892022">High-dimension Bayesian parameter estimation for WECC composite load model using realistic event measurements</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 40, no. 5, pp. 3979-3992, Sept. 2025.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, 
        "<a href="https://ieeexplore.ieee.org/document/10854889">Bayesian post-fault power system dynamic trajectory prediction</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 40, no. 6, pp. 4123-4136, Oct. 2025.
    </li>
    <li>
        Xinyu Zhao, <span class="author-highlight">Bendong Tan</span>, and Junbo Zhao, 
        "<a href="https://ieeexplore.ieee.org/document/10679897">Power system dynamic state estimation of grid-forming inverters with current limiter</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 40, no. 1, pp. 1156-1159, Jan. 2025.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, and Yousu Chen, 
        "<a href="https://ieeexplore.ieee.org/document/10614750">Scalable risk assessment of rare events in power systems with uncertain wind generation and loads</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 40, no. 2, pp. 1374-1388, Mar. 2025.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, 
        "<a href="https://ieeexplore.ieee.org/document/10477536">Data-driven adaptive unscented Kalman filter for time-varying inertia and damping estimation of utility-scale IBRs considering current limiter</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 39, no. 6, pp. 7331-7345, Nov. 2024.
    </li>
    <li>
        Jiahao Liu, Cheng Wang, Junbo Zhao, <span class="author-highlight">Bendong Tan</span>, and Tianshu Bi, 
        "<a href="https://ieeexplore.ieee.org/document/10209245">Simplified transient model of DFIG wind turbine for power system frequency dynamics analysis</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 39, no. 2, pp. 3752-3768, Mar. 2024.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, 
        "<a href="https://ieeexplore.ieee.org/document/10124366">Debiased uncertainty quantification approach for probabilistic transient stability assessment</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 38, no. 5, pp. 4954-4957, Sept. 2023.
    </li>
    <li>
        Maolin Zhu, Hao Liu, Junbo Zhao, <span class="author-highlight">Bendong Tan</span>, Tianshu Bi, and Samson Shenglong Yu, 
        "<a href="https://ieeexplore.ieee.org/document/10105888">Dynamic state estimation for DFIG with unknown inputs based on cubature Kalman filter and adaptive interpolation</a>", 
        <span class="journal-name">Journal of Modern Power Systems and Clean Energy</span>, vol. 11, no. 4, pp. 1086-1099, July 2023.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, and Nan Duan, 
        "<a href="https://ieeexplore.ieee.org/document/10056325">Amortized Bayesian parameter estimation approach for WECC composite load model</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 39, no. 1, pp. 1517-1529, Jan. 2024.
    </li>
    <li>
        Guozhou Zhang, Junbo Zhao, Weihao Hu, Di Cao, <span class="author-highlight">Bendong Tan</span>, Qi Huang, and Zhe Chen, 
        "<a href="https://ieeexplore.ieee.org/document/10005097">A novel data-driven self-tuning SVC additional fractional-order sliding mode controller for transient voltage stability with wind generations</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 38, no. 6, pp. 5755-5767, Nov. 2023.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, and Le Xie, 
        "<a href="https://ieeexplore.ieee.org/document/9996972">Transferable deep kernel emulator for probabilistic load margin assessment with topology changes, uncertain renewable generations and loads</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 38, no. 6, pp. 5740-5754, Nov. 2023.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, 
        "<a href="https://ieeexplore.ieee.org/document/9990924">Data-driven time-varying inertia estimation of inverter-based resources</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 38, no. 2, pp. 1795-1798, March 2023.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao and Marcos Netto, 
        "<a href="https://ieeexplore.ieee.org/document/9926125">A general decentralized dynamic state estimation with synchronous generator magnetic saturation</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 38, no. 1, pp. 960-963, Jan. 2023.
    </li>
    <li>
        Juelin Liu, Zhifang Yang, Junbo Zhao, Juan Yu, <span class="author-highlight">Bendong Tan</span> and Wenyuan Li, 
        "<a href="https://ieeexplore.ieee.org/document/9652094">Explicit data-driven small-signal stability constrained optimal power flow</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 37, no. 5, pp. 3726-3737, Sept. 2022.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Vladimir Terzija and Yingchen Zhang, 
        "<a href="https://www.sciencedirect.com/science/article/pii/S0142061521010693">Decentralized data-driven estimation of generator rotor speed and inertia constant based on adaptive unscented Kalman filter</a>", 
        <span class="journal-name">International Journal of Electrical Power & Energy Systems</span>, Vol.134, May 2022.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Nan Duan, Daniel Adrian Maldonado, Yingchen Zhang, Hongming Zhang, and Mihai Anitescu, 
        "<a href="https://ieeexplore.ieee.org/document/9676646">Distributed frequency divider for power system bus frequency online estimation considering virtual inertia from DFIGs</a>", 
        <span class="journal-name">IEEE Journal on Emerging and Selected Topics in Circuits and Systems</span>, vol. 12, no. 1, pp. 161-171, March 2022.
    </li>
    <li>
        Seyyed Rashid Khazeiynasab, Junbo Zhao, Issa Batarseh and <span class="author-highlight">Bendong Tan</span>, 
        "<a href="https://ieeexplore.ieee.org/document/9525328">Power plant model parameter calibration using conditional variational autoencoder</a>", 
        <span class="journal-name">IEEE Transactions on Power Systems</span>, vol. 37, no. 2, pp. 1642-1652, March 2022.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Marcos Netto, Venkat Krishnan, Vladimir Terzija, and Yingchen Zhang, 
        "<a href="https://www.sciencedirect.com/science/article/pii/S0142061521006013">Power system inertia estimation: review of methods and the impacts of converter-interfaced generations</a>", 
        <span class="journal-name">International Journal of Electrical Power & Energy Systems</span>, Jan 2022. 
        <span class="highlight">Best Journal Paper Award</span>
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Jun Yang, Yuan Liu, Wenjing Liu, Ting Zhou, and Yuanzhang Sun, 
        "Adaptive integrated assessment method for transient stability of power system considering PMU data missing", 
        <span class="journal-name">Automation of Electric Power Systems</span>, vol. 45, no. 23, pp. 68–75, 2021. (in Chinese, EI)
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Jun Yang, Ting Zhou, Xiangpeng Zhan, Yuan Liu, Shengbo Jiang, and Chao Luo, 
        "<a href="https://www.sciencedirect.com/science/article/pii/S0142061520307212">Spatial-temporal adaptive transient stability assessment for power system under missing data</a>", 
        <span class="journal-name">International Journal of Electrical Power & Energy Systems</span>, vol. 123, p. 106237, Dec. 2020.
    </li>
    <li>
        Ting Zhou, Jun Yang, Qiangming Zhou, <span class="author-highlight">Bendong Tan</span>, Yue Zhou, Jian Xu and Yuanzhang Sun, 
        "Power system transient stability assessment based on modified LightGBM", 
        <span class="journal-name">Power System Technology</span>, vol.43, no.6, pp.1931-1940, 2019. (in Chinese, EI)
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Jun Yang, Qiupin Lai, Peiyuan Xie, Jun Li, and Jian Xu, 
        "Data augmentation method for power system transient stability assessment based on improved conditional generative adversarial network", 
        <span class="journal-name">Automation of Electric Power Systems</span>, vol.43, no.1, pp.149-157, 2019. (in Chinese, EI)
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Jun Yang, Yufei Tang, Shengbo Jiang, Peiyuan Xie, and Wen Yuan, 
        "<a href="https://doi.org/10.1109/ACCESS.2019.2923799">A deep imbalanced learning framework for transient stability assessment of power system</a>", 
        <span class="journal-name">IEEE Access</span>, vol. 7, pp. 81759–81769, June 2019.
    </li>
</div>

<!-- -------------------- Conference Papers -------------------- -->

<div class="conference-publications publications">
    <h4>Conference Papers</h4>
    <li>
        Ketian Ye, Junbo Zhao, Mingguo Hong and Slava Maslennikov, <span class="author-highlight">Bendong Tan</span>, and Xiaochuan Luo, 
        "<a href="https://ieeexplore.ieee.org/document/10688568">Power system overloading risk assessment considering topology and renewable uncertainties</a>", 
        in <span class="journal-name">2024 IEEE Power & Energy Society General Meeting (PESGM)</span>, pp. 1-5, 2024. 
        <span class="highlight">Best Paper Award</span>
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Jiangkai Peng, Ningchao Gao, Junbo Zhao, and Jin Tan, 
        "<a href="https://ieeexplore.ieee.org/document/10688692">Comparative study of data-driven area inertia estimation approaches on WECC power systems</a>", 
        in <span class="journal-name">2024 IEEE Power & Energy Society General Meeting (PESGM)</span>, pp. 1-5, 2024.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Daniel Adrian Maldonado, and Jason Philhower, 
        "<a href="https://ieeexplore.ieee.org/document/10252855">Time-varying inertia estimation for inverter-based resources</a>", 
        in <span class="journal-name">2023 IEEE Power & Energy Society General Meeting (PESGM)</span>, pp. 1-5, 2023.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Tong Su, Qiuhua Huang, Yingchen Zhang, and Hongming Zhang, 
        "<a href="https://ieeexplore.ieee.org/abstract/document/9916892">Explainable Bayesian neural network for probabilistic transient stability analysis considering wind energy</a>", 
        in <span class="journal-name">2022 IEEE Power & Energy Society General Meeting (PESGM)</span>, pp. 1-5, 2022. 
        <span class="highlight">Best Paper Award</span>
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Weijia Liu, and Nan Duan, 
        "<a href="https://ieeexplore.ieee.org/document/10003627">Interpretable data-driven probabilistic power system load margin assessment with uncertain renewable energy and loads</a>", 
        in <span class="journal-name">11th International Conference on Innovative Smart Grid Technologies (Asia)</span>, 2022. 
        <span class="highlight">Best Paper Award</span>
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Junbo Zhao, Federico Milano, Qiupin Lai, Yingchen Zhang, and Daniel Adrian Maldonado, 
        "<a href="https://ieeexplore.ieee.org/document/9543055">Extended frequency divider for bus frequency estimation considering virtual inertia from DFIGs</a>", 
        in <span class="journal-name">2021 IEEE PES Innovative Smart Grid Technologies Conference - Latin America (ISGT Latin America)</span>, pp. 1-5, 2021.
    </li>
    <li>
        Bi Liu, Junbo Zhao, Qi Huang, Federico Milano, <span class="author-highlight">Bendong Tan</span> and Weihao Hu, 
        "<a href="https://ieeexplore.ieee.org/document/9637884">Robust nonlinear controller for wind turbine generator drivetrain torsional oscillation under large disturbances</a>", 
        in <span class="journal-name">2021 IEEE Power & Energy Society General Meeting (PESGM)</span>, Washington, DC, USA, 2021. 
        <span class="highlight">Best Paper Award</span>
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Jun Yang, Ting Zhou, Yi Xiao, and Qiangming Zhou, 
        "<a href="https://ieeexplore.ieee.org/document/8905487">A novel temporal feature selection for time-Adaptive transient stability assessment</a>", 
        in <span class="journal-name">2019 IEEE PES Innovative Smart Grid Technologies Europe (ISGT-Europe), Bucharest</span>, Romania, 2019, pp. 1-5.
    </li>
    <li>
        <span class="author-highlight">Bendong Tan</span>, Jun Yang, Xueli Pan, Jun Li, Peiyuan Xie, and Ciling Zeng, 
        "<a href="https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/joe.2017.0651">Representational learning approach for power system transient stability assessment based on convolutional neural network</a>", 
        in <span class="journal-name">The Journal of Engineering</span>, vol. 2017, no. 13, pp. 1847-1850, 2017.
    </li>
</div>


