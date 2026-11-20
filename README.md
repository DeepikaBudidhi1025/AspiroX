# AspiroX – Career Guidance and Exploration Platform

## Overview

AspiroX is an interactive career guidance and exploration platform designed to help individuals discover career opportunities, evaluate their skills, compare different career paths, and plan their professional development.

The platform provides multiple interactive modules that guide users through skill assessment, career comparison, personalized career exploration, skill-to-job matching, and career progression planning.

AspiroX aims to make career exploration more structured and accessible by bringing essential career planning resources together in one platform.

## Key Features

### 1. Skillify – Skill Assessment
- Interactive quiz-based skill assessment.
- Evaluates users' abilities and preferences through multiple-choice questions.
- Helps users understand their strengths and career interests.

### 2. Duel – Career Comparison
- Allows users to compare two different career options.
- Provides information to help evaluate career choices.

### 3. Mapify – Career Exploration Map
- Explores different career domains and their sub-branches.
- Provides career-related information and guidance.
- Helps users understand possible career directions.

### 4. MatchUp – Skill-to-Job Matching
- Offers predefined skill sets for different domains.
- Allows users to enter their own skills.
- Provides career recommendations based on the selected or entered skills.

### 5. Aspire – Goal-Based Career Exploration
- Helps users explore career options based on their professional preferences.
- Includes goals such as high salary, work-life balance, leadership opportunities, and interest in emerging technologies.
- Provides corresponding career progression and upskilling suggestions.

### 6. Simulate – Career Simulation
- Provides interactive, scenario-based career experiences.
- Allows users to make decisions in simulated workplace situations.
- Demonstrates different workplace responsibilities and decision-making scenarios.

### 7. Pathways – Career Progression
- Presents career progression opportunities.
- Provides information about different career stages.
- Suggests learning resources, skills, and certifications for professional growth.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and layout of webpages |
| CSS3 | Styling and user interface design |
| JavaScript | Interactive features and functionality |
| JSON | Storage of career information and career-path data |
| PHP | PHP component files included in the project |
| PDF, Images and MP4 | Supporting learning and visual assets |

## Project Structure

```text
AspiroX/
│
├── index.html
├── skillify.html
├── duel.html
├── mapify.html
├── matchup.html
├── aspire.html
├── simulate.html
├── pathways.html
│
├── style.css
├── app.js
│
├── careers.json
├── career-paths.json
│
├── header.php
├── footer.php
│
├── assets/
│   ├── images/
│   ├── pdfs/
│   └── videos/
│
├── .gitignore
└── README.md
```

## Installation and Setup

### Prerequisites
- A web browser (Google Chrome, Firefox, etc.).
- Visual Studio Code.
- Python 3 (for running a local development server).

### Steps to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/AspiroX.git
   ```

2. Navigate to the project directory:

   ```bash
   cd AspiroX
   ```

3. Start a local development server:

   ```bash
   python3 -m http.server 8000
   ```

4. Open your browser and visit:

   ```text
   http://localhost:8000
   ```

5. Open the home page and explore the available career guidance modules.

**Note:** Run the project through a local server rather than opening HTML files directly, because some features load JSON data using JavaScript fetch requests.

## Future Enhancements

- Integrate AI-powered personalized career recommendations.
- Introduce user authentication and profile management.
- Incorporate real-time job market information.
- Improve skill assessment using adaptive quizzes.
- Provide personalized learning and certification recommendations.
- Develop a centralized dashboard to track career development progress.

## Project Objective

To provide an interactive platform that simplifies career discovery, supports informed career decisions, and helps individuals plan their professional growth.

---

**AspiroX – Explore Your Potential. Discover Your Path.**