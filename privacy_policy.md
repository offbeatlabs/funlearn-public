# Funlearn privacy policy

Effective date: 9 September 2026. Covers Funlearn 2.0.0 and the existing account-management service.

Funlearn is provided by Offbeat Labs. Contact: ofbtlabs@gmail.com.

## Reading on your device

The included stories, dictionary, reading settings, favorites, reading positions, completed stories and saved words work locally. Saved reader libraries and nicknames from earlier versions remain on the device. Reading does not require an account, birth date, email address or real name. Funlearn does not upload reading histories or saved words to a reading-profile server. It has no advertising or reading-analytics SDK.

Android may back up the local library database using your device backup settings. Funlearn excludes authentication and purchase SDK preferences from its own backup rules. Library import and export controls are no longer offered in the app. If you exported a file using an earlier version, protect or delete it separately.

The device also stores the current daily reading/audio allowance and selected story identifiers. Clearing reading progress, changing profiles or importing a backup does not reset that allowance. These local usage records are replaced when a new daily allowance starts and are not uploaded to RevenueCat.

Daily story reminders are optional. Funlearn requests notification permission only when you enable a reminder, stores your selected time locally and schedules it on the device. No reminder schedule is uploaded to a server. You can change the time or turn reminders off in Settings.

## Story updates and offline voices

When online, the app checks Offbeat Labs' existing story service hosted using Amazon Web Services. Requests expose ordinary network information such as IP address, request path and timing to that infrastructure. The app does not attach your local reader profile, favorites or saved words to those requests.

Narration and word pronunciation use Android voices that report that they can work without a network connection. Story text is sent to the installed text-to-speech engine on the device. Voice installation and the engine's own settings and privacy practices are controlled by its provider. Funlearn does not send story text to Gemini or another cloud narration API.

## Optional purchases

The Pro area uses Google Play Billing and RevenueCat to process and restore Funlearn Pro. RevenueCat receives an app-user identifier, purchase and entitlement records, and device/app/network information needed to operate its service. We use purchase information to provide Pro and understand purchases, subscriptions and revenue. Funlearn does not provide RevenueCat with reader nicknames, reading activity, saved words, email addresses or advertising identifiers. Google Play handles payment details; Funlearn does not receive card numbers.

The purchase SDK starts when the Pro area is opened and on subsequent launches of that installation so that entitlements can be restored and maintained. Review [RevenueCat's privacy information](https://www.revenuecat.com/privacy/) and [Google's privacy policy](https://policies.google.com/privacy).

## Existing accounts and deletion

Reading in this version does not require registration. A person with an existing Funlearn account can use the account-deletion screen. This screen uses Google Firebase Authentication for email/password or Google authentication. Firebase processes account identifiers, credentials or authentication tokens, and associated authentication/security information. Google sign-in may provide the account's basic profile. Funlearn uses this authentication to identify and delete the existing account, and signs out of the deletion session when the screen is closed. Firebase's Google credential API can briefly create a record when no account exists; the app immediately requests deletion of such a record.

Delete an existing account from Settings > Privacy & data > Delete an existing account, or follow the [external deletion-request instructions](https://github.com/offbeatlabs/funlearn-public/blob/main/account_deletion.md). You can also email ofbtlabs@gmail.com from the associated email address. Never email a password. Authentication-account deletion removes the Firebase account profile. Request assistance for related support or RevenueCat purchase/account records. We retain those records while needed to provide or restore access and process support requests; after a verified deletion request, records are removed except where retention is required for accounting, fraud prevention or legal obligations. We will explain any applicable retention when handling the request. Account deletion does not automatically refund purchases or cancel Google Play subscriptions; subscriptions can be cancelled separately in Google Play.

To erase reading activity and saved reader libraries on this device, use Settings > Privacy & data > Clear reading data. You can also remove individual saved words. Clear previously exported files and manage Android backups separately.

## Children and contact

The core reading experience is designed to work without collecting a child's contact information. Purchase access and Privacy & data are in Settings. Parents can request assistance or correction/deletion of information by contacting ofbtlabs@gmail.com.

We update this policy when app behavior or data practices change and show the effective date above.
