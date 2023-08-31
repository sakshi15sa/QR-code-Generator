# QR-code-Generator
QR Code Generator HTML Documentation
Table of Contents
Introduction
HTML Structure
Document Declaration
Head Section
Body Section
Wrapper
Header
Input Form
QR Code Display
Script
Introduction
This document provides comprehensive documentation for the HTML code that constructs a QR Code Generator using JavaScript. This generator enables users to either paste a URL or enter text, and subsequently create a QR code image based on the input.

HTML Structure
The DOCTYPE declaration defines the document type and version of HTML being used, while the <html> element is the root element encapsulating the entire HTML document.
Head Section
The <head> section contains metadata and external resources for the document.

<meta charset="utf-8">: Specifies the character encoding for the document.
<title>: Sets the title of the web page, which is displayed in the browser tab.
<link rel="stylesheet" href="style.css">: Links an external stylesheet (style.css) for styling the page.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Configures the initial scaling behavior for different devices.
QR Code Display
The .qr-code div section is designated for displaying the generated QR code image. The src attribute of the <img> element is dynamically updated to showcase the generated QR code.
Script
The <script> tag references an external JavaScript file (script.js) that is expected to hold the logic for generating the QR code based on user input.
