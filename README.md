# COLLEGE_WEBSITE_DEVELOPMENT.
COLLEGE WEBSITE DEVELOPMENT  - PDEA's Baburaoji Gholap College, Sangvi, Pune
PROJECT REPORT
COLLEGE WEBSITE DEVELOPMENT
PDEA's Baburaoji Gholap College, Sangvi, Pune


1. INTRODUCTION
A college website is an important source of information for students, parents, staff, alumni, and visitors. It can introduce the institution, explain academic options, show campus facilities, and direct users to official notices and resources. This project is a student-developed front-end website for PDEA's Baburaoji Gholap College, Sangvi, Pune. It is designed as a clear starting point for visitors who need a quick overview of the college.
The page includes a home/hero area, college information, academic programme categories, a photo gallery section, campus facilities, vision and mission information, and contact/useful-link content. The supplied campus image and logo are used as visual elements. The website also directs users to official college pages for further details. The content should be checked against the college's latest official information before public release.
1.1 Motivation
The motivation for this project was to practise website development skills and organise college information in a readable digital format. A single-page layout can help visitors move between the main topics without searching through multiple menus. The project also provides practical experience with page structure, visual hierarchy, responsive styling, links, images, accessibility basics, and testing.
1.2 Problem Statement
College information can be spread across different pages and sections. A visitor who only needs a quick introduction, a list of academic areas, a view of the campus, or a link to official resources may have to navigate several pages. The problem addressed by this project is to provide a simple, mobile-friendly overview page that groups common information and guides visitors to the official source when more detail is required.
1.3 Purpose, Objectives and Goals
Purpose: To design and implement a simple informational website for an educational institution as an OJT learning project.
•	Present the college name and campus image clearly on the home section.
•	Provide an About section with a concise college introduction.
•	Organise academic areas into readable categories.
•	Provide a gallery section with links to the college's official gallery.
•	Show information about facilities, student activities, vision/mission, and contact resources where available.
•	Make navigation understandable on desktop and mobile screens.
•	Use semantic HTML, maintainable CSS, descriptive link text, and appropriately sized images.
•	Document current limitations and propose realistic future improvements.
1.4 Literature Survey
The project review focused on two types of references: the college's official website and general front-end web-development practices.
Reference / area	What was reviewed	Use in this project
Official college website	College background, academic information, and official navigation.	Used as a factual reference and as a destination for further information.
Official college gallery	Categories of college events and activities.	Used as a link target for visitors who want to view original college gallery material.
HTML documentation and standard practice	Semantic page structure, headings, links, and image alternative text.	Informs the organisation and accessibility of page content.
CSS responsive design practice	Flexible layouts, spacing, readable typography, and mobile navigation behaviour.	Guides the visual layout and responsive styling.

This is a practical literature review rather than a formal comparative research study. The website should be reviewed again before submission if the official college website changes.
1.5 Project Scope and Limitations
Scope of the current version:
•	A static front-end webpage with navigation to Home, About, Courses, Gallery, Facilities, and Contact sections.
•	A hero area using the supplied campus photograph and college-associated logo.
•	Informational sections about the college, academic areas, facilities, and vision/mission.
•	Gallery cards that link visitors to official college gallery resources.
•	Responsive styling intended to support common desktop and mobile screen sizes.
Limitations of the current version:
•	There is no database or server-side application.
•	There is no administrator login or content-management dashboard.
•	No online admission, registration, enquiry, or contact form is processed by the website.
•	No live notices, course availability, attendance, student records, or placement statistics are generated.
•	Gallery preview images may be illustrative where noted; the official gallery link should be used for authentic event photographs.
•	The project is not an official college publication and must not imply college endorsement without permission.
2. SYSTEM ANALYSIS
2.1 Existing Systems
The primary existing system is the college's official website, which is the authoritative place to check current institutional information and official gallery material. The student project is a lightweight companion-style overview page. It does not replace the official website, its notices, admission information, or institutional services.
2.2 Scope and Limitations of Existing Systems
The official website can contain detailed institutional information and multiple sections. For a visitor seeking only a quick introduction, a focused overview page may be easier to scan. However, a student-created static page cannot guarantee that its content is always current, and it does not have the authority or backend features of the official system. Any change in course offerings, contact information, dates, or institutional policy must be verified on the official website.
2.3 Project Perspective and Features
Feature	Current implementation	Purpose
Home / hero	College heading and campus image	Introduces the website and institution.
Navigation	Home, About, Courses, Gallery, Facilities, Contact	Helps users move to page sections.
About	College overview and student development information	Gives visitors a concise introduction.
Academic programmes	Grouped subject/programme categories	Makes academic areas easier to scan.
Gallery	Gallery cards and links to official gallery	Guides visitors to college event photographs.
Facilities	Informational facility cards	Highlights campus resources and activities.
Vision and mission	Informational section	Presents institutional purpose as described in source material.
Contact / useful links	Contact information and official links where included	Helps users continue to authoritative resources.
Footer credit	College attribution and student developer credit in small text	Identifies the project and its student creator.

