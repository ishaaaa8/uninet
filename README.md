
# UniNet

UniNet is a mobile application built with [Flutter](https://flutter.dev/) that aims to enhance campus life by offering a range of convenient services within the university community.

## Features

- **User Authentication**: Users can log in or sign up using their email and password to access the app's features.
- **Shuttle Services**: Discover available shuttle services nearby for easy commuting.
- **Pooling Mates**: Connect with other students for carpooling and sharing rides.
- **PG Mate Finder**: Find compatible roommates within university PG accommodations.
- **Mentorship Program**: Register as a mentor or find a mentor to guide you through your academic journey.

## Installation

Before you can run the UniNet application, you will need to install Flutter and its dependencies. You'll also need to set up Firebase for backend services.

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install)
- [Firebase](https://firebase.google.com/docs/flutter/setup)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/ishaaaa8/uninet.git
```

2. Install the project dependencies:

```bash
flutter pub get
```

3. Connect your Firebase project to the UniNet app:
   - Follow the instructions in the [Firebase documentation](https://firebase.google.com/docs/flutter/setup) to set up a new Firebase project or use an existing one.
   - Replace the `google-services.json` file in the `android/app` directory with the one provided by Firebase.

4. Run the UniNet app:

```bash
flutter run
```

The UniNet application should now be running on your local machine.

## Usage

To log in to the UniNet application, you will need to sign up for an account. Click the "Sign Up" button on the login page and follow the prompts to create a new account.

Once you are logged in, you can explore the various features of the app, such as shuttle services, pooling mates, PG mate finder, and mentorship program.

## Contributing

We welcome contributions to the UniNet project! If you have ideas for new features or improvements, please feel free to open an issue or submit a pull request.

Before contributing, please make sure to:

- Check the [issue tracker](https://github.com/ishaaaa8/uninet/issues) for existing discussions or bug reports.
- Follow the project's coding conventions and guidelines.
- Write tests to cover your changes, if applicable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

