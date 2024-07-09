## PriceSpy: E-commerce Product Scraping and Notification Platform

Welcome to PriceSpy, an e-commerce product scraping site developed using Next.js and Bright Data's WebUnlocker. PriceSpy is designed to assist users in making informed purchasing decisions by notifying them when a product drops in price and helping competitors by alerting them when products go out of stock. The entire process is automated and managed through cron jobs

## Features
PriceSpy is a powerful platform developed using Next.js, a framework for server-rendered React applications, and Bright Data's WebUnlocker for web scraping and data extraction. The site features a visually appealing header with a carousel showcasing key features and benefits. Users can input Amazon product links into a user-friendly search bar for scraping. Detailed information about scraped products is displayed, offering valuable insights into tracked items. The product details section showcases the product image, title, pricing, details, and other relevant information scraped from the original website, utilizing Cheerio for parsing and manipulating HTML. A modal, built with Headless UI, enables users to provide their email addresses and opt-in for tracking specific products. Automated email notifications, sent via Nodemailer, alert users about various scenarios such as back-in-stock alerts or lowest price notifications. MongoDB is used to store scraped data and user information, and Tailwind CSS provides a utility-first approach to styling the application. Additionally, cron jobs are utilized to automate periodic scraping, ensuring that the data is always up-to-date.


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