2.4 Stakeholders
Stakeholder	Interest / responsibility
Students and prospective students	Find a quick overview of the college and academic areas.
Parents and guardians	Understand the institution and locate official resources.
Faculty / project guide	Review the project, learning outcomes, documentation, and testing.
College administration	Ensure institutional details and branding are used accurately and appropriately.
Alumni and visitors	Navigate to information about activities and official gallery content.
Student developer	Build, test, maintain, and document the student project.

2.5 Requirement Analysis
Functional requirements
•	FR-01: The website shall display the college name and a home section.
•	FR-02: The website shall provide navigation links to the main page sections.
•	FR-03: The website shall present an About section and academic programme categories.
•	FR-04: The website shall show a gallery section and links to official gallery resources.
•	FR-05: The website shall present available facility, vision/mission, and contact/resource information.
•	FR-06: The website shall display the student developer credit in the footer.
•	FR-07: External links shall open the intended official resource.
Non-functional / performance requirements
•	NFR-01: The page should load efficiently on a typical modern browser and broadband/mobile connection.
•	NFR-02: Text should remain readable and content should fit common screen sizes.
•	NFR-03: Navigation and links should be consistent and easy to understand.
•	NFR-04: Images should have suitable dimensions and alternative text where appropriate.
•	NFR-05: The HTML and CSS should be maintainable and organised.
Security and privacy requirements
•	The current website does not collect or store personal information, and it has no login or database.
•	Only trusted, verified links should be included; external destinations should be checked before release.
•	Do not add student personal data, private phone numbers, or confidential college records.
•	If a contact form or database is added later, server-side validation, access control, secure transport (HTTPS), and a privacy notice will be required.
Constraints and assumptions
The project assumes that the browser supports standard HTML and CSS. It depends on accurate source information and permission to use college branding and photographs. The current static version can display only content already included in the file or linked from another website.
3. IMPLEMENTATION DETAILS: SOFTWARE / HARDWARE SPECIFICATIONS
Software specifications
Component	Specification / role
HTML5	Provides the page structure, headings, sections, links, and image elements.
CSS3	Controls layout, colours, typography, spacing, cards, and responsive presentation.
JavaScript	No custom JavaScript is present in the inspected current HTML file.
Web browser	A modern browser such as Google Chrome, Microsoft Edge, or Mozilla Firefox.
Code editor	Any text or code editor can be used to maintain the HTML and CSS.
Hosting	The current file can be opened locally or deployed to a static web host after approval.

Hardware specifications
Hardware	Minimum practical requirement
Development computer	A computer capable of running a modern browser and text editor.
Processor	Any recent entry-level desktop or laptop processor.
Memory	4 GB RAM or more recommended for comfortable browser/editor use.
Storage	Enough free space for the HTML file and image assets.
Display	Desktop/laptop display; mobile screen testing is also recommended.
Internet connection	Required for external official links and any externally hosted resources.

