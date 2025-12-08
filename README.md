
<img width="1920" height="1863" alt="image" src="https://github.com/user-attachments/assets/3d5078bf-6a82-46e5-96d2-f476d29e3077" />

githuburl:https://github.com/ankitmor96/media-query-clone


🚀 Project Overview

This project contains a fully responsive webpage layout created using HTML and CSS Flexbox, enhanced with media queries to ensure the design adjusts smoothly across mobile, tablet, and desktop screen sizes.

The layout includes:

Navigation bar

Secondary navbar

Hero section (container-1)

Image & content boxes

Additional content containers

Footer

📂 File Structure
project-folder/
│── index.html
│── style.css
│── images/
│     └── (your images)
└── README.md
🎨 CSS Structure Explained
1. Global Reset

Removes default margins, padding, and sets box sizing.

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
2. Navbar Styling

Flexbox used for alignment

Logo aligned using margin

Hover effects added for list items

3. Container Sections

.container-1 uses a side-by-side layout

.container-2, .container-3, .container-4 handle text and cards

4. Footer

Simple flex layout with centered content

📱 Media Queries Breakdown

Your project uses 4 responsive breakpoints:

### 🔹 @media (max-width: 576px) – Mobile

Hides header

Stacks .container-1 vertically

Makes images full width

Boxes become full width

🔹 @media (max-width: 768px) – Small Tablets

Navbar padding adjusts

Containers stack vertically

Images reduce width

🔹 @media (max-width: 992px) – Tablets

Content containers become centered

Flex items wrap

🔹 @media (max-width: 1200px) – Laptops

Adjusts logo spacing

Sets container width to full

🛠️ Technologies Used

HTML5

CSS3

Flexbox

Media Queries

🙌 Author

Created by Ankit Mor

Feel free to update and improve this README as your project grows!
