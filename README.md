# Frontend Dashboard Assignment

This is a **React-based Frontend Dashboard** built as part of an internship assignment. It uses dummy API data to render a profile screen and a comments dashboard with full functionality as specified.

---

## 📌 Features

### 🔹 Profile Screen (`/profile`)
- Displays details of the first user from the [JSONPlaceholder Users API](https://jsonplaceholder.typicode.com/users)
- Clean, card-style UI with user details: name, username, email, phone, company, and address
- Clickable user name in header navigates to this profile screen

### 🔹 Comments Dashboard (`/`)
- Lists 500 comments from the [JSONPlaceholder Comments API](https://jsonplaceholder.typicode.com/comments)
- Fully custom implementation:
  - ✅ **Pagination** (Prev, Next, Page size: 10 / 50 / 100)
  - ✅ **Search**: Single search bar filters by name, email, and comment
  - ✅ **Sorting**: By Post ID, Name, or Email (toggles between ascending, descending, and default)
  - ✅ **Routing** via React Router
  - ✅ **Client-side data persistence** using localStorage (search, sort, page, page size)
- Fully responsive layout using CSS Grid and Flexbox
- Div-based table layout for accessibility and responsiveness

---

## 🚀 Technologies Used

| Technology       | Purpose                                |
|------------------|----------------------------------------|
| React            | Frontend framework                     |
| React Router DOM | Routing between profile and dashboard  |
| Plain JavaScript | Logic for pagination, sorting, search  |
| CSS              | Component-level styling                |
| JSONPlaceholder  | Dummy API data                         |

---


## 🧪 How to Run the App

1. Clone the repository or download ZIP
2. Install dependencies:

   \`\`\`bash
   npm install
   \`\`\`

3. Start the development server:

   \`\`\`bash
   npm run dev
   \`\`\`

4. Open in browser:

   \`\`\`
   http://localhost:5173
   \`\`\`

---

## 🧾 Notes

- All logic for pagination, filtering, and sorting is **manually implemented**.
- No external UI component libraries (like MUI or Ant) were used.
- CSS is modularized per component.
- Fully responsive on mobile, tablet, and desktop.

---


## ✅ Submission Checklist

-  React used for all UI
-  Routing implemented
-  Pagination, sorting, search implemented without libraries
-  Data persistence on reload (localStorage)
-  Clean responsive design
-  All code modularized and clean

---

## 📎 Dummy APIs Used

- Users: https://jsonplaceholder.typicode.com/users
- Comments: https://jsonplaceholder.typicode.com/comments
