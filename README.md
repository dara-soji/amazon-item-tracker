<div align="center">

  <h3 align="center">Amazon Item Tracker Application</h3>

   <div align="center">
     Track price changes and availability of Amazon products using a web scraping engine built with JavaScript/TypeScript. Supports scheduled tracking, alert notifications, and data persistence for historical analysis.
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Links](#links)
7. 🚀 [More](#more)


## <a name="introduction">🤖 Introduction</a>

This Amazon product tracker is built with Next.js and leverages Bright Data's Web Unlocker to bypass bot protection and accurately scrape e-commerce data. It empowers users to make smarter shopping decisions by notifying them when product prices drop, and helps businesses stay competitive by alerting them when rival listings go out of stock. All tasks are scheduled and managed via robust cron jobs, ensuring continuous, hands-free operation.

## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- Bright Data
- Cheerio
- Nodemailer
- MongoDB
- Headless UI
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Header with Carousel**: Visually appealing header with a carousel showcasing key features and benefits

👉 **Product Scraping**: A search bar allowing users to input Amazon product links for scraping.

👉 **Scraped Projects**: Displays the details of products scraped so far, offering insights into tracked items.

👉 **Scraped Product Details**: Showcase the product image, title, pricing, details, and other relevant information scraped from the original website

👉 **Track Option**: Modal for users to provide email addresses and opt-in for tracking.

👉 **Email Notifications**: Send emails product alert emails for various scenarios, e.g., back in stock alerts or lowest price notifications.

👉 **Automated Cron Jobs**: Utilize cron jobs to automate periodic scraping, ensuring data is up-to-date.

and many more, including code architecture and reusability 

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/dara-soji/amazon-item-tracker.git
cd AmazonItemTracker
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
#SCRAPER
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

#DB
MONGODB_URI=

#OUTLOOK
EMAIL_USER=
EMAIL_PASS=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these specific websites from [BrightData](https://brightdata.com/), [MongoDB](https://www.mongodb.com/), and [Node Mailer](https://nodemailer.com/)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

