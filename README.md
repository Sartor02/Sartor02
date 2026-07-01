<!-- HEADER DINAMICO -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3&height=250&section=header&text=Alessandro%20Sartore&fontSize=60&desc=Computer%20Vision%20%7C%20Edge%20AI%20%7C%20Full%20Stack&descAlignY=75&descSize=20&animation=twinkling" alt="Alessandro Sartore Banner" width="100%">
</div>

# Hello! 👋 I'm Alessandro

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=3382ed&background=00000000&center=false&vCenter=false&width=435&lines=Computer+Vision+%26+Edge+AI+Dev;Full+Stack+Developer;AI+Systems+MSc+Student)](https://git.io/typing-svg)

<!-- SEZIONE BADGE SOCIAL -->
<p align="center">
  <a href="https://www.linkedin.com/in/alessandro-sartore-b506302b7/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="mailto:alessandrosartore02@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
  </a>
</p>

---

## 👨‍💻 About Me

Hi! I’m **Alessandro Sartore**, a MSc student in Artificial Intelligence Systems at the University of Trento, with a strong background in Computer Science and a focus on **Computer Vision and Edge AI**. I love bridging the gap between theoretical research and practical, high-performance industrial applications.

* 🔭 **Currently working at:** [VIDEAM SRL](https://videam.it/) as a Computer Vision & Edge AI Developer.
* 📈 **Academic focus:** Artificial Intelligence, Edge Computing, and Optimization.
* 🏋️ **Beyond the code:** I’m a fitness enthusiast who enjoys diving into papers about hypertrophy and nutrition. When I'm not training, I’m listening to **Twenty One Pilots** or practicing the piano.
* ⚡ **Fun fact:** I treat my code optimizations with the same discipline I apply to my training sessions: efficient, robust, and always improving!

---

## 📈 Badges

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api/streak/?username=Sartor02&theme=dark&show_icons=true" alt="GitHub Stats" />
  <a href="https://www.codewars.com/users/Sartor02">
    <img src="https://www.codewars.com/users/Sartor02/badges/large" alt="Codewars Badge"/>
  </a>
</p>

---

## 🛠️ Skills & Tools

<p align="center">
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

---

## 🗂️ Project Portfolio

### 🧠 Artificial Intelligence & Computer Vision
*   [AI Video Detection: Generalizing to SOTA Generators](#-ai-video-detection-generalizing-to-sota-generators)
*   [Proto-CLIP with Generalized vMF Loss](#-proto-clip-with-generalized-vmf-loss)
*   [Face Blurring & Detection Analysis](#-face-blurring--detection-analysis)
*   [Autonomous Software Agents](#-autonomous-software-agents)

### 🌐 Full-Stack Web Development & SaaS
*   [Schönblick Bellavista - Alpine Hotel Web Experience](#️-schönblick-bellavista---alpine-hotel-web-experience)
*   [Schönblick Reservation Manager (RAG-Enabled)](#️-schönblick-reservation-manager-rag-enabled)
*   [ScorlenTicket - Theatrical Event Booking Platform](#️-scorlenticket---theatrical-event-booking-platform)
*   [ScorlenTicket - Database Management Dashboard](#️-scorlenticket---database-management-dashboard)

### 🦀 Edge AI & Embedded Systems
*   [BlueCrabNet - Edge AI Invasive Species Detection](#-bluecrabnet---edge-ai-invasive-species-detection)

### ⚙️ Algorithms & Data Analysis
*   [Bachelor's Thesis: Multi-Agent Path Finding (MAPF) Analysis](#-bachelors-thesis-multi-agent-path-finding-mapf-analysis)

---

## 🚀 Featured Projects

### 🤖 AI Video Detection: Generalizing to SOTA Generators
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> A systematic research project and deep learning pipeline designed to detect artificially generated videos from State-of-the-Art (SOTA) models, such as OpenAI Sora and Pyramid Flow. It leverages 3D Vision Transformer (3D-ViT) architectures to identify temporal inconsistencies when spatial details are too photorealistic to trust. Is the video below real or fake? This project aims to answer that question with high accuracy.

<div align="center">
  <img src="sources/aiDetection/fireworks.gif" alt="AI Video Detection Preview" width="100%">
</div>
<br>

**👨‍💻 What I did**
I developed a Multi-Scale Temporal architecture to bridge the generalization gap toward unseen generators. By analyzing video clips at different frame rates, I focused the model on capturing both high-frequency flickering and long-term dynamic inconsistencies, achieving a 97.53% accuracy on SOTA test sets.

**✨ Key Features**
*   **Multi-Scale Temporal Sampling:** Samples clips at 4, 8, and 16 frames to successfully generalize across different video generation models.
*   **Wavelet Blending:** Implemented Discrete Wavelet Transform (DWT) to swap high-frequency components between real and fake videos, creating "Clean Fakes" to force the model to learn semantic motion rather than simple compression shortcuts.
*   **Explainability:** Conducted Stationary Wavelet Transform (SWT) analysis to uncover how the energy profiles of sophisticated fakes mimic real videos in mid-frequency bands.

**🛠️ What I used**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

**🔗 Links**
*   [💻 Source Code](https://github.com/sartor02/ai_video_detection)

---

### 🧠 Proto-CLIP with Generalized vMF Loss
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> A Deep Learning project investigating base-to-novel generalization on the Oxford Flowers102 dataset. This project improves class separation on the hypersphere by implementing a prototype-based classification head with a von Mises-Fisher (vMF) loss formulation, integrated with a frozen CLIP backbone.

<div align="center">
  <img src="sources/clip/clip00.png" alt="Proto-CLIP Preview" width="100%">
</div>
<br>

**👨‍💻 What I did**
I worked on the end-to-end reimplementation of Proto-CLIP, introducing a prototype-dispersion regularizer and a confidence-based rejection mechanism. My focus was on improving the Base-Novel trade-off, enabling the model to fall back to zero-shot CLIP when uncertain about Novel classes.

**✨ Key Features**
*   **vMF Spherical Loss:** Replaced standard Euclidean distances with temperature-scaled cosine similarities modeled on the von Mises-Fisher distribution.
*   **Inference-Time Rejection:** Implemented class-specific confidence thresholds estimated on training data, allowing a fallback to zero-shot CLIP for low-confidence inputs.
*   **Ablation Studies:** Conducted targeted experiments to evaluate the impact of Mix-Up augmentation and prototype-dispersion regularizers on the harmonic mean.
*   **Mathematical Modeling:** Utilized the Bhattacharyya distance coefficient to quantify class overlap on the hypersphere.

**🛠️ What I used**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![CLIP](https://img.shields.io/badge/OpenAI_CLIP-74aa9c?style=for-the-badge&logo=openai&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

**🔗 Links**
*   [📓 Jupyter Notebook](sources/Proto-CLIP.ipynb)
*   [📖 ArXiv Reference: Proto-CLIP](https://arxiv.org/abs/2307.03073)

---

### 👤 Face Blurring & Detection Analysis
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> A Python-based computer vision project designed to detect faces in images and videos, applying various blurring effects (Gaussian, Median, and Pixelation) for privacy protection and GDPR compliance. 

<div align="center">
  <img src="sources/blur/blur.gif" alt="Face Blurring Preview" width="50%">
</div>
<br>

**👨‍💻 What I did**
I conducted a comprehensive benchmarking study comparing the classic Viola-Jones algorithm with the modern YOLO architecture. I compiled OpenCV 3.4 from source to custom-train a Viola-Jones cascade classifier and evaluated both models on the WIDER FACE dataset to measure precision, recall, IoU, and inference speed. 

**✨ Key Features**
*   **Algorithm Benchmarking:** Analyzed the trade-off between the fast execution of Viola-Jones and the high accuracy of YOLO in complex environments.
*   **Custom Model Training:** Successfully trained a custom Haar cascade classifier from scratch to detect faces.
*   **Privacy Filters:** Implemented multiple anonymization techniques, including natural-looking Gaussian blur and high-security Median blur.
*   **Interactive Pipeline:** Developed a Jupyter Notebook providing a step-by-step guide to loading models and applying real-time video blurring.

**🛠️ What I used**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

**🔗 Links**
*   [💻 Source Code](https://github.com/Sartor02/Face_Blurring_Project)

---

### 🤖 Autonomous Software Agents
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> This project was developed for the Autonomous Software Agents course at the University of Trento and implements autonomous agents using the Belief-Desire-Intention (BDI) model. The agents operate within a simulated Deliveroo.js environment to efficiently pick up and deliver parcels.

<div align="center">
<table>
<tr>
<td>
<img src="sources/autonomusAgents/single_agent.gif" alt="Single Agent Preview" width="400">
</td>
<td>
<img src="sources/autonomusAgents/multi_agent.gif" alt="Multi-Agent Preview" width="400">
</td>
</tr>
</table>
</div>
<br>

**👨‍💻 What I did**
I collaborated to build both a standalone agent and a multi-agent system. For the single agent, I worked on the logic to independently explore the environment, update beliefs, and make decisions. For the multi-agent system, I helped implement coordination strategies allowing two agents to share information, divide tasks, and complete deliveries effectively.

**✨ Key Features**
*   **BDI Architecture:** Developed a system that allows agents to perceive their environment, form goals, and dynamically plan actions.
*   **Multi-Agent Coordination:** Implemented communication handlers and area managers for task division and handover coordination.
*   **Advanced Planning:** Integrated a PDDL planner and custom pathfinding logic to optimize parcel selection and delivery strategies.

**🛠️ What I used**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node JS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PDDL](https://img.shields.io/badge/PDDL-005F8F?style=for-the-badge&logo=prolog&logoColor=white)

**🔗 Links**
*   [💻 Source Code](https://github.com/Sartor02/Autonomous_Software_Agents)

---

### 🏔️ Schönblick Bellavista - Alpine Hotel Web Experience
![Status](https://img.shields.io/badge/Status-In_Progress-orange?style=for-the-badge)

**🎯 What it is**
> A modern, responsive web platform developed for *Schönblick Bellavista*, a historic Alpine hotel and restaurant located at 2,060 meters in Val Martello, Italy. The website showcases their unique mountain location, room accommodations, and South Tyrolean culinary offerings, while streamlining digital booking inquiries across multiple languages.

<div align="center">
  <img src="sources/schoenblick/schoenblick00.png" alt="Schönblick Bellavista Preview" width="100%">
</div>
<br>

<div align="center">
  <img src="sources/schoenblick/schoenblick01.png" width="49%">
  <img src="sources/schoenblick/schoenblick02.png" width="49%">
  <br>
  <img src="sources/schoenblick/schoenblick03.png" width="49%">
  <img src="sources/schoenblick/schoenblick04.png" width="49%">
</div>
<br>

**👨‍💻 What I did**
I built the entire web experience from the ground up, creating a multilingual, accessible interface. I implemented a robust backend architecture to handle dynamic API integrations, automated email workflows, and cloud-based image storage. I am also currently working on integrating physical IoT hardware to provide real-time views of the Alpine landscape.

**✨ Key Features**
*   **Multilingual Support:** Fully internationalized (i18n) to support English, German, and Italian, catering to the hotel's diverse Alpine clientele.
*   **Dynamic Social Feed:** Integrated the Instagram Graph API to automatically fetch and display the hotel's live social media feed.
*   **Cloud Image Management:** Utilizes Cloudflare R2 buckets for high-performance, optimized image serving.
*   **Automated Communication:** Configured Resend for fast, reliable email delivery for inquiries and booking requests.
*   **Modern UI/UX:** Modular and accessible interface crafted with Chakra UI.

**🛠️ What I used**
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Chakra UI](https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)
![Resend](https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white)

**🚧 Still in progress**
*   **Booking System:** Implementing a backend service to store and manage reservations in a **MongoDB** database.
*   **Alpine Live View:** Connecting a **Raspberry Pi** with a camera to the server to provide users with a live view of the Val Martello landscape directly on the website.

**🔗 Links**
*   [🌍 Live Demo](https://www.hug-the-mountains.com/en/schonblick)

---

### 🗓️ Schönblick Reservation Manager (RAG-Enabled)
![Status](https://img.shields.io/badge/Status-In_Progress-orange?style=for-the-badge)

**🎯 What it is**
> An intelligent administrative dashboard built for *Schönblick Bellavista* to visualize and manage booking reservations. It features a RAG (Retrieval-Augmented Generation) system, allowing hotel hosts to query their reservation database using natural language to quickly find specific guest data or booking trends.
<br>

**👨‍💻 What I did**
I am developing a full-stack system that connects a responsive calendar interface with a secure backend. I implemented a RAG pipeline that indexes MongoDB reservation data, enabling the hotel staff to perform complex searches and gain insights from their bookings through an AI-powered conversational interface.

**✨ Key Features**
*   **Intelligent RAG Search:** Leverages LLMs and vector search on MongoDB to allow hosts to ask questions like: *"How many guests are arriving next weekend?"* or *"Show me all bookings for the Junior Suite in August."*
*   **Dynamic Reservation Management:** A complete CRUD interface for adding, updating, and removing reservations with real-time calendar synchronization.
*   **Secure Role-Based Access:** Protected by a secure authentication layer, ensuring that sensitive guest data is accessible only to authorized hotel staff.
*   **Intuitive Visualization:** Calendar-based UI to provide an instant overview of room occupancy and upcoming events.

**🛠️ What I used**
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Node JS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![AI/RAG](https://img.shields.io/badge/RAG_AI-6C3483?style=for-the-badge&logo=openai&logoColor=white)

**🚧 Still in progress**
*   Refining the vector embeddings for more precise natural language queries on reservation notes and guest preferences.

---

### 🎟️ ScorlenTicket - Theatrical Event Booking Platform
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> A comprehensive full-stack ticketing platform created for theatrical events in the Trentino region (specifically Fai della Paganella and Trento). It provides a seamless flow for users to browse events, select their exact seats, process secure payments, and receive digital tickets via email.

<div align="center">
  <img src="sources/scorlenticket/scorlenticket00.png" width="49%">
  <img src="sources/scorlenticket/scorlenticket01.png" width="49%">
  <br>
  <img src="sources/scorlenticket/scorlenticket02.png" width="49%">
  <img src="sources/scorlenticket/scorlenticket03.png" width="49%">
</div>
<br>

**👨‍💻 What I did**
I built both the frontend and backend architectures from scratch. I designed an interactive user interface for seat selection and managed the complex backend logic required to handle real-time database updates for bookings, secure financial transactions, and automated ticket dispatching.

**✨ Key Features**
*   **Interactive Seat Selection:** Developed a dynamic frontend interface allowing users to visually pick their preferred seats for theater layouts.
*   **Secure Payments:** Integrated the Stripe API to handle safe and reliable checkout processes and financial transactions.
*   **Real-time Reservation Management:** Utilized MongoDB to store and manage event details, seat availability, and user bookings effectively.
*   **Automated Ticketing:** Implemented a backend mailing service using standard Gmail integration to automatically generate and dispatch tickets to users upon successful payment.

**🛠️ What I used**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Chakra UI](https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white)
![Node JS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=Stripe&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

**🔗 Links**
*   [🌍 Live Demo](https://scorlenticket.it)

---

### 🎛️ ScorlenTicket - Database Management Dashboard
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> An administrative web portal designed to manage the backend operations for *ScorlenTicket*. It provides a secure interface for administrators to oversee theatrical events, manage venue layouts, track real-time bookings, and perform comprehensive CRUD operations on the database.

<div align="center">
  <img src="sources/dbManager/dbManager01.png" width="49%">
  <img src="sources/dbManager/dbManager02.png" width="49%">
  <br>
  <img src="sources/dbManager/dbManager03.png" width="49%">
  <img src="sources/dbManager/dbManager04.png" width="49%">
</div>
<br>

**👨‍💻 What I did**
I built a secure, role-based administrative dashboard that acts as the control center for the ticketing platform. I implemented user authentication to ensure protected access and developed intuitive management tools to handle event lifecycle, seating configuration, and reservation oversight.

**✨ Key Features**
*   **Secure Admin Authentication:** Implemented login protection to restrict backend access to authorized personnel only.
*   **Full CRUD Functionality:** Developed interfaces to create, read, update, and delete event data, seat availability, and venue information.
*   **Reservation Oversight:** Provided a centralized view to monitor, manage, and edit bookings stored in MongoDB.
*   **Intuitive UI/UX:** Built with React and Chakra UI to ensure a clean, efficient workflow for administrators handling high volumes of data.

**🛠️ What I used**
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Chakra UI](https://img.shields.io/badge/chakra-%234ED1C5.svg?style=for-the-badge&logo=chakraui&logoColor=white)
![Node JS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

**🔗 Links**
*   [🌍 Live Demo](https://database-manager-two.vercel.app/)

---

### 🦀 BlueCrabNet - Edge AI Invasive Species Detection
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> An award-winning solution designed to combat the spread of invasive crab species. The project provides an end-to-end platform featuring real-time detection, intuitive reporting, and data visualization.

<div align="center">
<table>
<tr>
<td colspan="2">
<img src="sources/crabs/crabs01.png" width="49%">
<img src="sources/crabs/crabs02.png" width="49%">
</td>
</tr>
<tr>
<td>
<img src="sources/crabs/crabs.gif" width="70%" height="50%">
</td>
</tr>
</table>
</div>
<br>

**👨‍💻 What I did**
I developed the complete product stack, covering both frontend and backend development. My primary technical focus was on architecting the **Computer Vision pipeline** and optimizing deep learning models for deployment on edge hardware.

**✨ Key Features**
*   **End-to-End Stack:** Engineered the full application, including the user-facing interface, backend services, and database integration.
*   **Edge AI Pipeline:** Designed and implemented a high-performance vision pipeline using **YOLO-Nano**, optimized for real-time inference on resource-constrained edge devices.
*   **Hardware-Aware Optimization:** Applied model quantization and technical optimizations to maximize throughput while maintaining a minimal memory footprint.
*   **Recognition & Analytics:** Delivered a robust system capable of real-time recognition with high accuracy, ensuring reliable field data.
*   **Award-Winning Innovation:** Recognized as a winner at the **VenetoStars 2026** competition for technological excellence in environmental monitoring.

**🛠️ What I used**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![Edge AI](https://img.shields.io/badge/Edge_AI-FF0000?style=for-the-badge&logo=cpu&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

**🔗 Links**
*   [🌍 Project Website](https://bluecrabnet-project.netlify.app/)
*   [🏆 VenetoStars 2026 Winners](https://venetostars.com/#winners-2026)

---

### 🎓 Bachelor's Thesis: Multi-Agent Path Finding (MAPF) Analysis
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

**🎯 What it is**
> A comprehensive study and benchmarking of state-of-the-art Multi-Agent Path Finding algorithms (such as CBS, ICR, ICTS, and $X^*$), applied to a real-world industrial warehouse scenario to optimize collision-free routing for autonomous agents.


**👨‍💻 What I did**
I integrated the advanced $X^*$ algorithm into the university's Multi-Agent Open Framework (MAOF) using C++. I then designed and executed an extensive testing pipeline to compare its performance—analyzing memory usage, execution time, and success rate—against other algorithms, automating the data extraction and visualization with Python.

**✨ Key Features**
*   **Algorithm Integration:** Implemented the Windowed Anytime Multiagent Planning Framework (WAMPF) and $X^*$ solver in an existing C++ codebase, managing complex data structures and memory states.
*   **Industrial Benchmarking:** Evaluated algorithm performance on a topological graph representing a real robotic warehouse with hundreds of nodes and varying numbers of agents.
*   **Automated Data Pipeline:** Built Python scripts to parse experimental data from Excel files and generate survival and scatter plots for an in-depth comparative analysis.

**🛠️ What I used**
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

**🔗 Links**
*   [📄 Multi Agent Open Framework](https://gitlab.com/chaff800/MAOF)
*   [💻 Thesis](sources/BSc_thesis.pdf)

---

<div align="center">
  <h3>Thanks for stopping by! 🚀</h3>
  <p>I'm always open to discussing new projects, AI research, or simply chatting about fitness and music.</p>
  <p><i>"Optimization is the key to both code and training."</i></p>
  <p><b>Alessandro Sartore</b></p>
  <a href="mailto:alessandrosartore02@gmail.com">📫 Let's connect!</a>
</div>