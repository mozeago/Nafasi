# Nafasi - Real-time Parking App

## Project Scope

Nafasi is a mobile application built with Jetpack Compose for Android. It aims to streamline the parking experience for both drivers and parking space owners in Mombasa,Malindi-Kenya.

### Key Features (User)

* __Real-time Parking Search:__
  * Find available parking spaces with live updates.
* __Radius Control:__
  * Refine parking searches within a user-defined radius.
* __Location-based Search:__
  * Search for parking by town name and pinpoint a specific location.
* __Parking Details:__
  * View available amenities (restrooms, security) for each parking space.
* __Communication Channels:__
  * Contact parking attendant/owner via WhatsApp API or SMS for inquiries.
* __Parking Reviews & History:__
  * See past experiences and reviews from other users.

### Key Features (Parking Owner)

* __Parking Space Registration:__
  * Add parking spaces with details like vehicle category and capacity.
* __Parking Conditions:__
  * Set specific conditions for allowed vehicles (e.g., size restrictions).
* __Payment Confirmation:__
  * Send QR code receipts with payment details to users.

### Security Features

* __Vehicle Photos:__
  * Before leaving, users take 6 pictures of their car for evidence in case of theft.
* __Theft Alert System:__
  * Single-button alert to notify 5 closest police stations, prioritizing highway stations.
* __Community Alert:__
  * Broadcast notification to other users in the same parking spot for caution.
* __Probability-based Search:__
  * System sends search notifications to nearby Nafasi users to report a stolen vehicle.

### Technology Stack

* Android App Development
  * Jetpack Compose (UI)


* (To be confirmed, after research-ML): Backend technology (e.g., Firebase, Cloud Firestore)

* (To be confirmed): Third-party integrations (e.g., WhatsApp API)

#### TO-DO List (High Priority)

* __User Interface (UI):__
  + Design and develop core screens using Jetpack Compose.
  + Implement functionalities for real-time parking search, radius control, and location-based search.
  + Develop screens for displaying parking details, communication options, and user reviews.
* __User Functionality:__
  + Integrate real-time parking data updates.
  + Implement location services for user positioning and radius search.
  + Develop functionalities for contacting parking attendants/owners (WhatsApp API, SMS).
  + Integrate user authentication and review system.
* __Parking Owner Features:__
  + Design screens for parking space registration and management.
  + Develop functionalities for adding parking spaces, setting conditions, and sending QR code receipts.
* __Security Features:__
  + Implement functionality for taking and storing vehicle photos.
  + Integrate a theft alert system with location sharing to police stations.
  + Design a notification system for community alerts within the same parking spot.

### TO-DO List (Stretch Goals)

* __Probability-based Search for Stolen Vehicles:__
  * Develop an algorithm to send targeted search notifications to Nafasi users in the vicinity of a stolen car.
* __Monetization Strategy:__
  * Explore options like parking space listing fees or in-app purchases for premium features.
* __Accessibility Features:__
  * Implement functionalities for users with disabilities (e.g., voice search, clear labeling).
  * Scalability: Design the app's backend to handle future growth and feature additions.
* __Testing:__
  * Develop a comprehensive testing strategy for UI, functionalities, and performance.

This serves as a starting point for project discussions and development. It will be continuously updated as the project progresses.
