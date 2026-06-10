# ClientFlow

ClientFlow is a modern client management and project tracking platform designed for freelancers, agencies, and service-based businesses. It streamlines client onboarding, project management, communication, workflow tracking, and automated email communication through an intuitive and responsive interface.

## 🎥 Preview Video

<a href="https://www.instagram.com/reel/DYwvoj1KMju">
  <img src="https://github.com/renish-r/clientflow/blob/main/zenzerflow.webp" alt="ClientFlow Demo" width="250">
</a>
  
## 🚀 Features

* 👥 **Client Management**

  * Add, edit, and manage client information
  * Store contact details and project history
  * Track client status and engagement

* 📁 **Project Tracking**

  * Create and manage projects
  * Monitor project progress
  * Organize tasks and milestones

* 📧 **Email Automation**

  * Automatically send service-specific emails based on the client's current stage in the workflow
  * Schedule and trigger emails based on project updates
  * Streamline client communication and follow-ups
  * Reduce manual effort with automated workflows

* 📊 **Dashboard Analytics**

  * Overview of active clients and projects
  * Progress tracking and performance insights
  * Quick access to important metrics

* 🔐 **Secure Authentication**

  * User registration and login
  * JWT-based authentication
  * Protected routes and role-based access

* 📱 **Responsive Design**

  * Optimized for desktop, tablet, and mobile devices
  * Modern and user-friendly interface

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript (ES6+)
* HTML5
* CSS3 / Tailwind CSS
* React Router

### Backend

* Java
* Spring Boot
* Spring Security
* JWT Authentication
* RESTful APIs

### Database

* Postgres (Supabase)

### Tools & Deployment

* Git & GitHub
* Maven
* Postman
* Vercel (Frontend)
* Render (Backend)

## 📂 Project Structure

```bash
clientflow/
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/main/java/
│   ├── src/main/resources/
│   └── pom.xml
│
└── README.md
```

## API Endpoints

### Authentication

```http
POST /api/auth/register
POST /api/auth/login
```

### Clients

```http
GET    /api/clients
POST   /api/clients
PUT    /api/clients/{id}
DELETE /api/clients/{id}
```

### Projects

```http
GET    /api/projects
POST   /api/projects
PUT    /api/projects/{id}
DELETE /api/projects/{id}
```

### Email Automation

```http
POST   /api/emails/send
POST   /api/emails/schedule
GET    /api/emails/history
```

## 🎯 Use Cases

* Freelancers managing multiple clients
* Digital marketing agencies
* Web development agencies
* Consulting businesses
* Service-based startups
* Businesses looking to automate client communication and follow-ups

## 📈 Future Enhancements

* Advanced email templates
* Invoice generation
* Payment tracking
* Team collaboration
* Advanced reporting
* AI-powered client insights

## 👨‍💻 Author

**Renish R**

Founder of **ZenzerFlow** | Full-Stack Developer | Java Backend Developer

If you found this project useful, consider giving it a ⭐ on GitHub!
