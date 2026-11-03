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
  padding: 20px 0;
  border-bottom: 1px solid #e5e7eb;
}
.experience-logo-box {
  width: 72px;
  height: 72px;
  min-width: 72px;
  border-radius: 12px;
  border: 1px solid #e5e7eb;
  background-color: #ffffff;
  padding: 6px;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 1px 3px rgba(0,0,0,0.06);
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
  font-size: 1.25rem;
  font-weight: 700;
  color: #1f2937;
}
.experience-company {
  font-weight: 600;
  color: #1a73e8;
  margin-bottom: 6px;
  font-size: 1rem;
}
.experience-meta {
  font-size: 0.85rem;
  color: #6b7280;
  margin-bottom: 10px;
}
.experience-badge {
  display: inline-block;
  background-color: #eff6ff;
  color: #1a73e8;
  font-size: 0.78rem;
  font-weight: 600;
  padding: 2px 8px;
  border-radius: 4px;
  margin-right: 8px;
  border: 1px solid #dbeafe;
}
.experience-bullets {
  margin: 8px 0 0 16px;
  padding: 0;
  color: #374151;
  font-size: 0.95rem;
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

## 🎓 Education

<div class="experience-list">

  <!-- Education: IIT ISM Dhanbad -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/ism_logo.png" alt="IIT ISM Dhanbad Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Integrated Master of Technology (M.Tech) in Mathematics & Computing</h3>
      <div class="experience-company">Indian Institute of Technology (ISM), Dhanbad</div>
      <div class="experience-meta">
        <span class="experience-badge">2023 – Expected May 2028</span>
        <span>📍 Dhanbad, Jharkhand, India</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>Academic Standing:</strong> Current Cumulative GPA: <strong>8.80 / 10.00</strong>.</li>
        <li><strong>Core Focus:</strong> Rigorous curriculum spanning theoretical mathematics (Linear Algebra, Statistical Inference, Probability Theory) combined with core computer science (Data Structures, Algorithms, GPU Computing, OS, DBMS).</li>
        <li><strong>Leadership Roles:</strong> Student Placement Coordinator at Career Development Centre (CDC); Member of Fintech Club.</li>
      </ul>
    </div>
  </div>

</div>

---

## 💼 Work Experience & Internships

<div class="experience-list">

  <!-- Apparent Energy -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/apparent.png" alt="Apparent Energy Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Lead Software Engineer Intern</h3>
      <div class="experience-company">Apparent Energy Solutions Pvt. Ltd.</div>
      <div class="experience-meta">
        <span class="experience-badge">Jan 2026 – Present</span>
        <span>📍 Remote</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>Electrical Grid Digital Twin:</strong> Spearheading the automated mapping and reconstruction of India’s electrical grid infrastructure by integrating computer vision techniques with high-resolution satellite feeds and Google Street View imagery.</li>
        <li><strong>Deep Learning Detection & Segmentation:</strong> Trained and fine-tuned a custom <strong>YOLOv11</strong> model to detect electrical distribution poles from aerial imagery, and engineered hybrid segmentation-detection pipelines to track overhead transmission wires.</li>
        <li><strong>Graph & Spatial Modeling:</strong> Modeled pole-to-pole connectivity and transmission corridors using spatial algorithms and graph analysis to formulate an intelligent, queryable digital twin of nationwide grid topology.</li>
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
        <span class="experience-badge">Aug 2025 – Dec 2025</span>
        <span>📍 Remote</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>AI-Assisted Diagnostic Workflows:</strong> Developed an end-to-end medical assistant pipeline with human-in-the-loop validation, significantly accelerating diagnostic turnaround times for radiology departments.</li>
        <li><strong>Medical Image Segmentation:</strong> Fine-tuned and deployed <strong>MED-SAM 2</strong> for lesion and abnormality segmentation across CT scans and X-rays, achieving <strong>90%+ segmentation extraction accuracy</strong> for downstream clinical diagnosis.</li>
        <li><strong>Multimodal Agentic Reasoning:</strong> Orchestrated reasoning pipelines utilizing <strong>LangChain</strong> and <strong>LangGraph</strong> powered by <strong>Med Gemma 27B</strong> to synthesize structured patient summaries, pathology reports, and treatment plans.</li>
        <li><strong>Document Parsing & Cloud Serving:</strong> Integrated OCR pipelines with Nanonets and Google Cloud Vision APIs to standardize prescriptions and clinical reports. Deployed high-throughput, low-latency inference endpoints on <strong>AWS SageMaker</strong>.</li>
        <li><strong>Context-Aware Clinical Retrieval:</strong> Implemented an <strong>i-MedRAG</strong>-inspired retrieval pipeline generating contextual follow-up diagnostic inquiries, boosting clinical completeness and physician workflow efficiency.</li>
      </ul>
    </div>
  </div>

  <!-- Technod8.ai -->
  <div class="experience-item">
    <div class="experience-logo-box">
      <img src="{{ base_path }}/images/techno8.png" alt="Technod8.ai Logo" />
    </div>
    <div class="experience-content">
      <h3 class="experience-title">Generative AI Intern</h3>
      <div class="experience-company">Technod8 Innovations (Tecnod8.ai)</div>
      <div class="experience-meta">
        <span class="experience-badge">July 2025</span>
        <span>📍 Remote</span>
      </div>
      <ul class="experience-bullets">
        <li><strong>NCIIPC Startup India AI Grand Challenge:</strong> Contributed directly to competitive innovation pipelines by engineering deep-learning document understanding architectures for critical information infrastructure.</li>
        <li><strong>Document Layout Decomposition:</strong> Trained and fine-tuned a custom <strong>YOLOv10</strong> architecture to identify complex multilingual document layout primitives (tables, signatures, headings, paragraphs) and extract precise bounding coordinates for downstream OCR and entity extraction.</li>
      </ul>
    </div>
  </div>

</div>
