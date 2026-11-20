# AspiroX – Career Guidance and Exploration Platform

## Overview

AspiroX is an interactive career guidance and exploration platform designed to help individuals discover career opportunities, evaluate their skills, compare different career paths, and plan their professional development.

The platform provides multiple interactive modules that guide users through skill assessment, career comparison, personalized career exploration, skill-to-job matching, and career progression planning.

AspiroX aims to make career exploration more structured and accessible by bringing essential career planning resources together in one platform.
<img width="1424" height="828" alt="Screenshot 2026-11-20 at 2 54 27 PM" src="https://github.com/user-attachments/assets/379496fe-2902-4def-8f30-a49d74e3c9e5" />
<img width="1433" height="778" alt="Screenshot 2026-11-20 at 2 54 39 PM" src="https://github.com/user-attachments/assets/b172d835-e6fa-4bb6-a70e-4ef32aa0f99e" />


## Key Features

### 1. Skillify – Skill Assessment
- Interactive quiz-based skill assessment.
- Evaluates users' abilities and preferences through multiple-choice questions.
- Helps users understand their strengths and career interests.
<img width="1408" height="807" alt="Screenshot 2026-11-20 at 2 54 53 PM" src="https://github.com/user-attachments/assets/3a9506cf-1bed-4890-aace-1fcc5a6c1408" />


### 2. Duel – Career Comparison
- Allows users to compare two different career options.
- Provides information to help evaluate career choices.
  <img width="1431" height="791" alt="Screenshot 2026-11-20 at 2 55 07 PM" src="https://github.com/user-attachments/assets/2e689b5e-a9cc-455a-9810-45fb1a21c3dd" />


### 3. Mapify – Career Exploration Map
- Explores different career domains and their sub-branches.
- Provides career-related information and guidance.
- Helps users understand possible career directions.
  <img width="1439" height="802" alt="Screenshot 2026-11-20 at 2 55 20 PM" src="https://github.com/user-attachments/assets/01c4f1be-a184-4e5f-8940-ef3c16565382" />


### 4. MatchUp – Skill-to-Job Matching
- Offers predefined skill sets for different domains.
- Allows users to enter their own skills.
- Provides career recommendations based on the selected or entered skills.
  <img width="1433" height="810" alt="Screenshot 2026-11-20 at 2 55 28 PM" src="https://github.com/user-attachments/assets/3af92ff4-3595-4734-88e6-27646e0353b9" />


### 5. Aspire – Goal-Based Career Exploration
- Helps users explore career options based on their professional preferences.
- Includes goals such as high salary, work-life balance, leadership opportunities, and interest in emerging technologies.
- Provides corresponding career progression and upskilling suggestions.
  <img width="1415" height="767" alt="Screenshot 2026-11-20 at 2 55 38 PM" src="https://github.com/user-attachments/assets/e173f7bc-8cd0-4c21-ad77-a064a1e46f9b" />


### 6. Simulate – Career Simulation
- Provides interactive, scenario-based career experiences.
- Allows users to make decisions in simulated workplace situations.
- Demonstrates different workplace responsibilities and decision-making scenarios.
  <img width="1412" height="804" alt="Screenshot 2026-11-20 at 2 55 52 PM" src="https://github.com/user-attachments/assets/22156a55-5e78-494e-a16a-9b88e196d882" />


### 7. Pathways – Career Progression
- Presents career progression opportunities.
- Provides information about different career stages.
- Suggests learning resources, skills, and certifications for professional growth.
  <img width="1411" height="809" alt="Screenshot 2026-11-20 at 2 56 11 PM" src="https://github.com/user-attachments/assets/be82fa7d-ca8a-4dbf-87ab-1919212fbc9d" />


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
