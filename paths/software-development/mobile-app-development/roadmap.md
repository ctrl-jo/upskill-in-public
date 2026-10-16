# Mobile app development roadmap

## Before you start

Mobile development means making programs for phones and tablets. A platform is the device system your app runs on. This route begins with one language and one platform, then grows toward a developer role. There is no fixed deadline and no need to learn every platform.

1. Read the platform table below and open the matching official guide in [resources](resources.md). Check its computer and installation requirements before downloading tools. iOS development with Apple's Xcode tools requires a supported Mac.
2. For your first 20 minutes, choose one route, read its introductory lesson, and write a study-checklist app idea with three things the app should do. No installation or store account is needed for this first task.
3. Set a manageable weekly time using the [study plan](../../../start-here/study-plan-template.md). Save your work in [my-learning](../../../my-learning/README.md). Move on when you can show the checkpoint, or try the checkpoint first if you already know the topic.

## Stage 1: Choose a platform and learn its language

| Route | Language and screen tools | Useful starting choice |
| --- | --- | --- |
| Android | Kotlin and Jetpack Compose | Android apps; start here if you have no preference and a compatible computer |
| iOS | Swift and SwiftUI | Apple apps with access to a supported Mac |
| Cross-platform | Dart and Flutter | One shared codebase for multiple platforms; native build requirements still apply |
| Cross-platform after web basics | JavaScript and React Native | Learners already comfortable with JavaScript and React |

1. Choose one row. Native development focuses on one platform; cross-platform development shares some code across platforms but still needs platform-specific testing and setup.
2. Follow the official beginner guide to practice variables (named values), conditions (choices), loops (repeated actions), functions (reusable instructions), and lists.
3. Write a small function that marks a study task complete. Try an empty list and a list with several tasks.
4. Learn Git (file-change tracking) through [GitHub Hello World](https://docs.github.com/en/get-started/using-github/hello-world). Save one small change with an explanation.

Checkpoint: One chosen route and a small piece of code you can explain, including its empty-list behavior.

## Stage 2: Screens and interaction

1. Follow the selected guide's setup instructions and run its first app. An emulator or simulator is a program that imitates a device; a compatible physical device is another option.
2. Build a screen with a study-task list, an input field, and a button. Learn state: information the screen remembers and updates.
3. Add a second screen for task details. Practice navigation (moving between screens) and returning without losing the selected task.
4. Give controls clear labels, try larger text sizes, and check screen-reader support in the platform guide. Accessibility means making the app usable by people with different needs.

Checkpoint: Two connected screens with usable controls and a helpful message for empty input.

## Stage 3: Data and reliability

1. Save tasks on the device using your selected platform's local-storage lesson. Close and reopen the app to confirm the tasks remain.
2. Learn HTTP (web request-and-response rules), JSON (structured text data), and APIs (defined ways for programs to exchange data). Follow an official lesson to display public example data from a network request.
3. Add loading, empty, offline, and failure messages. Request device permissions only for a feature that needs them, and explain the reason to the user.
4. Test a normal task, blank text, repeated taps, lost connection, and reopening the app. Record expected and actual results; add an automated check for a small function when ready.

Checkpoint: A checklist that retains local data and handles a lost connection without losing the user's work.

## Stage 4: Build, share, and continue

1. Build your own study-checklist app using the chosen route. Explain setup, storage, permission choices, and checks using the [mini-project template](../../../templates/mini-project.md).
2. Share your own code, screenshots, or a short demonstration when ready. App-store publication is optional and can involve fees and review requirements; it is not needed to finish this roadmap.
3. Choose a next role-focused topic: Android app structure and device behavior, iOS app structure and device integration, or cross-platform code sharing and testing on each platform. Continue with the official guide for your chosen route.

Checkpoint: A working app demonstration and notes another learner can follow. Deeper role-focused projects and publishing walkthroughs are Planned — Coming soon; the beginner route is Available.
