---
layout: archive
title: "Education & Experience"
permalink: /experience/
author_profile: true
redirect_from:
  - /experiences/
  - /experiences.html
---

{% include base_path %}

<style>
.experience-item {
  display: flex;
  align-items: flex-start;
  gap: 20px;
  padding: 22px 0;
  border-bottom: 1px solid #e5e7eb;
}
.experience-logo-box {
  width: 68px;
  height: 68px;
  min-width: 68px;
  border-radius: 8px;
  border: 1px solid #e5e7eb;
  background-color: #ffffff;
  padding: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.experience-logo-box img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
.experience-content {
  flex: 1;
}
.experience-title {
  margin: 0 0 4px 0;
  font-size: 1.15rem;
  font-weight: 700;
  color: #111827;
}
.experience-company {
  font-weight: 600;
  color: #1a73e8;
  margin-bottom: 6px;
  font-size: 0.95rem;
}
.experience-meta {
  font-size: 0.85rem;
  color: #6b7280;
  margin-bottom: 10px;
}
.experience-badge {
  display: inline-block;
  background-color: #f3f4f6;
  color: #374151;
  font-size: 0.76rem;
  font-weight: 600;
  padding: 2px 8px;
  border-radius: 4px;
  margin-right: 8px;
  border: 1px solid #e5e7eb;
}
.experience-bullets {
  margin: 8px 0 0 16px;
  padding: 0;
  color: #374151;
  font-size: 0.93rem;
  line-height: 1.6;
}
.experience-bullets li {
  margin-bottom: 6px;
}
@media (max-width: 600px) {
  .experience-item {
    flex-direction: column;
    gap: 12px;
  }
}
</style>

## Education

<div class="experience-list">

  <!-- Education: IIT ISM Dhanbad -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/ism_logo.png" alt="IIT ISM Dhanbad Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Integrated Master of Technology (M.Tech) in Mathematics and Computing</h3>
      <div class="experience-company">Indian Institute of Technology (ISM), Dhanbad</div>
      <div class="experience-meta">
        <span class="experience-badge">2023 – Expected May 2028</span>
        <span>Dhanbad, Jharkhand, India</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>Academic Standing:</strong> Cumulative GPA: <strong>8.90 / 10.00</strong>.</li>
        <li><strong>Core Focus:</strong> Rigorous curriculum spanning theoretical mathematics (Linear Algebra, Statistical Inference, Probability Theory) combined with core computer science (Data Structures, Algorithms, GPU Computing, Operating Systems, Database Management Systems).</li>
        <li><strong>Positions:</strong> Student Placement Coordinator at Career Development Centre (CDC); Member of Fintech Club.</li>
      </ul>
    </div>
  </div>

</div>

---

## Work Experience

<div class="experience-list">

  <!-- Apparent Energy - Role 2 -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/apparent.png" alt="Apparent Energy Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Software Engineer Intern — Agentic MCP & Retrieval Systems</h3>
      <div class="experience-company">Apparent Energy Solutions Pvt. Ltd.</div>
      <div class="experience-meta">
        <span class="experience-badge">April 2026 – September 2026</span>
        <span>Remote</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>Agentic MCP Infrastructure:</strong> Architected and deployed a production FastMCP server integrating 16+ autonomous tools, enabling multi-step agentic workflows and cutting token overhead by approximately 40% through one-shot query bundling.</li>
        <li><strong>Deterministic RAG Retrieval:</strong> Engineered a schema-aware database retrieval pipeline (<code>describe_table</code> &rarr; <code>query_database</code>) featuring deterministic fallback paths, 30s timeout guards, and a 48-case test suite to eliminate SQL hallucinations.</li>
        <li><strong>LLM Evaluations & Benchmarking:</strong> Designed rigorous evaluation frameworks benchmarked against ground-truth database states to systematically track prompt stability, tool selection accuracy, and contextual grounding across multi-step execution traces.</li>
      </ul>
    </div>
  </div>

  <!-- Apparent Energy - Role 1 -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/apparent.png" alt="Apparent Energy Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Software Engineer Intern — AI & Computer Vision</h3>
      <div class="experience-company">Apparent Energy Solutions Pvt. Ltd.</div>
      <div class="experience-meta">
        <span class="experience-badge">January 2026 – March 2026</span>
        <span>Remote</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>High-Throughput Vision Pipelines:</strong> Orchestrated computer vision pipelines ingesting Google Street View and multi-spectral satellite imagery using a TensorRT-optimized <strong>YOLOv11</strong> model for transmission pole detection and hybrid wire segmentation.</li>
        <li><strong>Geospatial Topology Modeling:</strong> Formulated graph-theoretic network algorithms with GeoPandas and PostGIS to model pole-to-pole connectivity, constructing a geospatial digital twin of India's electrical transmission topology.</li>
      </ul>
    </div>
  </div>

  <!-- Aeroqube Inc -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/aeroqube.png" alt="Aeroqube Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Software Engineering Intern</h3>
      <div class="experience-company">Aeroqube Inc.</div>
      <div class="experience-meta">
        <span class="experience-badge">August 2025 – December 2025</span>
        <span>Remote</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>Clinical Decision Workflows:</strong> Developed an AI-assisted medical pipeline with human-in-the-loop verification to reduce diagnostic turnaround times.</li>
        <li><strong>Medical Image Segmentation:</strong> Applied <strong>MED-SAM 2</strong> for lesion and abnormality segmentation on CT scans and X-rays, achieving over 90% extraction accuracy for downstream diagnosis.</li>
        <li><strong>Multimodal Agentic Systems:</strong> Orchestrated reasoning pipelines using <strong>LangChain</strong> and <strong>LangGraph</strong> with <strong>Med Gemma 27B</strong> to synthesize structured diagnostic summaries and treatment outlines.</li>
        <li><strong>Document Processing and Cloud Serving:</strong> Integrated OCR pipelines with Nanonets and Google Cloud Vision APIs to standardize prescriptions and clinical reports. Deployed low-latency inference endpoints on <strong>AWS SageMaker</strong>.</li>
        <li><strong>Contextual Clinical Retrieval:</strong> Implemented an <strong>i-MedRAG</strong>-inspired retrieval pipeline to generate context-aware follow-up clinical inquiries, improving diagnostic completeness.</li>
      </ul>
    </div>
  </div>

  <!-- Technod8.ai -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/techno8.png" alt="Technod8 Innovations Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Generative AI Intern</h3>
      <div class="experience-company">Technod8 Innovations (Tecnod8.ai)</div>
      <div class="experience-meta">
        <span class="experience-badge">July 2025</span>
        <span>Remote</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>NCIIPC Startup India AI Grand Challenge:</strong> Contributed to the competition pipeline by developing computer vision models for complex document understanding in critical information infrastructure.</li>
        <li><strong>Document Layout Decomposition:</strong> Trained and fine-tuned a <strong>YOLOv10</strong> model to identify document layout primitives and extract bounding box coordinates for downstream OCR and parsing tasks.</li>
      </ul>
    </div>
  </div>

</div>
