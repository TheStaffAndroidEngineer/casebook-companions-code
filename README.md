# Mobile System Design Casebook — companion code

First-edition source code for *The Staff Android Engineer: Designing, Diagnosing, and Evolving Android Systems* by Rajesh Pattanaik.

The projects below retain their frozen `first-edition-2026.10` tags. Download the [compact source ZIP (packaging revision 2)](https://github.com/TheStaffAndroidEngineer/book-companions/releases/download/first-edition-2026.10-r2/the-staff-android-engineer-first-edition-2026.10-r2-source.zip), which preserves the `code/projects/` layout required by shared investigation tools. Extract it alongside the paid companion guide.

Before opening or building an Android project from this compact download, run `python3 code/setup.py --project commerce-app` from the extracted package folder, replacing `commerce-app` with its project name. Use `--list` to list projects or `--all` to prepare them all. Python 3.9 or newer is required; use `python` if that is your Python 3 command. Setup restores exact original images and fonts offline. The download stores them once; preparing projects increases disk use. Individually cloned repositories already include their assets and need no preparation step.

Revision 2 removes author-only scripts and fetches the pinned Chapter 24 bundletool on demand with SHA-256 verification. Application source, image quality, fonts and chapter checkpoints are unchanged. `code/PACKAGE.json` documents distribution changes relative to the original source archive.

Original companion code is MIT licensed. Required third-party notices and assets retain their own terms. Book chapters, exercises, written solutions and detailed reader guidance are supplied with the purchased book.

Use JDK27 and the pinned Gradle wrappers. Set `ANDROID_HOME` to the SDK specified by each project. Individual READMEs describe build/service entry points. For root JVM labs, run `./gradlew test` inside the bundle’s `code/` directory.

| Chapter | Code repository | First-edition version |
| --- | --- | --- |
| 33 | [reservation-payments](https://github.com/TheStaffAndroidEngineer/reservation-payments-code) | [`2cdaf42c8a`](https://github.com/TheStaffAndroidEngineer/reservation-payments-code/tree/first-edition-2026.10) |
| 34 | [live-location](https://github.com/TheStaffAndroidEngineer/live-location-code) | [`c3066e8e9a`](https://github.com/TheStaffAndroidEngineer/live-location-code/tree/first-edition-2026.10) |
| 35 | [messaging](https://github.com/TheStaffAndroidEngineer/messaging-code) | [`6b1013ce1b`](https://github.com/TheStaffAndroidEngineer/messaging-code/tree/first-edition-2026.10) |
| 36 | [social-feed](https://github.com/TheStaffAndroidEngineer/social-feed-code) | [`83fc116efe`](https://github.com/TheStaffAndroidEngineer/social-feed-code/tree/first-edition-2026.10) |
| 37 | [media-library](https://github.com/TheStaffAndroidEngineer/media-library-code) | [`7bb6e69a0c`](https://github.com/TheStaffAndroidEngineer/media-library-code/tree/first-edition-2026.10) |
| 38 | [realtime-calls](https://github.com/TheStaffAndroidEngineer/realtime-calls-code) | [`c5511196fa`](https://github.com/TheStaffAndroidEngineer/realtime-calls-code/tree/first-edition-2026.10) |
| 39 | [collaborative-notes](https://github.com/TheStaffAndroidEngineer/collaborative-notes-code) | [`6c56c4bf4d`](https://github.com/TheStaffAndroidEngineer/collaborative-notes-code/tree/first-edition-2026.10) |
| 40 | [resumable-transfer](https://github.com/TheStaffAndroidEngineer/resumable-transfer-code) | [`d3a8b75b3c`](https://github.com/TheStaffAndroidEngineer/resumable-transfer-code/tree/first-edition-2026.10) |
| 41 | [backend-scale](https://github.com/TheStaffAndroidEngineer/backend-scale-code) | [`11ed5a19b8`](https://github.com/TheStaffAndroidEngineer/backend-scale-code/tree/first-edition-2026.10) |
| 42 | [connected-device](https://github.com/TheStaffAndroidEngineer/connected-device-code) | [`c309d2d463`](https://github.com/TheStaffAndroidEngineer/connected-device-code/tree/first-edition-2026.10) |
| 43 | [camera-pipeline](https://github.com/TheStaffAndroidEngineer/camera-pipeline-code) | [`01e84c4165`](https://github.com/TheStaffAndroidEngineer/camera-pipeline-code/tree/first-edition-2026.10) |
| 44 | [ai-assistant](https://github.com/TheStaffAndroidEngineer/ai-assistant-code) | [`2cbba07a62`](https://github.com/TheStaffAndroidEngineer/ai-assistant-code/tree/first-edition-2026.10) |

[Machine-readable repository map](catalog.json). Report reproducibility problems or errata through this repository’s Issues; identify the chapter and edition without posting paid chapter text.
