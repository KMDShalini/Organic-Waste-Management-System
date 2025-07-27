# Organic-Waste-Management-System

📌 **Introduction**


Organic Waste Management System is a web-based platform designed to help users efficiently submit and categorize their organic waste. It simplifies the process for sellers or individuals to report the type, amount, and moisture content of organic waste, making it easier for municipal or private waste management entities to process and utilize.

***

🏗️ **Project Overview**


  **Key Features**:

  
   🌿 **Waste Type Classification**: Users can select common organic waste types or specify others manually.
    
   🧪 **Wetness Measurement Input**: Capture the moisture percentage to assist in composting and processing.
    
   ⚖️ **Weight Input**: Enter the weight in kilograms for precise tracking.
    
   📝 **Additional Details**: Users can leave contact info and comments for further clarification.
    
   ✅ **Responsive UI**: Clean and mobile-friendly interface.
   

  **Technology Stack**:

  
   **Frontend**: HTML, CSS, bootstrap
    
   **Backend**: PHP 
    
   **Server**: XAMPP (Apache & MySQL stack)

***

🎯 **Project Features**

 👤 **Seller Form**


   * **Select waste category**: Wet or Dry
       
   * **Choose waste type**: Fruit, Vegetable, Meat, Dairy, etc.
       
       Option to add a custom waste type
       
       Enter wetness percentage (0–100%)
       
       Enter weight in kg
       
       Provide contact details
       
       Add additional notes if needed
       
       Form data is saved with date and time


  ✉️ **Feedback Form**

  
      *  User can send a message to the admin
       
      * Fields: Name, Email, Message
       
      * Message is stored with timestamp
       

  🔐 **User Authentication**


       * Registration for Sellers, Buyers
       
       * Login with Email and Password
       
       * Redirected to respective dashboards after login
       

  🧾 **About Us Page**


       * Shows information about the platform
       
       * Explains the goal of reducing organic waste
       
       * Encourages eco-friendly practices

       

  🛒 **Shopping Page**
   
       * Includes links to useful products

       

  📄 **Seller Details Display Page**
  

       * Shows details of waste submitted by sellers
       
       * Includes: Category, Type, Wetness, Weight, Contact, Notes, Date
       
       * Helps buyers  to view available organic waste
       

***

🌐 **Frontend Pages**

* **Landing Page**:

  
<img width="1880" height="883" alt="Screenshot 2025-07-18 155521" src="https://github.com/user-attachments/assets/eeaf39c6-9d17-4c48-9d60-bcb23583c5bf" />


* **Login/Registration**:

  
<img width="1895" height="748" alt="Screenshot 2025-07-18 155446" src="https://github.com/user-attachments/assets/011fba89-ec85-4322-8592-3d622c9db5c0" />


<img width="1913" height="899" alt="Screenshot 2025-07-18 155500" src="https://github.com/user-attachments/assets/7b34519c-e89f-4709-9f03-f187e9de702b" />


* **Dashboard**:


<img width="1904" height="903" alt="Screenshot 2025-07-27 184543" src="https://github.com/user-attachments/assets/bd2ee2c3-d8a7-417b-82bb-16454c3cc771" />


* **Seller Page**:

  
<img width="1903" height="887" alt="Screenshot 2025-07-18 160005" src="https://github.com/user-attachments/assets/396fe889-986c-4ae8-924e-66a311924249" />


* **Shopping Page**:

  
<img width="1863" height="888" alt="Screenshot 2025-07-18 155740" src="https://github.com/user-attachments/assets/6fb9ec2e-121d-47fd-9444-c37686386b19" />


* **User Guide Pages**:

  
<img width="1895" height="879" alt="Screenshot 2025-07-18 155645" src="https://github.com/user-attachments/assets/d3d9d00c-b8d7-4c9e-a593-2ee8f43fd74f" />


<img width="1896" height="893" alt="Screenshot 2025-07-18 155656" src="https://github.com/user-attachments/assets/ebad0ad1-5962-467c-b98c-f5f08a466e40" />


<img width="1884" height="902" alt="Screenshot 2025-07-18 155722" src="https://github.com/user-attachments/assets/2e11a4d7-5700-47c0-bd68-95648508e815" />


* **Contact Us Page**:


<img width="1889" height="908" alt="Screenshot 2025-07-18 155559" src="https://github.com/user-attachments/assets/c95b6a55-8d1e-47bd-9720-5569cd1eb83d" />


* **About Us Page**:


<img width="1879" height="803" alt="Screenshot 2025-07-18 155542" src="https://github.com/user-attachments/assets/d08fc272-2c2c-4701-a16a-73d2ba6daeca" />



* **Seller Details Display Page**:


<img width="1898" height="864" alt="Screenshot 2025-07-18 160105" src="https://github.com/user-attachments/assets/96444cdc-5fe1-4cfa-b6fb-9b92ff4128ec" />


***


🛠️ **How to Run**


  **1. Clone the Repository**

       git clone https://github.com/your-username/organic-waste-management.git

   **2. Set Up the Database**
   
       Open phpMyAdmin or your preferred MySQL tool.
       
       Create a new database (e.g., zam).
       
       Import the provided .sql file with tables like:

            * users
            
            * seller_form
            
            * contact_messages

   **3. Configure Database Connection**
   
        Open the relevant PHP configuration file (e.g., server.php).
        
        Update the database credentials:

           $username = "";
           $email    = "";
           $errors = array(); 
           
           // connect to the database

           
           $db = mysqli_connect('localhost', 'root', '', 'jam');


   **4. Run the Application Locally**
   
        Place all project files inside your local server directory:

        For XAMPP: htdocs/organic-waste-management
        
        Start Apache and MySQL using XAMPP/WAMP.

   **5. Access the Application**
   
        Open your browser and go to:

            http://localhost/organic-waste-management
            

✅ **Now You Can**:

     * Register and log in as a Seller or Buyer
     
     * Submit organic waste via the Seller Form
     
     * View submitted waste data
     
     * Explore compost/biogas tips in the Shopping section
     
     * Contact admin through the Contact Us form


***

🤝 **Contributions:**

      Contributions, issues, and feature requests are welcome! Feel free to submit a pull request or open an issue for discussion.

