# Folio - Deliverable 4

**Eduvos · Midrand Campus · ITMDA3-34 · Group 9**

Folio is a student workspace for financial documents and study material. It brings document storage, source-linked AI assistance, revision tools and deadline planning into one application.

## Submission files

| Item | Open or download |
| --- | --- |
| Complete source code | [Folio-Source-Code.zip](Folio-Source-Code.zip) |
| Native Android demonstration | [Folio-Demonstration.mp4](Folio-Demonstration.mp4) |
| Slower Android user-story recording | [Folio-Android-Story.mp4](Folio-Android-Story.mp4) |
| Web application recording | [Folio-Web-Application.mp4](Folio-Web-Application.mp4) |
| Admin recording (fictional data) | [Folio-Admin-Demo.mp4](Folio-Admin-Demo.mp4) |
| PDF for myLMS | [Folio-Deliverable-4-Submission.pdf](Folio-Deliverable-4-Submission.pdf) |
| User manual | [Folio-User-Manual.pdf](Folio-User-Manual.pdf) |
| Application screenshots | [Browse screenshots](screenshots/) |

The **submission PDF** is the single file to upload to myLMS. It uses portrait pages and the Eduvos assessment format, with repository links and application screenshots. The **user manual** is a separate guide to the application's screens and workflows.

## Application features

- **Document vault:** organise financial paperwork and study material, upload files and review processing status.
- **Source reader:** read extracted pages, search their text and inspect document evidence.
- **AI assistance:** ask questions about selected documents and open supporting citations.
- **Practice quizzes:** answer document-based questions and review explanations with source references.
- **Study workspace:** organise courses, save notes and revisit revision cards.
- **Deadline planning:** review tasks and calendar dates associated with documents.
- **Account controls:** inspect security settings and local activity.
- **Administration:** review account, session and recorded AI-activity metadata. The admin page does not expose documents, prompts or answers.

## Demonstration recordings

All four MP4 recordings are silent so they can be edited and voiced over.

- **Folio-Demonstration.mp4** is the 1 minute 40 second native Flutter walkthrough captured in the Android emulator on 20 October 2026. It covers the document vault, source reader, study spaces, AI answer, quiz, deadlines and security.
- **Folio-Android-Story.mp4** is a slower 2 minute 19 second student study story recorded in the Android emulator on 21 October. It follows a sample lecture through its source page, study course, answer citation and quiz feedback.
- **Folio-Web-Application.mp4** is a 2 minute 15 second web walkthrough of the document reader, course setup, source-linked answer and quiz.
- **Folio-Admin-Demo.mp4** is a short admin walkthrough of the user, session and AI-usage views using fictional example accounts.

The Android story uses a local mock API; its sample AI answer and quiz are simulated. The web and admin recordings also use fictional local fixtures. Their account totals, session history, AI-usage rows and model label are sample data, not live service analytics. No production account activity or documents are shown in those recordings.

## Screenshots

| Folder | Contents | Capture date |
| --- | --- | --- |
| [Demonstration](screenshots/demonstration/) | Native Android emulator captures and desktop/phone admin page screenshots | 20-21 October 2026 |
| [User manual - desktop](screenshots/user-manual/desktop/) | Desktop web screens used for the earlier manual | 13 October 2026 |
| [User manual - Android](screenshots/user-manual/android/) | Native Android emulator screens | 13 October 2026 |
| [User manual - phone](screenshots/user-manual/phone/) | Web application at phone screen size | 13 October 2026 |

The admin screenshots are 20-admin-desktop.png and 21-admin-phone.png. They show only fictional account metadata and aggregates; no documents are included.

## Source code

The source ZIP contains the Next.js web application and API, Flutter mobile application, local mobile plugins, database migrations and development documentation. Extract it and open its Folio/README.md for setup instructions.

The archive is a source snapshot prepared on **19 October 2026**. Credentials, installed dependencies, generated builds and private capture tools are excluded.

## Demonstration data

The original native recording and its screenshots use a temporary demonstration account and synthetic lecture and fee documents. AI answers and quiz questions in that recording were requested through the running native app and API. The course, note and revision card were prepared for the walkthrough.

The new Android story uses a local mock API and synthetic lecture. The web and admin recordings and the new admin screenshots use a fictional local API fixture. They do not write to Folio's production database. A temporary debug capture build enabled Android screen recording; the submitted source retains its screen protection. Email delivery, sign-in/MFA delivery, physical-device behavior and camera scanning are outside the recordings' scope.

The earlier user manual remains included with its original, separately dated screenshots.

## Group members

| Name | Student number |
| --- | --- |
| Anotida Dzinotyiwei | EDUV4932003 |
| Nsuku Maswanganyi | EDUV4821574 |
| Londiwe Mahlangu | 36G7W75P7 |
| Surely Modupi | EDUV4918966 |