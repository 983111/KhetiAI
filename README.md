hetiAI (farms)
KhetiAI is a comprehensive Flutter-based mobile application designed to empower farmers and agricultural stakeholders. The app integrates modern technologies like Supabase for backend services, real-time weather tracking, marketplace capabilities, and AI-driven plant disease detection.

Features
Secure Authentication: Robust user onboarding with Sign-Up, Login, and OTP verification powered by Supabase.

Plant Disease Detection: AI-integrated service to help identify and manage crop health.

Agricultural Marketplace: A platform for users to browse, post, and manage agricultural products and services.

Budget & Finance Management: Tools for farmers to track transactions and manage agricultural budgets.

Weather & Location Services: Real-time weather updates and geolocation features to provide localized farming advice.

AI Chatbot: An interactive chatbot to assist users with agricultural queries.

Tech Stack
Frontend: Flutter (v3.8.1 SDK or higher)

Backend: Supabase (Database & Authentication)

Key Libraries:

geolocator & geocoding: For location-based services.

image_picker: For capturing/uploading plant photos for disease analysis.

intl: For localized date and currency formatting.

url_launcher: For external links and communication.

Getting Started
Prerequisites
Flutter SDK installed on your machine.

A Supabase project created for backend services.

Installation
Clone the repository:

Bash
git clone [repository-url]
Install dependencies:

Bash
flutter pub get
Configure Supabase:
Ensure your Supabase credentials (URL and Anon Key) are correctly set up in lib/services/SupabaseConfig.dart.

Run the application:

Bash
flutter run
Project Structure
The project follows a modular structure for scalability:

lib/screens/: Contains all UI views (Home, Marketplace, Weather, etc.).

lib/services/: Handles logic for Auth, Budgeting, and API integrations.

lib/widgets/: Reusable UI components like the AddTransactionSheet.

assets/: Contains application imagery (login/OTP illustrations).

License
This project is private and not intended for publication to pub.dev
