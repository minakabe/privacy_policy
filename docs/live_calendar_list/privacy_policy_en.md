# Privacy Policy

Last updated: October 29, 2026

"Live Calendar List" (the "App") respects your privacy and handles your information with care. This Privacy Policy explains how the App handles information.

The App is an unofficial app provided by an individual developer. It is not provided, endorsed, or sponsored by YouTube or Google LLC. "YouTube" is a trademark of Google LLC.

## 1. Information the App Handles

### 1.1 Google Account Information

The App uses Google Sign-In to retrieve your YouTube subscriptions. When you sign in, the App receives the following information from Google:

* Your Google account identifier (user ID)
* Your email address, display name, and profile picture
* An access token for reading your YouTube data, and an ID token for verifying your identity

Your email address, display name, and profile picture are used only to show the signed-in account on the settings screen.

To use the App's server features (Firebase), the App also signs you in to "Firebase Authentication", provided by Google LLC. When this happens, your Google account identifier, email address, display name, and profile picture are registered in Firebase Authentication. This information is used only for authentication; the developer does not use it for advertising, analytics, or any other purpose.

### 1.2 YouTube Data (YouTube API Services)

The App uses YouTube API Services. Only when you grant permission, the App uses a read-only scope for your YouTube account (youtube.readonly) to retrieve the following:

* The list of channels you are subscribed to (channel ID, channel name, icon image, etc.)

The App also displays scheduled live streams for those channels (video ID, title, thumbnail image, scheduled start time, and other information publicly available on YouTube).

The App requests read-only access only. It never writes to your YouTube account: it does not upload or delete videos, post comments, or change your subscriptions.

### 1.3 Information Stored on Your Device

The App stores the following information on your device:

* Retrieved subscription information, and the channels you choose to display and receive notifications for
* Scheduled live stream information (a cache for display)
* Notification settings (such as notification timing)
* Watch history (the video ID, title, thumbnail image, scheduled start time, and the date and time you selected "Watch on YouTube" in the App). Entries older than three months are deleted automatically.
* App settings, such as the date and time you extended the watch history viewing period by watching an ad

This information is used only to provide the App's features and, except as described in 1.4, is not sent to the developer's servers.

### 1.4 Information Sent to and Stored on the Server

To detect scheduled live streams, the App sends the channel IDs of the YouTube channels you choose to display to a server used by the developer (Firebase / Google Cloud Platform, provided by Google LLC), where they are stored. To prevent misuse, the App also sends your Google ID token, which the server verifies.

The server also uses YouTube API Services to retrieve publicly available information about live streams on YouTube (video ID, title, thumbnail image, scheduled start time, etc.) and stores it as a cache.

* The server stores only channel IDs and publicly available live stream information from YouTube.
* This information is not stored in a way that links it to your Google account identifier, email address, or any other information that identifies you. The ID token is used only for verification and is not stored.
* The cached live stream information is refreshed regularly to match YouTube, and entries for streams that have ended are deleted.

### 1.5 Watch History Backup

To help you move to a new device, the App lets you export and import your watch history as a JSON file.

* An exported file is saved only to the location you choose in your device's save dialog (such as device storage or a cloud storage service you choose).
* Importing reads only the file you choose in your device's file picker.
* Your watch history is never sent to the developer's servers.

### 1.6 Notifications

The App uses your device's notification feature to notify you before live streams start. Notifications are scheduled on your device, and no notification-related information is sent to the server.

## 2. How We Use Information

Information is used only for the following purposes:

* Signing in with your Google account and authenticating with the App's server features
* Retrieving and displaying your YouTube subscriptions
* Retrieving and displaying scheduled live streams in a list and a calendar
* Notifying you before live streams start
* Recording, displaying, and backing up your watch history
* Fixing bugs, and providing and improving the App's features

## 3. Handling of Information Received from Google APIs

The App's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

* YouTube data is used only to provide the App's features (displaying your subscriptions and scheduled live streams, and sending notifications).
* YouTube data is never used for advertising or user profiling, and is never sold or provided to third parties.
* The developer never views your YouTube data.

By using the App, you agree to be bound by the [YouTube Terms of Service](https://www.youtube.com/t/terms). For information on how Google handles data in YouTube API Services, please see the [Google Privacy Policy](https://policies.google.com/privacy).

## 4. Advertising

The App uses Google AdMob, an advertising service provided by Google LLC, to display banner ads and rewarded ads (ads that extend the watch history viewing period when watched).

AdMob may collect and use information such as advertising identifiers, device information, IP addresses, and app usage information for purposes including delivering ads and measuring ad performance. Depending on your consent status and region, personalized or non-personalized ads may be displayed.

The App never provides YouTube data or Google account information to AdMob. You can reset or delete your advertising ID in your device settings (under advertising or privacy settings). For more information about how Google handles information, please see [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/ads).

## 5. Sharing with Third Parties

The App does not provide or sell your information to third parties, except where required by law.

To provide its features, the App uses the following external services. The handling of information by these services is governed by their respective privacy policies.

* Google Sign-In (Google LLC)
* YouTube API Services (Google LLC)
* Firebase Authentication, Cloud Firestore, and Cloud Functions for Firebase (Google LLC)
* Google AdMob (Google LLC)

## 6. Retention and Deletion

* **Information on your device**: deleted when you uninstall the App. You can change which channels are displayed at any time in the App, and watch history entries older than three months are deleted automatically.
* **Connection to your Google account**: you can sign out from "Log out" on the settings screen. You can also revoke the App's access at any time from the [third-party apps & services page of your Google Account](https://myaccount.google.com/connections). After access is revoked, the App can no longer retrieve your YouTube data.
* **Information registered in Firebase Authentication**: contact us at the address in Section 11 and we will delete it.
* **Channel IDs and live stream information on the server**: these are not linked to any specific user, so they cannot be deleted as an individual user's information. Information for channels that no user displays any longer is updated and deleted over time.

## 7. Security

Communication between the App and the server is encrypted (HTTPS). The server database is configured so that it cannot be written to from users' apps; it is written only by processes running on the server.

## 8. Children

The App is not directed to children under the age of 13.

## 9. Changes to This Privacy Policy

This Privacy Policy may be updated in response to changes in laws or in the App's features. If significant changes are made, we will announce them in the App or on the page where this Privacy Policy is published.

## 10. Provider

The App is provided by an individual developer, "Minakabe".

## 11. Contact

For questions about this Privacy Policy or the App, or to request deletion of your information, please contact:

Contact: info@minakabe-growth.com
