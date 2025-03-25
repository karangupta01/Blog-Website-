# 📝 BlogB - Modern Blog Website

BlogB is a modern and responsive blog website built using **React.js** that allows users to create, edit, and publish rich-content blog posts. It integrates seamless content management, user authentication, and dynamic routing.

---

## 📚 Features

✅ Create, edit, and manage blog posts with rich-text editor (TinyMCE).  
✅ User authentication and authorization with Appwrite.  
✅ Responsive and modern UI using React.js and Redux Toolkit.  
✅ Dynamic routing using React Router DOM.  
✅ Real-time form validation with React Hook Form.  
✅ Parse and display HTML content using HTML React Parser.  
✅ Optimized for SEO and performance.  

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Redux Toolkit, React Router DOM, TinyMCE Editor  
- **Backend:** Appwrite  
- **State Management:** Redux Toolkit  
- **Form Handling:** React Hook Form  

---

## 📦 Dependencies

The project uses the following dependencies:

```json
"dependencies": {
  "@reduxjs/toolkit": "^2.6.1",
  "@tinymce/tinymce-react": "^6.0.0",
  "appwrite": "^17.0.0",
  "html-react-parser": "^5.2.2",
  "react": "^19.0.0",
  "react-dom": "^19.0.0",
  "react-hook-form": "^7.54.2",
  "react-redux": "^9.2.0",
  "react-router-dom": "^7.3.0",
  "tinymce-react": "^1.3.2"
}
```

---

## 📂 Project Structure

```
/blogb
├── /public
├── /src
│   ├── /components
│   ├── /pages
│   ├── /redux
│   ├── /utils
│   ├── App.js
│   ├── index.js
├── /node_modules
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/karangupta01/blogb.git
cd blogb
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add your Appwrite API keys and other environment variables.

```
REACT_APP_APPWRITE_ENDPOINT=<your-appwrite-endpoint>
REACT_APP_APPWRITE_PROJECT_ID=<your-project-id>
REACT_APP_TINYMCE_API_KEY=<your-tinymce-api-key>
```

### 4. Run the Application

```bash
npm start
# or
yarn start
```

The app will be available at [http://localhost:3000](http://localhost:3000).

---

## 📄 Usage

1. Sign up or log in to the platform.
2. Create new blog posts using the rich-text editor.
3. Manage and edit posts from the dashboard.
4. View and explore other users' blogs.

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss improvements.

---

## 🐛 Bug Reports & Feedback

If you encounter any issues or have suggestions, feel free to [open an issue](https://github.com/karangupta01/blogb/issues).

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📧 Contact

For any inquiries, reach out to:  
📩 **your.email@example.com**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/your-profile)

---

Happy Coding! 🎉✨

