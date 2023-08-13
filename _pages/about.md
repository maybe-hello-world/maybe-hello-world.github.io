---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Welcome

I'm a Ph.D. student at the University of California, Santa Barbara, working under the supervision of Prof. Arpit Gupta in the Systems and Networking Lab.

My current research lies at the intersection of networking, security, and machine learning. Specifically, I
am interested in developing credible ML-based artifacts for different networking and security problems,
and democratizing network research by creating public measurement infrastructures and tools.

I'm leading _netunicorn_ and _PINOT_ projects aimed to simplify developing trustworthy ML solutions in networking 
and make real-world data available for everyone (see [PINOT](https://pinot.cs.ucsb.edu/) and [netunicorn](https://netunicorn.cs.ucsb.edu)).

I also researched a Machine Learning models credibility in the Networking area, exploring vulnerabilities and problems in 
published existing solutions and how to fix them using Explainable AI methods (see [TrusteeML](https://trusteeml.github.io/)).


## Interests

* Machine Learning in Networking
  * \+ ML-based performance inference
  * \+ Explainability and robustness
  * \+ Reinforcement Learning
* Public Measurements and Infrastructures in Networking
* Hobby research interests: Deep Space Network and extra-terrestrial issues in networking

## Selected Publications
For detailed information on publications see: [Publications](https://maybe-hello-world.github.io/publications/)

<ol>
{% for post in site.publications reversed | where: "selected", true %}
  {% include archive-single-paper-custom.html %}
{% endfor %}
</ol>

## Invited Talks
 * netUnicorn: A Unified and Modular Data-Collection Platform for Developing Credible ML Models for Networking  
   _UC Santa Barbara (05/22)_, _The University of Chicago (10/22)_, _ACM SIGMETRICS Workshop on Measurements for Self-Driving Networks (06/22)_

## Awards
 * _UCSB CS Department Summer Fellowship Award, 2023_

## Education
 
* Ph.D. in Computer Science -- University of California, Santa Barbara
  *2021 - now, with Prof. Arpit Gupta*
* M.S. in Computer Science -- Peter the Great Saint-Petersburg Polytechnical University  
  *(Thesis: applying natural gradient descent to reinforcement learning algorithm)*
* B.S. in Computer Science -- Peter the Great Saint-Petersburg Polytechnical University  
  *(Thesis: creating music with generative adversarial networks)*

## Working experience

* On-Device ML Model Researcher at *Huawei Russia* (Mar. 2020 - Sep. 2021)
* Junior Reinforcement Learning Researcher at *JetBrains Research* (Oct. 2019 - Jun. 2020)
* Python tutor at *Higher School of Engineering* (Sep. 2018 - Sep. 2020)

## Hackathons & Challenges

* **Junction 2018** -- runner-up (in-team) in QOCO challenge  
  *([PlanPlanner](https://projects.hackjunction.com/projects/junction-2018/5bf841e36a75040015931a95) -- redirecting air traffic with graph algorithms)*
* **World-IT-Planet 2018** -- winner (solo) of the international stage in Cloud Systems track
* **BioHack 2018** -- Special award (in-team) by Institute of Bioinformatics  
  *(predicting 3D cell structure with ML)*
* **Junction 2017** -- winners (in-team) of track "Robots, Learning machines"  
  *([Mirror](https://devpost.com/software/mirr-wait-for-it-or) -- applied ML to Pepper robot to make him copy all our movements)*
* **World-IT-Planet 2017** -- winner (solo) of the international stage in Cloud Systems track  
* **Make your university 20.35** -- winners (in-team)  
  *(recommender system for people looking for a job)*

## Certifications

* Microsoft Certified: Azure AI Engineer Associate, *Microsoft*
* Certified Associate at Python programming, *OpenEDG*
* Microsoft Certified Solutions Expert: Cloud Platform and Infrastructure, *Microsoft*
* Microsoft Certified Solutions Associate: Windows Server 2016, *Microsoft*
* Microsoft Certified Professional, *Microsoft*
* Cisco CCNA Instructor, *Cisco*
* Cisco Certified Network Associate Routing and Switching, *Cisco*
* Huawei Certified Network Associate Storage, *Huawei*

## Thanks for your attention

Have any questions? Feel free to contact me in any way convenient for you.
