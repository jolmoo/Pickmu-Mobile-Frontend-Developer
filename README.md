# Pickmu — Mobile Frontend

**Role:** Mobile Frontend Developer  
**Tech Stack:** React Native, Expo, EAS, React Navigation, Context API/Redux, Geolocation APIs, Real-time Chat  

---

## Project Overview
Pickmu is a delivery mobile app connecting individuals and businesses with nearby riders. Users can request services, track orders in real time, manage profiles and wallets, upload documents, and communicate directly with riders.  

I developed the **complete mobile frontend**, including all user and rider interfaces, adaptive screens, and integration with APIs and device features such as geolocation, push notifications, and real-time updates using Webhooks.  

---

## Screens Overview

### Authentication Screens
- **Login:** User login via email, Google, or Apple.  
- **Register:** Create new accounts with email verification.  
- **Phone Verification:** Validate user phone number for security.  
- **Password Recovery:** Reset forgotten passwords.  
- **Onboarding Swiper:** Introductory slides for new users.  
- **Intro Screen:** Base introduction to the app.  

### User Screens
- **Home:** Main dashboard showing available services.  
- **Documents Upload (Docs):** Upload identification or service-related documents.  
- **Order History (Historial):** Track past services and deliveries.  
- **Profile:** View and edit user information.  
- **Wallet:** Manage balance, add funds, and view transactions.  
- **Settings (Ajustes):** App configuration options.  
- **Terms & Conditions:** Legal information.  
- **Multi-step Onboarding (OnBoarding*):** Guide users through service requests like food delivery, package pickup, or scheduled shipments.  
- **Current Order Tracking (PedidoEnCurso):** Track ongoing orders in real time.  

### Rider Screens
- **Home (inicioRider):** Rider dashboard with pending deliveries.  
- **Profile (perfilRider):** Manage personal and vehicle information.  
- **Chat:** Real-time communication between riders and users/support using Webhooks.  
- **Vehicle Management (vehiculos):** Register and manage vehicles.  
- **Documents Upload (Docs):** Upload and verify rider documents.  
- **Settings (Ajustes):** Configuration options for riders.  
- **Wallet:** Manage rider balance and transactions.  
- **Verification (verificacionRider):** Identity and vehicle verification.  
- **Rider Onboarding (RiderOnboardingSwiper):** Introductory flow specifically for riders.  

### UI Components
- **Maps (MapaPedido, TrackingMap):** Display order routes and real-time tracking.  
- **Navigation Bars (navbar, navbarRider):** Custom navigation components for users and riders.  
- **Profile Screens (profilescreen):** Detailed view of user or rider profiles.  
- **Info Pages (ayudaPage, privacidadPage, terminosPage):** Help, privacy policy, and terms & conditions.  

---

## Key Features
- Fully adaptive screens for responsive UI across devices.  
- **Geolocation & Maps:** Real-time tracking of orders and delivery routes.  
- **Authentication:** Email, Google, and Apple login options.  
- **Real-time Chat:** Communication between users, riders, and support via Webhooks.  
- **Vehicle & Document Management:** Register, verify, and manage rider information.  
- **Wallet Management:** View balance, add funds, and manage transactions.  
- **Notifications:** Push notifications for updates on services and orders using EAS.  
- **File Uploads:** Upload documents, photos, and other files securely.  

---

## Challenges and Solutions
During development, I faced several challenges:  

1. **Integrating geolocation and real-time tracking:** Ensuring accurate location updates and map rendering on both Android and iOS required optimizing state management and handling permission issues.  
2. **Adaptive UI for multiple screen sizes:** Some components did not scale correctly on smaller devices. Solved by using responsive layouts and dynamic styling.  
3. **Authentication across multiple providers:** Implementing Google, Apple, and email login in a single flow was complex. Used proper libraries and context-based state management to unify authentication logic.  
4. **Real-time chat integration with Webhooks:** Ensuring messages sync correctly between users and riders required careful handling of API calls, state updates, and webhook events.  
5. **Document uploads and validations:** Handling large files and validation errors without crashing the app involved testing multiple edge cases and asynchronous flows.  
6. **Push notifications via EAS:** Ensuring notifications were delivered correctly for order updates and chat required proper integration and testing across platforms.  

Thanks to **Fernando (backend developer)** for providing support with API endpoints, debugging, Webhooks, and backend integration, which made development much smoother.  

---

## Author
[Jolmo]  
[Portfolio Link]  
[GitHub Link]  

---

This README highlights all the screens, components, key features, and challenges of Pickmu's mobile frontend, including real-time updates via Webhooks and push notifications via EAS, while acknowledging backend collaboration and problem-solving during development.