Note: The specifications above are practical recommendations, not measured minimum requirements. The page is static and does not require a database server for its current features.
4. SYSTEM DESIGN
4.1 Design Constraints, Proposed Normalised Database Design and Data Dictionary
Design constraints: the present project is a static website. It has no database connection and does not store user input. Therefore, the database design below is a proposed design for a future dynamic version, included to address database-design concepts in the project report. It is not implemented in the current website.
For a future content-management version, the data could be separated into related tables to reduce repeated data and improve maintenance. A possible normalised design is:
Table	Fields	Key / relationship
Department	department_id (PK), department_name, description	One department may offer many courses.
Course	course_id (PK), department_id (FK), course_name, level, description, status	department_id references Department.department_id.
GalleryCategory	category_id (PK), category_name, description	One category may contain many gallery items.
GalleryItem	gallery_id (PK), category_id (FK), title, image_path, event_date, source_url, alt_text	category_id references GalleryCategory.category_id.
Facility	facility_id (PK), facility_name, description, image_path	Stores facility descriptions separately.
Notice	notice_id (PK), title, notice_text, publish_date, expiry_date, status	Could support a future notices module.
ContactMessage (optional)	message_id (PK), sender_name, sender_email, subject, message_text, created_at, status	Only if a secure enquiry form is approved and implemented.

Normalisation notes
•	First Normal Form (1NF): each field stores one value, and repeated groups such as multiple courses are stored as separate rows.
•	Second Normal Form (2NF): in tables with a single-column primary key, non-key attributes depend on the whole key.
•	Third Normal Form (3NF): department details are stored in Department rather than repeated in every Course row; category details are stored in GalleryCategory rather than repeated in every GalleryItem row.
•	The optional ContactMessage table would need privacy controls, retention rules, and protection from spam if implemented.
Data dictionary (proposed)
Field	Type (suggested)	Description / rule
department_id	INT, PK	Unique identifier for a department.
department_name	VARCHAR(100)	Required department name.
course_id	INT, PK	Unique identifier for a course.
department_id (Course)	INT, FK	Must match an existing Department record.
course_name	VARCHAR(150)	Required course title.
category_id	INT, PK	Unique gallery category identifier.
gallery_id	INT, PK	Unique gallery item identifier.
image_path	VARCHAR(255)	Path or URL for an image; validate the destination.
event_date	DATE, nullable	Date associated with a gallery item, if known.
notice_id	INT, PK	Unique notice identifier.
publish_date	DATE	Date on which a notice becomes visible.
status	VARCHAR(20)	Controlled value such as draft, published, or archived.
message_id	INT, PK	Identifier for an optional enquiry message.
sender_email	VARCHAR(254)	Optional form field; validate and protect if collected.

4.2 Data Model: FDD Diagram
The following Functional Decomposition Diagram (FDD) shows the main functions of the current static website. It is a functional view, not a database entity-relationship diagram.
COLLEGE WEBSITE
├── 1. Home
│   ├── College title and branding
│   └── Campus hero image
├── 2. College Information
│   ├── About the college
│   ├── Academic programme categories
│   └── Vision and mission
├── 3. Gallery
│   ├── Gallery preview cards
│   └── Links to official gallery resources
├── 4. Facilities and Activities
│   ├── Library / laboratories / ICT
│   └── Sports / NSS / NCC / student support
└── 5. Contact and Navigation
    ├── Section navigation
    ├── Contact / useful links
    └── Footer attribution and developer credit
4.3 User Interfaces
The interface uses a single-page layout. Visitors can select a navigation item and move to the relevant section. The main visual elements are the college heading, campus photograph, section headings, cards, links, and footer credits.
4.3.1 Menus
Menu item	Expected action
Home	Moves to the hero / introductory section.
About	Moves to the college overview.
Courses	Moves to academic programme categories.
Gallery	Moves to gallery preview cards and official gallery links.
Facilities	Moves to campus facilities and student activity information.
Contact	Moves to contact information and useful links.

