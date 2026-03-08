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

## 2026-03-07 - Pre-filled Subject in Contact Links
**Learning:** When a user's primary goal is known (e.g., seeking internship opportunities), friction for outreach can be reduced by appending query parameters to `mailto:` links to pre-fill the subject line, allowing recruiters or connections to respond quickly and directly without thinking of an email title.
**Action:** Append `?subject=...` and update tooltips on generic contact links (like `mailto:`) when the user has an explicit, dominant goal, to streamline the process for end-users to contact them.
