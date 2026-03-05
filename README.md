# 🛒 MySuperMarket - E-Commerce Project

Hello! Welcome to the **MySuperMarket** repository. This is a complete e-commerce project I built to practice how the Frontend communicates with the Backend (Client-Server architecture). I wanted to see how everything "ties" together, which is why I chose to write pure frontend code, without relying on ready-made frameworks!

---

## ⚠️ A small but important note

Here in this repository, I have uploaded **only the Frontend** part of the project (i.e., the HTML, CSS, and JavaScript files).

👉 **The Backend of the project (all the Server code in Java) is located in a separate repository! You can find and study it here:** [Java-Supermarket-App](https://github.com/elsakarvouni/Java-Supermarket-App)

The project is designed to work exactly with this Backend, which runs locally and reads/writes the data. Therefore, if you open the **Live Page** directly from the internet, **the page will appear empty of products**. 

The reason this happens is because the page's JavaScript tries to `fetch` data from `localhost:8080` (my own computer). If the server is not running in the background, it cannot pull the products or log in the users. *(If you want to see how it fully works, there is a link to the demo video at the end of the README!)*

---

## 💻 Technologies I used

* **Frontend:** HTML, CSS, JavaScript.
* **Backend:** Java ([Java-Supermarket-App](https://github.com/elsakarvouni/Java-Supermarket-App)).
* **Database:** File-based system (`.txt` files). This helped me keep the project lightweight and easy to run locally (reading users, products, and history directly from the files).

---

## ✨ What exactly does it do? (Core Features)

I have divided the project into two main environments, depending on the user's role.

### 🛒 For the Customer
* **Dynamic loading:** Products and categories are "painted" dynamically on the page after being fetched from the API.
* **Search & Filters:** There is a search bar based on the name, as well as a sidebar for filtering by category.
* **Sorting:** You can order the products (e.g., cheapest first, alphabetically, etc.).
* **Shopping Cart:** You add products, change quantities, and see the total cost. (If a product is out of stock, the button is automatically disabled!).
* **User Account:** Registration, login, and order history tracking system.

### ⚙️ For the Administrator (Admin Panel)
*Access to this page is allowed only if you have logged in with an account that has the `ADMIN` role.*
* **Product Management:** A complete panel where the admin can add new products, change prices, or update the stock of existing ones, and delete them.
* **Statistics:** Two special buttons that pull reports from the backend: one for sold-out products (Top Sellers) and one for items in shortage (Out of Stock).
* **Sorting:** You can order the products (e.g., cheapest first, alphabetically, etc.).

---

## 🎥 Demo Video

Because, as explained above, the application needs the local server to fully function and you cannot test it live here, I recorded a short presentation video. 

👉 **[Click here to see the Demo Video on YouTube](INSERT_YOUR_LINK_HERE)**
