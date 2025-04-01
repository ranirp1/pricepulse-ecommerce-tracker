# PriceWise: E-Commerce Price Tracking Application 

PriceWise is a web application that tracks product prices from e-commerce websites (like Amazon) and notifies users when prices drop or items come back in stock. Built with Next.js, it demonstrates modern web scraping techniques and automated notification systems.

## ✨ Features

✅ **Amazon Product Scraping** - Extract product details with just a URL. <br> 
✅ **Price Drop Alerts** - Get email notifications when prices fall. <br> 
✅ **Stock Monitoring** - Receive alerts when when out-of-stock items become available. <br> 
✅ **Automated Cron Jobs** - Regular price checks without manual intervention. <br> 
✅ **User-Friendly UI** - Clean interface built with Tailwind CSS and Headless UI. <br> 

## 🛠 Tech Stack
**Frontend:**<br>
![Next.js](https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000)
![TypeScript](https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4)
![Headless UI](https://img.shields.io/badge/-Headless_UI-black?style=for-the-badge&logoColor=white&logo=headlessui&color=66E3FF)

**Backend:**<br>
![Next.js API](https://img.shields.io/badge/-Next.js_API-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000) 
![Bright Data](https://img.shields.io/badge/-Bright_Data-black?style=for-the-badge&logoColor=white&logo=brightdata&color=FF6C37) 
![Cheerio](https://img.shields.io/badge/-Cheerio-black?style=for-the-badge&logoColor=white&logo=cheerio&color=3E863D)

**Database:**<br>
![MongoDB](https://img.shields.io/badge/-MongoDB-black?style=for-the-badge&logoColor=white&logo=mongodb&color=47A248) 
![Mongoose](https://img.shields.io/badge/-Mongoose-black?style=for-the-badge&logoColor=white&logo=mongoose&color=880000)

**Utilities:**<br> 
![Nodemailer](https://img.shields.io/badge/-Nodemailer-black?style=for-the-badge&logoColor=white&logo=nodemailer&color=339933) 
![Cron Jobs](https://img.shields.io/badge/-Cron_Jobs-black?style=for-the-badge&logoColor=white&logo=cron&color=5E3BEE)

## 🚀 Getting Started
**☑️ Prerequisites**
- Node.js (v18 or later)
- MongoDB Atlas account
- Bright Data account (for scraping)
- Email service credentials (for notifications)

**☑️ Installation**
1. Clone the repository:
    ```bash
    git clone https://github.com/ranirp1/pricepulse-ecommerce-tracker.git
    cd pricepulse-ecommerce-tracker
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the root directory
    - Copy the structure from `.env.example` and fill in your credentials

4. Run the development server:
    ```bash
    npm run dev
    ```

## ⚙️ Configuration
### Environment Variables
| Variable | Description | Example |
|----------|-------------|---------|
| BRIGHT_DATA_USERNAME | Bright Data account username | user123 |
| BRIGHT_DATA_PASSWORD | Bright Data account password | pass123 |
| MONGODB_URI | MongoDB connection string | mongodb+srv://... |
| EMAIL_USER | Email service username | your@email.com |
| EMAIL_PASS | Email service password | yourpassword |

## 🔍 How It Works
1. User adds a product URL (e.g., Amazon product page)
2. Backend scrapes the product page using Bright Data proxy
3. Product data is stored in MongoDB with price history
4. Cron jobs run periodically to check for price changes
5. Users receive email notifications when:
    - Price drops below a threshold
    - Product comes back in stock
    - Price reaches historical low

## 📄 License
This project is licensed under the [MIT License](./LICENSE) - see the LICENSE file for details.

 <h3 align="center"> ʘ‿ʘ </h3>



