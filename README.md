Minimalist Blog Post Viewer
Objective
This project is a simple, minimalist blog post viewer created with Next.js 14+, Tailwind CSS, and React. It demonstrates Next.js App Routing, dynamic slugs for post navigation, and data fetching from a free API.

Project Requirements
Next.js App Routing: Utilize the new Next.js App Routing feature for organized file-based routing.
Dynamic Slug Routing: Use dynamic slugs to handle individual blog post pages.
API Consumption: Fetch blog post data from the JSONPlaceholder API (https://jsonplaceholder.typicode.com/posts).
Responsive Design: Ensure the project is responsive across mobile, tablet, and desktop views.
Basic Styling: Apply minimalist, clean, and user-friendly styling using Tailwind CSS.
Features
Home Page

Displays a list of blog post titles fetched from the API.
Each title links to the post's individual details page.
Tailwind CSS used for styling to keep it clean and responsive.
Post Details Page

Shows the complete content of the selected blog post.
Accessible via dynamic routing based on the post ID in the URL.
Tailored styling for readability.
Navigation

Dynamic links between the Home page and Post Details pages using Next.js next/link.
Error Handling & Loading States (Bonus)

Basic error handling for fetch requests.
A loading state while data is being fetched from the API.
Project Structure
/app/page.js: The Home page that displays a list of blog post titles.
/app/posts/[slug]/page.js: Dynamic Post Details page that displays individual post content based on the slug (post ID).
Setup Instructions
Clone the repository.
Install dependencies by running npm install.
Run the project with npm run dev.
Dependencies
Next.js 14 or newer
React
Tailwind CSS
API Reference
This project uses the JSONPlaceholder API for fetching blog post data: https://jsonplaceholder.typicode.com/posts.
Contributing
Feel free to contribute to improve the code structure, styling, and features.
