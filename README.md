# 📚 English Center Management System

## 🎯 Overview
English Center Management System (ECMS) is a Full-stack web application designed to digitize and optimize operational management processes at English centers.

## ✨ Key Features:
- Student Management: register, track study progress, and manage personal information.
- Course & Classroom Management: set up class schedules, assign instructors, and manage learning materials.
- Instructor Management: track performance, work schedule, and professional profile.
---

## 🛠️ Tech Stack
This project is built on a modern Client-Server architecture, using the following technologies:

### Backend (Web API & Database)
| Technology |  |
| :--- | :--- |
| C# (.NET) | Main language for building APIs. |
| ASP.NET Core | Framework for high-performance and cross-platform Web API development. |
| Entity Framework Core (EF Core) | ORM (Object-Relational Mapper) to interact with the database. |
| SQL Server** | Database management system used to store data. |

### Frontend (User Interface)
| Technology |  |
| :--- | :--- |
| TypeScript | Primary development language for user interfaces, providing type safety. |
| React | JavaScript library for building component-based user interfaces. |
| SCSS | CSS Preprocessor to write more structured and maintainable CSS. |

---

## 🚀 Getting Started 

### Prerequisites
- .NET SDK
- Node.js (npm/Yarn)
- SQL Server Management Studio 

### Backend Setup
1. Install (optional) Microsoft SQL Server Management Studio (SSMS), visual studio, visual studio code
2. Open SSMS and create new database ex: "englishcenter"
3. Open the appsettings.json file (~\Graduation-Project\Backend\EnglishCenterManagement) and change the DefaultConnection field with the Connection String from the database just created in step 2
4. Open Package Manager Console (in visual studio) -> enter command line: "update-database"
   ![image](https://github.com/ngothilinh20187179/Graduation-Project/assets/74759189/832f9b75-1f92-4b38-a631-cdc1dcad2286)
   ![Untitled](https://github.com/ngothilinh20187179/Graduation-Project/assets/74759189/92a4f11c-e9cd-4bef-b3f1-d6bfba4d0661)
5. Run BE in EnglishCenterManagement.sln (~\Graduation-Project\Backend), the window with path "https://localhost:7054/swagger/index.html" open
  ![image](https://github.com/ngothilinh20187179/Graduation-Project/assets/74759189/b069153d-f005-4174-b8d0-02ff6b243499)

### Frontend Setup

1.  Install Dependencies
    - cd Frontend Web.
    - run: `yarn install`
2.  Start Frontend
    - run: `yarn start`

   ~\Graduation-Project\Frontend Web contains 3 projects about FE, after run see the results, ex:
  ![image](https://github.com/ngothilinh20187179/Graduation-Project/assets/74759189/f178573e-b464-4cdb-8778-280163305b8e)

