---
layout: posts
author_profile: true
permalink: /
classes: wide
---

## About Me {#about}
{::nomarkdown}
<div style="text-align: justify;">
{:/}
---
I am a graduate student pursuing MSc. in Robotics, Systems and Control at ETH Zurich. My interests lie in various aspects of field robotics with a particular focus on perception for robots. I am currently a visiting student researcher at NASA Jet Propulsion Laboratory (JPL) working on traversability mapping for offroad environments supervised by [Dr. Shehryar Khattak](https://www-robotics.jpl.nasa.gov/who-we-are/people/shehryar-khattak/) at JPL and [Prof. Marco Hutter](https://rsl.ethz.ch/the-lab/people/person-detail.MTIxOTEx.TGlzdC8yNDQxLC0xNDI1MTk1NzM1.html) at ETH Zurich. Prior to this I have worked on projects involving Neural implicit SLAM, high speed motion estimation, Collaborative Visual Inertial SLAM and Lidar guided Object detection. I have had the opportunity to work with a diverse range of sensors ranging from dynamic vision sensor (event camera), RGB/RGBD/Stereo cameras to LiDARs and IMUs. I have experience working on different robotc platforms including flying robots (quadcopters, hexacopters), wheeled ground robots (Polaris RZR Dune Buggy, SuperMegaBot, Clearpath Husky UGV) and legged robots (ANYmal C).  

{::nomarkdown}
</div>
{:/}

## Education
---
<div style="display: flex; justify-content: space-between; margin-bottom: -10px;">
  <div style="width: 20%;">
    <p style="margin-bottom: 0;">2021 - Present</p>
  </div>
  <div style="width: 75%;">
     <p style="margin-bottom: 0;"><strong>ETH Zurich, Switzerland</strong><br>Master of Science (MSc.) in Robotics, Systems, and Control</p>
  </div>
</div>
<div style="display: flex; justify-content: space-between; margin-bottom: -10px;">
  <div style="width: 20%;">
    <p style="margin-bottom: 0;">2017 - 2021</p>
  </div>
  <div style="width: 75%;">
     <p style="margin-bottom: 0;"><strong>Indian Institute of Technology Kharagpur, India</strong><br>Bachelor of Technology (B.Tech.) in Mechanical Engineer with Micro-specialisation in Entrepreneurship and Innovation</p>
  </div>
</div>

## Internships
---
<div style="display: flex; justify-content: space-between; margin-bottom: -10px;">
  <div style="width: 20%;">
    <p style="margin-bottom: 0;">Sep 2023  - Present </p>
  </div>
  <div style="width: 75%;">
     <p style="margin-bottom: 0;"><strong>Perception Systems (347J), NASA Jet Propulsion Laboratory, Pasadena, USA</strong><br>Master's Thesis <br><b>Project:</b> Bird's Eye View Learning for Traversability Mapping of Offroad Environments</p>
  </div>
</div>
<div style="display: flex; justify-content: space-between; margin-bottom: -10px;">
  <div style="width: 20%;">
    <p style="margin-bottom: 0;">Sep 2022 - Feb 2023 </p>
  </div>
  <div style="width: 75%;">
     <p style="margin-bottom: 0;"><strong>Sony RDC, Zurich. Switzerland</strong><br>Computer Vision Intern<br><b>Project:</b> High Speed Motion Estimation using Event-based Vision</p>
  </div>
</div>
<div style="display: flex; justify-content: space-between; margin-bottom: -10px;">
  <div style="width: 20%;">
    <p style="margin-bottom: 0;">May 2020  - Apr 2021 </p>
  </div>
  <div style="width: 75%;">
     <p style="margin-bottom: 0;"><strong>Robot Perception Group, Max Planck Institute for Intelligent Systems, Germany</strong><br>Bachelor's Thesis (Remote)<br><b>Project:</b> Mapping of Archaeological Sites using UAVs</p>
  </div>
</div>

## Teaching
---

<div style="display: flex; justify-content: space-between; margin-bottom: -10px;">

  <div style="width: 20%;">
    <p style="margin-bottom: 0;">Mar 2023 - Jul 2023 </p>
  </div>
  <div style="width: 75%;">
    <p style="margin-bottom: 0;"><strong>Teaching Assistant, Robotics Summer School, ETH Zurich</strong><br>Teaching assistant for the annual <a href="https://robotics-summerschool.ethz.ch/" target="_blank">Robotics Summer School</a> organized by RobotX</p>
  </div>
</div>



## Research {#publications}
---

<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">

  <!-- Left side with image -->
  <div style="width: 35%;">
    <img src="../assets/images/covins_1.png" alt="COVINS-G expriment" style="width: 100%; height: auto;margin-bottom: 10px;">

    <img src="../assets/images/covins_2.png" alt="COVINS-G architecture" style="width: 100%; height: auto;">
  </div>

  <!-- Right side with details -->
    <!-- Right side with details -->
  <div style="width: 75%; margin-left: 10px;">

    <!-- Title -->
    <h4 style="margin: 0;">COVINS-G: A Generic Back-end for Collaborative Visual-Inertial SLAM</h4>

    <!-- Authors -->
    <p style="margin: 0; font-size: 14px;"><i><u>Manthan Patel</u>, Marco Karrer, Philipp Bänninger, Margarita Chli</i></p>

    <!-- Conference Name -->
    <p style="margin: 0; font-size: 14px;">International Conference on Robotics and Automation (ICRA), 2023</p>

    <!-- Abstract -->
    <p style="margin: 0; text-align: justify; font-size: 16px;">

    Collaborative SLAM is essential for multi-robot systems, enabling co-localization in a common reference frame crucial for coordination. Traditionally, a centralized architecture uses agents with onboard Visual-Inertial Odometry (VIO), communicating data to a central server for map fusion and optimization. However, this approach's flexibility is constrained by the VIO front-end choice. Our work introduces COVINS-G, a generalized back-end building on <a href="https://arxiv.org/abs/2108.05756" target="_blank">COVINS</a>, making the server compatible with any VIO front-end, including off-the-shelf cameras like Realsense T265. The COVINS-G back-end deploys a multi-camera relative pose estimation algorithm for computing the loop-closure constraints allowing the system to work purely on 2D image data. In the experimental evaluation, we show on-par accuracy with state-of-the-art multi-session and collaborative SLAM systems, while demonstrating the flexibility and generality of our approach by employing different front-ends onboard collaborating agents within the same mission. The COVINS-G codebase, including a generalized ROS-based front-end wrapper, is open-sourced.

    </p>
    

    <!-- Links -->
    <p style="margin: 0; font-size: 16px;">
  <a href="https://arxiv.org/abs/2301.07147.pdf" style="text-decoration: none; color: #0366d6;">[Arxiv]</a> |
  <a href="https://arxiv.org/abs/2301.07147" style="text-decoration: none; color: #0366d6;">[Paper]</a> |
  <a href="https://youtu.be/xPjRJjKUmi0?si=Zua5ouuUjN_Bg0uK" style="text-decoration: none; color: #0366d6;">[Presentation]</a> |
  <a href="https://youtu.be/FoJfXCfaYDw?si=XWyvDxcUUuPHoZSZ" style="text-decoration: none; color: #0366d6;">[Experiments]</a> |
  <a href="https://github.com/VIS4ROB-lab/covins" style="text-decoration: none; color: #0366d6;">[GitHub]</a>
  </p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 20px;">

  <!-- Left side with image -->
  <div style="width: 35%;">
    <img src="../assets/images/ssrr_1.png" alt="cover photo" style="width: 100%; height: auto;">
  </div>

  <!-- Right side with details -->
    <!-- Right side with details -->
  <div style="width: 75%; margin-left: 10px;">

    <!-- Title -->
    <h4 style="margin: 0;">LiDAR-guided object search and detection in Subterranean Environments</h4>

    <!-- Authors -->
    <p style="margin: 0; font-size: 14px;"><i><u>Manthan Patel</u>, Gabriel Waibel, Shehryar Khattak, Marco Hutter</i></p>

    <!-- Conference Name -->
    <p style="margin: 0; font-size: 14px;">IEEE International Symposium on Safety, Security and Rescue Robotics (SSRR) 2022</p>

    <!-- Abstract -->
    <p style="margin: 0; text-align: justify; font-size: 16px;">

    Detecting objects of interest, such as human survivors, safety equipment, and structure access points, is critical to any search-and-rescue operation. Robots deployed for such time-sensitive efforts rely on their onboard sensors to perform their designated tasks. However, as disaster response operations are predominantly conducted under perceptually degraded conditions, commonly utilized sensors such as visual cameras and LiDARs suffer in terms of performance degradation. In response, this work presents a method that utilizes the complementary nature of vision and depth sensors to leverage multi-modal information to aid object detection at longer distances. In particular, depth and intensity values from sparse LiDAR returns are used to generate proposals for objects present in the environment. These proposals are then utilized by a Pan-Tilt-Zoom (PTZ) camera system to perform a directed search by adjusting its pose and zoom level for performing object detection and classification in difficult environments. The proposed work has been thoroughly verified using an ANYmal quadruped robot in underground settings and on datasets collected during the DARPA Subterranean Challenge finals.

    </p>
    <!-- Links -->
    <p style="margin: 0; font-size: 16px;">
  <a href="https://arxiv.org/abs/2210.14997" style="text-decoration: none; color: #0366d6;">[Arxiv]</a> |
  <a href="https://arxiv.org/pdf/2210.14997.pdf" style="text-decoration: none; color: #0366d6;">[Paper]</a>
  </p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 20px;">

  <!-- Left side with image -->
  <div style="width: 35%;">
    <img src="../assets/images/archeo_1.png" alt="cover photo" style="width: 100%; height: auto;">
  </div>

  <!-- Right side with details -->
    <!-- Right side with details -->
  <div style="width: 75%; margin-left: 10px;">

    <!-- Title -->
    <h4 style="margin: 0;">Collaborative Mapping of Archaeological Sites using multiple UAVs</h4>

    <!-- Authors -->
    <p style="margin: 0; font-size: 14px;"><i><u>Manthan Patel</u>, Aditya Bandopadhyay, Aamir Ahmad</i></p>

    <!-- Conference Name -->
    <p style="margin: 0; font-size: 14px;">International Conference on Intelligent Autonomous Systems (IAS 16), 2021</p>

    <!-- Abstract -->
    <p style="margin: 0; text-align: justify; font-size: 16px;">

    UAVs have found an important application in archaeological mapping. Majority of the existing methods employ an offline method to process the data collected from an archaeological site. They are time-consuming and computationally expensive. In this paper, we present a multi-UAV approach for faster mapping of archaeological sites. Employing a team of UAVs not only reduces the mapping time by distribution of coverage area, but also improves the map accuracy by exchange of information. Through extensive experiments in a realistic simulation (AirSim), we demonstrate the advantages of using a collaborative mapping approach. We then create the first 3D map of the Sadra Fort, a 15th Century Fort located in Gujarat, India using our proposed method. Additionally, we present two novel archaeological datasets recorded in both simulation and real-world to facilitate research on collaborative archaeological mapping. For the benefit of the community, we make the AirSim simulation environment, as well as the datasets publicly available.

    </p>
    <!-- Links -->
    <p style="margin: 0; font-size: 16px;">
  <a href="https://arxiv.org/abs/2105.07644" style="text-decoration: none; color: #0366d6;">[Arxiv]</a> |
  <a href="https://arxiv.org/abs/2105.07644.pdf" style="text-decoration: none; color: #0366d6;">[Paper]</a> |
  <a href="https://patelmanthan.in/castle-ruins-airsim/" style="text-decoration: none; color: #0366d6;">[Webpage]</a>
  <a href="https://patelmanthan.in/wp-content/uploads/2020/07/final_BTP_17ME10078.pdf" style="text-decoration: none; color: #0366d6;">[Extended Thesis]</a>

  </p>
  </div>
</div>


## Course Projects {#projects}
---
<div style="margin-top: 0px; margin-bottom: 20px; text-align: justify;">

  <strong>3D Vision:</strong> Learning-based methods for the task of reassembly of 3D fractured objects
  <a href="https://github.com/alexandrumeterez/3d-fracture-reassembly" style="text-decoration: none; color: #0366d6;">[Link]</a>
  <br>

  <strong>Deep Learning for Autonomous Driving:</strong> Projects on Multi-task Learning (Semantic Segmentation, Monocular Depth Estimation) and 3D Object Detection using LiDAR data
  <br>

  <strong>Vision Algorithms for Mobile Robotics:</strong> Implemented a Visual Odometry pipeline from scratch in MATLAB along with local Bundle Adjustment and evaluated the pipeline on 3 different datasets.
  <a href="https://github.com/manthan99/VAMR_project" style="text-decoration: none; color: #0366d6;">[Link]</a>
  <br>

  <strong>Planning and Decision Making for Autonomous Robots:</strong> Implemented an RRT-based global planner and MPC-based trajectory tracking for navigation of a spaceship in simulation.
  <a href="https://github.com/shobhit55/padm4ar_final21" style="text-decoration: none; color: #0366d6;">[Link]</a>
  <br>

  <strong>Probabilistic Artificial Intelligence:</strong> Projects on: 1) Bayesian Neural Network for classification on MNIST dataset, 2) Constrained Bayesian Optimization using Expected Improvement as the Acquisition function, 3) Advantage Actor Critic method for learning policy to land spaceship in a simulation environment
