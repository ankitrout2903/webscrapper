## Web Scraper with Next.js and Bright Data

This repository contains a web scraper application built with Next.js and various tools to automate data extraction from websites.

**Description:**

This web scraper utilizes the power of Next.js for a server-rendered React application and leverages Bright Data's residential proxies to bypass website restrictions and access data reliably. It employs Cheerio for efficient HTML parsing and manipulation, allowing easy extraction of the desired information. Nodemailer facilitates sending email notifications when specific data changes are detected. The scraped data is stored in a MongoDB database for persistence and future analysis. Headless UI components provide a foundation for building accessible and responsive user interfaces to interact with the scraped data. Tailwind CSS offers a utility-first approach to styling the application, ensuring a modern and consistent look and feel.

**Tech Stack:**

* **Frontend:** Next.js
* **Scraping:** Bright Data, Cheerio
* **Notifications:** Nodemailer
* **Database:** MongoDB
* **UI Components:** Headless UI
* **Styling:** Tailwind CSS

**Getting Started:**

1. Clone the repository:

   ```bash
   git clone https://github.com/ankitrout2903/webscrapper
   ```

2. Install dependencies:

   ```bash
   cd webscraper
   npm install
   ```

3. Configure Bright Data (refer to their documentation for setup instructions):
    - Create a Bright Data account and obtain your API key.
    - Set the `BRIGHTDATA_API_KEY` environment variable with your API key.

4. Configure MongoDB connection (refer to MongoDB documentation for connection details):
    - Set the `MONGODB_URI` environment variable with your MongoDB connection string.

5. Start the development server:

   ```bash
   npm run dev
   ```

**Features (may vary based on implementation):**

* Schedule scraping tasks to run periodically.
* Define scraping targets and desired data points.
* Persist scraped data in MongoDB for historical analysis.
* Send email notifications when specific data changes occur.
* User interface to view and interact with the scraped data (optional).

**Disclaimer:**

Please be aware of the website's terms and conditions when using scraping tools. This application is for educational purposes only, and responsible use is encouraged.
