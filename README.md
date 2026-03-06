# Cruciform Church

**Word-Centered, Cross-Focused**

Welcome to the Cruciform Church website project. Currently, the project consists of a high-fidelity, single-page HTML template (`index.html`) that provides the complete structure and styling for the church's online presence.

## Current State

The `index.html` file serves as a comprehensive front-end template built with modern HTML5, semantic elements, and vanilla CSS. It features:

- **Premium Aesthetics:** A visually striking design leveraging beautiful typography (`Playfair Display`, `Crimson Pro`, `Cinzel`) and a highly cohesive layout.
- **Theme Engine:** Built-in CSS Custom Properties enabling seamless switching between a rich Dark Mode and an elegant Light Mode.
- **Responsive Layout:** A mobile-first, fully responsive design comprising:
  - An animated Hero section with a custom cross pattern.
  - Welcome Banner displaying key church statistics.
  - About/Beliefs section outlining the core theological tenets.
  - Sermons section with grid layouts and interactive filtering.
  - Ministries and Events sections to display ongoing church activities.
  - Mobile-responsive navigation with a dropdown menu and sidebar.

## Future Roadmap

The immediate next steps for the project involve refactoring this static, single-page HTML template into a modern, dynamic web application. 

### Planned Refactor: React Application ⚛️

- Component-Based Architecture: We will break down the `index.html` file into reusable UI components (e.g., `<Navbar />`, `<HeroSection />`, `<SermonCard />`).
- State Management: Implementation of state for user interactions (like the theme toggle, sermon filters, and mobile menu).
- Modular Routing: Transitioning from purely vertical scroll sections to distinct routes (e.g., `/sermons`, `/about`, `/events`) if necessary.

### Planned Integration: Database Back-End 🗄️

To make the church's content dynamic, we will integrate a backend solution using **MongoDB** or **Supabase**.

- **Sermons Content Management:** Fetching Sermon series, audio tracks, and recent messages directly from the database instead of hardcoded HTML.
- **Events & Ministries:** Admin tools to create, update, and manage upcoming church events and ministry groups.
- **Data Modeling:** Creating schemas for `Sermons`, `Events`, `Ministries`, and potentially `Users` (for admin capabilities).

---
*Created as part of the initial front-end build and planning phase.*
