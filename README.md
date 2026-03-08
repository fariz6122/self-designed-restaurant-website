The Grand Awadh Fine Dining Website
This repository contains a professional, responsive single-page website for The Grand Awadh, a premium restaurant specializing in authentic Awadhi cuisine. The project features a modern dark-themed aesthetic with integrated WhatsApp ordering and reservation systems.

 Features
Premium Visual Design: A sophisticated dark UI with gold accents (#c5a059) and elegant typography using Playfair Display and Poppins.

Interactive Menu & Cart: A dynamic ordering system where users can select dishes, adjust quantities, and see a real-time bill calculation.

WhatsApp Integration: Both the "Order Now" and "Book a Table" features automatically format data and bridge directly to WhatsApp for instant communication with the restaurant.

Fully Responsive: Optimized for all devices, including desktops, tablets, and mobile phones.

Smooth Navigation: Features a sticky navigation bar with smooth-scroll transitions between sections (About, Menu, Gallery, etc.).

Chef's Specials Gallery: Showcases signature dishes like Galauti Kebab and Dum Pukht Biryani with high-quality imagery.

 Technologies Used
HTML5: Semantic structure for better SEO and accessibility.

CSS3: Custom styling featuring Flexbox, CSS Grid, and CSS Variables for easy theme management.

JavaScript (Vanilla): Logic for the dynamic shopping cart, price calculations, and WhatsApp message encoding.

Google Fonts: Playfair Display for headers and Poppins for body text.

 Project Structure
index.html: The main website file containing all HTML, CSS, and JS logic.

TGA MENU.pdf: The downloadable full menu referenced in the Chef's Specials section.

Assets/: (Optional) Folder for local images if not using external URLs.

📱 How the WhatsApp System Works
The website uses custom JavaScript listeners to capture form data. Upon clicking "Place Order" or "Confirm Booking":

The script gathers customer details (Name, Phone, Address, Guests).

It compiles the ordered items into a formatted list.

It encodes the text and opens a WhatsApp API link (https://api.whatsapp.com/send?phone=...) to send the message automatically to the restaurant's administration number.

 Customization
To use this for your own business:

Change the Phone Number: Update the adminNumber and whatsappNumber variables in the <script> section to your personal WhatsApp number (include country code without the +).

Update the Menu: Modify the dishes array in the JavaScript to reflect your actual items and prices.

Update Contact Info: Change the address, phone, and email in the "Contact Us" section.

Created by Faris.
