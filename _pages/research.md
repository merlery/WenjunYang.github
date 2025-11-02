---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Current Research Projects

### CorrelaPriv: Advanced Differential Privacy Framework for Correlated Data
**September 2022 - Present** | *Independent Research, University of Washington*

Developing a comprehensive differential privacy framework that addresses the unique challenges of correlated data in IoT and distributed systems.

#### Project Overview
Data correlation presents significant challenges for traditional differential privacy mechanisms. When data points are interdependent, adding noise to achieve privacy can either fail to provide adequate protection or excessively degrade data utility. CorrelaPriv addresses this fundamental challenge through innovative approaches.

#### Key Innovations

**Edge Computing Architecture**  
Unlike traditional centralized approaches, CorrelaPriv implements privacy protection at the data source using edge computing. This architecture:
- Reduces data transmission overhead
- Provides privacy guarantees before data leaves local devices
- Enables scalable privacy protection in large IoT networks
- Minimizes attack surface by processing sensitive data locally

**MIC-DP Framework**  
The Mutual Information Coefficient-based Differential Privacy (MIC-DP) framework:
- Quantifies correlation strength between data points using mutual information
- Adaptively adjusts noise injection based on correlation structure
- Maintains formal privacy guarantees (ε-differential privacy)
- Optimizes the privacy-utility trade-off through intelligent noise calibration

**Data Normalization Strategy**  
To handle heterogeneous data in networked environments:
- Normalizes data while preserving privacy requirements
- Maintains consistency across distributed nodes
- Ensures uniform privacy protection regardless of data scale
- Enables meaningful comparisons across different data sources

**Laplace Mechanism Optimization**  
Applies the Laplace mechanism with novel optimizations:
- Controlled randomness injection based on data correlation
- Dynamic sensitivity calculation for networked data
- Optimal noise distribution to balance privacy and utility
- Theoretical guarantees on both privacy protection and data quality

#### Research Outcomes

This work has produced significant academic contributions:

1. **MIC-DP Framework** - Accepted in *IEEE Transactions on Privacy* (2025)
2. **Participatory AI Framework** - Presented at *2025 ACM CHI Workshop*
3. **ULDP Optimization Method** - Published at *2024 IEEE AIIoT Congress*

#### Impact and Applications

The CorrelaPriv framework has potential applications in:
- Smart city infrastructure monitoring
- Healthcare data sharing networks
- Financial transaction systems
- Social network analysis
- Industrial IoT deployments

---

## Past Research Projects

### StreetSmarter: Navigation-Based Smart Parking System
**April 2019 - June 2019** | *Group Leader, University of Washington Tacoma*

Winner of 1st Prize at the 2019 University of Washington Tacoma Annual Hackathon, sponsored and judged by the Microsoft Azure Team.

#### Project Description
StreetSmarter addresses urban parking challenges by providing real-time navigation to the nearest available parking spot, reducing time spent searching for parking and decreasing traffic congestion.

#### System Architecture

**Hardware Components**
- Raspberry Pi controllers for each parking section
- Ultrasonic and infrared sensors for occupancy detection
- Network communication modules for real-time data transmission

**Backend Infrastructure**
- Python Flask web framework for API development
- SQLite database for parking space state management
- Real-time data processing pipeline
- RESTful API for mobile client communication

**Cloud Integration**
- IBM Watson cloud server for scalability
- Real-time synchronization across multiple parking locations
- Analytics dashboard for parking utilization patterns

**Frontend Application**
- Mobile-responsive web interface
- Real-time parking availability visualization
- Turn-by-turn navigation to available spots
- Historical data and predictions for parking availability

#### Technical Highlights
- Achieved 95%+ accuracy in occupancy detection
- Sub-second latency in status updates
- Scalable architecture supporting hundreds of parking spaces
- Cost-effective implementation using off-the-shelf components

#### Recognition
This project demonstrated the practical application of IoT technologies in solving real-world urban challenges and was recognized for its innovation, technical execution, and potential societal impact.

---

### High-Definition Video Image Mosaics
**2016 - 2017** | *Research Assistant, University of Washington*

Developed an adaptive H-SIFT algorithm for real-time high-definition video image mosaicing.

#### Research Contributions
- Improved feature detection accuracy in high-resolution video streams
- Reduced computational complexity for real-time processing
- Enhanced robustness to lighting variations and motion blur
- Published findings at ICMIA 2017

---

## Research Interests

My research spans multiple areas within computer science, with a focus on practical solutions to privacy and efficiency challenges:

### Primary Areas
- **Differential Privacy**: Theory and applications in real-world systems
- **Internet of Things**: Edge computing, sensor networks, distributed processing
- **Distributed Systems**: Scalable architectures, resource optimization
- **Privacy-Preserving Machine Learning**: Federated learning, secure computation

### Emerging Interests
- **Participatory AI**: Democratic decision-making with privacy guarantees
- **Trustworthy AI**: Transparency, fairness, and accountability in AI systems
- **Sustainable Computing**: Energy-efficient algorithms and green computing

---

## Collaboration Opportunities

I am actively seeking collaborations in:
- Privacy-preserving data analysis for IoT applications
- Edge computing architectures for smart cities
- Differential privacy implementations in real-world systems
- Participatory approaches to AI governance

If you're interested in collaborating or discussing research ideas, please [get in touch](/contact/).

---

## Funding and Support

My research has been supported by:
- University of Washington Graduates Merit Scholarship
- Carwein-Andrews Award
- University of Washington research facilities and resources
