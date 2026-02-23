# SkillSync - Skill-Sharing Community Platform

## Project Overview

SkillSync is a modern, responsive web application designed to facilitate skill-sharing within a community. It enables users to discover, learn, and teach skills with others in their local community. The platform creates meaningful connections between people with different expertise levels and interests.

## Features

### 🏠 Dashboard
- **Home Page** - Main landing page displaying featured community members and their skills
- **Responsive Grid Layout** - Three-column layout showcasing skill-sharing profiles with real user photos
- **Quick View Access** - Easy navigation to view detailed user profiles

### 👥 User Profiles
- **Individual Profile Pages** - Detailed pages for each community member:
  - BUGINGO Flexon - Traditional Cuisine & Farming Techniques Expert
  - UWINEZA Khadidja - Graphic Design & Adobe Tools Specialist
  - KADAMAGE Denise - Math Tutoring Professional
- **Profile Information**:
  - Real user photos and background images
  - Biography and expertise description
  - Skills they can teach
  - Skills they want to learn
  - Experience statistics
  - Location information
  - Star ratings and achievement metrics

### 📚 My Skills Management
- **Manage Your Skills** - Add, edit, and delete skills you can teach
- **Skill Cards** - Display your expertise with proficiency levels and categories
- **Profile Management** - Showcase your capabilities to the community

### 📋 Learning Requests
- **Browse Requests** - View learning requests from community members
- **Manage Requests** - Accept, decline, or track pending requests
- **Tabbed Navigation** - Organize requests by status (Pending, Accepted, Declined)

### ⚙️ Settings
- **Account Settings** - Manage profile information and preferences
- **Privacy Controls** - Configure who can view your skills and profile
- **Security Settings** - Password and authentication management
- **Notification Preferences** - Customize how you receive community updates

## Technical Stack

- **Frontend Framework**: HTML5 + Tailwind CSS
- **Styling**: Tailwind CSS (via CDN)
- **Responsiveness**: Mobile-first responsive design with Tailwind breakpoints
- **Interactivity**: Pure CSS-based interactions (no JavaScript)
- **Assets**: User photos stored in `/images` folder
  - flexon.jpg
  - khadidja.jpg
  - denise.jpg

## Project Structure

```
f:\CCAT\
├── index.html              # Main dashboard/home page
├── flexon.html             # Flexon's profile page
├── khadidja.html           # Khadidja's profile page
├── denise.html             # Denise's profile page
├── my-skills.html          # Skills management page
├── requests.html           # Learning requests page
├── settings.html           # Settings/preferences page
├── images/                 # User photos directory
│   ├── flexon.jpg
│   ├── khadidja.jpg
│   └── denise.jpg
└── README.md              # This file
```

## Design Features

### Visual Design
- **Dark Theme**: Professional dark blue interface (bg-slate-900) with light text
- **Sticky Header**: Always-accessible navigation with search functionality
- **Fixed Sidebar**: Quick navigation menu with category filters
- **Responsive Footer**: Consistent footer across all pages

### User Experience
- **Hover Effects**: Interactive elements with smooth transitions (duration-300)
- **Active States**: Visual feedback for selected filters and navigation items
- **Mobile-Friendly**: Hidden sidebar on mobile, visible on medium screens and above
- **Smooth Animations**: Scale and color transitions for better UX
- **Accessibility**: Semantic HTML with proper alt text for images

### Navigation
All pages are fully interconnected with proper navigation:
- Home page links to individual profiles
- Profile pages have back-to-dashboard links
- Sidebar menu provides quick access to all sections
- Responsive mobile navigation

## Color Scheme

- **Dark Background**: `bg-slate-900` - Professional dark interface
- **Text Primary**: `text-slate-300` - Main text color
- **Text Hover**: `text-white` - Highlighted text
- **Accent Colors**:
  - Blue (`bg-blue-600`) - Primary actions and active states
  - Amber/Orange - Used for Flexon (Traditional/Warm theme)
  - Indigo/Purple - Used for Khadidja (Creative theme)
  - Teal/Emerald - Used for Denise (Academic theme)

## Getting Started

### Running the Application
1. Navigate to the project directory: `f:\CCAT\`
2. Open `index.html` in a web browser
3. Use the navigation menu to explore different sections
4. Click on user profiles to view detailed information
5. Manage your skills and browse community requests

### Browser Requirements
- Modern browser with HTML5 support
- CSS3 support for Tailwind CSS
- No additional dependencies required

## Skills in the Community

### Can Teach:
- **Flexon**: Traditional Rwandan Cuisine, Urban Farming Techniques
- **Khadidja**: Graphic Design, Adobe Creative Suite Tools
- **Denise**: Mathematics Tutoring

### Want to Learn:
- **Flexon**: Smartphone Basics & Digital Literacy
- **Khadidja**: Guitar & Music Skills
- **Denise**: Kinyarwanda Language

## Community Statistics

- **Total Users**: 3 active community members featured
- **Skills Available**: Multiple expertise areas
- **Combined Experience**: 30+ years of teaching experience
- **Success Rate**: 95%+ learning success from tutoring programs
- **Student Impact**: 850+ students positively impacted

## Future Enhancements

Potential additions to the platform:
- User registration and authentication
- Real-time messaging between members
- Rating and review system
- Advanced search and filtering
- Calendar scheduling for lessons
- Payment integration for premium skills
- Community forums and discussion boards
- Mobile app version
- Video tutorials and live classes

## Design Notes

- All components use responsive Tailwind CSS utilities
- Pure CSS for interactivity (no JavaScript framework)
- Real user photos enhance community feel
- Consistent color themes for each user profile
- Dark theme reduces eye strain and modern UI aesthetics

## Accessibility

- Semantic HTML structure
- Alt text for all images
- Proper heading hierarchy
- Color contrast meets WCAG standards
- Keyboard-friendly navigation
- Focus states for interactive elements

---

**Platform**: SkillSync  
**Version**: 1.0  
**Last Updated**: February 2026  
**Location**: Kigali, Rwanda
"# SkillSync" 
