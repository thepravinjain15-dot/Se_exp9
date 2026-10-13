# SE_EXP9 --- Business Dashboard

A simple responsive business dashboard built with HTML, CSS, and
JavaScript. The project includes a landing page that directs users to a
dashboard for viewing sample business metrics, revenue charts, and
recent orders.

## Features

-   Landing page with **Get Started** and **Open Dashboard** navigation
-   Dashboard overview with sample revenue, customer, order, and product
    statistics
-   Revenue chart with weekly/monthly selection
-   Order-status doughnut chart
-   Recent orders table with status labels
-   Responsive layout for desktop and mobile screens

## Project Structure

``` text
Se_exp9/
├── index.html       # Landing page
├── dashboard.html   # Dashboard page
└── README.md        # Project documentation
```

> If your current dashboard is still named `index.html`, rename it to
> `dashboard.html` before creating the new landing page as `index.html`.

## Run Locally

### Option 1: Python HTTP server

1.  Open a terminal in the project folder.

2.  Start a local server:

    ``` bash
    python3 -m http.server 8000
    ```

3.  Open <http://localhost:8000> in your browser.

4.  Select **Get Started** to open the dashboard.

Stop the server with `Ctrl + C`.

### Option 2: Open the file directly

Open `index.html` in a browser. Some browser features may behave
differently when files are opened directly, so the local server option
is recommended.

## Technologies Used

-   HTML5
-   CSS3
-   JavaScript
-   [Chart.js](https://www.chartjs.org/) for dashboard charts, loaded
    from a CDN

An internet connection is required to load Chart.js from the CDN.

## Important Note

The revenue figures, customer counts, orders, and chart values in the
sample dashboard are demonstration data. They are not connected to a
live database or real business system.

## Git Commands

After editing or adding files, run these commands from the project
directory:

``` bash
git status
git add index.html dashboard.html README.md
git commit -m "Add landing page and project documentation"
git push
```

These commands assume that the GitHub remote is configured and you are
authenticated. If you removed the remote, check it with:

``` bash
git remote -v
```

To reconnect the repository, add your repository URL as the `origin`
remote:

``` bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Replace the example URL with your actual repository URL. Never put a
Personal Access Token directly into the remote URL or commit it to the
repository.
