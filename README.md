# HDECO: Hybrid Energy and Cost Optimization using VM Migration in Cloud Datacenters (2022)
Energy and cost-aware VM migration framework for workflow scheduling in heterogeneous cloud datacenters (HDECO, 2022).


## 🔗 DOI
https://doi.org/10.1016/j.comcom.2022.08.006

Published in: Computer Communications (Elsevier)

---

# 🌍 Executive Summary

Cloud datacenters consume massive amounts of:

- Electrical energy  
- Cooling power  
- Infrastructure cost  

Uncontrolled virtual machine (VM) migration and poor workload balancing lead to:

• Increased operational cost  
• Higher carbon emissions  
• SLA degradation  
• Reduced system performance  

HDECO introduces a hybrid energy–cost aware VM migration framework that:

- Classifies workflow inputs  
- Uses intelligent threshold detection (ITD)  
- Optimizes real execution time  
- Minimizes unnecessary VM migrations  

---

# 🚨 Core Problem

Cloud workflow scheduling is:

- NP-Complete  
- Heterogeneous  
- Resource-constrained  
- Energy-sensitive  

Traditional scheduling approaches:

- Focus only on makespan  
- Ignore migration overhead  
- Use static thresholds  
- Overlook real execution time  

HDECO addresses these limitations.

---

# 💡 HDECO Innovation

HDECO integrates:

### 1️⃣ Multi-Level Job Classification
Tasks are grouped into:
- Small  
- Medium  
- Large  

Based on:
- Input size  
- Processing distance  
- Real execution time  

---

### 2️⃣ Intelligent Threshold Detector (ITD)

Dynamic CPU-based threshold:

- Detects overloaded hosts  
- Detects underloaded hosts  
- Prevents unnecessary switch-on/off cycles  
- Reduces idle energy waste  

---

### 3️⃣ Hybrid Objective Function

Fitness function combines:

- Energy consumption  
- Monetary cost  
- Delay time  
- Real execution time  
- Migration count  

This multi-parameter integration improves prediction accuracy.

---

### 4️⃣ Energy-Aware VM Migration Strategy

- First-Fit VM selection  
- Controlled migration from high-load and low-load hosts  
- Reduction of excessive migrations  
- Load-balanced reallocation  

---

# ⚙ Mathematical & Simulation Model

Energy Model:

Energy consumption modeled as function of CPU load percentage.

Simulation Platform:

- CloudSim 3.0.3  
- Heterogeneous physical machines  
- Multiple VM types with hourly cost  

Performance Metrics:

Minimize:
- Total energy consumption  
- Total cost  
- Real execution time  
- Migration count  

---

# 📊 Experimental Results

Compared with ECIB and prior methods:

• Up to 10% energy reduction  
• Approximately 8% cost reduction  
• Reduced number of VM migrations  
• Improved workflow execution time  

Performance improvement increases under:

- Instance-intensive workflows  
- Heterogeneous hosts  
- High-load cloud environments  

---

# 🌱 Sustainability & Green Impact

Datacenters account for a significant portion of global energy consumption.

HDECO contributes to:

- Reduced CO₂ emissions  
- Lower power consumption  
- Improved green cloud operation  
- Sustainable resource management  

---

# 🧠 Real-World Applications

- Scientific workflow scheduling  
- Enterprise cloud orchestration  
- Green datacenter management  
- Energy-aware IaaS platforms  
- Large-scale distributed processing  

---

# 🏗 Framework Workflow

1. Batch job creation  
2. Input clustering  
3. CPU-based ITD threshold detection  
4. Overload/underload host detection  
5. VM selection via first-fit  
6. Controlled migration  
7. Objective function optimization  

---

# 📄 Publication Details

Title:
HDECO: A method for decreasing energy and cost by using virtual machine migration by considering hybrid parameters

Authors:
Arash Ghorbannia Delavar  
Reza Akraminejad  
Sahar Mozafari  

Journal:
Computer Communications  

Year:
2022  

DOI:
10.1016/j.comcom.2022.08.006  

---

# 📚 Citation (APA)

Ghorbannia Delavar, A., Akraminejad, R., & Mozafari, S. (2022). HDECO: A method for decreasing energy and cost by using virtual machine migration by considering hybrid parameters. Computer Communications. https://doi.org/10.1016/j.comcom.2022.08.006

---

# 📚 Citation (BibTeX)

@article{HDECO2022,
  title={HDECO: A method for decreasing energy and cost by using virtual machine migration by considering hybrid parameters},
  author={Ghorbannia Delavar, Arash and Akraminejad, Reza and Mozafari, Sahar},
  journal={Computer Communications},
  year={2022},
  doi={10.1016/j.comcom.2022.08.006}
}

---

# 🏫 Affiliation

Department of Computer Science  
Payame Noor University  
Tehran, Iran  

---

# ⚖ License

This repository is created for academic indexing and research visibility purposes.  
All publication rights belong to the journal publisher.

---

# ⭐ Cloud Optimization Research Line

This work is part of a structured research line focused on:

• Energy-Aware Scheduling  
• VM Migration Optimization  
• Intelligent Threshold Detection  
• Hybrid Cloud Resource Management  
• Sustainable Datacenter Architecture  
