Product Landing Page App
A modern, high-conversion responsive product landing page built with semantic HTML5 and advanced CSS Flexbox. This project fulfills all technical specifications, form validation constraints, and automated lab test cases for robust web applications.

1. Project Overview & Architecture
The Product Landing Page App is engineered for high-performance marketing and product promotion. It features a fixed-top responsive navigation bar, fluid content structuring via Flexbox, an embedded product showcase video, and integrated HTML5 email subscription capture.

+-----------------------------------------------------------------+
|     LOGO      |                      NAV BAR                    |
+-----------------------------------------------------------------+
|                                                                 |
|                      HERO & EMAIL CAPTURE                       |
|                                                                 |
+-----------------------------------------------------------------+
|                         FEATURE CARDS                           |
+-----------------------------------------------------------------+
|                    EMBEDDED PRODUCT VIDEO                       |
+-----------------------------------------------------------------+
|                         PRICING TIERS                           |
+-----------------------------------------------------------------+
|                            FOOTER                               |
+-----------------------------------------------------------------+
2. Technical Specifications & Layout Design
The core architecture relies on modern CSS Flexbox and fixed layout positioning:

A. Fixed Navigation Bar
Utilizes position: fixed; top: 0; left: 0; width: 100%; to anchor the navbar to the top of the viewport at all times.

Built with a flex layout (display: flex; justify-content: space-between; align-items: center;) to evenly distribute brand elements and interactive link targets.

B. Form Validation & Submission
Implements native HTML5 validation via type="email" and required attributes on the input field.

Routes data submissions directly to the required mock verification endpoint (action="[https://www.freecodecamp.org/email-submit](https://www.freecodecamp.org/email-submit)").

3. Detailed File Structure
Plaintext
product-landing-page-app/
│
├── index.html              # Core semantic structure containing all landmark tags
├── styles.css              # Flexbox grid systems, responsive styling, and custom variables
└── README.md               # Comprehensive project documentation and guide
4. Setup, Installation & Local Development
To get a local copy of this repository up and running on your machine, follow these simple steps using your terminal:

Step 1: Clone the Repository
Bash
git clone https://github.com/Regalson001/product-landing-page-app.git
Step 2: Navigate to the Project Directory
Bash
cd product-landing-page-app
Step 3: Open in Your Editor or Browser
Open the directory in VS Code:

Bash
code .
Launch index.html using a local development server (such as the VS Code Live Server extension) or open it directly in your web browser.

5. Development Roadmap & Future Enhancements
[x] Phase 1: Implement semantic HTML5 landmark structure (header, nav, main, form, footer).

[x] Phase 2: Integrate CSS Flexbox layout mechanics and fixed-top viewport positioning.

[x] Phase 3: Configure automated test constraints, responsive video embeds, and email input validation.

[ ] Phase 4: Add interactive modal dialogs for product customization previews.

[ ] Phase 5: Implement backend API integration for live email lead capture.

6. Author & License
Author: Oyugi (Regalson001)

Course/Track: Software Development & Technical Engineering Lab

License: Distributed under the MIT License. See LICENSE for more information.
