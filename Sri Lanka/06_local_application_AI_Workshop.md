<!--
author: Hannes Tegelbeckers
email: hannes.tegelbeckers@ovgu.de
version: 0.0.1
language: en
narrator: US English Female
comment: ASSET Project Presentation for Sri Lankan Policymakers
link: https://raw.githubusercontent.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/refs/heads/main/ASSET_basic.css

@style
.sector-card {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 2rem;
    margin: 1rem;
    border-radius: 15px;
    box-shadow: 0 8px 32px rgba(0,0,0,0.3);
    transition: transform 0.3s ease;
}

.sector-card:hover {
    transform: translateY(-5px);
}

.ai-tool-demo {
    background: #f8f9fa;
    border: 2px solid #007bff;
    border-radius: 10px;
    padding: 1.5rem;
    margin: 1rem 0;
}

.quiz-interactive {
    background: linear-gradient(45deg, #ff6b6b, #ffa726);
    color: white;
    padding: 1rem;
    border-radius: 10px;
    margin: 1rem 0;
}

.resource-link {
    background: #28a745;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    text-decoration: none;
    display: inline-block;
    margin: 0.25rem;
    transition: all 0.3s ease;
}

.resource-link:hover {
    background: #218838;
    transform: scale(1.05);
}

.glass-effect {
    background: rgba(255, 255, 255, 0.1);
    border: 1px solid rgba(255,255,255,0.3);
    backdrop-filter: blur(10px);
    padding: 1.5em;
    border-radius: 20px;
    color: #004e92;
    font-weight: bold;
    box-shadow: 0 4px 20px rgba(0,0,0,0.2);
}

.elegant-box {
    background: linear-gradient(to right, #d0eaff, #f0faff);
    padding: 2em;
    border-radius: 20px;
    color: #2e4d1b;
    font-weight: bold;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
}
@end

@customQuiz
[[...]]
<script>
"@0" == btoa( "@input".trim().toLowerCase() )
</script>
@end

@aiDemo: <div class="ai-tool-demo">**AI Demo:** @0<br>**Tool:** @1<br>**Try it:** [Click here](@2)</div>

@sectorCard: <div class="sector-card">**@0**<br>@1</div>

@resourceLink: <a href="@1" class="resource-link" target="_blank">@0</a>
-->

<svg xmlns='http://www.w3.org/2000/svg' width='1100' height='400' viewBox='0 0 800 450'>
  <!-- Background -->
  <rect width='800' height='450' fill='#1A237E' />
  
  <!-- White rounded rectangle container -->
  <rect x='50' y='50' width='700' height='350' rx='20' fill='white' />
  
  <!-- Title -->
  <text x='400' y='130' font-family='Segoe UI, Arial, sans-serif' font-size='50' font-weight='bold' text-anchor='middle' fill='#1A237E'>
    "ASSET: AI for Skills, Sustainability & Training"
  </text>
  
  <!-- Subtitle -->
  <text x='400' y='180' font-family='Segoe UI, Arial, sans-serif' font-size='24' font-weight='bold' text-anchor='middle' fill='#3949AB'>
    UNESCO-UNEVOC Initiative in TVET
  </text>

  <!-- Additional presenter info -->
  <text x='400' y='220' font-family='Segoe UI, Arial, sans-serif' font-size='18' font-weight='bold' text-anchor='middle' fill='#3949AB'>
    90-Minute Workshop for Sri Lankan Policymakers
  </text>

  <!-- Faculty info -->
  <text x='400' y='250' font-family='Segoe UI, Arial, sans-serif' font-size='16' font-weight='bold' text-anchor='middle' fill='#3949AB'>
    Building AI Competencies in Technical and Vocational Education
  </text>

  <!-- University info -->
  <text x='400' y='280' font-family='Segoe UI, Arial, sans-serif' font-size='16' font-weight='bold' text-anchor='middle' fill='#3949AB'>
    Presenter: Hannes Tegelbeckers, Otto Von Guericke University Magdeburg
  </text>
</svg>

---

# 1. Project Overview: What is ASSET?

<div class="glass-effect">

- **AI for Skills, Sustainability & Training**: An international initiative to develop an AI self-learning course for TVET educators
- **Context**: Responds to rapid digitalization and AI revolution impacting jobs and training
- **Problem**: Many TVET teachers lack relevant, accessible materials to teach about AI, especially in vocational contexts
- **Solution**: Co-creating an open, modular course on AI in TVET
- **Alignment**: Supports global education goals (SDG 4.4 on skills for work; SDG 8.5 on inclusive growth)

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>

---

## 2. ASSET Alignment with UNESCO Framework

<div class="elegant-box">

**How ASSET Maps to UNESCO Competencies:**

- **Ethics of AI:** Modules address bias, data privacy, and responsible AI use in TVET contexts
- **AI Pedagogy:** Practical classroom applications demonstrating AI as teaching enhancement tool
- **Foundational Knowledge:** Core AI concepts explained in accessible, TVET-relevant terms
- **Professional Development:** Structured pathway for educators to grow AI competencies

**Ensures:**
- Training is not ad-hoc but builds capacity systematically
- Internationally recognized competency development
- Confidence in navigating teacher-AI-student dynamic
- Structured preparation for Sri Lankan educators

</div>

<!-- Leftmost: UNEVOC -->
<div style="position: fixed; bottom: 1px; left: 300px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 1px; left: 400px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 1px; left: 550px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 1px; left: 800px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 1px; left: 1000px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 1px; left: 1150px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 1px; right: 140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- Rightmost: MITD -->
<div style="position: fixed; bottom: 1px; right: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>

---

# 3. AI Learning Nuggets: Design & Structure

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>
---

## Bite-Sized Interactive Modules

<div class="glass-effect">

**AI Learning Nuggets (~15 minutes each):**

- Stand-alone, targeting introductory-level understanding
- Designed for TVET audiences (instructors, trainees)
- Clear outcomes, engaging content, practice activities
- Consistent pedagogy across all modules

**Typical Learning Outcomes:**
- **Define** generative AI and identify examples (ChatGPT)
- **Describe** practical AI applications in vocational fields
- **List** benefits and limitations of AI in education
- **Demonstrate** simple AI tool usage in teaching
- **Suggest** classroom integration while maintaining human oversight

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>

## Consistent Module Structure

<div class="elegant-box">

**1. Introduction (Context Setting):**

- Relatable TVET scenario to hook learners
- Example: "Imagine you have an AI assistant in your workshop class"
- Connects AI concepts to daily teaching environment

**2. Mini-Lecture Segments:**

- Core content in short, clear chunks (text, images, media)
- Topics: What is Generative AI?, Using AI for lesson planning, AI in Automotive Maintenance
- Simple language with visuals (alt-text included)

**3. Embedded Activities:**

- Quick activities after each content piece
- Multiple-choice questions, short answers, mini-scenarios
- Immediate practice turns passive reading into active learning

**4. Summary & Takeaways:**

- Brief recap highlighting main points
- Reinforces that AI enhances teaching, doesn't replace teachers
- Leads to final quiz or reflective task

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>
---

## International Partnership & Sri Lanka's Role

<div class="elegant-box">

- **Project Lead:** Handwerkskammer OWL (Germany)
- **Partner UNESCO-UNEVOC Centres:**

  - Otto von Guericke University Magdeburg (Germany)
  - National Institute of Business Management (Sri Lanka)
  - MITD (Mauritius)
- **Sri Lanka's Involvement:** Ensures content relevance to local needs and contexts
- **This Workshop:** Part of co-creation phase, held alongside conference to draft course content
- **Policymaker Engagement:** Crucial for supporting national TVET strategies

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>
---

## 2025 Objectives & Vision

<div class="elegant-box">

**By the end of 2025, ASSET will:**

- Pilot an interactive LiaScript-based AI course for TVET
- Build capacity of at least 60 educators across three countries
- Foster a community of practice on AI in TVET

**Ultimate Vision:**
Scale up an inclusive model for AI teacher training that can inform policy and strengthen Sri Lanka's TVET system in the AI era.

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>
---


## Assessment & Inclusion Strategy

    {{0}}
### Assessment-as-Learning Approach
<div class="elegant-box">
**Formative Assessment (Continuous):**

- Embedded quizzes with instant feedback
- Scenario-based decision making
- Fill-in-the-blank key terms
- Real-time misconception correction

    {{1}}
**Summative Assessment (Module End):**

- 3-5 question final quiz covering main points
- Practical application tasks
- "Can-Do" self-assessment checklists
- Confidence scaling (1-5) for self-reflection

    {{2}}
### Inclusive Design Principles

**Accessibility (WCAG Compliant):**

- Alt text for all images and graphics
- Screen reader compatibility
- Keyboard navigation support
- Text-to-speech capability

    {{3}}
**Multilingual & Cultural Inclusion:**

- Simple, jargon-free English
- Culturally diverse examples (tea farming, rice cultivation)
- Easy translation to Sinhala/Tamil
- Local context adaptation encouraged

    {{4}}
**Low-Bandwidth & Offline Access:**

- Progressive Web App functionality
- Compressed media and lightweight design
- Offline caching capabilities
- Works on basic devices and smartphones

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>

---

## Interactive Demo: Learning Nugget

### Experience ASSET in Action

<div class="elegant-box">

@resourceLink(Try Learning Nugget 03_1 - Generative AI Basics, https://liascript.github.io/course/?https://raw.githubusercontent.com/OVGU-VET-TechEd/ASSET_AI_Learning_Nuggets/refs/heads/main/Learning_Nugget_03_1_Claude.md)

@resourceLink(Try Learning Nugget 03_2 - AI Applications Demo, https://liascript.github.io/course/?https://github.com/OVGU-VET-TechEd/ASSET_AI_Learning_Nuggets/blob/main/Learning_Nugget_03_2_Claude.md)

    {{1}}
### What You'll Experience:
- **Self-paced navigation** through interactive content
- **Real-time quizzes** with immediate feedback
- **Practical exercises** you can apply immediately
- **Modular design** - mix and match topics as needed

    {{2}}
### Key Demonstration Points:
- Simple browser-based access (no software installation)
- Works offline once loaded
- Engaging multimedia without high bandwidth needs
- Assessment that builds confidence, not anxiety
</div>

---

    {{3}}
<div class="quiz-interactive">

**Quick Poll:** On a scale of 1-5, how confident are you about explaining an AI application to a colleague?

[[1] [2] [3] [4] [5]]

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>


---

## Why LiaScript? Platform Rationale

### Strategic Technology Choice
<div class="elegant-box">
**Interactive & Offline Capability:**

- Fully browser-based, works without internet once loaded
- Lightweight design ideal for low-bandwidth environments
- No server required for core functionality


**Accessibility & Inclusion:**

- Built-in screen reader compatibility
- Text-to-speech engine in modern browsers
- Easy translation and localization support
- Simple text-based content structure


**Modularity & Reusability:**

- Self-contained nuggets easily updated
- Mix-and-match curriculum flexibility
- Open format prevents vendor lock-in
- Encourages collaborative development

**Open-Source & Sustainable:**

- No recurring license fees
- Content remains editable in simple Markdown
- Community-driven improvements
- Aligns with OER (Open Educational Resources) policies

> **Policy Impact:** Maximum access, adaptability, and sustainability without heavy infrastructure requirements

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>

---

## Participation Opportunities


### Join the ASSET Initiative

<div class="elegant-box">


**Community of Practice:**

- Online forum for sharing experiences and resources
- Connect policymakers, educators, and industry partners
- Stay informed of latest developments and insights


**Workshops & Training-of-Trainers:**

- Follow-up sessions to refine content
- Integration with existing professional development
- Host sessions at your institutions


**Evaluation & Feedback:**

- Surveys, interviews, classroom observations
- Policy perspective reviews on interim findings
- Shape recommendations for national scaling


**Future Collaboration:**

- Version 2.0 content expansion opportunities
- Cross-ministry partnerships (agriculture, industry)
- Private sector engagement possibilities
</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>

---

## Policy Discussion: AI Readiness


### Key Discussion Areas
<div class="elegant-box">
**Strategic Alignment:**
- How does AI fit into your current digitalization strategy for TVET?
- What role should AI integration play in curriculum development?
- Are there existing policy frameworks we should align with?


### High-Potential Sectors in Sri Lanka

@sectorCard(Agriculture, Smart farming, agri-tech, AI-driven crop monitoring and tea plantation management)

@sectorCard(Manufacturing, Industry 4.0 automation, smart production systems)

@sectorCard(Tourism & Hospitality, AI-driven customer service, personalized experiences)


**Content Prioritization:**

- What AI topics are most crucial for Sri Lankan TVET educators?
- Which sectors should we emphasize in training examples?
- Are there specific local use cases we should include?


**Implementation Challenges:**

- **Policy Level:** Need for clear AI skills frameworks
- **Institutional:** IT infrastructure limitations
- **Human:** Teacher readiness and mindset shifts
- **Ethical:** Trust, bias, and automation concerns

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>


---

## Sri Lankan Context: Opportunities


### Sector-Specific Applications

<div class="elegant-box">
**Agriculture & Food Processing:**

- Drone-based crop monitoring for rice paddies
- AI weather prediction for harvest timing
- Smart irrigation systems
- Tea plantation quality assessment using computer vision

    {{1}}
**Manufacturing & Textiles:**

- Predictive maintenance for textile machinery
- Quality control using AI vision systems
- Supply chain optimization
- Energy efficiency monitoring

    {{2}}
**Tourism & Services:**

- Multilingual chatbots for hospitality
- Personalized travel recommendations
- Cultural heritage preservation using AI
- Smart city applications

    {{3}}
### Local Data & Innovation Potential

**Discussion Points:**

- What local datasets could support AI education projects?
- Are there existing government data initiatives we could leverage?
- How can we ensure data privacy while enabling innovation?
- What role should industry partnerships play?
</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>


---

## AI Tool Demonstrations


### Megaprompt 1: Agriculture Training
<div class="elegant-box">
@aiDemo(AI for Agriculture Training (TVET Teacher use case), ChatGPT/Claude, #)

**Sample Prompt:**
> *"You are a teacher at a vocational training center in Sri Lanka, specializing in agriculture. Draft a 1-week lesson plan (5 days) on **'AI in Sustainable Farming'** for your students. Include local examples (like using drones for paddy field monitoring or AI apps for tea plantation management), hands-on activities, and discussion questions for each day."*


**What AI Could Provide:**
- Day 1: Introduction to AI in agriculture with Sri Lankan success stories
- Day 2: Drone technology for rice paddy monitoring in Anuradhapura
- Day 3: Smart irrigation case studies from local farms
- Day 4: AI market price prediction tools for farmers
- Day 5: Ethics debate - "Will AI help small farmers or only large agribusinesses?"

</div>

### Megaprompt 2: Policy Framework

<div class="elegant-box">
@aiDemo(AI for Policy Planning (Administrator use case), ChatGPT/Claude, #)

**Sample Prompt:**
> *"You are an expert consultant AI. The Sri Lankan TVET authority is developing a **policy framework for integrating AI into technical education**. Provide an outline of key policy measures under: Teacher Training, Curriculum Development, Infrastructure & Resources, Industry Partnerships, and Ethics/Safeguards."*

**AI-Generated Policy Framework:**
- **Teacher Training:** Continuous professional development programs, UNESCO-aligned certification
- **Curriculum Development:** AI literacy modules across trades, new elective courses
- **Infrastructure:** Computer lab upgrades, reliable internet, Sinhala language datasets
- **Industry Partnerships:** Innovation fund for student-company AI projects
- **Ethics & Safeguards:** Data privacy guidelines, bias prevention, inclusion mandates
</div>


<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>


---


## Thank You - Questions & Discussion

<div class="elegant-box">

### Key Takeaways

**ASSET Project:**

- Open, modular AI training for TVET educators
- UNESCO-aligned, human-centered approach
- Accessible, inclusive design for all learners

**Your Role:**

- Shape content through participation and feedback
- Support pilot program implementation
- Champion AI-ready TVET policy development


### Discussion Topics

**Strategic Questions:**

- How can ASSET best support your TVET digitalization goals?
- What specific AI applications should we prioritize for Sri Lankan context?
- What policy frameworks need to be developed alongside this training?

**Implementation Support:**

- What teacher support mechanisms would ensure successful adoption?
- How can we address infrastructure and connectivity challenges?
- What industry partnerships would amplify impact?


### Let's Continue the Conversation

**Open Floor for:**

- Questions about the ASSET project
- Ideas for Sri Lankan contextualization
- Partnership and collaboration opportunities
- Policy integration discussions

> **Your insights will directly shape how we implement ASSET for maximum impact in Sri Lanka's TVET system.**

</div>

<!-- UNEVOC -->
<div style="position: fixed; bottom: 20px; left: 20px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UNESCO-UNEVOC_logo.png?raw=true" alt="UNEVOC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UNEVOC</div>
</div>

<!-- ASSET -->
<div style="position: fixed; bottom: 20px; left: 180px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/ASSET_icon.png?raw=true" alt="ASSET Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">ASSET</div>
</div>

<!-- HWK Blume -->
<div style="position: fixed; bottom: 20px; left: 340px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/HWK_Blume.png?raw=true" alt="HWK Blume Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 7px;">HWK Blume</div>
</div>

<!-- GIZ -->
<div style="position: fixed; bottom: 20px; left: 500px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/giz-logo.gif?raw=true" alt="GIZ Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">GIZ</div>
</div>

<!-- UoVT -->
<div style="position: fixed; bottom: 20px; left: 660px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/UoVT_Logo.png?raw=true" alt="UoVT Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">UoVT</div>
</div>

<!-- OVGU -->
<div style="position: fixed; bottom: 20px; left: 820px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/Masub27/Intro/blob/main/ovgu.png?raw=true" alt="OVGU Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">OVGU</div>
</div>

<!-- HRDC -->
<div style="position: fixed; bottom: 20px; left: 980px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/hrdc_logo.png?raw=true" alt="HRDC Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">HRDC</div>
</div>

<!-- MITD -->
<div style="position: fixed; bottom: 20px; left: 1140px; opacity: 0.9; z-index: 1000; text-align: center; width: 100px;">
  <img src="https://github.com/OVGU-VET-TechEd/ASSET_UNESCO_Coinitiative/blob/main/media/mitd_logo.png?raw=true" alt="MITD Logo" style="height: 60px; width: auto; border-radius: 10px;" />
  <div style="font-size: 0.8em; color: #555; margin-top: 5px;">MITD</div>
</div>


