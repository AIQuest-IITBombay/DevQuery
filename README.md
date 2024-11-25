# DevQuery: AI-Powered Q&A Platform for Developers

![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![AI Integration](https://img.shields.io/badge/AI-Integrated-4285F4?style=for-the-badge&logo=artificial-intelligence&logoColor=white)

# DevQuery: AI-Powered Q&A Platform for Developers

DevQuery is an intelligent, AI-enhanced question-and-answer platform designed to facilitate knowledge sharing among developers. This platform combines traditional Q&A functionalities with advanced AI capabilities to provide accurate and efficient responses.

## Features

- **User Registration and Authentication**: Secure user accounts with role-based access control.
- **Question and Answer Management**: Post, edit, and delete questions and answers with rich text support.
- **AI-Generated Responses**: Leverage AI to provide immediate answers and tag suggestions.
- **Automatic Tagging**: AI-driven tagging for improved searchability and organization.
- **Question Analysis and Summarization**: AI-powered insights and summaries for complex questions.
- **User Profiles and Reputation System**: Track contributions and build reputation within the community.
- **Admin Dashboard and Moderator Panel**: Tools for content moderation and platform management.
- **Responsive Design**: Accessible on various devices with a modern, user-friendly interface.

## Technology Stack

- **Backend**: Python, Flask
- **Database**: SQLAlchemy ORM
- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: Custom AI helper (details in `utils/ai_helper.py`)## Technology Stack

- **Backend**: Python, Flask
- **Database**: SQLAlchemy ORM
- **Frontend**: HTML, CSS, JavaScript
- **AI Integration**: Custom AI helper (details in `utils/ai_helper.py`)
## Key Components

### Models
- `User`: User information and authentication
- `Question`: Represents questions asked by users
- `Answer`: Stores answers to questions
- `Tag`: Manages tags for questions
- `Vote`: Handles voting on questions and answers

### Routes
- User authentication (register, login, logout)
- Question and answer management
- Admin and moderator functionalities
- Main page and search results

### Utils
- `ai_helper.py`: AI integration for answer generation, tagging, and analysis
- `decorators.py`: Custom decorators for route protection

## Usage

1. Register for an account or log in
2. Ask questions or browse existing ones
3. Answer questions or view AI-generated answers
4. Use the search functionality to find specific topics
5. Gain reputation by receiving upvotes on your questions and answers
6. Admins and moderators can access additional features through their respective panels
