# Gaushala CRM

## Overview
Gaushala CRM is a comprehensive management system developed by **AGS Solution** for efficiently handling donor lists, animal stock, receipts, reports, and other administrative functionalities. The system provides a user-friendly interface and robust features to streamline operations.

## Project Structure
```
gaushala-crm/
├── README.md
├── index.html
├── package.json
├── postcss.config.cjs
├── tailwind.config.cjs
├── vite.config.js
├── public/
│   └── img/
└── src/
    ├── App.css
    ├── App.jsx
    ├── index.css
    ├── main.jsx
    ├── components/
    │   ├── DashboardNavbar.jsx
    │   ├── SideNav.jsx
    │   ├── Footer.jsx
    │   ├── ProtectedRoute.jsx
    │   ├── Logout.jsx
    │   ├── common/
    │   │   ├── AnimalStockFilter.jsx
    │   │   ├── DisableRightClick.jsx
    │   │   ├── DropDown.jsx
    │   │   ├── EncryptDecrypt.jsx
    │   │   ├── PageTitle.jsx
    │   │   ├── TextField/
    │   │   │   ├── FamilyDropDown.jsx
    │   │   │   ├── TextField.jsx
    │   │   └── dataCard/
    │   │       └── CommonCard.jsx
    ├── layout/
    │   └── Layout.jsx
    ├── pages/
    │   ├── AnimalStock/
    │   │   ├── Animal/
    │   │   │   ├── Animal.jsx
    │   │   │   ├── CreateAnimal.jsx
    │   │   │   └── EditAnimal.jsx
    │   │   ├── AnimalBornArrival/
    │   │   │   ├── AnimalBornArrival.jsx
    │   │   │   └── CreateBornArrival.jsx
    │   ├── DonorList/
    │   │   ├── AddDonorList.jsx
    │   │   ├── DonorDetails.jsx
    │   │   ├── EditDonorList.jsx
    │   │   ├── ViewDonorDetails.jsx
    │   ├── Reports/
    │   │   ├── StockReport.jsx
    │   │   ├── ViewStockSummary.jsx
    │   ├── WebDonation/
    │   │   └── WebDonation.jsx
    │   ├── auth/
    │   │   ├── SignIn.jsx
    │   │   ├── SignUp.jsx
    │   │   ├── ForgetPassword.jsx
    │   ├── profile/
    │   │   ├── Profile.jsx
    │   │   ├── ChangePassword.jsx
    ├── utils/
    │   └── ContextPanel.jsx
```

## Installation
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- [Vite](https://vitejs.dev/)

### Steps to Set Up
1. Clone the repository:
   ```sh
   git clone <https://github.com/AG-Solutions-Bangalore/gaushala-crm>
   cd gaushala-crm
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm run dev
   ```
4. Build for production:
   ```sh
   npm run build
   ```
5. Preview the build:
   ```sh
   npm run preview
   ```

## Tech Stack
- **Frontend**: React, Vite, TailwindCSS, Material UI
- **State Management**: React Context API
- **Routing**: React Router
- **Charts & Reports**: Chart.js, ApexCharts
- **Utilities**: Moment.js, Day.js, Crypto.js

## Features
- 🏠 **Dashboard**: Overview of stats and analytics
- 🐄 **Animal Stock Management**: CRUD operations for animals
- 💰 **Donor Management**: Manage donations and receipts
- 📜 **Reports**: Generate and download reports
- 🔐 **Authentication**: Secure login, signup, and password management
- 📥 **Downloads**: Various modules for downloading reports

## Environment Variables
Create a `.env` file in the root directory and add the required variables:
```sh
VITE_API_BASE_URL=<your_api_base_url>
```

## Contribution Guidelines
1. Fork the repository.
2. Create a feature branch (`feature/your-feature-name`).
3. Commit your changes with a meaningful message.
4. Push the branch and create a pull request.

## License
This project is private and proprietary to **AGS Solution**.

## Contact
For any queries, contact **AGS Solution**.

---

### Notes
- The project uses `vite` for fast development.
- TailwindCSS is configured for styling.
- React Context API manages state globally.

---
📌 **Happy Coding!** 🚀

