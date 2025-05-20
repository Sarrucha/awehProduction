# 🛡️ Aweh Productions Vaccination Verification System

## 📌 Project Overview
This cloud-based solution was developed for Aweh Productions to verify vaccination status at event entrances. The system uses **Azure Functions with a Queue Trigger** to process incoming vaccination records and store them securely in an **Azure SQL Database**.

## 🚀 Technologies Used
- Azure Function App (Queue Trigger)
- Azure Storage Queue
- Azure SQL Database
- .NET Core Console Application
- Microsoft Azure Portal
- Visual Studio

## 🧩 Key Features
- Queue-triggered Azure Function for asynchronous processing  
- .NET Core Console App to send formatted vaccination messages to the queue  
- Automatic storage of vaccination records in Azure SQL Database  
- Supports multiple data formats from different vaccine providers  
- Scalable, serverless architecture with minimal operational cost  

## 🏁 Final Project Outcome
- ✅ Developed a robust **Queue-Triggered Azure Function**  
- ✅ Processed vaccination data asynchronously via **Azure Storage Queue**  
- ✅ Inserted verified records into **Azure SQL Database**  
- ✅ Ensured support for **varied input formats**  
- ✅ Deployed and tested the entire solution in a **live Azure environment**

## 📺 Demonstration Video
You can view a walkthrough of the working system here:  
🔗 [Aweh Productions Function Verification System - Demo](https://drive.google.com/file/d/12O3r2gcEKvz-bxKRgu6mvFWBZQz5vSd4/view?usp=drive_link)

> ⚠️ **Disclaimer:** I no longer have access to the Azure portal where the application was deployed. However, the video above demonstrates the final working version of the system in action.

## 🧪 Sample Message Formats
ID123456789:CenterA:2024-01-10:VAC001
VAC987654321:2024-01-12:CenterB:ID54321


## 🧪 Testing Summary
- Ran the .NET Console App to send test messages to the queue  
- Verified queue messages appeared in Azure portal  
- Confirmed accurate insertion of each record into SQL database  
- Validated successful function execution via Azure logs  

## 📬 Connect with Me
- 📧 Email: [lwazi094@gmail.com](mailto:lwazi094@gmail.com)
