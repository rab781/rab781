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

## 2026-03-08 - Tooltips for Markdown Text Links
**Learning:** Standard markdown text links, especially those pointing to external projects or resources, can leave users uncertain about the destination. Adding descriptive `title` attributes (tooltips) provides better context and improves accessibility by giving users an expectation of what they are clicking before taking action.
**Action:** Always include descriptive `title` attributes for standard markdown text links to external projects or resources to enhance user context and navigation confidence.

## 2026-03-09 - Actionable Availability Statements
**Learning:** Transforming static statements (like "Open for Internship Opportunities") into direct, clickable communication links (e.g., `mailto:` with pre-filled subjects) changes passive text into an immediate call-to-action. This reduces friction for outreach by allowing recruiters or connections to contact the user instantly without having to find the contact section.
**Action:** When a user expresses a clear, actionable status or goal in plain text (such as seeking opportunities), convert those statements into accessible, descriptive links that enable immediate interaction.

## 2026-03-14 - Screen Reader Friendly Separators
**Learning:** Using pipe characters (`|`) as text separators can disrupt the reading flow for screen reader users, as some screen readers announce "vertical line" or "pipe". Bullet characters (`•`) are often ignored or read more naturally as list items or pauses.
**Action:** Prefer bullet characters (`•`) over pipe characters (`|`) for separating inline text items to improve accessibility and screen reader flow.

## 2026-03-14 - Prominent Visual Badges for Calls-to-Action
**Learning:** Converting primary inline text calls-to-action (like "Open for Internship Opportunities") into visually distinct, larger targets such as Shields.io badges enhances visual prominence and click target accessibility, making it easier for users to notice and interact with key links.
**Action:** Use distinct visual elements like badges for primary calls-to-action to improve visual hierarchy and accessibility.
