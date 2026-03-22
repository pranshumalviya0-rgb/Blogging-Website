# 📝 Blogify — Blogging Website

Blogify is a full‑stack blogging platform built with Node.js, Express, MongoDB, and EJS. It allows users to sign up, create blogs, upload images, and interact through comments in a clean and simple interface.

## 🚀 Features

* 👤 User Authentication (Sign up / Sign in / Logout)
* ✍️ Create, read, and view blog posts
* 🖼️ Upload images for blog posts
* 💬 Comment on blog posts
* 🏠 Home page displaying all blogs
* 🔒 Protected routes using authentication middleware
* 📱 Responsive UI using EJS templates

## 🛠️ Tech Stack

**Backend:** Node.js, Express.js
**Frontend:** EJS (Embedded JavaScript Templates), HTML, CSS
**Database:** MongoDB (via Mongoose)
**Authentication:** Custom JWT‑based authentication
**File Uploads:** Stored locally in `/public/uploads`

## 📂 Project Structure

```
blogify/
│
├── app.js                # Entry point
├── package.json          # Project dependencies
│
├── models/               # Mongoose models
│   ├── user.js
│   ├── blog.js
│   └── comment.js
│
├── routes/               # Express routes
│   ├── user.js
│   └── blog.js
│
├── middlewares/          # Custom middleware
│   └── authentication.js
│
├── services/             # Business logic (auth, etc.)
│   └── authentication.js
│
├── views/                # EJS templates
│   ├── home.ejs
│   ├── blog.ejs
│   ├── addBlog.ejs
│   ├── signup.ejs
│   ├── signin.ejs
│   └── partials/
│
└── public/               # Static files
    ├── images/
    └── uploads/
```

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/blogify.git
cd blogify
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure environment variables

Create a `.env` file in the root directory:

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the application

```bash
npm start
```

App will run at:

👉 [http://localhost:5000](http://localhost:5000)

## 🧪 Usage

1. Create a new account
2. Sign in to your account
3. Add a new blog post with image
4. View all blogs on the home page
5. Open a blog to read and comment


## 🌐 Deployment

You can deploy this project on:

* Render
* Railway
* Heroku
* VPS (DigitalOcean, AWS, etc.)

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 🐞 Issues

If you find a bug or want to request a feature, please open an issue.

## 📄 License

This project is licensed under the MIT License.


⭐ If you like this project, give it a star on GitHub!
