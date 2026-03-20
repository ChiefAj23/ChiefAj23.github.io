---
layout: page
title: Nashville Crime Hotspot Analysis App
description: ML-powered safety analytics and route planning for crime hotspot awareness in Nashville.
img: assets/img/Nashville-Crime-Hotspot-Analysis-App.png
importance: 2
category: Research
---

<p align="justify"> In this project, we present a crime hotspot analysis and safety intelligence application designed for Nashville, Tennessee. The system helps tourists and local residents identify high-risk areas, receive alerts near potentially unsafe zones, and make more informed travel decisions while exploring the city. Built using a modern full-stack architecture with <b>Python</b>, <b>FastAPI</b>, <b>React</b>, and <b>TypeScript</b>, the application combines geospatial analytics, machine learning, and interactive visualization to transform raw public safety data into practical real-world guidance. </p>

<p align="justify"> At the core of the project is a spatial crime analysis pipeline built on publicly available Metro Nashville Police Department 911 call data. We use the <b>DBSCAN</b> clustering algorithm to detect naturally occurring crime hotspots without predefining the number of clusters. Incidents are grouped based on geographic density using a 400-meter radius and minimum incident threshold, allowing the model to distinguish persistent hotspot regions from isolated events. To better reflect real-world severity, we also introduce a weighted <b>risk scoring framework</b> that assigns different importance to violent, property, and low-priority incidents, enabling more meaningful hotspot ranking than simple frequency counting. </p>

<p align="justify"> Beyond hotspot detection, the system incorporates several intelligent analysis modules, including <b>safety score estimation</b>, <b>crime-type filtering</b>, <b>distance-aware hotspot proximity analysis</b>, <b>historical trend exploration</b>, <b>time-of-day crime pattern analysis</b>, <b>nearby safe-place discovery</b>, and <b>weather-aware contextual information</b>. The backend is organized as a set of modular services exposed through FastAPI endpoints, while the frontend provides an interactive map interface, live location tracking, safe route planning, dashboards, and personalized settings. This structure makes the platform scalable, maintainable, and easy to extend for future smart-city or public safety applications. </p>

<p align="justify"> A key contribution of this work is the integration of <b>machine learning-driven hotspot identification</b> with a <b>user-centric safety application layer</b>. Rather than only visualizing crime statistics, the platform translates spatial and temporal crime patterns into actionable insights such as route recommendations, risk-aware navigation, and location-based alerts. The project demonstrates how open civic data, spatial intelligence, and modern web technologies can be combined to create practical public-interest tools that improve situational awareness in urban environments. </p>

Implementation of entire project can be found here: <a href="https://github.com/ChiefAj23/Nashville-Crime-Hotspot-Analysis-App"> Code </a>