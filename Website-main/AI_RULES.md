# AI_RULES.md

## Tech Stack Overview

- **React** with **TypeScript** for all UI and logic.
- **Vite** as the build tool and dev server.
- **Tailwind CSS** for all styling and layout.
- **shadcn/ui** for prebuilt, accessible UI components (use these whenever possible).
- **React Router** for client-side routing (routes live in `src/App.tsx`).
- **lucide-react** for all icons.
- **react-helmet-async** for SEO and meta tags.
- **Supabase** for backend, authentication, and database (if needed).
- **date-fns** for date/time utilities.
- **tiptap** for rich text editing (if needed).
- **Cal.com** for demo/meeting scheduling (via iframe).
- **No jQuery, Bootstrap, or other CSS frameworks**—only Tailwind and shadcn/ui.

## Library Usage Rules

- **UI Components:**  
  - Use **shadcn/ui** components first.  
  - If a component is not available in shadcn/ui, build it with React and Tailwind CSS.
- **Styling:**  
  - Use **Tailwind CSS** utility classes for all custom styles.  
  - Do not use plain CSS files or CSS-in-JS.
- **Icons:**  
  - Use **lucide-react** for all icons.
- **Routing:**  
  - Use **React Router** (`react-router-dom`).  
  - Define all routes in `src/App.tsx`.
- **SEO:**  
  - Use **react-helmet-async** for meta tags and structured data.
- **Backend/Auth/DB:**  
  - Use **Supabase** for authentication, database, and backend logic.
- **Date/Time:**  
  - Use **date-fns** for all date/time formatting and calculations.
- **Rich Text:**  
  - Use **tiptap** and its extensions for any rich text editing needs.
- **Scheduling:**  
  - Use **Cal.com** via iframe for demo/meeting booking.
- **No jQuery, Bootstrap, or Material UI**—stick to the stack above.

## General Rules

- Keep all source code in the `src` directory.
- Place pages in `src/pages/` and components in `src/components/`.
- Use TypeScript for all files.
- Keep code simple, readable, and maintainable.
- Do not add libraries outside this stack without explicit approval.