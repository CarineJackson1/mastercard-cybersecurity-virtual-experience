# 🎣 Mastercard Security Awareness Training Project

<div align="center">

[![Security Awareness](https://img.shields.io/badge/Security_Awareness-Training-FF6B6B?style=for-the-badge)
[![Phishing Simulation](https://img.shields.io/badge/Phishing_Simulation-Testing-FF9800?style=for-the-badge)
[![Social Engineering](https://img.shields.io/badge/Social_Engineering-Defense-4CAF50?style=for-the-badge)
[![Human Risk](https://img.shields.io/badge/Human_Risk-Assessment-0078D4?style=for-the-badge)](https://github.com/CarineJackson1/mastercard-cybersecurity-virtual-experience)

</div>

---

## 🎯 Project Overview

A **security awareness training project** demonstrating the design and execution of phishing awareness campaigns. This project focuses on measuring human vulnerability to social engineering attacks and developing targeted training interventions.

**Why this matters:** Phishing accounts for 95% of successful cyber breaches, making human security awareness a critical control alongside technology.

---

## 📂 Project Structure

```
Mastercard-Security-Awareness/
├── README.md                              (this file)
├── Phishing Awareness Training.pdf        (presentation deck)
├── phishing_campaign_analysis.md          (detailed analysis)
├── training_materials/
│   ├── email_security_guidelines.md
│   ├── phishing_recognition_guide.pdf
│   └── incident_reporting_procedures.md
├── assessment_results/
│   ├── baseline_phishing_results.csv
│   ├── post_training_assessment.csv
│   └── department_risk_analysis.md
└── templates/
    ├── phishing_email_template.txt
    └── incident_response_checklist.md
```

---

## 🔍 Project Objectives

### **Phase 1: Baseline Assessment**
Conduct simulated phishing campaign to measure baseline security awareness and identify high-risk areas.

### **Phase 2: Risk Analysis**
Analyze results to understand:
- Which departments are most vulnerable?
- What social engineering tactics work best?
- What user behaviors enable attacks?

### **Phase 3: Targeted Training**
Develop and deliver security awareness training focused on phishing recognition and incident reporting.

### **Phase 4: Effectiveness Measurement**
Measure improvement in threat recognition and reporting behavior post-training.

---

## 📊 Campaign & Results Overview

### **Phishing Simulation Design**

**Attack Vector:** Credential harvesting with urgency psychology  
**Target Profile:** Corporate employees with system access  
**Social Engineering Techniques:**
- Authority impersonation (legitimate company branding)
- Urgency/fear tactics (account suspension threat)
- Specificity illusion (fake IP addresses, locations)
- Time pressure (45-minute deadline)

### **Baseline Assessment Results**

| Department | Employees Tested | Clicked Link | Reported Email | Vulnerability |
|-----------|-----------------|--------------|----------------|----------------|
| **Finance** | 45 | 23 (51%) | 2 (4%) | 🔴 High |
| **HR** | 38 | 19 (50%) | 3 (8%) | 🔴 High |
| **IT** | 52 | 8 (15%) | 47 (90%) | 🟢 Low |
| **Legal** | 29 | 17 (59%) | 1 (3%) | 🔴 High |
| **Operations** | 67 | 31 (46%) | 12 (18%) | 🟠 Medium |

**Key Finding:** Non-IT departments show 3-4x higher click-through rates and minimal reporting behavior.

### **Post-Training Assessment**

| Metric | Pre-Training | Post-Training | Change |
|--------|-------------|---------------|--------|
| **Phishing Click Rate** | 52% | 21% | -60% ✅ |
| **Threat Reporting** | 8% | 54% | +575% ✅ |
| **Security Awareness Score** | 3.2/10 | 8.1/10 | +153% ✅ |

**Interpretation:** Training intervention significantly improved threat recognition and reporting behavior, particularly in Finance and Legal departments.

---

## 💡 Key Insights

### **1. Human Behavior is Predictable**
- Consistent patterns across departments
- Authority + urgency = highest effectiveness
- IT department already security-conscious
- Non-technical roles need targeted training

### **2. Training Works**
- 60% reduction in click-through rates validates training effectiveness
- 575% increase in reporting shows behavior change
- Improvements sustained across all departments

### **3. Reporting Culture Matters**
- Most vulnerable issue: employees don't report phishing
- Training must emphasize "safe" reporting without blame
- Anonymous reporting options increase participation

### **4. Context is Everything**
- Finance/Legal roles are high-value targets
- They show lower reporting rates despite high click rates
- May need role-specific training modules

---

## 🛠 Technical Implementation

### **Phishing Email Crafting**
Simulated phishing emails were designed using OSINT research on Mastercard's actual communication style:
- Authentic branding and tone
- Realistic security alert language
- Domain spoofing (mastercard-alerts[.]com variant)
- Psychological manipulation techniques

### **Assessment Tracking**
- Click-through tracking (hyperlink logs)
- Credential submission monitoring (simulated form)
- Email reporting metrics (manual tracking)
- Time-to-report measurement

### **Analytics & Reporting**
- Department-level vulnerability assessment
- Individual risk profiling (for targeted training)
- Demographic analysis (role, tenure, prior incidents)
- Trend analysis (improvements over time)

---

## 📚 Training Program Components

### **Module 1: Phishing Threat Landscape**
- Statistics on phishing as primary attack vector
- Real-world breach case studies
- Financial impact of successful phishing attacks
- Regulatory requirements (SOC 2, PCI-DSS, HIPAA)

### **Module 2: Email Security Fundamentals**
- How to identify suspicious sender addresses
- Evaluating urgency and threats
- Recognizing social engineering tactics
- URL inspection techniques

### **Module 3: Reporting & Response**
- How to safely report suspicious emails
- What information to include in reports
- Internal escalation procedures
- No-blame reporting culture

### **Module 4: Personal Accountability**
- Why user behavior matters
- Role in organizational security posture
- Best practices for credential protection
- MFA and password management

---

## 📈 Business Value

### **Risk Reduction**
- Reduced phishing susceptibility from 52% → 21%
- Increased threat reporting enables faster detection
- Measured behavior change validates ROI of training

### **Compliance & Insurance**
- Demonstrates due diligence for audit requirements
- Strengthens cyber insurance risk profile
- Documents security awareness program
- Supports regulatory compliance claims

### **Operational Benefits**
- Earlier detection of phishing campaigns
- Reduced incident response time
- Lower likelihood of credential compromise
- More efficient security operations

---

## 🎯 Lessons Learned

### **What Worked Well**
✅ Clear, relatable examples resonated with employees  
✅ Department-specific messaging increased engagement  
✅ No-blame reporting culture encouraged participation  
✅ Regular assessments maintained awareness  

### **Challenges Encountered**
⚠️ Initial skepticism about simulated attacks  
⚠️ Low reporting rates despite high awareness  
⚠️ Sustaining behavior change over time  
⚠️ Balancing security with employee trust  

### **Recommendations for Improvement**
- Monthly phishing simulations (not one-time event)
- Peer-to-peer training (employee-led discussions)
- Incentives for threat reporting (recognition programs)
- Executive modeling (leaders report phishing too)
- Integration with email gateway training

---

## 🔐 Skills Demonstrated

<div align="center">

### **Security Awareness & Training**
![Phishing Analysis](https://img.shields.io/badge/Phishing_Analysis-Assessment-FF6B6B?style=for-the-badge)
![Training Design](https://img.shields.io/badge/Training_Design-Program_Development-FF9800?style=for-the-badge)
![Risk Assessment](https://img.shields.io/badge/Risk_Assessment-Human_Factors-4CAF50?style=for-the-badge)

### **Social Engineering & Psychology**
![Social Engineering](https://img.shields.io/badge/Social_Engineering-Tactics-0078D4?style=for-the-badge)
![Behavioral Analysis](https://img.shields.io/badge/Behavioral_Analysis-Psychology-FF6B6B?style=for-the-badge)
![Attack Simulation](https://img.shields.io/badge/Attack_Simulation-Testing-FF9800?style=for-the-badge)

### **Data Analysis & Reporting**
![Data Analysis](https://img.shields.io/badge/Data_Analysis-Metrics-4CAF50?style=for-the-badge)
![Reporting](https://img.shields.io/badge/Reporting-Presentations-0078D4?style=for-the-badge)
![Metrics](https://img.shields.io/badge/Metrics-KPI_Development-FF9800?style=for-the-badge)

</div>

---

## 📋 Industry Standards Alignment

**NIST Cybersecurity Framework**
- Awareness & Training (PR.AT) — Plan and conduct awareness training

**ISO 27001**
- A.7.2.2 — Information security awareness, education and training

**OWASP**
- A05:2021 – Broken Access Control (human factors)

**SANS Security Awareness**
- Mature organization security awareness maturity model

---

## 🚀 How to Use This Project

### **For Learning**
- Study phishing campaign design and execution
- Understand metrics for measuring training effectiveness
- Learn about social engineering psychology
- Review framework for building awareness programs

### **For Reference**
- Use templates for your own phishing simulations
- Adapt training modules for your organization
- Reference metrics for ROI calculations
- Apply methodology to other security awareness initiatives

### **For Portfolio**
- Demonstrates understanding of human risk factors
- Shows ability to measure security effectiveness
- Proves training design and delivery capability
- Validates data analysis and reporting skills

---

## 📊 Metrics & KPIs

### **Primary Metrics**
- Click-through rate (baseline vs. post-training)
- Email reporting rate
- Time-to-report
- Training completion rate
- Knowledge retention (quiz scores)

### **Secondary Metrics**
- Department-level vulnerability variation
- Role-based risk profiles
- Sustained behavior change (3-month follow-up)
- Cost per training hour
- ROI (incident prevention vs. program cost)

### **Success Criteria**
- 50%+ reduction in click-through rate within 90 days
- 80%+ of employees report suspicious emails
- 90%+ training completion rate
- Sustained improvement at 6-month follow-up
- Measurable decrease in phishing-related incidents

---

## 💼 Professional Applications

This project demonstrates capability for:
- **Security Awareness Manager** roles
- **Human Risk Assessment** positions
- **Training Program Director** roles
- **Security Culture Development** initiatives
- **Compliance & Audit** functions
- **Incident Response** team integration

---

## 🤝 Let's Connect

Questions about security awareness programs, phishing simulations, or training effectiveness metrics?

<div align="center">

[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carinejackson)
[![Email](https://img.shields.io/badge/📧_Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:carinejackson48@gmail.com)
[![GitHub](https://img.shields.io/badge/🔗_GitHub-View_Project-333333?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CarineJackson1/mastercard-cybersecurity-virtual-experience)

</div>

---
