---
layout: archive
title: Overview
permalink: /research/
author_profile: true
---

<h2><strong>Localization <i>(2022-Present)</i></strong></h2>

<ul>
    <li> UAV-aided indoor localization for emergency applications
        <ul>
            <li> Drones as first responders or locating first responders </li>
            <li> Cramér–Rao lower bound (CRLB) based analyses by considering various system parameters. </li>
            <li> Algorithm development to meet CRLB: Two-Stage Weighted Projection (TS-WPM), Reformulated IPPM. </li>
        </ul>
	<strong><i>Resulted Publications</i></strong>: <a href="https://arxiv.org/abs/2502.19354v1">Low-Complexity TS-WPM</a>, <a href="https://ieeexplore.ieee.org/document/10632801">Analytical Framework + Reformulated IPPM</a>, <a href="https://ieeexplore.ieee.org/document/10139944">CRLB Sensitivity Analysis</a> <br>
	<strong><i>Collaborators</i></strong>: Prof. Harpreet S. Dhillon and Prof. R. Michael Buehrer
    </li>
    <li> NTN-based 6G localization
        <ul>
            <li> Feasibility of developing a positioning infrastructure complementary/potential replacement to GNSS. </li>
            <li> Identified prospective study items for NTN-based accurate positioning in 6G: Multi-LEO positioning, GNSS + LEO positioning. </li>
            <li> Design insights for LEO-based NTN positioning: LEO constellation, navigation signaling, initial acquisition, precise positioning. </li>
        </ul>
	<strong><i>Resulted Publications</i></strong>: <a href="https://arxiv.org/abs/2410.18301">LEO Positioning Design Insights</a>, <a href="https://ieeexplore.ieee.org/document/10355106">Study Items for NTN-based 6G Localization</a> <br>
	<strong><i>Collaborators</i></strong>: Prof. Harpreet S. Dhillon, Prof. R. Michael Buehrer, and Dr. Chiranjib Saha
    </li>
    <li> 3GPP-compliant simulation frameworks to assess the positioning performance. </li>
</ul>

<h2><strong>ORAN ULPI Architectures <i>(Summer 2023)</i></strong></h2>

Analysis of Performance Differences in ORAN ULPI Proposed Architectures
<ul>
    <li> Developed an uplink multi-user MIMO link level simulator (LLS) leveraging 5G toolbox in MATLAB. </li>
    <li> Investigated proposed uplink performance improvement (ULPI) architectures compliant to ORAN 7-2x. </li> 
    <li> LLS Features: Channel estimation, equalization with modular granularity, MU-MIMO, hybrid ARQ, antenna array, CDL channel model, and evaluation metrics (sum throughput and post-processing SINR). </li>
</ul>
<strong><i>Collaborators</i></strong>: Dr. Serdar Ozen, Dr. Rapeepat Ratasuk, and Mark Cudak

<h2><strong>RAN Intelligent Controller (RIC) <i>(2021-2022)</i></strong></h2>

Developed a system framework to enable real-time RIC functionality.
<ul>
    <li> Developed scheduling algorithms and enabled the wireless system (srsRAN) to support simultaneous connections from multiple users. </li>
    <li> Facilitated the collection of scheduling weights from the RIC and efficient resource allocation for the connected users. </li>
</ul>
<strong><i>Resulted Publications</i></strong>: <a href="https://dl.acm.org/doi/abs/10.1145/3498361.3538787">Real-Time RIC</a> <br>
<strong><i>Resulted Patents</i></strong>: <a href="https://patents.google.com/patent/US20240267794A1/en">Google Patents</a> <br>
<strong><i>Collaborators</i></strong>: Prof. Srinivas G Shakkottai, Dr. Woo-Hyun Ko, Ujwal Dinesha, Dr. G. Venkata Siva Santosh, Dr. Dinesh Bharadia, Raini Y Wu, Ushasi Ghosh

<h2><strong>System Level Simulator (SLS) <i>(2018-2021)</i></strong></h2>

