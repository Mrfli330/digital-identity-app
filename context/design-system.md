You are a senior UI/UX designer and Flutter design-system architect.

Your task is to create a complete and implementation-ready file named:

design-system.md

The design system will be used as the single source of truth for building a Flutter portfolio app called:

"My Digital Identity"

IMPORTANT:
- Do NOT build the Flutter application yet.
- Do NOT create Dart files yet.
- Do NOT modify the existing application UI yet.
- Your current task is ONLY to create/update design-system.md.
- The design system must be practical and directly usable by a Flutter AI coding agent later.
- Keep the design clean, modern, minimal, professional, and suitable for a university student's first portfolio project.

==================================================
1. PROJECT CONTEXT
==================================================

This is a mini challenge called:

"My Digital Identity App"

The app is the user's first small Flutter application and will become part of their portfolio.

The app must contain:

- Name
- NIM
- Study Program
- Skill list
- Contact information
- Profile photo / avatar
- One multimedia element
- About Me section
- Video placeholder
- Video description placeholder

User information:

Name:
Muhamad Rafli

NIM:
2411073

Study Program:
Informatika

Skills:
- JavaScript
- React
- Tailwind CSS
- UI/UX
- Node.js
- Git/GitHub
- Figma
- Flutter

Contact information must contain placeholders for:
- Phone number
- Email
- LinkedIn
- GitHub

The multimedia element should currently be a placeholder.

For example:
- About Me text placeholder
- Video thumbnail/player placeholder
- Short video description placeholder

Do not invent real contact information.

==================================================
2. TECHNOLOGY STACK
==================================================

The application will be developed using:

- Flutter
- Dart

The design system must therefore be written with Flutter implementation in mind.

The design system should use concepts that map naturally to Flutter widgets such as:

- Scaffold
- SafeArea
- AppBar
- Container
- Card
- Column
- Row
- Stack
- Wrap
- ListView
- SingleChildScrollView
- CircleAvatar
- ClipRRect
- IconButton
- Text
- Image
- InkWell / GestureDetector
- Divider
- Chip
- FilledButton / OutlinedButton where appropriate

Do not introduce unnecessary frameworks or web-only concepts.

==================================================
3. VISUAL REFERENCE
==================================================

There is a visual reference image available in the project.

The reference is a projected classroom presentation showing a mobile "Digital Identity" profile app.

The desired visual direction is:

- Light theme
- Clean
- Minimal
- Modern
- Professional
- Student portfolio style
- Mobile-first
- Spacious layout
- Soft rounded corners
- Clear visual hierarchy
- White/light background
- Dark readable typography
- Subtle borders and shadows
- Blue/purple accent colors may be used carefully
- Avoid excessive decoration
- Avoid a complicated dashboard appearance

The final application should feel like a polished personal digital identity/profile card rather than a business dashboard.

IMPORTANT:
Do not blindly copy the screenshot.
Use it as a visual direction/reference while creating a more polished and consistent Flutter design system.

==================================================
4. IMAGE ASSETS
==================================================

The project already contains an img folder.

Expected assets:

img/identity-app-img.png
img/profile-picure.png

IMPORTANT:
- Use the existing assets.
- Do not replace them with generated images.
- Do not create fake replacement assets.
- Do not rename the files unless absolutely necessary.
- The profile image should be used as the user's avatar/profile picture.
- identity-app-img.png is a reference image and should be considered when understanding the intended visual direction.

The design system must document how these assets should be displayed in the Flutter application.

For the avatar:
- Use a circular presentation.
- Preserve aspect ratio.
- Avoid stretching.
- Use a clean border or subtle visual treatment if appropriate.

If SVG rendering is used later, the design system should explain the intended visual behavior, but do not force an SVG implementation if the existing image asset is raster.

==================================================
5. DESIGN SYSTEM STRUCTURE
==================================================

Create design-system.md with the following major sections:

1. Design System Overview
2. Design Principles
3. Color System
4. Typography System
5. Spacing System
6. Layout System
7. Border Radius
8. Elevation and Shadows
9. Iconography
10. Image and Avatar Guidelines
11. Component System
12. Screen Structure
13. Interaction States
14. Responsive Behavior
15. Accessibility
16. Flutter Implementation Guidelines
17. Content Guidelines
18. Asset Usage
19. Design Tokens
20. Final UI Checklist

