# Notion Clone

## Overview

This project is a feature-rich Notion clone, built with Next.js 14, TypeScript, Tailwind CSS, Zustand, Clerk for authentication, Convex for real-time updates, Edge Store for file management, and a rich text editor for versatile note creation.

https://github.com/ateebasif/Notion-Clone/assets/22915645/be25d13a-167a-433f-92cb-5b07b8827884

### Live Demo 🔗

Check out the live demo: [Notion Clone](https://notion-clone-five-rust.vercel.app/)

## Features

- **Real-time Updates**: Benefit from real-time updates powered by Convex.
- **Notion-style editor**: Create versatile notes with different types of blocks.
- **Collapsible and Resizable Sidebar**: Similar to Notion, the sidebar can be collapsed and resized for a customized user experience.
- **Light☀️ and Dark🌑 Mode**: Switch between light and dark themes to suit your preference.
- **Create Note** 📝: Easily create a new note from the sidebar or the documents page.
- **Nested Level Notes**: Organize your notes with nested levels for a structured approach.
- **Emojis and Cover for Notes**: Personalize your notes with emojis and custom covers.
- File upload 📂
- File deletion
- File replacement
- **Update Note Title**: Modify note titles conveniently from the toolbar or the page itself.
- **Trash Management** 🗑️: Move notes to trash, recover from trash, and permanently delete when needed.
- **Publish Live on Web**: Share your notes with others by publishing them live on the web for preview. Un-publish when desired.

## Technologies Used

- **Next.js 14**
- **TypeScript**
- **Tailwind CSS**
- **Shadcn UI (for ui components)**
- **Zustand (for state management)**
- **Clerk (for authentication)**
- **Convex (for real-time updates)**
- **Edge Store (for file management)**
- **@blocknote/react (rich text editor)**
- **Vercel (for deployment)**

### Prerequisites

**Node version 18.x.x**

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ateebasif/Notion-Clone.git
   cd notion-clone
   ```

2. Install dependencies:

   ```bash

   npm install
   # or
   yarn
   ```

3. Configuration
   To run this project locally, create a `.env.local` file with the following variables:
   you need the following keys for configuration

- [Convex](https://www.convex.dev) database for Real-time update
- [Clerk](https://clerk.com) For Authentication
- [Edge Store](https://edgestore.dev) for File Storage

  ```bash

  CONVEX_DEPLOYMENT=""
  NEXT_PUBLIC_CONVEX_URL=""
  NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=""
  CLERK_SECRET_KEY=""
  EDGE_STORE_ACCESS_KEY=""
  EDGE_STORE_SECRET_KEY=""
  ```

4. Setup Convex

   ```
   npx convex dev

   ```

5. Run the development server:

   ```bash
   npm run dev
   #or
   yarn dev
   ```

   Open http://localhost:3000 in your browser to see the result.
