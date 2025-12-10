# Farhan's Personal Blog

This is a simple personal blog project built as an exercise to hone my CRUD skills using JavaScript.

This blog features full **CRUD (Create, Read, Update, Delete)** functionality and showcases a modern **Neumorphism (Soft UI)** design.


<img width="1916" height="907" alt="Screenshot 2025-11-11 213240" src="https://github.com/user-attachments/assets/314f8d6e-9dcb-4453-a57c-2100ea0adadb" />


## 🚀 Key Features

* **Create Posts:** Write and publish new posts via a form.
* **View Posts:** All posts are displayed chronologically on the main page.
* **Edit Posts:** Update the title and content of existing posts.
* **Delete Posts:** Remove posts from the list.
* **Neumorphism Design:** A unique "Soft UI" look where elements appear "extruded" from the background.
* **Animations:** Satisfying *hover* and *focus* effects, as well as *fade-in* animations when loading posts.

---

## 🛠️ Technologies Used

* **Backend:**
    * [**Node.js**](https://nodejs.org/): Server-side JavaScript execution environment.
    * [**Express.js**](https://expressjs.com/): Framework for building web applications and handling routing.
* **Frontend:**
    * [**EJS (Embedded JavaScript)**](https://ejs.co/): Templating engine for rendering HTML dynamically.
    * **CSS3:** For custom styling, specifically to create Neumorphism effects using `box-shadow`.
* **Project Structure:**
    * Uses EJS *partials* for reusable components (like header and footer).

---

## ⚙️ Installation and Setup

To run this project on your local machine:

1.  **Clone this repository:**
    ```bash
    git clone [https://github.com/farhandavin/blog_pribadi_farhan.git](https://github.com/farhandavin/blog_pribadi_farhan.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd blog_pribadi_farhan
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```
    *(Ensure `express`, `ejs`, and `body-parser` are installed)*

4.  **Start the server:**
    ```bash
    node index.js
    ```
    *(Or `nodemon index.js` if you use it)*

5.  **Open in browser:**
    Open `http://localhost:3000` in your browser.
