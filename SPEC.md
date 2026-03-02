# Personal Portfolio Website Specification

## Project Overview
- **Project Name**: Personal Portfolio
- **Type**: Single-page portfolio website
- **Core Functionality**: Showcase skills, services, and projects to attract clients
- **Target Users**: Business owners, startups, individuals seeking web development services

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with logo and menu links
- **Hero**: Split layout (text left, image right)
- **About**: Two-column grid
- **Services**: 4-card grid
- **Skills**: Animated progress bars
- **Portfolio**: Filterable image grid with modal
- **Testimonials**: Card slider
- **Contact**: Form + info split layout
- **Footer**: Multi-column with links

### Responsive Breakpoints
- Desktop: > 1024px
- Tablet: 768px - 1024px
- Mobile: < 768px

### Visual Design

#### Color Palette
- Primary: `#4F46E5` (Indigo)
- Secondary: `#7C3AED` (Purple)
- Accent: `#06B6D4` (Cyan)
- Dark: `#1E1B4B`
- Light: `#F8FAFC`
- White: `#FFFFFF`
- Gray: `#64748B`

#### Typography
- Headings: 'Outfit', sans-serif (700 weight)
- Body: 'DM Sans', sans-serif (400, 500 weight)
- Sizes: H1: 3.5rem, H2: 2.5rem, H3: 1.5rem, Body: 1rem

#### Spacing System
- Section padding: 100px vertical
- Container max-width: 1200px
- Card padding: 30px
- Gap: 30px

#### Visual Effects
- Card shadows: `0 10px 40px rgba(79, 70, 229, 0.1)`
- Hover transitions: 0.3s ease
- Gradient background: linear gradient with subtle mesh
- Border radius: 16px for cards, 50px for buttons

### Components

#### Navigation
- Logo text with gradient
- Menu items with hover underline animation
- Mobile hamburger menu

#### Hero Section
- Large heading with gradient text accent
- Profile image with floating animation
- CTA buttons with gradient and outline variants

#### Service Cards
- Icon with gradient background
- Title and description
- Hover: lift effect with shadow increase

#### Skill Bars
- Animated fill on scroll
- Percentage label
- Gradient fill matching theme

#### Portfolio
- Filter tabs with active state
- Image overlay with project title on hover
- Modal with project details

#### Testimonials
- Card with client photo, name, company
- Star rating (5 stars)
- Navigation dots

#### Contact Form
- Floating labels
- Input focus states
- Submit button with loading state

## Functionality Specification

### Core Features
1. Smooth scroll navigation
2. Sticky header with background on scroll
3. Portfolio filter (All, Web, Branding, UI/UX)
4. Portfolio modal popup
5. Testimonial slider auto-play
6. Form validation
7. Mobile menu toggle
8. Scroll-triggered animations

### Animations
- Hero: Fade in up on load
- Sections: Fade in on scroll
- Skills: Animate width on scroll into view
- Cards: Hover lift effect
- Buttons: Scale on hover

## Acceptance Criteria
- [ ] All 8 sections visible and properly styled
- [ ] Responsive on mobile, tablet, desktop
- [ ] Smooth scrolling works
- [ ] Portfolio filters correctly
- [ ] Modal opens/closes properly
- [ ] Form validates required fields
- [ ] Animations trigger on scroll
- [ ] No console errors