==================================================
6. DESIGN PRINCIPLES
==================================================

Define clear principles such as:

- Simplicity
- Readability
- Personal identity
- Consistency
- Visual hierarchy
- Mobile-first design
- Accessibility
- Professional portfolio presentation

Explain each principle briefly.

Avoid unnecessary long theoretical explanations.

The document should be practical.

==================================================
7. COLOR SYSTEM
==================================================

Create a complete light-theme color system.

Use a restrained palette.

Define semantic colors rather than only random hex values.

For example:

Primary
Primary Container
Secondary
Secondary Container
Background
Surface
Surface Variant
Text Primary
Text Secondary
Text Muted
Border
Divider
Success
Warning
Error
On Primary
On Surface

The color palette should visually match the reference direction:

- Light background
- Dark text
- Blue/purple accent
- Soft neutral surfaces

Do not use too many colors.

Provide exact HEX values.

Also explain where each color should be used.

Example format:

| Token | HEX | Usage |
|------|-----|------|
| Primary | #... | Main accent |
| Background | #... | Main screen background |

==================================================
8. TYPOGRAPHY SYSTEM
==================================================

Define a complete typography hierarchy.

Include:

- Display / Hero
- Screen Title
- Section Title
- Card Title
- Body Large
- Body
- Body Small
- Caption
- Label
- Button Text

Use a modern, readable font suitable for Flutter.

Prefer a system-friendly font such as:

Inter

If the project does not include a custom font, explain that Flutter's available font strategy should be used.

Define:

- Font size
- Font weight
- Line height
- Letter spacing where necessary
- Typical usage

Keep the typography hierarchy simple.

==================================================
9. SPACING SYSTEM
==================================================

Create a consistent spacing scale.

Use an 8-point based system.

For example:

4
8
12
16
20
24
32
40
48

Explain when each spacing value should be used.

Avoid arbitrary spacing values whenever possible.

==================================================
10. LAYOUT SYSTEM
==================================================

Define the mobile layout rules.

The app should be optimized primarily for a smartphone screen.

Define:

- Screen horizontal padding
- Maximum content width
- Section spacing
- Card padding
- Header spacing
- Grid/list behavior
- Vertical rhythm

The layout should remain comfortable on common Android phone sizes.

Do not design around a desktop screen.

The UI should not feel cramped.

==================================================
11. BORDER RADIUS
==================================================

Define a consistent radius system.

For example:

Small
Medium
Large
Extra Large
Pill

Specify exact values in dp.

Use rounded corners consistently for:

- Cards
- Skill chips
- Buttons
- Video placeholder
- Contact cards
- Profile container

==================================================
12. ELEVATION AND SHADOWS
==================================================

Keep shadows subtle.

The application should not use heavy or dramatic shadows.

Define:

- No elevation
- Low elevation
- Medium elevation

Explain which components use each level.

Prefer subtle depth using a combination of:

- Border
- Surface color
- Very soft shadow

==================================================
13. ICONOGRAPHY
==================================================

Define the icon style.

Use consistent Material Icons or another Flutter-compatible icon system.

Suggested contact icons:

Phone
Email
LinkedIn
GitHub

Suggested UI icons:

Arrow
Play
Menu
External link
Location if needed

Do not mix many different icon styles.

Define:

- Icon size
- Icon color
- Active state
- Disabled state

==================================================
14. PROFILE / AVATAR GUIDELINES
==================================================

Define the visual treatment for:

- Profile avatar
- Avatar border
- Avatar size
- Spacing around avatar
- Name
- NIM
- Program badge or label

The profile section should be the strongest visual identity area.

Suggested hierarchy:

Avatar
↓
Muhamad Rafli
↓
NIM: 2411073
↓
Informatika
↓
Short introduction

Do not make the profile area excessively large.

==================================================
15. SKILL SYSTEM
==================================================

Create a reusable skill-chip component specification.

Skills:

JavaScript
React
Tailwind CSS
UI/UX
Node.js
Git/GitHub
Figma
Flutter

Define:

- Chip height
- Horizontal padding
- Border radius
- Background color
- Text color
- Font size
- Font weight
- Spacing between chips
- Wrapping behavior

