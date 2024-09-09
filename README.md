## Image to PDF Converter
A simple web application that allows users to convert images to PDF files.

### Table of Contents
* [Introduction](###Introduction)
* [Features](###Features)
* [Prerequisites](###Prerequisites)
* [Getting Started](###Getting-Started)
* [Project Structure](###Project-Structure)
* [Usage](###Usage)
* [Dependencies](###Dependencies)
* [Contributing](###Contributing)

### Introduction
The Image to PDF Converter is a web application built with Express.js that enables users to convert images into PDF documents. It provides a user-friendly interface for uploading images and generating PDF files effortlessly.

### Features
* **Image to PDF Conversion:** Upload multiple images and convert them into a single PDF file.
* **Sortable Images:** Arrange the order of images using drag-and-drop functionality.
* **Responsive Design:** The site is designed to work seamlessly on various devices and screen sizes.

### Prerequisites
Before you begin, ensure you have the following installed:
* [Node.js](https://nodejs.org/en)
* [npm](https://www.npmjs.com)

### Getting Started
1. Clone the repository:
```bash
git clone https://github.com/your-username/image-to-pdf-converter.git
```
2. Navigate to the project directory:
```bash
cd image2pdf
```
3. Install dependencies:
```bash
npm install
```
4. Set the debug environment variable:
```bash
set DEBUG=img2pdf:*  # On Windows
```
or
```bash
export DEBUG=img2pdf:*  # On Linux/Mac
```
5. Run the development server:
```bash
npm run devstart
```
or
```bash
npm start
```
6. Open your browser and go to http://localhost:3000.

### Project Structure
* bin: Contains the script to start the server (www).
* node_modules: Node.js modules used in the project.
* public: Static files (HTML, images, JavaScript, stylesheets, PDFs).
* routes: Express.js route files (index.js, users.js).
* views: Jade templates for rendering views.
* app.js: Main application file.
* package.json: Project metadata and dependencies.
* README.md: Project documentation.

### Usage
1. Visit the web application in your browser.
2. Upload one or more images.
3. Arrange the order of images using the drag-and-drop feature.
4. Click the "Convert to PDF" button.
5. Download the generated PDF file.

### Dependencies
* [Express.js](https://expressjs.com): Web application framework.
* express-session: Session middleware.
* [nodemon](https://nodemon.io): Development server with auto-restart.

### FreeCodeCamp.com
Did that project with a freeCodeCamp course.