4.3.2 Input Screens Using Sample Data
There are no data-entry screens in the current version. The website is informational and does not submit or save form data. To make the testing requirements clear, the following is an example of a future enquiry form only; it is not a feature that should be described as already implemented.
Proposed field	Sample test value	Validation expected
Full name	Aarav Patil	Required; letters and ordinary name punctuation allowed.
Email	aarav@example.com	Required; must follow a valid email format.
Subject	Course enquiry	Required; limit length.
Message	Please share the official course information link.	Required; reject empty or excessively long input.

If this form is developed, the values must be validated in both the browser and server. A client-side form alone is not enough to store messages securely.
4.3.3 Output Screens
Screen / section	Visible output
Home	College name, introductory statement, campus image, and navigation.
About	College overview and student-development information.
Courses	Academic categories grouped into cards or sections.
Gallery	Gallery preview cards and links to the official gallery.
Facilities	Facility and student activity information.
Vision and Mission	Institutional purpose information based on the reference source.
Contact / footer	Available contact/useful links and small copyright/developer attribution.

For the final printed submission, add actual screenshots of the running webpage in this section. Recommended screenshots: (1) top/home section, (2) About and Courses, (3) Gallery and Facilities, and (4) footer with the developer credit. Screenshots should be captured from the actual project in a browser, not recreated as if they were real outputs.
4.3.4 Reports and Graphs Using Sample Data
The current website does not generate reports, charts, analytics, or database outputs. This is expected for a static informational page. A future administrator module could generate a course list, gallery inventory, notice list, or monthly enquiry summary. The sample table below illustrates a possible future report and is not live college data.
Example category	Illustrative item count	Meaning
Academic programme categories	6	Example count of categories displayed in the student page, not official course totals.
Gallery preview cards	6	Number of preview cards in the current webpage layout.
Facility cards	6	Example count of facility/activity cards shown in the page.

These values describe the page layout only. They must not be presented as official college statistics. A graph is not included because the current project has no meaningful live dataset to plot.
5. TESTING
Testing should confirm that the page content appears correctly, navigation works, links lead to the intended destinations, and the layout remains usable on different screen sizes. The cases below are a test plan. Mark a result as Pass only after executing that test in the browser; do not claim tests were completed if they have not been run.
Test Plan: Black Box / Data Validation Test Cases
Test ID	Test input / action	Expected result	Result to record
BB-01	Open the HTML file in a current browser.	Page loads without a blank screen or visible broken structure.	Pending execution
BB-02	Select Home in navigation.	Home section is reached.	Pending execution
BB-03	Select About, Courses, Gallery, Facilities, Contact.	Each menu link reaches the corresponding section.	Pending execution
BB-04	Select an official gallery link.	Browser opens the intended official college gallery page.	Pending execution
BB-05	Inspect campus image and logo.	Images appear correctly and are not stretched or missing.	Pending execution
BB-06	Resize browser to a narrow mobile width.	Content remains readable; no major horizontal overflow.	Pending execution
BB-07	Inspect footer at the bottom of the page.	College attribution and developer credit appear in small text.	Pending execution
BB-08	Open all external links.	Each link points to a relevant, intended resource.	Pending execution

White Box / Functional Validation Test Cases
White-box testing normally checks internal code paths and logic. Since the current project has no custom JavaScript functions or backend logic, internal testing is limited to reviewing the HTML structure, CSS rules, and link targets.
Test ID	Inspection	Expected result	Result to record
WB-01	Review HTML for balanced tags and valid nesting.	No obvious structural errors; page sections are nested correctly.	Pending execution
WB-02	Review heading hierarchy.	Headings describe sections in a logical order.	Pending execution
WB-03	Review image markup and alt text.	Images have meaningful alternative text where appropriate.	Pending execution
WB-04	Review CSS responsive rules.	Layout adapts at the breakpoints/rules defined in the stylesheet.	Pending execution
WB-05	Review URLs in gallery and useful links.	URLs are correctly formed and point to intended destinations.	Pending execution
WB-06	Search for form handlers/database calls.	No active form submission or database functionality is claimed for the current version.	Pending execution

