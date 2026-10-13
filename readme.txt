--Readme document for *YOUR NAME*, *YOUR_EMAIL@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
- images with descriptive alt text
examples:
    - profile photo on home page
    - Candid project screenshots on home and projects pages.
- headings and paragraph text, using one h1 per page with h2 sections and h3 items
- links to external pages:
    - link to Candid vercel site
    - link to Candid Youtube demo
    - links to GitHub, LinkedIn, and email 
- Three pages (Home, Resume, Projects) navigable through a Bootstrap navbar. The current page is highlighted using aria-current="page".
- HTML tags: header, nav, main, section, article, aside, and footer
- Decorative custom icons from Boostrap icons, using aria-hidden="true"


(b) CSS features
- Custom padding an dmargins on cards, sections, resume timeline, sidebar, and hero to make content more spaced out
and easier to read.
- Custom color palette (cream, pink, lavender, mint, butter yllow, dark purple, hot pink) for text color, backgrounds, card shadows,
buttons, and hovering states for the cursor. 
-  Bootstrap CSS: grid, img-fluid, table, flex and spacing
- Google Fonts: Fraunces for headings and DM Sans for other body text with fallback fonts, such as Georgia, Helvetica Neue, Arial



(c) Advanced features
- Skills table on resume page that works with screen readers
    - includes caption, thead, tbody, th elements, and id/headers
    - On smaller screens like a phone the table is scrollable sidways
- Complex page layout that features a responsive navbar 
    - navbar collapses into a hamburger style menu on smaller screens
    - resume section features two sections/columns:
        1. Left column has a vertical timeline of work expereince
        2. right column has cards for relevant classes and interests
- Nested selectors for CSS that have parent and child relationships between related elements    
    - examples include: .site-nav .nav-link, .sidebar .siderbar-label
- Responsive layout: card grids in featured projects and current focuses collapse from two columns 
to one column on smaller layouts, profile photo moves above the intro text on smaller layout, and padding, image size,
and borders are also adjusted.



3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
I fixed all of the known and likely problems which included the following: 
    1. using i element: I used <i> for Bootstrap Icons and changed them to <span> since icons aren't italic text
    2. I added id and header attributes and a caption to the skills table.
    3. I changed "Relevant coursework" and "curent coursework" label to h3 headings since under them are lists
    4. I changed "University of California, Irvine" to a paragraph label instead of heading and just made it bold with a class instead.
    
Potential Problems that I ignored:
    1. Language and text direction was ignored due to all content being in English and lang="en" is already section
    2. Scripts had a warning but I only used Bootstrap's bundle which was for the navbar toggle. The toogle is a <button> and works from the keyboard.
    3. Navigation: each page has a skip link (embedded into my name) and uses the same navbar, header, and footer in the same order. 
    4. Page titles and links I dismissed because each page has its own title, and the link names for external sources are described accurately with "Visit Candid", "watch demo".
    5. Images warnings I ignored because photos and screenshots of profile and projects are used purposefully, so I added alt text. 
    6. Table warnings: The table I have currently is a simple three-column table with a caption, thead, tbody, and headers so it wouldn't need a summary.

4. How long, in hours, did it take you to complete this assignment?

    ~18 hours

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
https://developers.google.com/fonts/docs/getting_started
https://getbootstrap.com/docs/5.0/getting-started/introduction/#quick-start 
https://www.w3schools.com/accessibility/accessibility_skip_links.php 
https://www.w3schools.com/html/html_id.asp
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/main 
https://getbootstrap.com/docs/5.3/components/navbar/ 
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Reference/Attributes 
https://getbootstrap.com/docs/5.0/layout/containers/ 
https://getbootstrap.com/docs/4.0/layout/grid/ 
https://getbootstrap.com/docs/5.0/utilities/spacing/
https://www.w3schools.com/html/html_css.asp 
https://getbootstrap.com/docs/5.0/components/card/ 
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/footer
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/justify-content 
https://getbootstrap.com/docs/4.0/utilities/flex/ 
https://www.w3schools.com/accessibility/accessibility_labels.php
https://www.w3schools.com/css/css_font.asp
https://www.w3schools.com/css/css3_shadows_box.asp
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/ul 
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/flex-wrap 
https://getbootstrap.com/docs/4.0/content/images/ 
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/aspect-ratio 
https://www.w3schools.com/css/css_table.asp
https://getbootstrap.com/docs/5.3/content/tables/ 
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:focus-visible 
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@media
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:nth-child
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/meta/name/viewport 




6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

    none 

7. Is there anything special we need to know in order to run your code?

No index.html just needs to be opened in the browser. Bootstrap and Google Fonts load from CDNs.