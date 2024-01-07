# Fullstack Notion Clone: Next.js 14, React, Convex, Tailwind, Edgestore.

This is a repository for Fullstack Notion Clone: Next.js 14, React, Convex, Tailwind, EdgeStore

# Project Features and Specifications

## Real-time Database 🔗

The project leverages Convex EdgeStore to implement a real-time database, ensuring instant updates and synchronization across the entire application.

## Notion-style Editor 📝

Utilizing an intuitive text editor inspired by Notion, users can create and edit content with a range of formatting options for a rich and dynamic experience.

## Light and Dark Mode 🌓

The application offers both light and dark modes, allowing users to customize their visual preferences for a comfortable viewing experience.

## Infinite Children Documents 🌲

Users can create an unlimited number of child documents within each parent document, enabling a hierarchical and organized content structure.

## Trash Can & Soft Delete 🗑️

A trash can feature is implemented, providing users with the ability to soft delete documents. Deleted items are moved to the trash can, allowing for easy recovery if needed.

## Authentication 🔐

The project incorporates a robust authentication system to secure user data and control access, ensuring that only authorized users can interact with and modify content.

## File Upload

Users can easily upload files, expanding the application's capabilities to handle various types of media.

## File Deletion

Files can be deleted from the system, with the option for users to recover them from the trash can if necessary.

## File Replacement

The application supports file replacement, allowing users to efficiently manage and update existing media assets.

## Icons for Each Document (Changes in Real-time) 🌠

Dynamic icons are associated with each document, updating in real-time to provide visual cues and enhance the overall user experience.

## Expandable Sidebar ➡️🔀⬅️

The sidebar is designed to be expandable and collapsible, offering users the flexibility to customize their workspace based on personal preferences.

## Full Mobile Responsiveness 📱

The application is fully responsive on mobile devices, ensuring a seamless and consistent user experience across various screen sizes.

## Publish Your Note to the Web 🌐

Users have the option to publish their notes to the web, extending the reach of their content beyond the confines of the application.

## Fully Collapsible Sidebar ↕️

The sidebar can be fully collapsed, providing users with a distraction-free environment when focusing on specific tasks.

## Landing Page 🛬

A dedicated landing page welcomes users to the application, offering an introduction to key features and providing easy navigation.

## Cover Image of Each Document 🖼️

Users can enhance the visual appeal and organization of their content by adding cover images to each document.

## Recover Deleted Files 🔄📄

Deleted files can be recovered from the trash can, providing users with the ability to undo accidental deletions.

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell
git clone https://github.com/harsh3294/Notion-Clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```
