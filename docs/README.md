# CareCompass

A mobile application designed to help caregivers manage doctor's appointments and medications for their loved ones with warmth and compassion.

![CareCompass Logo](path/to/logo.png)

## Overview

CareCompass simplifies the often overwhelming task of coordinating healthcare by offering an intuitive interface, timely reminders, and a supportive experience. It addresses the emotional and logistical challenges faced by caregivers, fostering peace of mind and enabling better care for loved ones.

### Key Features

- **Appointment Tracking**: Easily schedule and manage doctor's appointments
- **Medication Management**: Track medications with customizable reminders
- **Multi-Profile Support**: Manage healthcare for multiple care recipients
- **Offline Functionality**: Full app functionality without internet connection
- **Secure & Private**: HIPAA-compliant with local encryption and optional cloud sync
- **Caregiver-Focused**: Designed with empathy for the caregiving experience

## Screenshots

[Screenshots will be added as development progresses]

## Tech Stack

- **Frontend**: React Native with TypeScript
- **UI Components**: React Native Paper
- **Navigation**: React Navigation
- **State Management**: Redux Toolkit with Redux Persist
- **Backend**: Firebase (Authentication, Firestore, Cloud Messaging)
- **Local Storage**: Firestore with offline persistence, AsyncStorage, react-native-encrypted-storage
- **Device Integration**: Calendar sync, biometric authentication, push notifications

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/carecompass.git

# Navigate to the project directory
cd carecompass

# Install dependencies
npm install

# Start the development server
npm start

# Run on iOS
npm run ios

# Run on Android
npm run android
```

## Project Structure

```
src/
├── components/     # Reusable UI components
├── screens/        # App screens organized by feature
├── navigation/     # Navigation configuration
├── services/       # Firebase and API services
├── hooks/          # Custom React hooks
├── utils/          # Helper functions and utilities
├── store/          # Redux state management
├── types/          # TypeScript type definitions
└── constants/      # App constants and configuration
```

## Features in Detail

### User Authentication
- Sign up with email and password
- Log in with email and password
- Biometric login (fingerprint or face ID)
- Password reset functionality

### Appointment Management
- Add, edit, and delete appointments
- View appointments in calendar or list view
- Set reminders for upcoming appointments
- Track appointment history

### Medication Management
- Add, edit, and delete medications
- Set medication schedules with custom frequencies
- Receive reminders for medication doses
- Track medication adherence history
- Manage medication inventory and refill reminders

### Profile Management
- Create profiles for multiple care recipients
- Switch between profiles easily
- Customize profile details and relationships

### Data Security & Privacy
- Local data encryption
- Optional cloud sync with explicit user consent
- Complete data deletion option
- HIPAA-compliant data handling

## Development Roadmap

- **Phase 1**: Core functionality and authentication
- **Phase 2**: Medication management and multi-profile support
- **Phase 3**: Polish and advanced features

## Contributing

While this is primarily a personal project, contributions, suggestions, and feedback are welcome. Please feel free to open an issue or submit a pull request.

## Privacy Policy

CareCompass takes user privacy seriously. The app:
- Stores sensitive health data locally with encryption
- Only syncs to the cloud with explicit user consent
- Never shares user data with third parties
- Allows complete data deletion

## License

[MIT License](LICENSE)

## Acknowledgments

- This project was inspired by the challenges faced by caregivers everywhere
- Special thanks to the open-source community for the amazing tools that make this project possible

---

*CareCompass: Caring with confidence*
