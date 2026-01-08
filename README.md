# Code Snippet Manager 🚀

A modern **Code Snippet Management Application** built with **Next.js**, **Tailwind CSS**, **Prisma**, and **shadcn/ui**.  
This app helps developers save, organize, and reuse code snippets efficiently.

---

## ✨ Features

- 🔐 Authentication (optional / planned)
- 📂 Create, edit, delete code snippets
- 🏷️ Tag snippets by language or category
- 🔍 Search & filter snippets
- 🎨 Clean UI with shadcn/ui components
- 🌙 Dark / Light mode support
- ⚡ Fast & responsive design
- 🗄️ Database powered by Prisma

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Database ORM:** Prisma
- **Database:** PostgreSQL / MySQL / SQLite
- **Language:** TypeScript
- **Icons:** Lucide Icons

---

## 📁 Project Structure

```bash
.
├── app/                # App Router pages
├── components/         # Reusable UI components
├── lib/                # Utility functions
├── prisma/             # Prisma schema & migrations
├── public/             # Static assets
├── styles/             # Global styles
└── README.md

```

🚀 Getting Started
1️⃣ Clone the repository

```bash

git clone https://github.com/your-username/code-snippet-manager.git
cd code-snippet-manager

```


2️⃣ Install dependencies
```bash
npm install
# or
yarn install

```

3️⃣ Setup Environment Variables
```bash
Create a .env file in the root directory:


DATABASE_URL="your_database_url"
```

4️⃣ Prisma Setup

```bash
npx prisma generate
npx prisma migrate dev

```

5️⃣ Run the development server

```bash
npm run dev

```

Open 👉 http://localhost:3000

🧩 Prisma Example Schema

```bash

model Snippet {
  id        String   @id @default(uuid())
  title     String
  code      String
  language  String
  createdAt DateTime @default(now())
}

```

📸 Screenshots

Add screenshots of your UI here


🗺️ Roadmap

✅ CRUD for snippets

🔐 User authentication

⭐ Favorite snippets

📤 Export snippets

📊 Snippet analytics

🤝 Contributing

Contributions are welcome!
Feel free to open issues or submit pull requests.

📄 License

This project is licensed under the MIT License.


👤 Author

Rehan
Front-End Web Developer

GitHub: [https://github.com/rehan606]

LinkedIn: [https://www.linkedin.com/in/kh-rehan207/]



⭐ If you like this project, don’t forget to give it a star!

```bash

If you want, I can also:
- Customize this README for **GitHub portfolio**
- Make it **shorter or more beginner-friendly**
- Add **deployment (Vercel) section**
- Write a **Prisma + Next.js setup guide**

Just tell me 👍

```