# PlanIt

_PlanIt_ is a group event management app for decision-making, scheduling, and tracking participation. The app helps users easily create, join, and RSVP to events, as well as sync event details with their calendars. It also facilitates group decision-making by allowing users to vote on options for events.

---

## **1. Minimal Viable Product (MVP)**

### **Overview**

The MVP version of _PlanIt_ is focused on allowing users to create and RSVP for events, view event details, and receive basic notifications. The app syncs events with the user's calendar and has a simple backend to manage user data and events. Additionally, it includes a voting system for making decisions on event options.

### **Features for MVP**:
1. **User Authentication & Profile Setup**
   - Sign-up/Login via email or social accounts.
   - Basic user profile creation.

2. **Home Screen (Dashboard)**
   - View a list of upcoming events.
   - Button to create new events.

3. **Event Creation**
   - Ability to create a new event (name, date, time, location).
   - Invite others to the event (basic invite system).

4. **RSVP System**
   - Users can RSVP as "Going," "Maybe," or "Not Going."
   - View attendee list and their RSVP status.

5. **Event Details Screen**
   - Detailed information about the event: name, time, location, description, and RSVP status of all attendees.

6. **Basic Notifications**
   - Push notifications for event updates (e.g., when the event is approaching or when someone RSVPs).

7. **Calendar Integration**
   - Sync event with the device's calendar (Google Calendar, iOS Calendar).
   - Option to add the event to the user’s calendar from the event detail screen.

8. **Decision-Making Feature (Voting)**
   - Event organizers can create a list of options for decision-making (e.g., restaurant choices, activities, event time).
   - Group members can vote on the options presented.
   - Display results in real-time (e.g., vote tally, "winning" option).
   - Options can be presented as a poll or a selection menu (radio buttons, dropdown list).

9. **Backend (API)**
   - Simple **.NET API** to manage user data, events, and RSVPs.
   - Basic database setup to store event details, user info, RSVP statuses, and voting data.

---

## **2. Full Features**

### **Overview**

The full version of _PlanIt_ includes all features from the MVP and additional enhancements for event decision-making, social interaction, user engagement, and more.

### **Full Features List**:

1. **User Authentication & Profile Management**
   - Advanced user registration and login (email, Google/Facebook login).
   - Customizable user profiles (photo, bio, preferences).
   - Privacy settings to control who can see user profiles and events.

2. **Home Screen (Dashboard)**
   - Enhanced event overview with upcoming events, past events, and quick access to "Create Event."
   - Filtering and sorting events based on time, status, and participation.
   - Option to search for specific events.

3. **Event Creation and Management**
   - Event creation with additional details: description, event type (party, dinner, meeting, etc.), location, and budget.
   - Option to add tags (e.g., “outdoor,” “family-friendly,” “sports”).
   - Set event thresholds (minimum attendance needed to confirm the event).
   - Event reminders and calendar sync options.

4. **RSVP System**
   - Expanded RSVP options (Yes, Maybe, No, Waiting).
   - Option to add meal choices, transportation details, or other preferences.
   - Waiting list feature (if an event reaches capacity, users can be placed on a waiting list).

5. **Event Voting & Decision-Making**
   - **Option to Create Decision-Making Polls**: Event organizers can create options (e.g., restaurant choices, activity types, or other event details) for group voting.
   - Users vote on the options, and results are updated in real time.
   - Visual representation of the voting results (e.g., bar charts or pie charts).
   - Display the winning option dynamically (e.g., "Winner: Restaurant A").
   - Ability to close the poll once a decision is made and lock the options.

6. **Event Details Screen**
   - Rich event description with media (images, links).
   - Interactive map for location (Google Maps or OpenStreetMap integration).
   - Attendee list with the ability to see individual RSVP statuses.
   - Comments and discussion section for group coordination.

7. **Notifications**
   - Real-time push notifications for updates: RSVP changes, event reminders, new voting options.
   - Customizable notification settings (reminder intervals, types of notifications).

8. **Calendar Integration**
   - Full integration with external calendars (Google Calendar, iOS Calendar, etc.).
   - Auto-syncing of event dates and reminders with the user’s personal calendar.
   - Option to create a recurring event (e.g., weekly lunches or meetings).

9. **Social Sharing & Group Invitations**
   - Option to invite friends and family via email, SMS, social media, or QR code.
   - Share event details on social media (Facebook, Twitter, WhatsApp).
   - Group chats within events for coordination.

10. **User Engagement & Gamification**
    - Earn badges or points for participating in events, voting, or organizing events.
    - Ranking system for active users (e.g., "Top Organizer," "Most Engaged").
    - Personal stats (number of events attended, events created).

11. **Event History & Analytics**
    - View past events, attendance history, and participation stats.
    - Financial tracking for events (split costs, track who owes what).

12. **Backend & Scalability**
    - More robust **.NET API** with enhanced security, performance, and scalability for a growing user base.
    - Database management for a larger number of users and events.
    - Server-side event validation (e.g., checking if enough RSVPs are received before confirming the event).
    
13. **Admin Dashboard (Optional)**
    - Event administrators can manage users, approve events, and moderate discussions.
    - Event leaders can set custom event rules (e.g., no-show penalties).

---

## **Installation & Setup**

### **Prerequisites**:
- Android Studio for Kotlin development.
- .NET SDK for backend development.
- Firebase (for notifications).
- Google Maps API (for location features).
- A basic understanding of Kotlin, .NET, and mobile app development.

### **Backend (API) Setup**:
1. Clone the repository for the **.NET API**.
2. Set up the database (SQL or NoSQL).
3. Configure Firebase for notifications.
4. Configure calendar integration with Google API or iOS Calendar API.

### **Android App Setup**:
1. Open the project in **Android Studio**.
2. Install necessary dependencies (e.g., Firebase, Maps SDK).
3. Configure Android app to interact with the backend API.
4. Implement the UI according to the provided designs.

---

## **Contributing**

We welcome contributions to make **PlanIt** better! Please fork this repository, submit pull requests, and report issues to help improve the app.

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
