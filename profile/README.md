<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

# CircleConnect - Social Networking Platform

## Project Overview
CircleConnect is a scalable microservices-based social platform enabling community interactions, post sharing, and real-time notifications. Developed for SW Architecture and Design (Spring 2025).

## Features
### Core Functionality
- **Google OAuth2 Authentication**
- **Community Management**
  - Create/join communities (Admin restricted)
  - Post creation and interactions
  - 24-hour ephemeral stories
- **Real-time Notifications**

## 🏗 System Architecture
### Key Components
- **Microservices**: 6 independent services (Auth, Communities, Posts, Stories, Notifications, Admin)
- **API Gateway**: Gateway for request routing
- **Database**: MongoDB with sharding for scalability
- **Cache**: Redis for session management
- **Message Broker**: Kafka for event-driven notifications
- **Auth**: Google OAuth2 with JWT

## 🛠️ Core Technologies
**Backend:**
- Node.js
- Express
- MongoDB
- Redis
- Python
- Java
- GoLang


## 👥 Development Team
<p align="center">
  <table align="center">
    <tr>
      <th align="center">Co-Developer</th>
      <th align="center">Lead Developer</th>
      <th align="center">DevOps Engineer</th>
      <th align="center">Technical Architect</th>
    </tr>
    <tr>
      <td align="center">
        <img src="https://avatars.githubusercontent.com/u/148449014?s=100" width="100"><br>
        @HaneenMohamed
      </td>
            <td align="center">
        <img src="https://avatars.githubusercontent.com/u/125549462?v=4" width="100"><br>
        @Mustafa
      </td>
      <td align="center">
        <img src="https://avatars.githubusercontent.com/u/121519896?s=100" width="100"><br>
        @yehiahesham2938
      </td>
      <td align="center">
        <img src="https://github.com/Yasmine.png" width="100"><br>
        @Yasmine
      </td>
    </tr>
    <tr>
      <td align="center">Full-stack development</td>
      <td align="center">Infrastructure & deployment<br>Full-stack development</td>
      <td align="center">Infrastructure & deployment<br>Full-stack development</td>
      <td align="center">ADR reports<br>Code contributions</td>
    </tr>
  </table>
</p>
