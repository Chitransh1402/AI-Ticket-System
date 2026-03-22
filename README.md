 AI Ticket Management System (MERN + AI)

An intelligent full-stack **AI-powered Ticket Management System** that helps organizations manage support tickets efficiently using **real-time updates, role-based access control, and AI-driven insights**.

Built with **MongoDB, Express, React, Node.js, Socket.IO, and Inngest AI workflows**.



 Key Features

Authentication & Authorization

* JWT-based secure login & signup
* Role-based system:

  *  User
  *  Moderator
  *  Admin


Ticket Management System

* Create and manage support tickets
* Assign tickets to moderators
* Update ticket status:

  * `TODO`
  * `IN_PROGRESS`
  * `COMPLETED`
* Delete tickets (Admin only)

---

 AI Integration

* AI-generated:

  * Ticket summaries
  * Helpful notes
  * Suggested skills
* Automatic ticket processing using **Inngest + Gemini API**


 Real-Time Updates

* Built with **Socket.IO**
* Instant updates when:

  * Ticket is created
  * Status is updated
  * Moderator is assigned
  * Ticket is deleted



 Admin Dashboard

* View all tickets & users
* Assign roles (user / moderator / admin)
* Assign moderators to tickets
* View analytics:

  * Total tickets
  * Completed / Pending / In Progress
  * Total users


 Advanced Features

* Search tickets by title/description
* Filter tickets by status & priority
* Optimized queries with MongoDB indexing



Tech Stack

 Frontend

* React.js (Vite)
* CSS (Glass UI)

 Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

 Real-Time Communication

* Socket.IO

 AI & Automation

* Inngest
* Google Gemini API



Project Structure

```
Backend/
  controllers/
  models/
  routes/
  middlewares/
  inngest/

Frontend/
  src/
    pages/
    components/
    api/
```



 Environment Variables

Create `.env` file in **Backend**:

```
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_api_key
```



 Installation & Setup

1. Clone Repository

```
git clone https://github.com/your-username/AI-Ticket-System.git
```

---

2. Install Dependencies

Backend:

```
cd Backend
npm install
```

Frontend:

```
cd Frontend
npm install
```

---

3. Run Project

Backend:

```
npm run dev
```

Frontend:

```
npm run dev
```


 Future Enhancements

* Email notifications 
* File attachments 
* Advanced analytics dashboard 
* Cloud deployment (AWS / Render)



 Use Cases

* Customer support systems
* Issue tracking platforms
* Internal team task management



 Author

**Chitransh Shrivastava**



Support

If you like this project, give it a ⭐ on GitHub!
