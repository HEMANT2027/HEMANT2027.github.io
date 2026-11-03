---
title: "Real-Time Sentiment Dashboard"
excerpt: "A real-time sentiment analysis and alert clustering system using Streamlit and Gemma 1B. Ingests live data streams, infers nuanced sentiment, and clusters negative feedback for instant escalation.<br/><br/>**Tech Stack:** Python, Streamlit, Gemma 1B, Pandas, Hugging Face Transformers<br/><a href='https://github.com/HEMANT2027/Sentiment-Analysis-Dashboard' target='_blank' class='btn btn--primary'><i class='fab fa-github'></i> View on GitHub</a>"
collection: portfolio
date: 2025-07-28
---

{% include base_path %}

## Overview

A high-performance sentiment telemetry and monitoring dashboard designed to help product and operations teams process high-velocity incoming user messages, detect PR emergencies, and spot product defects before they escalate.

## Key Features

* **LLM-Powered In-Flight Analysis**: Integrated Google's **Gemma 1B** parameter open model via Hugging Face to conduct context-aware sentiment classification, sarcasm detection, and sentiment intensity scoring.
* **Negative Feedback Clustering**: Implemented sentence embeddings with DBSCAN density clustering to aggregate incoming negative reviews into distinct incident buckets (e.g., checkout failures, latency spikes).
* **Live Telemetry & Alerts**: Interactive UI powered by **Streamlit** that renders live throughput metrics, polarity breakdown charts, and real-time triggers for support engineers.

## Source Code & Links

* **GitHub Repository:** [https://github.com/HEMANT2027/Sentiment-Analysis-Dashboard](https://github.com/HEMANT2027/Sentiment-Analysis-Dashboard)

