# StickyChat.js 💬

![jQuery](https://img.shields.io/badge/jQuery-%230769AD.svg?style=flat&logo=jquery&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Size](https://img.shields.io/badge/Size-Under_2KB-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

An elegant, responsive, flexible, and lightweight jQuery plugin that adds a sticky WhatsApp floating chat button to your website. 

Built with modern CSS (Flexbox, CSS Variables, Backdrop Filters) and zero image dependencies (pure SVG).

### 🌟 See it in action:
![StickyChat Demo](lib/demo.gif)

## ✨ Features
* **Extremely Lightweight:** Under 2KB zipped.
* **Modern Design:** Uses glassmorphism (backdrop-filter) for the tooltip.
* **Responsive:** Adapts automatically to mobile screens.
* **Accessible:** Includes ARIA labels and `noopener noreferrer` tags for secure external links.
* **Customizable:** Easily change colors, messages, and positioning via JS or CSS variables.

# 🚀 Usage

$(document).ready(function() {
    $('body').stickyChat({
        phoneNumber: "1234567890", // Your country code + number (no + sign)
        message: "Need help? Chat with us!",
        position: "right", 
        defaultText: "Hi! I found your website and need some assistance."
    });
});

## Configuration Options (API)

1. phoneNumber String	"1234567890"	The WhatsApp number (include country code, no +).
2. message	String	"Chat with us on WhatsApp!"	The text inside the hover bubble.
3. position	String	"right"	Choose "left" or "right" side of the screen.
4. backgroundColor	String	"#25D366"	The color of the button background.
5. defaultText	String	"Hello..."	The pre-filled message that appears in the WhatsApp app.


## To contribute:

1. Fork the Project

2. Create your Feature Branch (git checkout -b feature/AmazingFeature)

3. Commit your Changes (git commit -m 'Add some AmazingFeature')

4. Push to the Branch (git push origin feature/AmazingFeature)

5. Open a Pull Request

This project is licensed under the MIT License. Feel free to use it in personal and commercial projects.
**Would you like me to walk you through the Git commands to initialize this project, commit these files, and push them up to your new GitHub repository?**

## 🚀 Installation

1. Download the `jquery.stickychat.css` and `jquery.stickychat.js` files.
2. Include them in your HTML file, making sure jQuery is loaded first.

```html
<link rel="stylesheet" href="css/jquery.stickychat.css">

<script src="[https://code.jquery.com/jquery-3.7.1.min.js](https://code.jquery.com/jquery-3.7.1.min.js)"></script>
<script src="js/jquery.stickychat.js"></script>
