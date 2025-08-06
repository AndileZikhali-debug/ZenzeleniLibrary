# ZenzeleniLibrary

Library Card Generator
A static website for generating professional library cards. Users can input library and member details, preview the card, and download it as a PNG image. Built with React, Tailwind CSS, and html2canvas.
Setup

Clone the Repository:
git clone https://github.com/your-username/library-card-generator.git
cd library-card-generator


Install Dependencies:No dependencies need to be installed since the app uses CDN-hosted React, Tailwind CSS, and html2canvas.

Run Locally:Serve the index.html file using a local server. For example, with Python:
python -m http.server 8000

Then, open http://localhost:8000 in your browser.


Deployment to GitHub Pages

Create a GitHub Repository:

Go to GitHub and create a new repository named library-card-generator.
Push the files (index.html, README.md, .gitignore) to the repository.


Enable GitHub Pages:

In the repository settings, go to the "Pages" section.
Set the source to the main branch and the / (root) folder.
Save, and GitHub will provide a URL (e.g., https://your-username.github.io/library-card-generator).


Access the App:

Once deployed, visit the GitHub Pages URL to use the app.



File Structure

index.html: Main HTML file with React app and Tailwind CSS.
README.md: This file with setup and deployment instructions.
.gitignore: Ignores unnecessary files (e.g., node_modules, though none are used here).

Customization

Logo: Replace the gray logo placeholder in LibraryCard component with an <img> tag pointing to your logo URL.
Styles: Modify Tailwind CSS classes in index.html to change colors, fonts, or layout.
Barcode: The barcode is a placeholder; integrate a library like jsbarcode for real barcodes.

Notes

The app uses CDN-hosted libraries for simplicity, making it a true static site.
To generate multiple cards, you can extend the app by adding a list of members and rendering multiple LibraryCard components.
For PDF downloads, consider integrating jsPDF (add via CDN and update the handleDownload function).
