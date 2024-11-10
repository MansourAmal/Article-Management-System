

### **Article Management System**

This project is an **Article Management System** built using **Symfony**. It provides functionalities for managing articles and categories, allowing users to:

- **Add articles**: Create and add new articles with relevant details.
- **Add categories**: Define categories for articles, and associate articles with their respective categories.
- **Update articles**: Modify the details of existing articles.
- **Delete articles**: Remove articles from the system.
- **Search by price range**: Users can search for articles based on a minimum and maximum price.
- **Search by name**: Articles can be filtered by their name.
- **Search by category**: Articles can be filtered by their associated categories.

### **Features**
- **Article management**: Add, modify, and delete articles with ease.
- **Category management**: Create and assign categories to articles.
- **Search functionality**: Search articles by name, price range, or category.
- **User interface**: Intuitive and easy-to-use interface for managing articles and categories.

### **Technologies Used**
- **Symfony**: The core framework used to build the application.
- **Doctrine ORM**: For interacting with the database.
- **Twig**: For rendering templates and creating dynamic HTML views.
- **MySQL**: The database used to store articles and categories.
  
### **How to Run the Project**:
![Capture d'écran 2024-11-10 204935](https://github.com/user-attachments/assets/6e1f4a4a-ffac-44c3-be51-eb4ac6764957)
![Capture d'écran 2024-11-10 205007](https://github.com/user-attachments/assets/6a0f5cb3-3a23-4e25-b16f-a7117ca91847)
![Capture d'écran 2024-11-10 205149](https://github.com/user-attachments/assets/d6eca180-4eea-4e05-b7b5-21d1abbff916)
![Capture d'écran 2024-11-10 204856](https://github.com/user-attachments/assets/2b7c477b-9331-4cfe-affb-ba32da8fdd69)
![Capture d'écran 2024-11-10 204826](https://github.com/user-attachments/assets/bf1291ba-6621-4aed-928f-449ae64ac936)

### **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <project_directory>
   ```

2. Install dependencies:
   ```bash
   composer install
   ```

3. Set up the database:
   - Create the database:
     ```bash
     php bin/console doctrine:database:create
     ```
   - Run migrations to set up the schema:
     ```bash
     php bin/console doctrine:migrations:migrate
     ```

4. Start the Symfony server:
   ```bash
   symfony serve
   ```

5. Access the application at `http://127.0.0.1:8000`.

### **Directory Structure**

- **src/**: Contains the Symfony controllers, entities, and other backend logic.
- **templates/**: Contains the Twig templates for rendering the user interface.
- **public/**: The public directory where assets like CSS, JS, and images are stored.
- **config/**: Contains configuration files, including routing and services.

### **Usage**

- **Adding Articles**: Go to the "Add Article" page and fill out the form with article details (name, price, category, etc.).
- **Categories**: Categories can be created and assigned to articles.
- **Searching**: Use the search form to filter articles by name, price range, or category.

