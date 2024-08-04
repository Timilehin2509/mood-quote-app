# Quotes App Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Project Overview
The Quotes App is an Android application that provides users with a collection of inspirational quotes. Users can browse, search, and add their favorite quotes. This project is developed by a sub-group within our CS group as part of our course requirements.

## Features
- Browse a collection of quotes
- Search for quotes by author or keyword
- Add new quotes
- User authentication and profile management
- Responsive design for different screen sizes

## Technologies Used
- Language: Kotlin
- IDE: Android Studio
- Database: Firebase Firestore
- Authentication: Firebase Authentication
- Version Control: Git

## Installation

### Prerequisites
- Android Studio (latest version)
- A Firebase project with Firestore and Authentication set up

### Steps
1. **Clone the repository:**
    #### Using GitHub Desktop:
    - Open GitHub Desktop.
    - Click on `File > Clone Repository`.
    - In the `URL` tab, paste the repository URL: `https://github.com/YourUsername/quotes-app.git`.
    - Click `Clone`.

    #### Using the web UI:
    - Go to the repository on GitHub: `https://github.com/YourUsername/quotes-app`.
    - Click the `Code` button and select `Download ZIP`.
    - Extract the ZIP file to your desired location.

    #### Using Git commands:
    ```sh
    git clone https://github.com/YourUsername/quotes-app.git
    ```

2. **Open the project in Android Studio:**
    - Open Android Studio.
    - Click on `File > Open`.
    - Navigate to the cloned repository and select the `quotes-app` folder.
    - Click `OK` to open the project.

3. **Set up Firebase:**
    - Go to the Firebase Console and create a new project (if you don't have one).
    - Add an Android app to your Firebase project and follow the instructions to download the `google-services.json` file.
    - Place the `google-services.json` file in the `app` directory of your Android project.

4. **Configure the project:**
    - Open `build.gradle (Project: quotes-app)` and ensure you have the following classpath in the `dependencies` section:
      ```gradle
      classpath 'com.google.gms:google-services:4.3.10'
      ```
    - Open `build.gradle (Module: app)` and add the following at the bottom:
      ```gradle
      apply plugin: 'com.google.gms.google-services'
      ```

5. **Sync the project with Gradle files:**
    - Click on `Sync Now` in the bar that appears or go to `File > Sync Project with Gradle Files`.

6. **Run the application:**
    - Connect an Android device or start an emulator.
    - Click on `Run > Run 'app'` or press `Shift + F10`.

## Usage
- **Browsing Quotes:** Open the app to see a list of available quotes.
- **Searching Quotes:** Use the search bar to find quotes by author or keyword.
- **Adding Quotes:** Navigate to the add quotes section, enter the details, and save.

### Accessing the Repository in Android Studio
1. **Clone the repository:**
    #### Using GitHub Desktop:
    - Open GitHub Desktop.
    - Click on `File > Clone Repository`.
    - In the `URL` tab, paste the repository URL: `https://github.com/YourUsername/quotes-app.git`.
    - Click `Clone`.

    #### Using the web UI:
    - Go to the repository on GitHub: `https://github.com/YourUsername/quotes-app`.
    - Click the `Code` button and select `Download ZIP`.
    - Extract the ZIP file to your desired location.

    #### Using Git commands:
    ```sh
    git clone https://github.com/YourUsername/quotes-app.git
    ```

2. **Open the project in Android Studio:**
    - Open Android Studio.
    - Click on `File > Open`.
    - Select the `quotes-app` folder.
    - Click `OK` to open the project.

## Contributing
We welcome contributions! Here are the steps to contribute:
1. **Fork the repository:**
    Click the "Fork" button at the top-right corner of the repo page.

2. **Clone your fork:**
    #### Using GitHub Desktop:
    - Open GitHub Desktop.
    - Click on `File > Clone Repository`.
    - In the `URL` tab, paste the URL of your fork: `https://github.com/YourUsername/quotes-app.git`.
    - Click `Clone`.

    #### Using the web UI:
    - Go to your fork on GitHub.
    - Click the `Code` button and select `Download ZIP`.
    - Extract the ZIP file to your desired location.

    #### Using Git commands:
    ```sh
    git clone https://github.com/YourUsername/quotes-app.git
    ```

3. **Create a new branch:**
    ```sh
    git checkout -b feature-name
    ```

4. **Make your changes and commit them:**
    ```sh
    git add .
    git commit -m "Description of your changes"
    ```

5. **Push to your fork:**
    ```sh
    git push origin feature-name
    ```

6. **Create a pull request:**
    Go to the original repository on GitHub and create a pull request from your fork.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please reach out to:
- **Name:** Your Name
- **Email:** yourname@example.com
- **GitHub:** [YourUsername](https://github.com/YourUsername)