The skills should appear as clean compact chips.

Use Wrap-style behavior in Flutter rather than forcing all skills into one row.

==================================================
16. CONTACT SYSTEM
==================================================

Create a reusable contact-item component.

The contact section should support:

- Phone
- Email
- LinkedIn
- GitHub

Each item should have:

Icon
Label
Value / placeholder

Use placeholders for actual contact details.

Example:

Phone
+62 XXX-XXXX-XXXX

Email
your.email@example.com

LinkedIn
linkedin.com/in/username

GitHub
github.com/username

Make it obvious that these are placeholders and must be replaced later.

Do not invent real accounts.

==================================================
17. MULTIMEDIA / VIDEO SYSTEM
==================================================

The application must include one multimedia element.

For now, create a design specification for a video placeholder.

The placeholder should contain:

- Video thumbnail area
- Play button
- Optional video duration placeholder
- Title
- Short description
- About Me context

The video section should visually stand out but still match the overall light theme.

Example content:

"About Me"

"Video introduction placeholder. This section will contain a short introduction video in a future version."

Do not require an actual video file at this stage.

==================================================
18. COMPONENT SYSTEM
==================================================

Define reusable components.

At minimum include specifications for:

1. ProfileHeader
2. IdentityInfo
3. SectionHeader
4. SkillChip
5. SkillList
6. ContactItem
7. ContactCard
8. VideoPlaceholder
9. AboutMeCard
10. PrimaryButton
11. SecondaryButton
12. Divider

For every component define:

- Purpose
- Visual structure
- Dimensions
- Padding
- Typography
- Colors
- Radius
- Interaction
- Flutter implementation suggestion

Do not write full Dart code.

The design system should tell a Flutter developer exactly how each component should look.

==================================================
19. SCREEN STRUCTURE
==================================================

Define the main screen structure.

The main screen should be a single scrollable digital identity/profile screen.

Suggested structure:

--------------------------------------------------
Top / Profile
--------------------------------------------------

Avatar

Muhamad Rafli

NIM: 2411073

Informatika

Short profile description

--------------------------------------------------
Skills
--------------------------------------------------

Skill chips

JavaScript
React
Tailwind CSS
UI/UX
Node.js
Git/GitHub
Figma
Flutter

--------------------------------------------------
About Me
--------------------------------------------------

Short placeholder description

--------------------------------------------------
Multimedia
--------------------------------------------------

Video placeholder
Play button
Title
Description

--------------------------------------------------
Contact
--------------------------------------------------

Phone
Email
LinkedIn
GitHub

--------------------------------------------------
Footer
--------------------------------------------------

Simple portfolio footer / identity text

--------------------------------------------------

The actual design system may improve this structure if needed, but it must remain simple and appropriate for the assignment.

==================================================
20. INTERACTION STATES
==================================================

Define states for interactive elements:

- Default
- Pressed
- Hover where applicable
- Focused
- Disabled
- Selected

Since this is a mobile Flutter application, prioritize:

- Tap
- Press
- Focus
- Scroll

Do not design unnecessary web-only interactions.

==================================================
21. RESPONSIVE BEHAVIOR
==================================================

Define how the UI should behave on:

- Small Android phones
- Normal Android phones
- Large Android phones
- Tablet if applicable

The design should primarily target mobile.

Define:

- Minimum horizontal padding
- Maximum content width
- Skill wrapping
- Contact layout behavior
- Video aspect ratio

The UI must not overflow horizontally.

==================================================
22. ACCESSIBILITY
==================================================

Include practical accessibility rules.

For example:

- Maintain readable text contrast.
- Do not rely only on color to communicate information.
- Use sufficiently large touch targets.
- Use semantic labels for contact icons.
- Ensure text remains readable on small screens.
- Avoid excessively small captions.
- Preserve meaningful hierarchy.

Use at least approximately 44–48 dp touch targets for interactive controls.

==================================================
23. FLUTTER IMPLEMENTATION GUIDELINES
==================================================

Explain how the design system maps to Flutter.

Recommend creating centralized theme/design tokens.

For example:

ThemeData
ColorScheme
TextTheme
BorderRadius constants
Spacing constants
Elevation constants

