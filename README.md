<img width="1024" height="572" alt="WhatsApp Image 2026-10-13 at 4 28 35 PM" src="https://github.com/user-attachments/assets/34ca9b30-82d5-4171-bca7-73e53d7e073a" />

# ReuniteQR – A Simple QR for Safer Reunions

## 1. Project Overview

**ReuniteQR** is a web-based lost-and-found and family reunification application designed to help individuals reconnect with their family members during crowded events, festivals, public gatherings, and other situations where people may become separated.

The application uses QR-code-based identification to provide access to relevant profile information and contact details. It also offers location assistance and lost-and-found management features to support safer and more efficient reunification.

**Live Application:** [https://reuniteqr-web.onrender.com/qr](https://reuniteqr-web.onrender.com/qr)

## 2. Objectives

- Simplify the process of reconnecting separated family members.
- Enable QR-based access to relevant user profile information.
- Facilitate communication through accessible contact details.
- Provide map-based location assistance and meeting-point coordination.
- Support the management of lost-and-found records through an administrative interface.
- Promote a convenient and user-friendly digital reunification solution.

## 3. Key Features

- **QR Code Generation:** Generate a personal QR code associated with a user's profile.
- **QR Code Scanning:** Scan QR codes to access the corresponding profile and facilitate contact.
- **Secure User Authentication:** Support Google sign-in through Firebase Authentication.
- **User Profile Management:** Maintain relevant personal information and emergency contact details.
- **Location Assistance:** Use interactive maps to view locations and identify potential meeting points.
- **Lost-and-Found Management:** Support lost and found information management.
- **Administrative Portal:** Provide administrative pages for managing records, users, and application settings.
- **Responsive Web Interface:** Support access through desktop and mobile web browsers.

## 4. Technology Stack

| Technology              | Purpose                                |
| ----------------------- | -------------------------------------- |
| Next.js                 | Web application framework              |
| React                   | Component-based user interface         |
| TypeScript              | Type-safe application development      |
| Tailwind CSS            | Responsive interface styling           |
| Firebase Authentication | Google authentication                  |
| Cloud Firestore         | Data storage and management            |
| HTML5 QR Code           | QR code scanning                       |
| QR Code Library         | QR code generation                     |
| Leaflet                 | Interactive map integration            |
| OpenStreetMap           | Map tiles and geographic visualization |

## 5. Project Structure

```text
ReuniteQR/
├── public/                      # Static assets
├── src/
│   ├── app/
│   │   ├── (admin)/             # Administrative pages
│   │   └── (user)/              # User-facing pages
│   ├── components/              # Reusable UI components
│   ├── context/                 # Application context
│   ├── lib/
│   │   └── firebase/            # Firebase configuration and services
│   └── types/                   # TypeScript type definitions
├── .gitignore                   # Git exclusion rules
├── firestore.rules              # Firestore security rules
├── next.config.ts               # Next.js configuration
├── package.json                 # Dependencies and scripts
├── package-lock.json            # Dependency lockfile
├── tsconfig.json                # TypeScript configuration
└── README.md                    # Project documentation
```
<img width="1024" height="572" alt="WhatsApp Image 2026-10-13 at 4 31 06 PM" src="https://github.com/user-attachments/assets/5d4d9a3b-4e21-4d47-a523-8ba7d8fb6c46" />


## 6. Installation and Setup

### Prerequisites

- Node.js
- npm
- Git
- A Firebase project with Authentication and Cloud Firestore configured

### Step 1: Clone the Repository

```bash
git clone https://github.com/aryakalbhor9983/ReuniteQR.git
cd ReuniteQR
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Configure Firebase

Create a `.env.local` file in the project root and configure the Firebase environment variables required by the application.

The following are examples of common variable names. Use the exact names referenced in `src/lib/firebase/config.ts`.

```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

Enable Google sign-in in Firebase Authentication and configure the authorized domains. Ensure that Firestore security rules are configured appropriately before deployment.

### Step 4: Start the Development Server

```bash
npm run dev
```

### Step 5: Build and Run for Production

```bash
npm run build
npm run start
```

The production server runs according to the application's Next.js configuration.

## 7. Security and Privacy

- Exclude `.env.local` and private credentials from version control.
- Configure Firestore security rules to restrict unauthorized access.
- Limit access to personal and emergency contact information to appropriate use cases.
- Protect administrative functionality through suitable authentication and authorization.
- Review QR-linked profile access to prevent unintended disclosure of personal information.
- Test authentication, database permissions, and profile access before deployment.

## 8. Future Enhancements

- Multilingual support for improved accessibility.
- Emergency notification functionality.
- Enhanced privacy controls for QR-linked profiles.
- Improved lost-and-found matching and record management.
- Additional location-sharing and reunification assistance features.

## 9. Conclusion

ReuniteQR aims to make family reunification and lost-and-found coordination more accessible through QR-based identification, digital profiles, and location assistance. By combining modern web technologies with authentication and database services, the application provides a foundation for a convenient and user-friendly reunification platform.

## 10. Project Information

**Project Name:** ReuniteQR

**Category:** Web Application

**Domain:** Web Development, QR-Based Identification, and Family Reunification

**Live Demo:** [https://reuniteqr-web.onrender.com/qr](https://reuniteqr-web.onrender.com/qr)
  Github link:	https://github.com/aryakalbhor9983-lang/ReuniteQR


