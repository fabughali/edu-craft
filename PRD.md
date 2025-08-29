# EduCraft - Product Requirements Document (PRD)

## 1. Executive Summary

EduCraft is a comprehensive online learning platform designed to connect students (clients) with educational content and instructors (tutors). The platform serves three primary user roles: Clients (students), Tutors (instructors), and Administrators. EduCraft aims to provide a seamless, responsive, and engaging learning experience across mobile, tablet, and desktop devices.

**Current Status**: ✅ **LIVE AND DEPLOYED** at [https://fabughali.github.io/edu-craft/](https://fabughali.github.io/edu-craft/)

## 2. Product Overview

### 2.1 Vision
To create an accessible, feature-rich educational platform that empowers learners to acquire new skills and knowledge while providing educators with tools to effectively share their expertise.

### 2.2 Target Audience
- **Clients/Students**: Individuals seeking to learn new skills or expand their knowledge
- **Tutors/Instructors**: Subject matter experts who create and deliver educational content
- **Administrators**: Platform managers who oversee operations and ensure quality

## 3. User Roles and Personas

### 3.1 Client/Student
- Browses and searches for courses
- Enrolls in and completes courses
- Tracks learning progress
- Saves favorite courses to wishlist
- Makes payments for premium content
- Manages personal profile

### 3.2 Tutor/Instructor
- Creates and manages course content
- Monitors student progress and engagement
- Receives payments for course sales
- Manages personal profile and credentials

### 3.3 Administrator
- Oversees platform operations
- Manages users and content
- Reviews and approves courses
- Handles dispute resolution
- Accesses analytics and reporting

## 4. Feature Requirements

### 4.1 Authentication & User Management
- User registration and login
- Role-based access control (Client, Tutor, Admin)
- Profile management
- Password recovery

### 4.2 Client Features
- Course discovery and browsing
- Advanced filtering and search
- Course details view with comprehensive information
- Wishlist functionality
- Course enrollment and progress tracking
- Payment processing
- Reviews and ratings

### 4.3 Tutor Features
- Course creation and management
- Student progress monitoring
- Analytics dashboard
- Revenue tracking
- Profile and credential management

### 4.4 Admin Features
- User management
- Content moderation
- Platform analytics
- System configuration

### 4.5 Common Features
- Responsive design for all device sizes
- Theme customization (light/dark mode)
- Notifications system
- Search functionality

## 5. Technical Requirements

### 5.1 Architecture
- Flutter-based cross-platform application
- Riverpod for state management
- Go Router for navigation

### 5.2 State Management
- Use of Riverpod providers
- AsyncNotifierProvider for asynchronous state
- StateProvider for simple state

### 5.3 UI/UX Requirements
- Material Design 3 implementation
- Responsive layouts for all screen sizes
- Light and dark theme support
- Consistent branding and visual language

### 5.4 Performance Requirements
- Fast loading times
- Smooth animations and transitions
- Efficient resource usage
- Offline capabilities for enrolled courses

## 6. User Interface Design

### 6.1 Design System
- Consistent color palette with primary green (#60B502)
- Typography hierarchy
- Component library for consistent UI elements
- Responsive grid system

### 6.2 Key Screens
- Login/Signup
- Client Home with course discovery
- Course Details
- Payment Processing
- User Profile
- Tutor Dashboard
- Admin Dashboard

### 6.3 Navigation
- Bottom navigation for mobile clients
- Side navigation for desktop
- Breadcrumb navigation for deep linking

## 7. Data Models

### 7.1 User
- Basic information (name, email, etc.)
- Role (Client, Tutor, Admin)
- Profile details

### 7.2 Course
- Title, description, instructor
- Content (lessons, sections)
- Pricing information
- Ratings and reviews
- Categories and tags

### 7.3 Enrollment
- User-course relationship
- Progress tracking
- Completion status

### 7.4 Payment
- Transaction details
- Payment method
- Course purchase information

## 8. Non-Functional Requirements

### 8.1 Performance
- App startup time under 3 seconds
- Smooth scrolling and transitions (60fps)
- Efficient memory usage

### 8.2 Security
- Secure authentication
- Data encryption
- Payment information security

### 8.3 Accessibility
- WCAG 2.1 compliance
- Screen reader support
- Keyboard navigation

### 8.4 Internationalization
- Multi-language support
- Localization framework

## 9. Future Enhancements

### 9.1 Phase 2 Features
- Live sessions between tutors and students
- Community forums and discussion
- Subscription-based pricing model
- Advanced analytics for tutors
- Content recommendation engine

### 9.2 Phase 3 Features
- Offline course access
- Mobile notifications
- Social learning features
- Certification verification system
- Integration with third-party learning tools

## 10. Success Metrics

- User acquisition and retention rates
- Course completion rates
- Revenue generation
- User satisfaction scores
- Platform uptime and performance

## 11. Timeline and Milestones

### 11.1 Phase 1 (MVP) ✅ **COMPLETED**
- Authentication system
- Basic course browsing and enrollment
- Payment processing
- User profiles
- **Web deployment completed**

### 11.2 Phase 2
- Enhanced course discovery
- Tutor dashboard improvements
- Review and rating system
- Advanced filtering

### 11.3 Phase 3
- Admin dashboard
- Analytics and reporting
- Community features
- Mobile optimizations

## 12. Technical Implementation Notes

The application is built using Flutter with a focus on:
- Clean architecture principles
- Separation of concerns
- Reusable components
- Comprehensive testing
- Performance optimization
- Accessibility compliance

State management utilizes Riverpod with AsyncNotifierProvider for handling asynchronous operations and proper loading/error states.

UI follows Material Design 3 guidelines with custom theming to maintain brand identity across both light and dark modes.

## 13. Deployment Information

### 13.1 Current Deployment
- **Status**: ✅ Live and accessible
- **URL**: [https://fabughali.github.io/edu-craft/](https://fabughali.github.io/edu-craft/)
- **Repository**: [https://github.com/fabughali/edu-craft/](https://github.com/fabughali/edu-craft/)
- **Branch**: gh-pages (default)
- **Last Updated**: Current deployment

### 13.2 Technical Stack
- **Frontend**: Flutter Web
- **State Management**: Riverpod
- **Navigation**: Go Router
- **Backend**: Firebase (Auth, Firestore, Storage, Analytics)
- **Deployment**: GitHub Pages
- **Build System**: Flutter Web Build

---

*Last Updated: Current deployment - EduCraft is live and ready for users!* 