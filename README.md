# Dynamic Posts List Application

[DEMO LINK](https://momos1703.github.io/react_dynamic_posts_list/)

A dynamic React application for managing and displaying posts with filtering, search, and user details functionality.

## Technologies Used

- **React 18**
- **TypeScript**
- **SCSS/Bulma** for styling
- **Font Awesome** for icons
- **Vite** for project building
- **ESLint/Prettier** for code quality

## Features

- Display posts in a table format
- Filter posts by:
  - All posts
  - By user
  - By category
- Search posts by title
- View detailed post information in a modal including:
  - Post title
  - Post content
  - User details
  - Comments
- Loading states with custom spinner
- Responsive design

## Project Structure

```
src/
  ├── components/           # React components
  │   ├── Loader/          # Loading spinner
  │   ├── PostFilter/      # Filtering and search
  │   ├── PostList/        # Post items display
  │   └── PostModal/       # Post details modal
  ├── types/               # TypeScript interfaces
  │   ├── Filters.ts       # Filter types
  │   ├── Post.ts          # Post interface
  │   └── User.ts          # User interface
  ├── api.ts              # API calls
  ├── App.tsx             # Main application
  └── index.tsx           # Entry point
```

## Code Quality

The project follows strict code quality standards with:
- ESLint configuration with Airbnb style guide
- Prettier for consistent code formatting
- StyleLint for SCSS formatting
- TypeScript for type safety
