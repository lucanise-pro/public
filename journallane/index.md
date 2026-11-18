---
title: Journal Lane
---

> **Journal Lane has been discontinued.** It was a hobby app, and there will be no further updates or support. Your journal stays yours: the pages are in your own calendar and the photos in your own drive. With Apple Calendar, Journal Lane keeps working on your iPhone as it is. Google connections end on 31 December 2026. The privacy policy, terms of use and license agreement it was offered under are kept below for reference.

Contents: [Privacy Policy](#1-privacy-policy) · [Terms of Use](#2-terms-of-use) · [License Agreement](#3-license-agreement)

---

**Last Updated:** 18 November 2026

---

## 1. Privacy Policy

**Effective:** 18 November 2026

Journal Lane is developed and maintained by a single independent developer, not a company. There is no team and no support desk, and any support, reply or update is best-effort only.

### The short version

Journal Lane has no account with us, no server of ours and no analytics. We never see what you write.

Your entries are saved as all-day events in **your own calendar**, in one calendar of their own named *Journal Lane*, and your photos and files in **your own storage**. You connect one account at a time:

- **Apple:** the *Journal Lane* calendar is in your iCloud (or *On My iPhone* if iCloud for Calendars is off), and files go to your iCloud Drive (or *On My iPhone* if iCloud Drive is off).
- **Google:** the *Journal Lane* calendar is in your Google Calendar, and files go to your Google Drive.

Your other calendars are read only to show your day around each page. Journal Lane never changes them.

When you connect Google, the app talks **directly** from your iPhone to that company's services, on your behalf. Nothing passes through us, because there is nothing of ours to pass through.

### 1. Zero knowledge

We don't know who you are, what you write or which files you add. We run no servers, keep no database of users or content, and have no way to read, recover or delete anything in your accounts.

### 2. What the app uses, and why

| What | Why | Where it goes |
|---|---|---|
| Your calendars (Apple: full calendar access on this iPhone; Google: the permissions you grant when you connect) | To save entries as all-day events, show them back to you and show the rest of your day around them | Only between this iPhone and your own calendar account |
| Photos and files you pick | To attach them to an entry | Your own storage: iCloud Drive or Google Drive. Photos are re-saved as a new JPEG under 1 MB with all location and camera metadata removed |
| Sign-in tokens (Google only) | So the app can keep acting for you without asking you to sign in again | Kept in this iPhone's Keychain only, never sent to us |
| Remembered account and preferences | The account you connected, where your journal calendar is, hidden calendars, last view, reminders setting | This iPhone only |
| A small setup file (`managed-calendars.json`) | Records your *Journal Lane* calendar (its name and id) and the calendars Journal Lane created, so a new device or a reconnected account finds the same journal | Your own storage, in the *Journal Lane* folder, never sent to us |
| Camera (only when you tap Camera) | To take a photo for an entry | Re-saved like any other photo in your own storage. Never saved to your photo library, never sent to us |
| Widget snapshot | So the "Today's page" widget can show today's date, whether you wrote today, and one "On this day" title | A small file in a private space shared by the app and its widget, on this iPhone only |
| Items you share to Journal Lane | So photos, files, links and text sent from other apps appear on today's page | Kept in the same private space on this iPhone only until you next open the app, then placed on today's page and removed |

- Photos are chosen through the system picker, so the app never gets access to your whole photo library. It only receives the photos you select.
- The camera is used only when you tap **Camera** while writing.
- The app never asks for location, contacts, notifications, microphone, Local Network or tracking permission. It never uses the advertising identifier.
- It contains no third-party code: no analytics SDK, no ads and no crash reporter.

### 3. Google user data

This section covers the data Journal Lane receives from Google APIs when you connect a Google account.

#### 3.1 What Journal Lane accesses

- *Your email address and basic profile*, to show which Google account is connected.
- *Read your calendars* (`calendar.readonly`), to show your other calendars' events around each journal page.
- *Edit events* (`calendar.events`), to write, edit and delete your journal pages as all-day events.
- *Manage calendars created by Journal Lane* (`calendar.app.created`), so it can create its own *Journal Lane* calendar, and nothing more.
- *Only the Drive files Journal Lane created* (`drive.file`), to save and show the photos you add. It cannot see the rest of your Drive.

Journal Lane never asks for full control of your calendars: it writes and edits only journal entries in its own *Journal Lane* calendar, and only reads the others.

#### 3.2 How it is used

Google user data is used only on your iPhone, only to provide the features you see: showing your days, writing your journal, and keeping your photos. It is never used for advertising, never used to build profiles, never sold, and never used to develop, improve or train AI or machine-learning models.

#### 3.3 Sharing, transfer and disclosure

**Journal Lane does not share, transfer or disclose Google user data to anyone.**

- It is never sent to us. We run no servers and have no way to receive it.
- It is never sent to third parties: there are no analytics, advertising, crash-reporting or other third-party services or SDKs in the app.
- It travels only between your iPhone and Google's own services, directly, on your behalf.
- The only copies that leave the app are ones you make yourself: a Markdown export or a bound-month PDF, created on your iPhone and handed to you through the iOS share sheet. Where you save or send them is your choice.

#### 3.4 How it is protected

- **In transit:** every connection to Google uses HTTPS (TLS). The app allows no unencrypted connections (Apple's App Transport Security, at its strict default).
- **Sign-in:** Google sign-in uses Google's own page with OAuth 2.0 and PKCE. Journal Lane never sees your Google password.
- **Sign-in tokens** are kept only in the iOS Keychain on this iPhone, readable only after the device has been unlocked once since starting, never synced to your other devices, never restored to another device from a backup, and never sent to us.
- **On the device:** calendar data is kept in the app's memory while you use it. The few things written to storage (preferences, the widget's snapshot of today, items waiting from the share sheet) stay in Journal Lane's private storage on the iPhone, shared only with its own widget and share extension, protected by iOS Data Protection, and are never sent anywhere.
- **Photos** are re-saved without location or camera data before they are uploaded to your Drive.
- **Least access:** Journal Lane requests only the permissions listed above. It cannot read the rest of your Drive, and it changes no calendar other than its own.

#### 3.5 Retention and deletion

- Journal Lane keeps no copy of Google user data on any server.
- On your iPhone, **Disconnect** asks Google to revoke Journal Lane's access and deletes the sign-in tokens. **Forget This Device** (Settings › This device) also erases everything else Journal Lane stored on the iPhone.
- Your journal pages and photos stay in your Google Calendar and Google Drive, under your control, until you delete them there.
- You can remove Journal Lane's access at any time at myaccount.google.com/permissions.

#### 3.6 Limited Use

Journal Lane's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

### 4. Where your journal lives

- **Entries** are ordinary all-day events: the entry title is the event title, and your text is in the event notes. You can read, change or delete them in any calendar app, with or without Journal Lane.
- **Files** are ordinary files named by date, for example `20261018-sunday-walk.jpg`, in a *Journal Lane* folder in your storage.
- If you delete Journal Lane, your entries and files stay where they are.

### 5. Exports and keepsakes

The **Markdown export** and the **bound month (PDF)** are made on this iPhone from your own calendars and storage, and handed to you through the share sheet. Nothing is uploaded by us. Once you save or share them, they are wherever you put them, and their safety and privacy are up to you.

### 6. Calendars you share

If you share your *Journal Lane* calendar with other people, or an employer or school can access your account, they may see your entries. The same is true of anyone who can use your iPhone or see its Lock Screen widget. Choosing and managing who can see your calendars and device is up to you.

### 7. Actions outside Journal Lane

Your calendars and storage can be changed from places we cannot see: other apps, other devices, a provider's website or iOS Settings. Deleting events, removing an account, signing out of iCloud or running out of storage can change or remove your journal. We cannot detect, prevent, undo or recover any of these actions.

### 8. Log out, disconnect, forget this device

- **Log out** removes this iPhone's sign-in tokens. It keeps which account you used and your preferences, so you can continue later.
- **Disconnect** forgets your account on this iPhone. For Google, it also asks Google to revoke Journal Lane's access.
- **Forget this device** (Settings → This device) disconnects your account and erases what Journal Lane stored on this iPhone: tokens, preferences, the widget snapshot and anything waiting in the share inbox.

None of these delete your entries or files.

### 9. Not a backup

Journal Lane is a simple journaling tool, not a backup or secure storage. Sync keeps your devices matching each other, so a deletion travels too. **We are not liable for any data loss, for any reason.** Keep your own copies of anything that matters.

The app, any feature or any provider connection may be changed, discontinued, withdrawn or transferred to another owner at any time, without notice. Because we hold no data, there is nothing for us to hand over: your journal stays in your own calendars and storage.

### 10. No tracking

Journal Lane contains no analytics, advertising, crash reporting or data brokers. Apple may provide us with anonymous, aggregated App Store statistics (such as downloads, and usage if you opted in to share analytics with developers in iOS Settings). We never receive anything that identifies you or your content.

### 11. Check it yourself

Don't take our word for it. Open **Settings → Privacy & Security → App Privacy Report**. The only places Journal Lane contacts are the Google services of the accounts you connected. With only Apple calendars, the app contacts nothing, and it works in Airplane Mode.

### 12. Your rights

We hold no data about you, so there is nothing for us to access, correct, export or delete on your behalf. Your journal is already in your own calendar and storage, where you can read, export or delete it at any time.

### 13. Children

The app is not directed at children and collects no data from anyone.

### 14. Changes

We may update this document. Because we keep no account and no way to contact you, we cannot notify you. The current version is the one published at https://github.com/lucanise-pro/public/blob/main/journallane/index.md. The copy in the app is provided for convenience and may be out of date.

### 15. Contact

If you have a question about this policy, the honest answer is usually: "We don't know, we don't have your data." You can still write via the contact link in the app or on the App Store page.

---

## 2. Terms of Use

**Effective:** 18 November 2026

These Terms of Use say the same thing as the Journal Lane End User License Agreement (EULA), written out plainly. Reading either gives you the complete picture; where they differ, the EULA applies.

Journal Lane is developed and maintained by a single independent developer, not a company. There is no team and no support desk, and any support, reply or update is best-effort only, if at all.

### Critical disclaimers

- Simple journaling tool, NOT secure storage, NOT a backup.
- NO WARRANTY of any kind.
- NO LIABILITY for data loss, for any reason.
- We store NOTHING and cannot recover anything.
- Your journal lives in your own calendars and storage, under those providers' terms.
- The App can change, stop, disappear or change owner at any time, without notice.
- Keep your own copies, elsewhere. Do not use the App as the only home of anything irreplaceable.

### 1. Acceptance

By downloading, opening or using Journal Lane (the "App"), including its widget and share extension, you agree to these Terms of Use, to the EULA and to the Privacy document. If you do not agree, do not use the App.

### 2. What the App does, and what it doesn't

The App writes your journal entries as all-day events in calendars you choose, and your photos and files to your own iCloud Drive or Google Drive. It shows them back to you, together with the rest of your day.

It does **not** keep a copy anywhere else. It is **not** a backup, an archive, a vault or secure storage, and it does not protect your data from loss, change or access by others.

### 3. Data loss

Your entries and files can be lost, deleted, changed, duplicated or corrupted, and we are not responsible for any of it. Possible causes include:

- your own actions or anyone else's;
- a device failure, loss or theft;
- an iOS, App or provider update;
- a provider outage, limit, policy change or account suspension;
- sync conflicts, revoked permissions, a full storage, or deleting the App.

**We cannot see your data and cannot recover anything, ever, for any reason.**

### 4. No warranty

The App is provided "as is" and "as available", without any warranty, express or implied. Nothing is guaranteed to work, to keep working, or to be accurate. That includes:

- connections to Apple or Google;
- the widget and the share extension;
- On this day, Year and Lane;
- the Markdown export and the bound month.

### 5. No liability

To the maximum extent permitted by law, we are not liable for any damage or loss of any kind connected to the App: data, files, photos, memories, time, money, opportunities, or anything else, direct or indirect, even if we were told it could happen. If any liability cannot be excluded, it is limited to what you paid for the App in the previous twelve months (which may be zero).

### 6. Your providers

Apple and Google run the calendars and storage your journal lives in. Their terms, privacy policies, limits and decisions apply. They can change or end their services, or stop the App from connecting, at any time, and the App may stop working as a result. We are not affiliated with, endorsed by or responsible for any of them.

### 7. Journaling only

The App keeps your journal in one calendar, *Journal Lane*, which it creates in your account when there is none. It writes, edits and deletes only journal entries there. Every other calendar is shown read-only. Deletions you confirm are permanent in your account.

### 8. Sharing and other people

Calendars and folders you share, devices others can use, and widgets on your Lock Screen can show your journal to other people. Deciding who can see your calendars, storage and device is your responsibility alone.

### 9. Discontinuation, changes and transfer

At any time, at our sole discretion, without notice and without any obligation or liability to you, we may:

- change, reduce or remove any feature;
- stop support or updates;
- withdraw the App from sale;
- suspend or permanently end the App;
- sell, transfer or assign the App, these terms and its ownership to someone else.

Because we keep no data and no account, there is nothing to hand over, migrate or return. Your journal stays in your own calendars and storage, so keep your own copies and never depend on the App or on us continuing to exist.

### 10. Price

The App may be offered at no charge, for a price, with in-app purchases or with subscriptions, and this can change at any time. Price changes give no right to refunds or credits. Any purchase or subscription is made through Apple, on the terms shown at the moment of purchase; subscriptions renew until cancelled in your Apple Account, and refunds are handled by Apple.

### 11. Your content and acceptable use

You own what you write and add; the App is licensed to you, not sold. Do not use it for unlawful content or to harm anyone, and do not copy, modify or reverse engineer it except where the law allows.

### 12. Not professional advice

The App is a personal journaling tool, not medical, psychological, legal or any other professional advice or care.

### 13. No account; we cannot contact you

We keep no account and no contact details, so we cannot reach you about anything, including changes to these terms or the end of the App.

### 14. Changes to these terms

We may change these terms at any time without notice. The current version is the one published at https://github.com/lucanise-pro/public/blob/main/journallane/index.md. The copy in the App is for convenience and may be out of date. Using the App after a change means you accept it.

### 15. Your responsibility to us

If anyone brings a claim against us because of how you used the App or what you stored with it, you agree to cover us for it.

### 16. If part of these terms does not apply

If any part is found invalid, the rest stays in force. Not enforcing a part is not a waiver. Mandatory consumer rights you have by law are not affected.

### 17. The whole agreement

These Terms of Use, the EULA and the Privacy document are the entire agreement between you and us. Nothing else (marketing, screenshots, App Store text, the website, support replies) creates any obligation, warranty or guarantee.

---

## 3. License Agreement

**Effective:** 18 November 2026

This End User License Agreement ("Agreement") is a legal agreement between you ("you") and **Lucanise** ("we", "us", the "Developer") for the Journal Lane application, its widget, its share extension and all of its features (together, the "App"). By downloading, installing, opening or using the App, you agree to this Agreement. If you do not agree, do not use the App and delete it.

**Journal Lane is developed and maintained by a single independent developer, not a company. There is no team and no support desk, and any support, reply or update is best-effort only, if at all.**

### Critical disclaimers

- Simple journaling tool. **NOT** secure storage, **NOT** a backup and **NOT** an archive.
- **NO WARRANTY** of any kind.
- **NO LIABILITY** for any loss, deletion, corruption, duplication or exposure of your entries, files, photos or calendars, for any reason.
- We store **nothing**. We have no server, no account for you and no copy of anything. **We cannot see, recover, restore or hand over your data, ever.**
- Your entries live in **your own calendars**, and your files in **your own storage** (iCloud Drive or Google Drive). Those providers' terms, limits, outages and changes apply.
- The App, any feature or any provider connection can be **changed, suspended, discontinued, withdrawn, sold or transferred at any time, without notice**.
- **Keep your own copies** of anything that matters. Your exports are the only copy that doesn't depend on the App, on us or on any provider.

### Section A — Journal Lane terms

**A1. What the App is.** Journal Lane is a simple journaling tool. It writes what you type as all-day events in calendars you choose, and the files you add to your own storage. It is **NOT** a secure storage solution and is **NOT** designed to be the primary or sole place for important, sensitive or irreplaceable information. You must always keep your own safe copies of anything important, elsewhere.

**A2. No warranty ("as is").** The App is provided **"AS IS" and "AS AVAILABLE", without warranty of any kind**, express or implied, including merchantability, fitness for a particular purpose, accuracy and non-infringement. We do not warrant or guarantee that the App, or any feature, will:

- be error-free, secure, uninterrupted or available;
- work with any calendar, storage service, device or iOS version;
- save, sync, display, export, find or keep anything you write or add.

Features that read your journal back (Lane, Year, On this day, the widget, the bound month and the Markdown export) show what your providers return at that moment. They may be incomplete, late or wrong.

**A3. No liability.** To the maximum extent permitted by law, **we accept no responsibility and no liability for anything**. That includes any loss, deletion, corruption, duplication, misplacement or exposure of your entries, files, photos, calendars or exports, whatever the cause, including:

- your own actions or anyone else's;
- device failure, loss or theft;
- App, iOS or provider updates;
- provider outages, limits, policy changes or account suspensions;
- sync conflicts, network conditions, revoked permissions or storage running out.

**You use the App entirely at your own risk.**

**A4. We store nothing; we cannot intervene.** We operate no server and keep no database, account, copy, log or backup of your content or your identity. As a result:

- we cannot read, see, reach, control, recover, restore, repair, undo, export or delete anything for you, ever, for any reason;
- if you lose your device, your accounts or your data, we cannot help;
- actions taken outside the App can change or remove your journal, and we cannot detect, prevent or reverse them. Examples: editing or deleting events in another app, removing an account, signing out of iCloud, revoking permissions, deleting files in your drive, or running out of storage.

**A5. Your accounts and their providers.** The App acts on your behalf inside accounts you own: your Apple calendars and iCloud Drive, or your Google Calendar and Google Drive.

- Each provider's terms, privacy policy, limits (including limits on the length of event notes, on file sizes and on storage) and decisions apply to what is stored there.
- We are not responsible for any provider, its availability or behaviour, or what it does with your data.
- A provider may change or close its services, or stop allowing the App to connect, at any time. The App may then stop working in part or in full, and we have no obligation to adapt it.

**A6. Permissions you grant.** When you connect Google, you grant the App the permissions shown at sign-in. When you use Apple calendars, the camera or the photo picker, you grant the permissions iOS asks for. You can remove these permissions at any time in your account settings or in iOS Settings, and the App may stop working as a result. The App uses them only to do what you ask.

**A7. Journaling only.** The App keeps your journal in one calendar, *Journal Lane*, which it creates in your account when there is none. It writes, edits and deletes only all-day journal entries in that calendar. All other events and calendars are shown read-only. Deleting an entry or a file is permanent in your account and cannot be undone by us. You confirm each deletion yourself and accept its consequences.

**A8. Shared calendars and devices.** If you share your Journal Lane calendar with, or make it accessible to, other people (including an employer or school), they may see your entries. The same applies to anyone with access to your device, its widgets, its notifications or your accounts. Choosing who can see your calendars, storage and device is your sole responsibility.

**A9. Files, photos and the camera.** Photos you add are re-saved as smaller JPEGs, without location or camera details, and may lose quality. Your original stays wherever it was (for example in your photo library). Deleting an entry does not delete its files unless you explicitly choose to. Removing a file from an entry leaves the file in your storage. A deleted file cannot be restored by us.

**A10. Widget and share extension.**

- **Widget:** shows a small summary of your day on your Home and Lock Screen, where others may see it.
- **Share extension:** keeps shared items on your device until you next open the App, then places them on today's page. If you leave that page without saving, or delete the App before opening it, those items are gone.

Neither the widget nor the share extension is a backup.

**A11. Exports and the bound month.** Markdown exports and bound month PDFs are made on your device from what your providers return at that moment, and are handed to you through the system share sheet. They may be incomplete. Once shared or saved, they are outside the App, and keeping them safe and private is your responsibility. Exports are offered as a convenience, with no guarantee that they can be read or imported anywhere.

**A12. Termination, end of support, withdrawal and transfer of ownership.** We may, at any time and at our sole discretion, **without notice and without any obligation or liability to you**:

- end, reduce or stop support, updates or fixes for the App or any feature;
- change, limit or remove any feature, including any provider connection, the widget, the share extension, exports or the bound month;
- withdraw the App from sale or from the App Store in any or all countries;
- suspend, pause or **permanently discontinue and terminate** the App or any part of it;
- **transfer, sell, assign or otherwise dispose of the App, this Agreement and/or ownership of the App** to any other party, who may continue, change or end it.

Because we store no data and keep no account, **there is nothing for us to hand over, migrate or return to you** in any of these cases. Your journal stays in your own calendars and storage, and it is your responsibility to keep your own copies so you never depend on the App or on us continuing to exist.

**A13. Price, purchases and subscriptions.** The App may be offered at no charge, for a price, with in-app purchases, with subscriptions, or with any mix of these, and **this can change at any time**.

- We may introduce, change, discount or remove any price, purchase or subscription, and change what each one includes, at any time.
- A change in price never gives a right to a refund, a credit or the difference.
- Anything you have already written stays in your own calendar, whatever the price.
- Any purchase or subscription is made through Apple, at the price and on the terms shown at the moment of purchase. Subscriptions renew automatically unless cancelled in your Apple Account at least 24 hours before the end of the current period. Refunds are handled exclusively by Apple.

**A14. Your content and acceptable use.** You own everything you write and add; the App is licensed to you, not sold. You agree:

- not to use the App for unlawful content or to infringe anyone's rights;
- not to use it in any way that harms the App, a provider or anyone else;
- not to copy, modify, reverse engineer or redistribute the App, except where the law expressly permits it.

**A15. Privacy.** We do not require an account with us, and we collect, store and share no personal data. See the Privacy document. By continuing to use the App, you acknowledge these limitations and accept full responsibility for your data.

**A16. No account; we cannot contact you.** We keep no account, user database or contact details, and have no way to identify, contact, notify or reach you, including about changes, problems or the end of the App.

**A17. Changes to this Agreement.** We may update, change or replace this Agreement at any time, at our sole discretion. **Because we keep no account and no way to contact you, we do not and cannot notify you of changes.**

- The current version is the one published at https://github.com/lucanise-pro/public/blob/main/journallane/index.md.
- The copy inside the App is provided **only for your convenience and may be out of date. It is your responsibility to review the current version.**
- Your continued use of the App after any change means you accept the then-current Agreement.

**A18. Responsibility for use by others.** We are not responsible for how the App, your device, your accounts, your calendars or your storage are accessed or used by anyone other than you. That includes family members, anyone with access to your device or accounts, and anyone a calendar or file is shared with. Keeping them secure is your responsibility.

**A19. No affiliation.** We are independent and **not affiliated with, endorsed by, sponsored by or acting on behalf of Apple or Google.** Their names and services belong to them. We use their services only as permitted by their terms, and they, not us, are responsible for those services.

**A20. Not professional advice.** The App is a personal journaling tool. Nothing in it is medical, psychological, legal or any other professional advice or care, and it must not be relied on for any such purpose.

**A21. You accept the nature of the App.** Journal Lane keeps your journal in your own calendars and storage. That is its nature, and it carries the risks that come with it. Entries and files can be lost, changed, corrupted, duplicated, exposed or made unreachable by:

- a device failure;
- a system, App or provider update;
- a provider change or outage;
- sync, sharing settings or permissions;
- your own actions.

**By using the App you accept those risks in full and agree that they are yours alone, not ours.**

**A22. Limitation of liability.** To the maximum extent permitted by law, **we are not liable for any damage or loss of any kind** arising from or connected to the App or your use of it, **even if we were aware such loss was possible.** That includes loss of data, content, files or photos; loss of memories or time; distress; lost profits or opportunities; business interruption; and any direct, indirect, incidental, special, punitive or consequential loss. If any liability cannot be excluded, **our total liability for all claims combined is limited to the amount you paid for the App and its in-app purchases in the twelve months before the claim arose** (which may be zero).

**A23. Your responsibility to us.** You are responsible for what you write, store, share and do with the App. If anyone else brings a claim, demand or cost against us because of your use of the App, your content or your failure to follow this Agreement, **you agree to cover us for it**, including reasonable legal costs.

**A24. If part of this Agreement does not apply.** If any part of this Agreement is found invalid or unenforceable, that part is treated as removed (or limited to the minimum extent necessary) and every other part continues in full force. If we do not enforce a part at some point, that is not a waiver; we may still enforce it later. Nothing in this Agreement limits rights you have under mandatory consumer law that cannot be excluded.

**A25. The whole agreement.** This Agreement, together with the Terms of Use and the Privacy document, is **the entire agreement** between you and us about the App. **Nothing else creates any obligation, warranty or guarantee on our part.** That includes marketing material, screenshots, App Store descriptions, our website, support replies and any other communication.

### Section B — Apple-required minimum terms

The following terms are required by Apple for apps distributed through the App Store and apply in addition to Section A.

1. **Acknowledgement.** This Agreement is concluded between you and the Developer only, and **not with Apple.** The Developer, not Apple, is solely responsible for the App and its content.
2. **Scope of License.** The license granted to you for the App is a non-transferable license to use the App on any Apple-branded products that you own or control, and only as permitted by the Usage Rules set out in the Apple Media Services Terms and Conditions.
3. **Maintenance and Support.** The Developer is solely responsible for providing any maintenance and support for the App. **Apple has no obligation** to furnish any maintenance or support services for the App.
4. **Warranty.** The Developer is solely responsible for any product warranties, whether express or implied by law, to the extent not effectively disclaimed. If the App fails to conform to any applicable warranty, you may notify Apple, and Apple will refund the purchase price of the App (if any) to you. To the maximum extent permitted by applicable law, Apple will have no other warranty obligation whatsoever with respect to the App.
5. **Product Claims.** The Developer, not Apple, is responsible for addressing any claims by you or any third party relating to the App or your possession and/or use of the App, including but not limited to:
   - (a) product liability claims;
   - (b) any claim that the App fails to conform to any applicable legal or regulatory requirement; and
   - (c) claims arising under consumer protection, privacy, or similar legislation.
6. **Intellectual Property Rights.** In the event of any third-party claim that the App or your possession and use of the App infringes that third party's intellectual property rights, the Developer, not Apple, will be solely responsible for the investigation, defense, settlement, and discharge of any such claim.
7. **Legal Compliance.** You represent and warrant that:
   - you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country; and
   - you are not listed on any U.S. Government list of prohibited or restricted parties.
8. **Developer Name and Address.** Any questions, complaints, or claims regarding the App should be directed to the developer, **Lucanise**, via the **Send a message** link in the App's Settings. The App's terms are published at https://github.com/lucanise-pro/public/blob/main/journallane/index.md.
9. **Third-Party Terms of Agreement.** You must comply with applicable third-party terms of agreement when using the App, including the terms of Apple or Google for the accounts you connect.
10. **Third-Party Beneficiary.** You acknowledge and agree that Apple, and Apple's subsidiaries, are third-party beneficiaries of this Agreement, and that, upon your acceptance of this Agreement, Apple will have the right (and will be deemed to have accepted the right) to enforce this Agreement against you as a third-party beneficiary thereof.
