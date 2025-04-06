# BLOG APPLICATION

Blog Application is a blogging platform built with React, Redux, and Appwrite. It allows users to create, edit, and manage blog posts with features like authentication, rich text editing, and file uploads.

## Features

- **Authentication**: Users can sign up, log in, and log out securely.
- **Post Management**: Create, edit, delete, and view blog posts.
- **Rich Text Editor**: Use a rich text editor for creating and editing posts.
- **File Uploads**: Upload and manage featured images for posts.
- **Role-Based Access**: Only authors can edit or delete their posts.
- **Responsive Design**: Built with TailwindCSS for a responsive and modern UI.

## Tech Stack

- **Frontend**: React, React Router, Redux Toolkit
- **Backend**: Appwrite (for authentication, database, and file storage)
- **Styling**: TailwindCSS
- **Build Tool**: Vite
- **Rich Text Editor**: TinyMCE

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mega-blog-project.git
   cd mega-blog-project
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the root directory and configure the following variables:

   ```env
   VITE_APP_APPWRITE_URL=<Your Appwrite URL>
   VITE_APP_APPWRITE_PROJECT_ID=<Your Appwrite Project ID>
   VITE_APP_APPWRITE_DATABASE_ID=<Your Appwrite Database ID>
   VITE_APP_APPWRITE_COLLECTION_ID=<Your Appwrite Collection ID>
   VITE_APP_APPWRITE_BUCKET_ID=<Your Appwrite Bucket ID>
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

   The application will be available at `http://localhost:5173`.

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.
- `npm run lint`: Run ESLint to check for code quality issues.

## Project Structure

```
src/
├── appwrite/          # Appwrite configuration and services
├── components/        # Reusable React components
├── pages/             # Application pages
├── store/             # Redux store and slices
├── conf/              # Configuration files
├── main.jsx           # Entry point for the application
├── App.jsx            # Main application component
├── index.css          # Global styles
```

## Key Components

- **Authentication**: Managed using Appwrite's authentication service.
- **Post Management**: CRUD operations for posts using Appwrite's database and storage services.
- **Rich Text Editor**: Integrated using TinyMCE for creating and editing post content.

## Deployment

To deploy the application, build the project using:

```bash
npm run build
```

The production-ready files will be available in the `dist` directory. You can deploy these files to any static hosting service like Vercel, Netlify, or AWS S3.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Open a pull request.


## Acknowledgments

- [Appwrite](https://appwrite.io) for backend services.
- [TinyMCE](https://www.tiny.cloud/) for the rich text editor.
- [TailwindCSS](https://tailwindcss.com) for styling.

---

Feel free to reach out if you have any questions or suggestions!