The future implementation should avoid hardcoding random values throughout Dart files.

Recommend a structure such as:

lib/
  theme/
    app_theme.dart
    app_colors.dart
    app_spacing.dart
    app_typography.dart
    app_radius.dart

This is only a recommendation for the future implementation.

Do NOT create these files now.

Explain that all UI components should consume centralized design tokens.

==================================================
24. DESIGN TOKENS
==================================================

Create a compact design-token table containing:

- Colors
- Font sizes
- Font weights
- Spacing
- Radius
- Icon sizes
- Component heights
- Content width
- Video aspect ratio

These tokens must be internally consistent.

Use dp/logical pixels terminology appropriate for Flutter.

==================================================
25. CONTENT GUIDELINES
==================================================

Use the following exact identity information:

Name:
Muhamad Rafli

NIM:
2411073

Program:
Informatika

Skills:
JavaScript
React
Tailwind CSS
UI/UX
Node.js
Git/GitHub
Figma
Flutter

Contact information must remain placeholder-based.

Do not create fake personal information.

Do not change the user's name, NIM, or program.

==================================================
26. DESIGN STYLE
==================================================

The final design system should describe the visual style as:

"Minimal modern digital identity portfolio"

Characteristics:

- Light theme
- Clean white/light gray background
- Dark typography
- Blue/purple primary accent
- Rounded cards
- Subtle borders
- Soft shadows
- Clear spacing
- Strong profile identity
- Compact skill chips
- Simple contact section
- Modern video placeholder
- Professional but still suitable for a university student

Avoid:

- Neon colors
- Excessive gradients
- Heavy glassmorphism
- Excessive animations
- Overly complex navigation
- Dashboard-like layouts
- Too many cards
- Excessive shadows
- Very small text
- Cluttered UI
- Dark theme

==================================================
27. REFERENCE IMAGE INTERPRETATION
==================================================

Use the provided classroom reference image as visual inspiration.

The reference communicates a mobile digital identity/profile concept with:

- Profile avatar
- Name
- NIM
- Program/skill information
- Contact icons
- About Me area
- Multimedia/video element

The final design system should preserve this conceptual structure while making the UI more polished, consistent, and modern.

Do not attempt to reproduce classroom projection artifacts, wall cracks, projector distortion, or other elements from the photograph.

Only use the application UI shown in the reference as design inspiration.

==================================================
28. DOCUMENT QUALITY REQUIREMENTS
==================================================

The resulting design-system.md must be:

- Written in clear English.
- Easy for an AI coding agent to understand.
- Structured with Markdown headings.
- Specific enough to implement without guessing.
- Concise enough to remain practical.
- Consistent across all sections.
- Free from contradictory values.
- Based on reusable design tokens.
- Flutter-oriented.
- Suitable for a first portfolio application.

Use tables where they make the design tokens easier to understand.

Avoid vague descriptions such as:

"Use some padding."

Instead specify:

"Use 16 dp horizontal padding for standard cards."

Avoid vague color descriptions such as:

"Use a nice blue."

Instead provide exact HEX values.

==================================================
29. FINAL CHECK
==================================================

Before finishing design-system.md, verify:

[ ] All required identity information is included.
[ ] The design is light theme.
[ ] Flutter is the target technology.
[ ] The design is mobile-first.
[ ] The profile/avatar section is defined.
[ ] All 8 skills are defined.
[ ] Contact information uses placeholders.
[ ] Multimedia/video placeholder is defined.
[ ] About Me section is defined.
[ ] Colors have exact HEX values.
[ ] Typography has exact sizes and weights.
[ ] Spacing tokens are defined.
[ ] Radius tokens are defined.
[ ] Icon sizes are defined.
[ ] Components are reusable.
[ ] Responsive behavior is defined.
[ ] Accessibility is addressed.
[ ] Flutter implementation guidance is included.
[ ] Asset paths are documented.
[ ] No real contact information is invented.
[ ] No Dart implementation is created.
[ ] No unnecessary dependencies are introduced.

==================================================
30. OUTPUT REQUIREMENT
==================================================

Create ONLY:

design-system.md

Do not create the Flutter UI yet.

The final design-system.md should serve as the design contract that a future AI coding agent can follow to implement the "My Digital Identity" Flutter application consistently.