Developed a 3GPP-compliant downlink and uplink SLS for design validation of massive MIMO beamforming and scheduling solutions.
<ul>
    <li> SLS Features: FD-MIMO Channel Model, Antenna Array, Different Numerologies, Flexible Slot Formats, CSI Feedback, Traffic Modeling, Proportional Fair Scheduler, SU/MU-MIMO Multiplexing, MU-MIMO User Pairing, Precoding, Hybrid ARQ, Outer Loop Rate Control, and Uplink Power Control. </li>
    <li> Conducted channel model and throughput calibration aligned with 3GPP. </li>
    <li> Devised an innovative scheduler capable of efficiently managing hundreds of users, supporting both SU-MIMO and MU-MIMO. </li>
    <li> Developed novel user pairing algorithms to spatially multiplex users for downlink MU-MIMO transmission. </li>
    <li> Designed and validated beamforming algorithms to enhance downlink control channel capacity in 4G systems. </li>
    <li> Designed receiver beamforming algorithms for the uplink to reduce computational complexity and hardware cost for receivers. </li>
    <li> Proposed uplink coverage enhancements for extremely large cells in 5G NR. </li>
    <li> Proposed port signaling for reference signals as a means to mitigate inter-cell interference. </li>
    <li> Self-Organizing Networks (SON):
        <ul>
            <li> Implemented SON functionality to monitor and control RAN parameters. </li>
            <li> SON Features: Configuring cell-specific parameters such as transmit power, antenna pattern, boresight, downtilt, etc., flexible eNB locations, multiple eNBs, intra-inter frequency handover, and collecting key metrics (RSRP, SINR, CQI, etc.). </li>
        </ul>
    </li>
</ul>
<strong><i>Resulted Publications</i></strong>: <a href="https://ieeexplore.ieee.org/document/9027449">Enhancing DL PDCCH Capacity</a>, <a href="https://www.sciencedirect.com/science/article/abs/pii/S1570870520307034">Beamformed PDCCH</a>, <a href="https://jwcn-eurasipjournals.springeropen.com/articles/10.1186/s13638-022-02133-3">UL Coverage Enhancements</a><br>
<strong><i>Resulted Patents</i></strong>: <a href="https://patents.google.com/?q=WiSig+Networks&inventor=Harish+Kumar+Dureppagari&oq=inventor:(Harish+Kumar+Dureppagari)">Google Patents</a>, <a href="https://www.freepatentsonline.com/result.html?sort=relevance&srch=top&query_txt=Harish+Kumar+Dureppagari%2C+WiSig+Networks&submit=&patents_us=on">FPO Link</a><br>
<strong><i>Collaborators</i></strong>: Dr. Pavan Reddy Manne, Prof. Kiran Kuchi, Dr. SaiDhiraj Amuru, G. Koteswara Rao, and Dr. M. Sibgath Ali Khan

<h2><strong>Structural MIMO for 6G</strong></h2>

Structural MIMO (S-MIMO) to overcome practical limitations of current 5G MU-MIMO systems and enhance network capacity.  
<ul>
    <li> Highly directional beams associated with each antenna port/panel to maximize coverage and improve spectral efficiency. </li>
    <li> Three-dimensional structural arrangements of multiple antenna panels to enable full coverage in both azimuth and elevation. </li>
    <li> Joint baseband processing across multiple antenna panels, incorporating TDD reciprocity calibration, MU-MIMO precoding in the downlink, and joint uplink signal processing. </li>
</ul>
<strong><i>Resulted Publications</i></strong>: <a href="https://ieeexplore.ieee.org/document/10419340">Massive MIMO with Circular Antenna Array</a>, <a href="https://ieeexplore.ieee.org/document/10857324">Outdoor Massive MIMO</a>, <a href="https://ieeexplore.ieee.org/abstract/document/10772838">OTFDM & Structural MIMO</a> <br>
<strong><i>Collaborators</i></strong>: Spandan Bisoyi, P Muralimohan, Dr. Pavan Reddy Manne, Dr. SaiDhiraj Amuru, and Prof. Kiran Kuchi