</div>


## Awards and Achievements {#awards}
---
<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">

  <!-- Left side with month and year -->
  <div style="width: 15%;">
    <p style="margin: 0; font-size: 14px;">Sep 2021 - Mar 2023</p>
  </div>
  <!-- Right side with title and description -->
  <div style="width: 80%; margin-left: 10px;">
    <!-- Title -->
    <h3 style="margin: 0; font-size: 16px;">ETH D-Mavt Scholarship</h3>
    <!-- Description -->
    <p style="margin: 0; font-size: 14px;">Full, merit-based scholarship awarded to less than 2.5% of all D-Mavt Masters students at ETH Zurich</p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
  <!-- Left side with month and year -->
  <div style="width: 15%;">
    <p style="margin: 0; font-size: 14px;">Dec 2021</p>
  </div>
  <!-- Right side with title and description -->
  <div style="width: 80%; margin-left: 10px;">
    <!-- Title -->
    <h3 style="margin: 0; font-size: 16px;">Dr. B C Roy Memorial Gold Medal</h3>
    <!-- Description -->
    <p style="margin: 0; font-size: 14px;">Adjudged best all-rounder (Academic and extra-curriculars) among all graduating (1400) B.Tech students at IIT Kharagpur</p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
  <!-- Left side with month and year -->
  <div style="width: 15%;">
    <p style="margin: 0; font-size: 14px;">Dec 2021</p>
  </div>
  <!-- Right side with title and description -->
  <div style="width: 80%; margin-left: 10px;">
    <!-- Title -->
    <h3 style="margin: 0; font-size: 16px;">Institute Silver Medal (Academic Rank 1)</h3>
    <!-- Description -->
    <p style="margin: 0; font-size: 14px;">Highest Cumulative Grade in Mechanical Engineering among all graduating B.Tech students at IIT Kharagpur</p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
  <!-- Left side with month and year -->
  <div style="width: 15%;">
    <p style="margin: 0; font-size: 14px;">Apr 2020 - Dec 2020</p>
  </div>
  <!-- Right side with title and description -->
  <div style="width: 80%; margin-left: 10px;">
    <!-- Title -->
    <h3 style="margin: 0; font-size: 16px;">DAAD WISE Scholarship</h3>
    <!-- Description -->
    <p style="margin: 0; font-size: 14px;">Recipient of the prestigious scholarship to perform a research internship at a German Research Institute (MPI-IS)</p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
  <!-- Left side with month and year -->
  <div style="width: 15%;">
    <p style="margin: 0; font-size: 14px;">2018 - 2020</p>
  </div>
  <!-- Right side with title and description -->
  <div style="width: 80%; margin-left: 10px;">
    <!-- Title -->
    <h3 style="margin: 0; font-size: 16px;">Inter-IIT Tech Meet 7.0, 8.0 and 9.0</h3>
    <!-- Description -->
    <p style="margin: 0; font-size: 14px;">Represented IIT Kharagpur three consecutive times in Inter-IIT Tech events for problem statements invovling autonomous agricultural robot, multi-UAV search mission and UAV-based Sub-terranean exploration mission. <br>Results: Second Runner Up (2018), First Runner Up (2019) and Winner (2020)</p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
  <!-- Left side with month and year -->
  <div style="width: 15%;">
    <p style="margin: 0; font-size: 14px;">Oct 2020</p>
  </div>
  <!-- Right side with title and description -->
  <div style="width: 80%; margin-left: 10px;">
    <!-- Title -->
    <h3 style="margin: 0; font-size: 16px;">OP Jindal Engineering and Management Scholarship</h3>
    <!-- Description -->
    <p style="margin: 0; font-size: 14px;">Recipient of the scholarship awarded to 100 students across India for academic and leadership excellence</p>
  </div>
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
  <!-- Left side with month and year -->
  <div style="width: 15%;">
    <p style="margin: 0; font-size: 14px;">Jun 2019</p>
  </div>
  <!-- Right side with title and description -->
  <div style="width: 80%; margin-left: 10px;">
    <!-- Title -->
    <h3 style="margin: 0; font-size: 16px;">27th Intelligent Ground Vehicle Competition (IGVC) </h3>
    <!-- Description -->
    <p style="margin: 0; font-size: 14px;">Secured the second position in the AutoNav Challenge among 40+ participating international teams at Michigan, USA</p>
  </div>
</div>