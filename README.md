## Portfolio Prototype 
This project is a single-page portfolio prototype aimed at providing students an easy and efficient way to present their achievements, projects, and skills to potential employers. The website is designed to be adaptive and optimized for various screen sizes with a focus on the tablet and desktop breakpoints. It includes multiple sections such as a hero banner, about me, project showcases, and a collaboration form.

**Breakpoints and Responsiveness**
The portfolio follows adaptive design principles with specific breakpoints:
- Mobile: Starts with a flexible layout from 320px and becomes fully adaptive from 375px.
- Tablet: Layout adjusts at 768px.
- Desktop: Full desktop view from 1440px.

**Project Structure**
The website contains the following sections:
- Header: Contains logo, site navigation, and "Order the project" button.
On mobile, the navigation is hidden behind a burger menu, revealed via JavaScript on click.
- Hero: Displays the main heading “Hello. I’m Fullstack developer Lloyd Jefferson.”
Includes social media links and a contact email, all implemented using an unordered list (<ul>).
The background is set using a .png image.

- About Me: Features a hidden heading for SEO and screen readers.
Provides information about the student, their experience, and skills.
Skills list is presented as a horizontal slider using Swiper.js.

- Benefits: Highlights the advantages of working with the student, structured as an unordered list.
- Projects: Includes a horizontal slider of projects, with each project linking to the team’s GitHub page.
- FAQ: Contains a list of frequently asked questions, collapsible via an accordion feature using a JavaScript library.
- Covers: Displays a list of cover images, optionally implemented as a marquee-style row that moves on viewport visibility.
- Reviews: Showcases user reviews, fetched from the backend.
Uses a slider, and if the request fails, displays a fallback "Not found" message.
- Work Together: Displays a form for contacting and collaborating with the student.
Validates the email input using a pattern and processes the submission via a POST request.
On submission, either a success modal appears, or an error message prompts for corrections.
- Modal Window: Thank you message for cooperation, with close actions bound to clicking on the backdrop, the close button, or pressing Escape.

**Technical stack**
- Valid HTML and CSS: Ensured by validators such as W3 HTML Validator and CSS Validator.
- Semantic HTML5: Adheres to HTML5 standards for accessibility and SEO.
- Font Integration: Includes web fonts as specified in the project.
- Image Optimization: Supports retina screens with optimized images. Icons are added via SVG sprite for efficiency.
Images are optimized for fast loading times.
- Interactive Elements: All buttons and links have hover effects.
- Animations: Enhance user experience.

**Features**
- Responsive Design: Adaptable for different screen sizes and devices.
- Smooth Scroll: Anchor navigation with a smooth scrolling effect.
- Form Validation: Inline form validation for email input.
- Dynamic Content: Reviews fetched from the backend with error handling. A modal window for form submission confirmation.

**Dependencies**
- Swiper.js for sliders.
- Accordion library for FAQ and About Me sections.
- Backend API: Portfolio API.

**How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/NatalySheludko/portfolio-goit-team-project.git
2. Install dependencies:
    ```bash
    npm install
3. Run the development server:
    ```bash
    npm run dev
4. Open the browser at:
    ```bash
    http://localhost:5173
   
