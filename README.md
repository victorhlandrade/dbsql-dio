# 📘 How to Create an Azure SQL Database

This guide walks you through the steps to create a SQL database instance in Microsoft Azure using the Azure Portal.

![Image](https://github.com/user-attachments/assets/5c9a2a99-989a-4bc9-851e-1870b3ff85ac)

## 🔧 Prerequisites

- An active Azure subscription
- Access to the [Azure Portal](https://portal.azure.com)

## 🚀 Steps to Create an Azure SQL Database

1. **Login to Azure Portal**

   Go to [https://portal.azure.com](https://portal.azure.com) and sign in with your credentials.

2. **Navigate to SQL Databases**

   - In the left-hand menu, select **"SQL databases"**.
   - If there are no existing databases, you will see a message saying:  
     `"No SQL databases to display"`

3. **Click "Create SQL database"**

   - Click the **"+ Create SQL database"** button in the center or at the top of the page.

4. **Configure the Database Basics**

   Fill in the following required fields:
   - **Subscription**: Choose your Azure subscription.
   - **Resource Group**: Select an existing group or create a new one.
   - **Database Name**: Enter a unique name for your SQL database.
   - **Server**: 
     - Choose an existing SQL server or create a new one.
     - When creating a new server, define:
       - Server name
       - Admin login and password
       - Region

5. **Configure Compute + Storage (Optional)**

   - Select the appropriate **compute tier** and **storage size** based on your performance needs.

6. **Networking Settings**

   - Choose the connectivity method.
   - Optionally allow Azure services and resources to access this server.

7. **Additional Settings**

   - Choose whether to use a **sample database**, **backup**, or start **with a blank database**.
   - Optionally configure **Data source**, **Collation**, and **Tags**.

8. **Review + Create**

   - Review your configuration settings.
   - Click **"Create"** to deploy the SQL database.

## ✅ Done!

Once deployment is complete, your new SQL database instance will be available under **SQL databases** in the Azure portal.

---

🧠 *Tip: Always configure proper firewall rules and authentication methods to secure your SQL database.*