Testing notes and acceptance criteria
•	The project is acceptable for demonstration when the page opens, the main sections are accessible, key images render, and links have been checked.
•	Check keyboard navigation and visible focus, image alternative text, colour contrast, and mobile layout before publication.
•	Record the actual browser, device/screen width, date, and observed result after running each test.
•	If any test fails, correct the HTML/CSS or link and repeat the test.
6. CONCLUSION AND RECOMMENDATIONS
The project delivers a simple front-end overview website for PDEA's Baburaoji Gholap College. It groups the main informational areas into a single page and uses a campus photograph, logo, navigation, academic categories, facilities information, and gallery links to make the content easier to browse. It also provides practice in page structure, styling, responsive design, and documentation.
The current version is static, so it should be understood as an informational student project rather than a complete college-management system. Before publishing it publicly, the developer should verify all institutional details, check all links, replace any illustrative gallery previews with authorised original photographs, and obtain permission where required to use the college name, logo, and photographs.
Recommendations
•	Ask the project guide to review the final page and report before submission.
•	Use only verified college information and keep a record of the official source pages consulted.
•	Replace illustrative gallery thumbnails with original photographs that are authorised for use, or label them clearly as previews.
•	Test the page on at least one desktop browser and one mobile-sized viewport.
•	Keep the student-project attribution and avoid presenting the page as an official college website without authorisation.
7. FUTURE SCOPE
•	Create separate About, Courses, Gallery, and Contact pages if the content grows.
•	Build an administrator content-management system so authorised staff can update notices, programmes, and gallery items.
•	Add a secure enquiry form with server-side validation, spam protection, and a clear privacy notice.
•	Use a database for structured course, facility, gallery, and notice content if dynamic management becomes necessary.
•	Add a searchable gallery with categories and an accessible image lightbox.
•	Improve accessibility through keyboard testing, colour-contrast checks, semantic landmarks, and descriptive alternative text.
•	Optimise image sizes and use responsive image formats to improve loading on mobile networks.
•	Add analytics only if approved, with appropriate privacy disclosure and consent where required.
•	Publish on an approved hosting service only after reviewing permissions, accuracy, and security.
8. BIBLIOGRAPHY AND REFERENCES
The following public resources were used as references for the college information and the general implementation approach. Access dates should be updated to the date on which the student verifies the pages for submission.
1. PDEA's Baburaoji Gholap College. Official college website. https://www.pdeabgcollege.edu.in/
2. PDEA's Baburaoji Gholap College. About College. https://www.pdeabgcollege.edu.in/AboutCollege.jsp
3. PDEA's Baburaoji Gholap College. Public Gallery. https://www.pdeabgcollege.edu.in/PublicGallery
4. MDN Web Docs. HTML: HyperText Markup Language. https://developer.mozilla.org/en-US/docs/Web/HTML
5. MDN Web Docs. CSS: Cascading Style Sheets. https://developer.mozilla.org/en-US/docs/Web/CSS
Date accessed: [Enter the date you personally checked each source].
APPENDIX A: FINAL SUBMISSION CHECKLIST
•	Replace all bracketed placeholders, including guide name, department/institute, academic year, and access date.
•	Insert actual browser screenshots into Section 4.3.3.
•	Execute the test cases and update each result from “Pending execution” to Pass/Fail with notes.
•	Confirm the official college information and all links are current.
•	Confirm the college's rules for use of its logo, photographs, and name.
•	Proofread the report and ensure the project file submitted is the final tested version.
