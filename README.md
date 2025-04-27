
Built by https://www.blackbox.ai

---

```markdown
# E-Learning Safety Riding

## Project Overview
The E-Learning Safety Riding project is an interactive web application designed to educate users on the basics of safe motorcycle riding practices. This platform provides various learning modules including basic safety, braking techniques, hazard anticipation, and more, with integrated quizzes to assess users' knowledge. Utilizing local storage, it also tracks user progress and generates analytics on module completion and average scores.

## Installation
To run the project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/e-learning-safety-riding.git
   cd e-learning-safety-riding
   ```

2. Serve the project using your preferred method (e.g., by opening `index.html` in a web browser or using a local server such as Live Server in Visual Studio Code).

## Usage
1. Open `index.html` in your web browser to access the login page.
2. Enter your NPK, full name, and select your department.
3. After logging in, you will be redirected to the dashboard where you can select different learning modules.
4. Complete the provided quizzes after each module to track your learning progress.
5. Access the analytics dashboard to visualize your module completion and scores.

## Features
- **User Authentication**: Users can log in and maintain sessions.
- **Learning Modules**: Multiple modules covering essential safety riding topics.
- **Progress Tracking**: User progress and scores are saved and displayed.
- **Export Data**: Users can export their learning progress and scores as a CSV file.
- **Department Analytics**: View access statistics and average scores by department.

## Dependencies
The primary dependencies used in this project can be located within `index.html` and include:
- Tailwind CSS for styling the application.
- Font Awesome for icons.

No separate package.json dependencies have been specified since this project does not utilize any server-side frameworks or additional libraries apart from CDN links.

## Project Structure
```
/e-learning-safety-riding
│
├── index.html          # Login page
├── dashboard.html      # User dashboard
├── analytics.html      # Analytics dashboard
├── basic.html          # Basic safety riding module
├── braking.html        # Braking techniques module
├── hazard.html         # Hazard anticipation module
├── microsleep.html     # Micro sleep awareness module
├── blindspot.html      # Blind spots awareness module
├── auth.js             # JavaScript for authentication and progress tracking
└── style.css           # CSS for custom styles (if any)
```

## Conclusion
This project aims to enhance riders' understanding of safe motorcycle practices through an effective e-learning platform. For more information, feel free to explore the modules or contribute to the project.
```