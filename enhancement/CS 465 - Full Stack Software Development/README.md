<h1>Artifact Description</h1>

The artifact I chose for this milestone is my Travlr App. This is a web application that helps users plan and organize trips. It lets users create an account, log in, save trip details, add destinations, and see an itinerary. I originally created this app in my Web Application Development course.

<h1>Why I Selected This Artifact</h1>

I selected the Travlr App because it shows many important skills in software design and engineering. It has a full stack architecture with a front end, back end, and a database, which demonstrates my ability to design and build a complete application. Some parts of the app that showcase my skills include the registration and login system with password hashing, the CRUD operations for trips and destinations, and the clean and responsive user interface.

For this milestone, I completed a set of enhancements to improve the app’s quality. I improved the backend by fixing response logic and adding better input validation to the trips.js controller. I improved error handling and replaced unclear errors with specific, helpful messages. On the frontend, I added a responsive navigation bar, breadcrumbs to show users where they are in the site, and better input validation on the contact form. I also updated the CSS to include media queries for better mobile and tablet responsiveness.

<h1>Course Outcomes Achieved</h1>
These enhancements helped me meet some of the program’s outcomes, like using solid software engineering practices and tools, and improving security in my design by validating user input. My outcome coverage plan has not changed because my enhancements stayed focused on making the app more secure, maintainable, and user-friendly.

<h1>Reflection on the Process</h1>
Working on these enhancements taught me a lot about why clean and secure code matters. I learned how moving business logic into cleaner, more maintainable code and adding good validation make the app more reliable. I also learned how responsive design and user-friendly error messages improve usability. A challenge I faced was making sure my backend changes didn’t break existing functionality and testing my CSS changes on different screen sizes. Overall, I am proud of the improvements I made and feel more confident in my ability to deliver professional-quality software.

Detailed Enhancements Completed
1: Backend: Improved Input Validation and Error Handling
•	Added validation to the trips.js controller for tripCode parameter to ensure it is provided and valid.
•	Fixed the response logic to correctly return 200 if a trip is found, or 404 with a clear message if not.
•	Added proper server error handling (500) with helpful error output.
2: Frontend: Navigation and Usability
•	Added a responsive navigation bar to the top of each page (index.html, about.html, contact.html), with links to all main sections of the site.
•	Added breadcrumbs below the navbar on each page to show the user’s current location.
3: Frontend: Input Validation
•	Added required attributes to form inputs and textareas in contact.html to prevent submitting empty forms and improve user experience.
4: Frontend: Responsive Design
•	Added media queries to styles.css to make the site look better on tablets and mobile screens.
•	Adjusted layout so navbar stacks vertically on small screens and buttons and text resize appropriately.

<img src="https://raw.githubusercontent.com/Jbryson88/ePortfolio/refs/heads/main/enhancement/CS%20465%20-%20Full%20Stack%20Software%20Development/Trip%20UI%20in%20SPA.png"/>
