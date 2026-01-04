==================================================
BARBERSHOP WEBSITE TEMPLATE - CLASSIC CUTS
==================================================

Thank you for purchasing the "Classic Cuts" template! Your website will be ready in minutes.

--------------------------------------------------
1. ZIP FILE CONTENTS
--------------------------------------------------
When you unzip the file, you will find:
- index.html (Website structure)
- /css/styles.css (Global styles)
- /js/main.js (Mobile menu functionality)
- /img/ (images: hero.png, 1.png, 2.png, etc.)
- README.txt (This document)

--------------------------------------------------
2. KEY EDITING (Customize Your Business!)
--------------------------------------------------
Open the `index.html` file in your code editor (VS Code, Sublime Text, etc.) to make edits.

A. CUSTOMIZING TEXT AND SERVICES:
1. To **ADD a new service**, copy and paste the entire service card block:
    ```html
    <div class="service-card">
            <h3>Service Name</h3>
            <p>Service Description.</p>
    </div>
    ```
    Paste it inside the `<div class="services">` section and edit its content.
2. To **EDIT existing text** (titles, descriptions, hours), simply search for the text in `index.html` and replace it.

B. CONFIGURING CONTACT INFO (WhatsApp, Socials, Address, and Map):

| Element to Edit | Section in `index.html` | Instruction |
| :--- | :--- | :--- |
| **WhatsApp (Button)** | `<section class="hero">` and `<section id="contacto">` | Replace `https://wa.me/5210000000000` with your WhatsApp number. |
| **Social Media** | `<div class="socials">` (in Contact) | Replace the `#` in the `href` attributes of the `<a>` tags with your Instagram and Facebook links. |
| **Contact Address** | `<section id="contacto">` | Edit the text starting with `📍` (your physical address). |
| **Phone Number** | `<section id="contacto">` | Edit the text starting with `📞` (your phone number). |

### **EMBEDDING YOUR LOCATION MAP**

The map requires the Embed URL from Google Maps:

1.  **Find your location on Google Maps.**
2.  In the side menu, click **"Share"**.
3.  Select the **"Embed a map"** tab.
4.  Copy **ONLY the long URL** found inside the `src="URL GOES HERE"` attribute of the `<iframe>` tag.
5.  Paste that complete URL as the new `src` value in the `<section id="ubicacion">` of your `index.html`:
    ```html
    <iframe 
      src="YOUR_NEW_GOOGLE_MAPS_URL"
      loading="lazy">
    </iframe>
    ```
    **Important:** Only paste the URL, without the quotation marks or the rest of the `<iframe>` code.

C. CHANGING GLOBAL COLORS:
1. Open the `/css/styles.css` file.
2. The main accent color (brown/gold, code `#c59d5f`) is used for buttons and links. Edit it in the following lines:
    ```css
    .nav-links li a:hover { color: #c59d5f; }
    .btn { background: #c59d5f; ... }
    .socials a { color: #c59d5f; }
    ```
    Change `#c59d5f` to your desired color code.

D. REPLACING IMAGES:
1. Upload your photos (e.g., `my_cut.png`) to the `/img/` folder.
2. Update the file path in `index.html` (e.g., in the Gallery, change `src="img/1.png"` to `src="img/my_cut.png"`).

--------------------------------------------------
3. LICENSE AND SUPPORT
--------------------------------------------------
This purchase includes a usage license for **ONE UNIQUE PROJECT**. If you have any questions, please contact us [alcantarasotomiguelarturo@gmail.com].