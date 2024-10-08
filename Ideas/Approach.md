# Outline

## Repository Structure & Content Review

Review the content of the repository, particularly the R scripts and console outputs. 

Identify key parts of the project to showcase, such as:

- Script explanations
- Project summaries
- Data visualizations or results from the R scripts

## Plan Website Structure

Homepage: Brief overview of my hackbio internship.

R/Bash Scripts Page: Dynamic loading of script descriptions, including output.

Results Page: Data visualizations or analysis results generated from the R scripts.

Console Logs: Display console outputs in a formatted, readable manner.

## Frontend Development (HTML/CSS/JS)

HTML: Use HTML to create page layouts.
CSS: Style the website for clarity and presentation.
JavaScript: Enable interactivity (e.g., dynamically load R script outputs or toggle visibility of content).

## Dynamic Content (JavaScript or Django)

*Option 1: JavaScript (Client-Side Rendering)*

Write a JavaScript script that reads raw R code and outputs it in a formatted way.
Use JavaScript to display logs/outputs dynamically on the webpage.
JSON could be used to store structured data (e.g., R code metadata) that JavaScript can parse and render dynamically.

*Option 2: Django (Server-Side Rendering)*

Install Django and create a project that fetches content from the repository.
Define Django templates for each section (homepage, script page, etc.).
Use Django views to load R scripts and console outputs from the repo, displaying them in a structured format.

## Integrating Repository Content

R Code Integration: Embed formatted R code into HTML using code blocks. Provide dynamic links to each script stored in your GitHub repository.

Results: dynamically display figures or tables generated from R scripts using <img> or table elements.

Console Outputs: Use <pre> tags to show console logs in a readable format.

## Deploying the Website

Can deploy it using GitHub Pages (if using static HTML/CSS/JS) or a service like Heroku for dynamic Django-based sites.

Note: I used ChatGPT in order to guide me into a direction. 

---
# Sources

## HackBio repository

## Courses and tutorials taken

https://openclassrooms.com/en/courses/5265446

https://openclassrooms.com/en/courses/6967196
