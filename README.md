## PriceSpy: E-commerce Product Scraping and Notification Platform

Welcome to PriceSpy, an e-commerce product scraping site developed using Next.js and Bright Data's WebUnlocker. PriceSpy is designed to assist users in making informed purchasing decisions by notifying them when a product drops in price and helping competitors by alerting them when products go out of stock. The entire process is automated and managed through cron jobs

## Features
PriceSpy features a visually appealing header with a carousel showcasing key features and benefits of the platform. It includes a user-friendly search bar that allows users to input Amazon product links for scraping. Detailed information about the products scraped so far is displayed, offering valuable insights into tracked items. The product details section showcases the product image, title, pricing, details, and other relevant information scraped from the original website. A modal enables users to provide their email addresses and opt-in for tracking specific products. Automated email notifications alert users about various scenarios, such as back-in-stock alerts or lowest price notifications. Additionally, cron jobs automate periodic scraping, ensuring that the data is always up-to-date.


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
