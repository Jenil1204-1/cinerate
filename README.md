🎬 CineRate — Movie Review & Rating Analysis Website

A fully interactive movie review platform with rating calculation, image slider, show/hide reviews, and a contact form. Designed in Figma and deployed via Google Sites embed.


📌 Project Information
FieldDetailsProject TitleMovie Review & Rating Analysis WebsiteSubjectWeb Design & DevelopmentPlatformGoogle Sites (via HTML Embed)Design ToolFigmaTechnologyHTML5, CSS3, Vanilla JavaScriptAuthorJenil — KU2507U0548UniversityKarnavati University

🎯 Objective
To design and develop a movie review platform that allows users to browse movies, read and hide reviews, calculate ratings using an interactive calculator, submit their own reviews, and contact the platform — all within a visually rich, cinema-themed interface.

🗂️ Pages
PageDescriptionHomeHero banner, image slider (3 featured films), trending movies grid, buttons showcase, about stripMoviesFull movie grid (12 films), genre filter buttons, rating badges, per-card action buttonsReviewsRating calculator with sliders, submit review form, user review cards with show/hideContactContact form, info cards (email, location, response time), social links

🖱️ Required UI Buttons (All 5 Implemented)
ButtonLocationFunctionView ReviewMovie cards, Review cardsShows the hidden review textHide ReviewMovie cards, Review cardsHides the review textCalculate RatingReviews page, Movie cardsComputes average from 5 category slidersSubmit ReviewReviews page formAdds a new review card dynamically to the pageContactNavbar, Home page, Contact formNavigates to Contact page / submits the form

⚙️ Functional Features
🖼️ Image Slider

3 featured movie slides with auto-play (4 seconds interval)
Left / Right arrow navigation
Dot indicator navigation
Auto-play pauses on mouse hover

👁️ Show / Hide Reviews

Each review card has independent View Review and Hide Review buttons
Review text toggles visibility without page reload
Toast notification confirms the action

🧮 Rating Calculator

5 category sliders: Story, Acting, Direction, Visuals, Music
Each slider ranges from 1–10
Live average is recalculated on every slider move
Final result displayed in large format with a Calculate button

✍️ Submit Review (Dynamic)

User fills Movie Name, Their Name, Review text, and Star Rating
On submit, a new review card is injected at the top of the reviews list
Form clears after successful submission
Validation ensures no empty fields

📩 Contact Form

Fields: Full Name, Email, Subject, Message
Validation on submit
Toast confirmation on success

🔍 Genre Filter (Movies Page)

Filter buttons: All, Action, Drama, Sci-Fi, Comedy, Crime
Movies grid re-renders instantly based on selected genre


🗃️ File Structure
cinerate-project/
│
├── cinerate-website.html     ← Main website file (single-file app)
├── README.md                 ← This file

The entire site is a single self-contained HTML file — no external dependencies beyond Google Fonts (Bebas Neue + DM Sans loaded via CDN).


🚀 How to Deploy on Google Sites
Google Sites does not support direct code editing, but it supports embedding external URLs as iframes. Follow these steps:
Step 1 — Host the HTML file on GitHub Pages (Free)

Create a free account at github.com
Click New Repository → Name it cinerate
Upload cinerate-website.html → rename it to index.html
Go to Settings → Pages → Branch: main → Save
Wait ~2 minutes → Your live URL: https://yourusername.github.io/cinerate

Step 2 — Embed into Google Sites

Open sites.google.com → Create a new site
On any page, click Insert → Embed
Select the By URL tab
Paste your GitHub Pages URL (e.g. https://yourusername.github.io/cinerate)
Click Insert → Resize the embed block to full width
Click Publish (top right corner)

✅ Your CineRate site is now fully visible and functional inside Google Sites.

⚠️ Important Note on Google Sites Limitations
MethodWhat Works✅ Embed via URL (GitHub Pages)Full JS, CSS, animations, all buttons❌ Paste raw HTML into embed boxJS is stripped, buttons won't work
Always use the hosted URL method for full functionality.

🎨 Design Details
ElementChoiceColor SchemeDark cinema theme — #080810 background, #E50914 red accentFontsBebas Neue (headings) + DM Sans (body)Card StyleDark glass cards with subtle border and hover liftRating BadgeAmber (#F5A623) pill badges on poster imagesButtons5 distinct styles — Red, Amber, Green, Blue, GhostSliderCSS transition with JS-controlled transformFigma DesignView Figma File

🧪 Testing Checklist

 Image slider auto-plays and arrows work
 Slider dots navigate correctly
 All 4 nav links navigate to correct pages
 Genre filters show correct movies
 View Review button makes text visible
 Hide Review button hides text
 Rating calculator sliders update average live
 Calculate Rating button shows toast
 Submit Review form validates empty fields
 Submitted review appears at top of list
 Contact form validates and shows confirmation
 All 5 required buttons present and functional
 Site renders correctly inside Google Sites embed


📚 Technologies Used

HTML5 — Semantic page structure
CSS3 — Custom properties, Grid, Flexbox, transitions, animations
Vanilla JavaScript — DOM manipulation, event handling, dynamic rendering
Google Fonts CDN — Bebas Neue, DM Sans
Figma — UI/UX wireframe and design prototype


📄 License
This project is submitted as an academic assignment for Karnavati University. All movie titles and related content are referenced for educational purposes only.
