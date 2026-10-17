# Online Library

A React + Redux app for browsing and cataloging books — filter by category, search, view book details, and add new entries to the catalog.

### Features

- Browse all books, or filter by category (`/browse/:category`)
- Book detail page per title
- Search bar + category list navigation
- Add-book form that dispatches into the Redux store
- 404 page for unmatched routes

### Tech stack

React 19 · Redux + React-Redux · React Router 7 · Vite

Note: catalog data currently lives in the Redux store (seeded with sample books) rather than a backend API — there's no persistence layer yet.

### Running locally

```bash
cd onlineLibrary
npm install
npm run dev
```

### Project structure

```
onlineLibrary/src/
├── components/   # Navbar, BookCard, SearchBar, CategoryList
├── pages/        # HomePage, BrowseBooksPage, BookDetailsPage, AddBookPage, NotFoundPage
└── redux/        # store, actions, bookReducer
```
