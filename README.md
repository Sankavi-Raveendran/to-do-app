# to-do-app
# PHP To-Do List Project with MySQL Database

##  Prerequisites
Before running this project, ensure you have the following installed:
- [XAMPP](https://www.apachefriends.org/) (Apache, MySQL, PHP)
- [Visual Studio Code](https://code.visualstudio.com/)
- A web browser (Chrome, Firefox, etc.)

---

##  How to Run This Project

### 1⃣ Start XAMPP
1. Open **XAMPP Control Panel**.
2. Start **Apache** and **MySQL**.

---

### 2⃣ Setup the Database
1. Open your web browser and go to **http://localhost/phpmyadmin/**.
2. Click on **Databases** and create a new database:
   ```sql
   CREATE DATABASE to_do_list;
   ```
3. Select your new database and go to the **Import** tab.
4. Click **Choose File**, navigate to the **/database** folder, and select **to_do_list.sql**.
5. Click **Import** to restore the database.

---

### 3⃣ Configure the Project
1. Place the project folder inside **htdocs**:
   ```
   C:\xampp\htdocs\to_do_list\
   ```

---

### 4⃣ Run the Project
1. Open **VS Code** and go to **File → Open Folder** → Select `C:\xampp\htdocs\to_do_list\`.
2. In the browser, open:
   ```
   http://localhost/to-do-list/to-do-app/
   ```
3. You should see the homepage of the To-Do List project.

---

