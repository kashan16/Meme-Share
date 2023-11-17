# Memeshare App

Memeshare is a Kotlin-based Android application that allows users to browse and share memes from Reddit. The app utilizes the Glide library to efficiently render and display images and integrates with the Reddit API to fetch the latest memes.

## Features

- **Meme Feed:** Browse through a curated collection of memes from Reddit.
- **Share Functionality:** Share your favorite memes with friends through various apps on your device.

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/kashan16/Meme-Share.git
```

2. Open the project in Android Studio.

3. Obtain Reddit API Credentials:
    - Visit the [Reddit Developer Portal](https://www.reddit.com/prefs/apps).
    - Create a new application to get the `CLIENT_ID` and `CLIENT_SECRET`.
    - Update the `gradle.properties` file with your credentials:

    ```properties
    REDDIT_CLIENT_ID=your_client_id
    REDDIT_CLIENT_SECRET=your_client_secret
    ```

4. Build and run the app on your Android device or emulator.

## Usage

1. Open the Memeshare app on your device.
2. Explore the meme feed by scrolling through the images.
3. Tap on a meme to view it in full screen.
4. Use the share button to share the meme through your preferred messaging or social media apps.

## Libraries Used

- **Glide:** The app uses the Glide library to efficiently load and display images.
- **Reddit API:** Memeshare integrates with the Reddit API to fetch the latest memes.

## Contributing

Contributions are welcome! If you would like to contribute to the development of Memeshare, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.

## Issues

If you encounter any issues or have suggestions for improvement, please create a new issue on the [GitHub repository](https://github.com/kashan16/memeshare/issues).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Thank you to the Reddit community for providing a vast collection of memes.
- The Memeshare app is built with love by [Mohd Kashan Yunus].
