# Flutter Playground

This repository serves as a playground for learning Flutter development. 

## How to Contribute

1. **Clone the Repository:** Start by cloning this repository to your local machine using the following command:

```swift
git clone https://github.com/Masaya1582/Flutter_Playground.git
```
***
2. **Create a Branch:** Create a new branch from the `develop` branch to work on your changes. Use a descriptive branch name that reflects the feature or fix you are working on.

```swift
git checkout -b feature/add-login-screen
```

***
3. **Work on Your Changes:** Make the necessary modifications and add new files or SwiftUI components to implement the feature or fix.

***
4. **Commit Your Changes:** Once you are done with your changes, commit them with a descriptive commit message:

```dart
git add .
```

```dart
git commit -m "Add login screen UI"
```

***
5. **Push to Your Fork:** Push the changes to your forked repository:

```dart
git push origin feature/add-login-screen
```

***
6. **Create a Pull Request:** Go to the original repository (https://github.com/Masaya1582/Flutter_Playground.git) and create a Pull Request from your branch to the `develop` branch. Be sure to provide a clear description of the changes you made.
***
7. **Review and Merge:** After creating the Pull Request, it will be reviewed by the project maintainers. Once approved, it will be merged into the `develop` branch.
***
8. **Syncing with Upstream:** To keep your fork up to date with the original repository, you can add the original repository as an upstream remote and fetch its changes:

```dart
git remote add upstream https://github.com/Masaya1582/Flutter_Playground.git
```

```dart
git fetch upstream
```

***
Then, to update your fork's `develop` branch with the latest changes:

```dart
git checkout develop
```

```dart
git merge upstream/develop
```

```dart
git push origin develop
```

***
## Code of Conduct

Please note that this project follows a [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful and considerate in all interactions.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code for learning purposes.
