# EXPLODE-Serverless
EXPLODE Serverless App is a serverless app using static HTML + HTMX 2.0 + SQLITE3 + pubsub + TailwindCSS + CloudFlare R2 + CloudFlare D1 + Workers.

## Static HTML
Static HTML websites can run on Github pages, or anything for that matter. 

## HTMX 2.0
HTMX 2.0 is a library that allows you to access modern browser features directly from HTML, rather than using javascript. This anchor tag tells a browser: “When a user clicks on this link, issue an HTTP GET request to '/blog' and load the response content into the browser window”. We use is to make a static html shell with dynamic content.

## SQLITE.js
sqlite.js refers to a JavaScript library that allows SQLite databases to be used directly in the browser environment. This library compiles SQLite to JavaScript, enabling EXPLODE to create and manage relational databases entirely within web applications. We are using SQLITE.js to power user accounts, user profiles, view counters, viewing history, games activity, comments, blogs, tips/donation history, media uploads, playlist data, and metadata.

## PUBSUB - postal.js
Pub/Sub library providing wildcard subscriptions, complex message handling, etc. Works server and client-side. Working with sqlite.js + htmx 2 to dynamically post, upload and share media, and comments. (WIP)

## TAILWIND CSS
Tailwind CSS is a utility-first CSS framework designed to streamline web development by using utility classes directly in HTML, eliminating the need for traditional CSS stylesheets.

We have built a beautiful UI we are calling Glassmorphic, in both light and dark modes.

## CLOUDFLARE R2+D1+Workers+Pages
Cloudflare R2 Storage allows EXPLODE to store large amounts of unstructured data without the costly egress bandwidth fees associated with typical cloud storage services. CF-R2 is user content is stored, audio, video, pictures, and SQLITE for postal.js, user profiles, view counters, viewing history, games activity, comments, blogs, tip/donation history, media uploads, playlist data, and user metadata.

### As we are developing Explde-Serverless we will update this README with changes, additions, or modifications.
