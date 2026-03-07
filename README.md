# CreateALoop LMS

A browser-based learning management system built for K-12 computer science education.

## Live Demo

Visit the live site: **https://dunlap119.github.io/createaloop-lms**

## Features

- **Role-based access** â Teacher and student views with separate dashboards
- **Course builder** â Create courses with modules and sequential lessons
- **Embedded code editor** â Students write and run Python, JavaScript, and HTML directly in the browser (powered by CodeMirror)
- **Auto-grading with partial credit** â Define test cases per assignment; submissions are graded automatically based on output matching, string containment, or assertions
- **Drip curriculum** â Lessons unlock sequentially as students complete each one
- **Teacher-controlled feedback visibility** â Choose whether students see test results immediately, after teacher review, or never
- **Gradebook** â Teachers review submissions, see auto-grade breakdowns, and can override scores
- **Student progress tracking** â Visual dashboards showing completion across courses
- **Announcements** â Teachers post updates per course
- **Mobile-friendly** â Responsive layout with collapsible sidebar

## Tech Stack

This is a **single HTML file** with zero build steps or dependencies to install:

- **React 18** (via CDN)
- **CodeMirror 5** for the code editor (via CDN)
- **localStorage** for data persistence
- Pure CSS (no framework)

## Getting Started

1. Download `index.html`
2. Open it in any modern browser
3. Use the quick-login buttons to try the demo, or create your own account

All data is stored in your browser's localStorage. To reset to the demo data, clear localStorage for the page.

## For Developers

Since everything is in a single file, just edit `index.html` directly. The code is organized into clearly labeled sections:

- Sample data and data persistence
- Code execution engine (JavaScript + basic Python interpreter)
- Auto-grader engine
- React components (login, sidebar, dashboard, course views, editor, modals)

## License

Built for [CreateALoop](https://createaloop.org) â a computer science education nonprofit for K-12 students.
