# 🔍 AutomateX: Lost and Found Website

**AutomateX** is a centralized **Lost and Found Management System** designed to streamline the process of reporting and recovering lost items in institutions like colleges, offices, or public spaces. Built with a focus on accessibility, automation, and real-time updates, the platform connects item finders and seekers quickly and securely.

## 📌 Features

* 📝 **Submit Lost or Found Reports** with item details, images, and location.
* 🔍 **Search & Filter System** for browsing reported items.
* 🧾 **Claim History** for users to track their submitted/claimed items.
* 📱 **Responsive Design** for seamless mobile and desktop experience.
* 🔐 **Authentication & Authorization** for secure access and role-based features.

## 🛠 Tech Stack

* **Frontend:** React.js, Tailwind CSS / Bootstrap
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT, bcrypt.js
* **Cloud Storage:** Cloudinary
* **Deployment:** Render

## 📸 Demo

🌐 [Live Website](https://your-live-site-url.com)

## 📂 Project Structure

```
automatex-lost-found/
├── frontend/         # React frontend
│   └── ...
├── backend/         # Node.js backend
│   └── ...
├── README.md
└── ...
```

## 🧑‍💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-group-name/automatex-lost-found.git
cd automatex-lost-found
```

### 2. Install dependencies

#### For client:

```bash
cd frontend
npm install
```

#### For server:

```bash
cd backend
npm install
```

### 3. Configure environment variables

Create a `.env` file in the `backend` directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4. Run the app locally

#### Start the backend server:

```bash
cd backend
npm run dev
```

#### Start the frontend dev server:

```bash
cd frontend
npm run dev
```

## 🤝 Contributors

👥 This project is developed as a group collaboration.
Add your team members here:

| Name              | Role                 |
| ----------------- | -------------------- |
| Slok Tulsyan      | Full Stack Developer |
| Krishna Jhanwar   | Full Stack Developer|
| Siddharth Rai     | Full Stack Developer                 |
| Dhruv Choksey     | Full Stack Developer                 |

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 🙌 Acknowledgements

* MongoDB for data management
* React for building dynamic UI
* Express and Node for backend logic
* Cloudinary for image storage
* All open-source packages and communities that helped during development

