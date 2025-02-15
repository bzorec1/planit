# PlanIt

App Name: PlanIt
A group event management app for decision-making, scheduling, and tracking participation.

1. Minimal Viable Product (MVP)
Overview
The MVP version of EventEase is focused on allowing users to create and RSVP for events, view event details, and receive basic notifications. The app syncs events with the user's calendar and has a simple backend to manage user data and events.

Features for MVP:
User Authentication & Profile Setup

Sign-up/Login via email or social accounts.
Basic user profile creation.
Home Screen (Dashboard)

View a list of upcoming events.
Button to create new events.
Event Creation

Ability to create a new event (name, date, time, location).
Invite others to the event (basic invite system).
RSVP System

Users can RSVP as "Going," "Maybe," or "Not Going."
View attendee list and their RSVP status.
Event Details Screen

Detailed information about the event: name, time, location, description, and RSVP status of all attendees.
Basic Notifications

Push notifications for event updates (e.g., when the event is approaching or when someone RSVPs).
Calendar Integration

Sync event with the device's calendar (Google Calendar, iOS Calendar).
Option to add the event to the user’s calendar from the event detail screen.
Backend (API)

Simple .NET API to manage user data, events, and RSVPs.
Basic database setup to store event details, user info, and RSVP statuses.
2. Full Features
Overview
The full version of EventEase includes all features from the MVP and additional enhancements for event decision-making, social interaction, user engagement, and more.

Full Features List:
User Authentication & Profile Management

Advanced user registration and login (email, Google/Facebook login).
Customizable user profiles (photo, bio, preferences).
Privacy settings to control who can see user profiles and events.
Home Screen (Dashboard)

Enhanced event overview with upcoming events, past events, and quick access to "Create Event."
Filtering and sorting events based on time, status, and participation.
Option to search for specific events.
Event Creation and Management

Event creation with additional details: description, event type (party, dinner, meeting, etc.), location, and budget.
Option to add tags (e.g., “outdoor,” “family-friendly,” “sports”).
Set event thresholds (minimum attendance needed to confirm the event).
Event reminders and calendar sync options.
RSVP System

Expanded RSVP options (Yes, Maybe, No, Waiting).
Option to add meal choices, transportation details, or other preferences.
Waiting list feature (if an event reaches capacity, users can be placed on a waiting list).
Event Voting & Decision-Making

Voting for restaurant choices, activity types, or other event details (time, location).
Real-time voting results (visual representation like a bar chart or pie chart).
Quick feedback after voting (e.g., "You voted for X!" or "This option is winning").
Event Details Screen

Rich event description with media (images, links).
Interactive map for location (Google Maps or OpenStreetMap integration).
Attendee list with the ability to see individual RSVP statuses.
Comments and discussion section for group coordination.
Notifications

Real-time push notifications for updates: RSVP changes, event reminders, new voting options.
Customizable notification settings (reminder intervals, types of notifications).
Calendar Integration

Full integration with external calendars (Google Calendar, iOS Calendar, etc.).
Auto-syncing of event dates and reminders with the user’s personal calendar.
Option to create a recurring event (e.g., weekly lunches or meetings).
Social Sharing & Group Invitations

Option to invite friends and family via email, SMS, social media, or QR code.
Share event details on social media (Facebook, Twitter, WhatsApp).
Group chats within events for coordination.
User Engagement & Gamification

Earn badges or points for participating in events, voting, or organizing events.
Ranking system for active users (e.g., "Top Organizer," "Most Engaged").
Personal stats (number of events attended, events created).
Event History & Analytics

View past events, attendance history, and participation stats.
Financial tracking for events (split costs, track who owes what).
Backend & Scalability

More robust .NET API with enhanced security, performance, and scalability for a growing user base.
Database management for a larger number of users and events.
Server-side event validation (e.g., checking if enough RSVPs are received before confirming the event).
Admin Dashboard (Optional)

Event administrators can manage users, approve events, and moderate discussions.
Event leaders can set custom event rules (e.g., no-show penalties).
Installation & Setup
Prerequisites:
Android Studio for Kotlin development.
.NET SDK for backend development.
Firebase (for notifications).
Google Maps API (for location features).
A basic understanding of Kotlin, .NET, and mobile app development.
Backend (API) Setup:
Clone the repository for the .NET API.
Set up the database (SQL or NoSQL).
Configure Firebase for notifications.
Configure calendar integration with Google API or iOS Calendar API.
Android App Setup:
Open the project in Android Studio.
Install necessary dependencies (e.g., Firebase, Maps SDK).
Configure Android app to interact with the backend API.
Implement the UI according to the provided designs.
Contributing
We welcome contributions to make EventEase better! Please fork this repository, submit pull requests, and report issues to help improve the app.

License
This project is licensed under the MIT License - see the LICENSE file for details.
