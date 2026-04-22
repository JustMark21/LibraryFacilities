# KBCC L-Building Facilities Fix Campaign

A grassroots, student-led advocacy tool designed to help Kingsborough Community College (KBCC) students respectfully report severe facility outages in the L Building (Library) to Campus Facilities.

## 📌 About the Project

Currently, the L Building lacks basic amenities: there are no working drinking water fountains, and student restrooms on multiple floors are either broken or locked for staff-use only. 

This repository hosts a lightweight, mobile-first web page that allows students to easily generate a pre-formatted, polite email to the KBCC Campus Facilities department (`Service.Issues@kbcc.cuny.edu`). By lowering the barrier to reporting, this tool helps students create a undeniable paper trail of maintenance requests to encourage the administration to prioritize repairs.

## ✨ Key Features

* **Privacy-First (No Data Collection):** The site does not use a backend database or server. It utilizes a dynamic `mailto:` link executed entirely in the user's browser. No personal identifiable information (PII) is ever collected, stored, or transmitted by this site.
* **Anti-Spam Randomization:** To prevent campus IT systems from flagging the campaign as a botnet or spam attack, the JavaScript dynamically randomizes the email subject lines, greetings, openings, and closings for every single user. 
* **Mobile-Optimized:** Designed with a clean, responsive UI (powered by Tailwind CSS) so students can easily fill it out on their phones after scanning a QR code on campus.
* **Frictionless Sharing:** Includes built-in one-tap sharing buttons for WhatsApp and SMS so students can easily circulate the link to their classmates and study groups.
* **Fallback Copy Button:** Includes a "Copy Text" feature for users whose default email clients are not properly configured on their devices.

## 🚀 How to Deploy (GitHub Pages)

This project consists of a single `index.html` file and requires no build steps. 

1. Fork or clone this repository.
2. Go to your repository **Settings**.
3. Navigate to the **Pages** section on the left sidebar.
4. Under **Build and deployment**, set the Source to `Deploy from a branch`.
5. Select the `main` branch and `/root` folder, then click **Save**.
6. GitHub will generate a live URL for your site within a few minutes.

## 📱 How to Use (For Students)

1. Navigate to the live GitHub Pages URL (or scan the campaign QR code).
2. Enter your Full Name in the required field.
3. Tap **Generate & Open Email**.
4. Your device's default email app (Gmail, Apple Mail, Outlook, etc.) will open with the To, Subject, and Body fields fully populated.
5. Review the drafted text and press **Send**.

## ⚠️ Disclaimer

This is an independent student initiative and is not officially affiliated with, endorsed by, or sponsored by Kingsborough Community College (KBCC) or the City University of New York (CUNY). 

Students participating in this campaign are exercising their protected rights to advocate for better campus conditions. Please ensure all communications sent to campus staff remain polite, professional, and strictly related to the maintenance issues.
