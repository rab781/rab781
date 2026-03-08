## 2024-05-24 - Consistent Badge Components for External Links
**Learning:** Using consistent badge components (like Shields.io) for important external links such as email, LinkedIn, and GitHub improves visual UX and click target accessibility, making it easier for users to interact with the interface.
**Action:** Default to using consistent badge components or similarly styled interactive elements for important external links in documentation to ensure a unified and accessible user experience.

## 2026-03-04 - Badge Label Capitalization
**Learning:** Proper and consistent capitalization in badge labels (e.g., "Python", "React.js" instead of "python", "react") enhances visual readability, perceived professionalism, and consistency with brand guidelines.
**Action:** Always use standard Title Case or proper brand names when creating technology or skill badges.

## 2026-03-05 - Interactive Profile Stats Cards
**Learning:** Default markdown image behavior on platforms like GitHub opens the raw SVG image when clicked, creating a confusing and dead-end user experience. This affects large visual elements like profile stat cards which users naturally expect to be clickable. Wrapping these cards in meaningful destination links (like the user's profile or repositories tab) with hover titles transforms them into large, accessible click targets.
**Action:** When adding visual stat cards or large informational images, always wrap them in relevant links with descriptive title attributes to prevent raw image views and improve navigation.

## 2026-03-06 - Meaningful Links for All Badges
**Learning:** Just like large stat cards, clicking on standard skill/technology badges in Markdown on platforms like GitHub opens the raw image file if not wrapped in a link. This breaks user flow and creates a confusing experience. Wrapping these small badges in meaningful links (like official documentation or a relevant website) with descriptive hover titles transforms decorative elements into useful, accessible resources and prevents raw image views.
**Action:** Always wrap standard Markdown badges (e.g., skill/technology shields) in meaningful external links with descriptive `title` attributes (tooltips) to enhance utility and prevent dead-end interactions.

## 2026-03-08 - Pre-filled Email Subject
**Learning:** Adding pre-filled subject parameters to `mailto:` links reduces friction for user outreach and clearly signals intent. This provides a smoother and more guided experience for key contact scenarios, such as seeking internships.
**Action:** Always include relevant pre-filled subjects (and optionally bodies) in `mailto:` links, especially when the contact link has a primary, anticipated use case. Ensure the hover title attribute reflects this context.
