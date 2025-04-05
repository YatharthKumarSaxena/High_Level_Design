# 🏗️ Welcome to the High Level Design (HLD) Repository!
> **I'm the README.md file of this folder, here to guide you step-by-step!** 🚀

---

## 📁 Table of Contents
- [📖 Introduction](#-introduction)
- [🧠 Folder Structure](#-folder-structure)
- [📚 HLD Projects Overview](#-hld-projects-overview)
- [🛠️ Architectural Highlights](#-architectural-highlights)
- [📈 Scalability & Infrastructure](#-scalability--infrastructure)
- [📑 What Makes This Repo Unique?](#-what-makes-this-repo-unique)
- [🎯 Final Takeaway](#-final-takeaway)

---

## 📖 **Introduction**
This repository is my curated collection of High-Level Design (HLD) solutions to popular real-world system design problems. These designs were created as part of my advanced learning journey in system architecture, focusing on breaking down complex applications into scalable, performant, and modular components.

I’ve individually worked on each of these problems and prepared a PDF that reflects my design choices, trade-offs, and component interactions in a large-scale distributed environment.

---

## 🧠 **Folder Structure**
This folder contains **7 design PDFs** – each representing a unique system's High Level Design.

📄 `Web Crawaler Design.pdf`  
> A scalable architecture for crawling and indexing the internet.

📄 `Design Uber (Ride Sharing App).pdf`  
> Real-time matching, GPS tracking, and load balancing for ride-booking.

📄 `Design Online Chatting Application (Whatsapp, Messanger etc.).pdf`  
> Chat service with message queues, storage, and end-to-end delivery guarantees.

📄 `Design An Online Streaming Application.pdf`  
> Adaptive bitrate streaming, CDNs, caching strategies for video platforms.

📄 `Design LinkedIn Application.pdf`  
> Profile graph design, connection recommendations, news feed scaling.

📄 `Design Truecaller Application.pdf`  
> Real-time spam detection, caller identification, and contact sync.

📄 `Design Zomato Swiggy Application.pdf`  
> Order placement, delivery routing, restaurant sync and real-time tracking.

Each folder contains just a single `.pdf` file capturing the HLD details.

---

## 📚 **HLD Projects Overview**
Each design solution follows a structured format:
- **Problem Statement**
- **High-Level Goals**
- **System Requirements (Functional & Non-functional)**
- **Prioritisation**
- **Infrastructure Estimation**
- **Component Identification**
- **Final Design**

This sequence mirrors the actual process followed in industry-level HLD discussions and reviews.

---

## 🛠️ **Architectural Highlights**
Across the designs, I’ve applied:
- **Microservices Architecture** with decoupled services  
- **Service Oriented Architecture (SOA)** for modular and interoperable components  
- **Load Balancers** for traffic distribution  
- **Message Queues** like Kafka for async operations  
- **Zookeeper** for distributed coordination and service discovery  
- **Database Sharding & Replication** strategies  
- **CDNs & Caching** for low-latency content delivery  
- **APIs** that follow RESTful patterns  
- **Rate Limiting** and **Security layers**  

---

## 📈 **Scalability & Infrastructure**
A core part of every design is infrastructure planning:
- Estimating **QPS (queries per second)**
- **Storage calculations** (message count, media size, daily ingestion)
- **Redundancy & Failover mechanisms**
- Use of **Master-slave DB setups**, **Read Replicas**
- **Horizontal scaling** and **Stateless services**

Every diagram reflects scale-aware decisions with clarity.

---

## 📑 **What Makes This Repo Unique?**
- All content is **self-authored** after deep research and brainstorming.  
- Designs are presented in **PDF format** — easy to read, structured, and visual.  
- **Diagrams and workflows** are crafted using 🛠️ **Draw.io**, ensuring clarity and precision in component representation.  
- Focused purely on **High Level Design** — no coding, no low-level principles here.  
- Reflects understanding from multiple system design resources, compiled with my personal touch.

---

## 🎯 **Final Takeaway**
This repository stands as a **testament to my understanding of scalable system design**.  
Each document helped me:
- Build component-first thinking  
- Understand real-world constraints  
- Develop a design-first mindset  
- Prepare confidently for system design interviews  

These aren't just diagrams — they are architectural blueprints shaped by curiosity, learning, and persistence.

---
