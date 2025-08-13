<a id="readme-top"></a>

<div align="center">
  <h1>Resume Optimizer Pro</h1>
  <h3>An AI-powered tool to create, optimize, and analyze resumes for better job opportunities.</h3>
  
  [![Live Demo](https://img.shields.io/badge/Try-Live_Demo-green)](https://resumeoptimizerpro.streamlit.app/)

</div>

## Table of Contents
1. [Why Resume Optimization Matters](#challenge)
2. [Features](#features)
3. [How It Works](#how-it-works)
4. [Key Technologies](#technologies)
5. [Installation](#installation)
6. [Usage Guide](#usage)

<a name="challenge"></a>
## Why Resume Optimization Matters

Job seekers often submit generic resumes that fail to align with specific job requirements. Applicant Tracking Systems (ATS) and recruiters prioritize resumes that match:
- Keywords from the job description
- Required skills and experiences
- Industry-specific terminology

**The result?** Qualified candidates get overlooked due to poor resume-job alignment, despite having relevant qualifications.

Resume Optimizer Pro is an AI-powered web application that:
1. Analyzes your resume against target job descriptions
2. Identifies gaps and optimization opportunities
3. Generates tailored improvements with:
   - Keyword optimization for ATS
   - Skills alignment
   - Actionable formatting suggestions
4. Provides an optimized resume ready for submission

<a name="features"></a>
## Key Features

| Tool              | Highlights |
|-------------------|------------|
| Create New Resume | Build professional resumes from scratch with guided sections |
| Edit Resume       | AI-powered rewriting, keyword optimization |
| Analyze Resume    | Gap analysis, improvement suggestions |
| ATS Checker       | Compatibility scoring, formatting tips |


<a name="how-it-works"></a>
## How It Works: 

Select an option from:  

### 1. Create New Resume
- Build a resume from scratch with guided sections
- Input personal information, experience, education, and skills
- Generate and download a professionally formatted document

### 2. Edit Resume
- Upload your existing resume (PDF or Word)
- Provide the target job description
- Receive an AI-optimized version with:
  - Keyword integration
  - Content restructuring
  - Improved formatting

### 3. Analyze Resume
- Upload your current resume
- Compare against a job description
- Receive detailed feedback including:
  - Missing keywords
  - Suggested improvements
  - ATS compatibility score

### 4. ATS Checker
- Evaluate how applicant systems will parse your resume
- Get specific recommendations for:
  - Keyword optimization
  - Formatting adjustments
  - Content organization

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<a name="technologies"></a>
## Key Technologies  

| Component          | Technology |
|--------------------|------------|
| Frontend           | Streamlit  |
| Backend            | Python     |
| AI Processing      | OpenAI API  GPT models|
| NLP                | spaCy, keyword extraction  |
| Resume text extraction| PyPDF2, python-docx |
| Data Handling | JSON |

<a name="installation"></a>
## Installation  

1. Clone the repository:
   ```bash
   git clone https://github.com/UjuAyoku/resume-optimizer-pro.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key in a `.env` file:
   ```
   OPENAI_API_KEY=your-api-key-here
   ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

<a name="usage"></a>
## Usage Guide  

### Create New Resume
```python
1. Select "Create New Resume" from the sidebar
2. Fill in all relevant sections:
   - Personal Information
   - Professional Summary
   - Work Experience
   - Education
   - Skills
3. Click "Generate Preview" to see your resume
4. Download in Word format
```

### Edit Existing Resume
```python
1. Select "Edit Resume" from the sidebar
2. Upload your existing resume (PDF or Word)
3. Paste the target job description
4. Click "Analyze Resume" to get AI-powered optimizations
5. Review and download the improved version
```

### Analyze Resume
```python
1. Select "Analyze Resume" from the sidebar
2. Upload your resume
3. Provide the job description
4. Click "Run Optimization Analysis" to get:
   - Keyword matching
   - ATS score
   - Actionable suggestions
```

### ATS Check
```python
1. Select "ATS Checker"
2. Upload resume
3. Provide job description
4. View compatibility score and suggestions
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

 
 
