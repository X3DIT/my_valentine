💖 Valentine's Day Invitation Web App
A playful, interactive web application designed to ask that special someone to be your Valentine. It features a "dodging" No button, adorable cat animations, heart particle effects, and automatic email notifications.

✨ Features
Personalized Experience: Asks for the user's name before starting the invitation.

The "Shy" No Button: Every time the cursor (or touch) hits the "No" button, it jumps to a random position on the card and displays a funny, pleading message.

Dynamic Visuals: Includes a floating heart background and a heart-explosion effect when they finally say "Yes!"

Email Notifications: Integrated with EmailJS to send you a real-time notification the moment they accept, including their name and the exact time.

Mobile Responsive: Fully optimized for both desktop and mobile screens.

🚀 Live Demo
[Insert your GitHub Pages or Vercel link here]

🛠️ Built With
HTML5 / CSS3: Custom animations and responsive layouts.

JavaScript (Vanilla): Button logic and particle systems.

EmailJS: For serverless email delivery.

⚙️ Setup & Installation
Clone the repository:

Bash

git clone https://github.com/yourusername/valentine-invite.git
Add your Images: Place your images (cat GIFs and JPGs) inside an images/ folder as referenced in the code.

Configure EmailJS:

Sign up at EmailJS.

Create a Service ID and a Template ID.

In the index.html file, update the following lines with your own keys:

JavaScript

emailjs.init("YOUR_PUBLIC_KEY");
// ...
emailjs.send('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', templateParams);
📧 Email Template Configuration
To make the emails look as good as the app, set up your EmailJS template with these variables:

{{name}}: The person who said yes.

{{time}}: The date and time of acceptance.

{{message}}: The confirmation message.

📜 License
This project is for personal use—feel free to use it to ask your crush out! 🥂
