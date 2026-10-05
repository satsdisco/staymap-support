# StayMap Support

StayMap keeps your hotel journal on your device. Optional accounts add email forwarding, private Friends and recommendations you explicitly send or receive. Signing in does not back up or synchronize your journal.

## Build 34: Friends highlights and arrival details

Friends highlights and arrival details are **available in public TestFlight build 34**. Update StayMap in TestFlight to use them. Existing invitations, recommendations and email/photo/PDF imports continue to work as described below.

### Travel highlights you choose to share

Friends has a direct entry on **Stays** and a **Your travel highlights** card. Sharing starts off. Choose **Preview sharing** to inspect three totals calculated from completed stays: stays, nights and number of countries. Current and future stays are excluded. Choose **Share with friends** only if you want to publish that snapshot.

Your **current and future accepted friends** can see the three totals and the time you shared them alongside your chosen Friends name. No hotel or country names, individual travel dates, future bookings, costs, booking details, photos or private notes are included. These are totals supplied by your app, not independently verified travel records. There is no public stats directory.

Highlights stay as last published until you replace them or stop sharing; they do not expire automatically. Changing or deleting a local stay does not update them. **Preview an update** lets you inspect new totals before explicitly replacing the shared snapshot. A friend's card shows when their highlights were shared, so an older snapshot is easy to identify.

Choose **Stop sharing highlights**, then confirm **Stop sharing**, to remove the active totals and their publication time. Removing a friend or blocking also removes that person's access. Unblocking alone does not reconnect you; accepting a connection again while highlights are still shared grants access to the existing snapshot. Previously seen information and screenshots cannot be recalled. Signing out does not stop sharing. Deleting the account removes its summary and retained revision record, as described in the privacy policy.

If a network error leaves sharing status uncertain, refresh it before trying again; do not assume a publish or stop action failed. If another action changed the snapshot, review the refreshed state and prepare a new preview. There is no automatic retry that turns sharing back on.

### Arrival details in confirmation review

Newly read confirmations can suggest explicitly labelled **check-in from**, **check-out by**, **breakfast details** and **arrival instructions**. Review these optional fields in **Arrival details** before saving. Edit or clear anything that does not match the actual booking. Clock times are local to the property; the parser does not infer a time zone or assume a meal is included.

This uses the existing on-device reading flow for pasted text, forwarded email text, selected email photos/PDFs, local captures and the share extension. Ambiguous or missing details may remain empty, and conflicting values need review. Your corrections, including deliberately cleared fields, stay with the local draft when you close and reopen it. Older reviewed drafts and saved stays are not silently re-imported or updated.

Arrival details remain in your private stay. They are included in journal backups and a deleted stay's recovery copy. Companion booking sharing includes them only if you explicitly enable its separate arrival-details option; Friends highlights and direct recommendations do not include them. Review access instructions for sensitive information before sharing a booking copy.

## Import a booking

From **Stays**, open the **+** menu and choose **Import confirmation**. Choose **Forwarded email**, **Photos**, **PDF or file**, or **Paste text**. Photos, files and pasted text work without an account. Choosing a source does not add a stay: review the extracted hotel, location, dates, confirmation number and nightly rate before saving.

Open **Confirmations** from the Stays **+** menu to return to unfinished reviews and forwarded emails in one place. Closing a review keeps its corrections on this device. Local reviews are not uploaded or synchronized by signing in. If a row says **Already added**, it opens the saved stay instead of adding another copy.

### Forward a booking, including photos and PDFs

1. In **Confirmations**, choose **Set up email forwarding** and sign in with the code emailed to you. Your first sign-in creates the optional account. You can also use **Settings → Account & forwarding**.
2. Choose **Forward a confirmation** and copy your private forwarding address. Forward one booking directly to it as the only recipient, without CC/BCC.
3. Refresh **Confirmations** and open the email. Select relevant booking photos/PDFs and email text; leave unrelated logos out.
4. Choose **Read confirmation**, then check the suggested booking details before saving. Receipt of an email never automatically adds, changes or cancels a stay.

Supported attachments are JPEG, PNG, HEIC, HEIF, WebP and PDF: up to 20 per email, 20 MiB per file, 20 pages per PDF and 64 megapixels per image. Selected files are downloaded and read on your iPhone. The complete forwarded message, including attachments, passes through Resend. Original files are not kept as permanent booking documents; extracted text and corrections remain in the local review.

If a logo or file cannot be read, deselect it and retry with the booking pages. **Refresh files** renews temporary links while keeping excluded files unselected. Cancelling reading leaves the email available. Reopening a review preserves your corrections; **Read other booking files** in its options starts a separate review. In Account & forwarding, the equivalent action is **Read other files**. For unsupported or oversized files, use a smaller PDF/image or import its text directly. Conflicting hotels, dates, references or prices require review; parsing is not guaranteed for every provider or language.

Emails with attachments stay in the temporary forwarding inbox until discarded or the 30-day retention period expires. Text-only email copies can be removed after a successful local handoff. **Remove email copy** in Confirmations, or **Discard email** in Account & forwarding, leaves downloaded reviews and saved stays on your device. **Remove review copy** removes only the selected local review; it does not remove a separate cloud email or cancel a reservation. Outages may delay scheduled cleanup; providers retain their own copies separately.

Missing code or confirmation? Check the address and spam folder, then refresh. Forwarding requires an internet connection. **Get a new address** replaces an exposed forwarding address; the old address stops accepting mail. Anyone who knows your forwarding address can send mail to it.

## Explore a property and choose your own cover

Open a stay's **Explore hotel** or **Explore property** screen and choose **Photos on Google Maps**. Check or edit the property name and city, then choose **Search Google Maps**. Select the correct address before browsing Google's photos and details. Opening this screen alone does not search. Photos and listing coverage vary; there may be no matching listing or photo.

The search uses the property's saved map area when the text is unchanged. Otherwise, Apple first helps locate the text you submit. It uses the property or search area, not your phone's live location. Google receives the submitted text, search area and network information, including your IP address; its SDK declares device identifier collection for functionality and analytics. Keep personal booking details out of the search field. StayMap does not add your booking dates, confirmation codes, ratings or notes to these requests. See the [privacy policy](https://gist.github.com/satsdisco/314ec0ece5154b0453e3373584e86214) for the full data flows.

If Google cannot load, try again later or use **Apple Maps & Look Around**. The Apple screen can search when opened; choose the correct listing, then open its place details or **Look around the area** where coverage is available. Street imagery is not a hotel photo gallery. Provider errors and usage limits do not change or remove your saved stay.

Photos and street imagery in these Google and Apple exploration views remain provider content. They do not become your journal cover, a journal backup photo or an image sent to a friend. Use the photo control on your stay to choose a personal cover from Photos. StayMap saves a smaller local copy without the source image's embedded location metadata; the original in Photos stays unchanged. Your own cover is included in exported journal backups.

### Google Maps terms

StayMap includes Google Maps features and content. Your use of those features and content is subject to the current [Google Maps End User Additional Terms](https://maps.google.com/help/terms_maps/) and [Google Privacy Policy](https://policies.google.com/privacy). **About Google results** in the viewer explains Google's search ranking and opens these links. **Settings → Map provider notices** contains the SDK's open-source notices.

## Remember places around your hotel

Open a stay and choose **Around your stay** to save a café, restaurant, bar, sight or other find with an optional private note. Apple Maps search uses the hotel's recorded location or city/country. Check the result's address and pin; distances are straight-line estimates, not walking times. Editing the name/address clears an old search match so directions do not quietly point somewhere else.

**Share these finds** previews the places you select as a readable guide. **Include my notes** is off by default. Your booking dates, references, room details, spending, loyalty information and other journal content are excluded. Recipients do not need StayMap to read the guide, and shared copies cannot be recalled.

## Connect privately in Friends

Open **Friends** in Settings or Your places. Choose a display name, create an invite and share it privately with someone you know. They can open the link or paste the code and send a request; you must accept before you connect. Names are user-chosen, not verified identities, and email addresses are not public names. There is no contact-book upload or public directory.

Invites expire after seven days. Creating a new invite replaces the previous code; **Turn off invite** disables it. Neither action cancels existing requests. You can decline or withdraw requests and remove friends. A link requires StayMap to be installed; there is no automatic web sign-up fallback. Accounts currently allow up to 50 friends and 20 pending requests.

## Send and save a recommendation

From a saved hotel's menu, a single-property recommendation screen or a saved nearby spot, choose **Send to a friend**. Pick one accepted friend, write a fresh optional note and inspect the card before sending. Private journal notes and recommendations you received are never copied into the new note automatically.

The recipient opens or refreshes **From friends** in Your places or Friends. A hotel saves to Your places as an idea, without adding a stay or changing statistics. A nearby find saves to an existing stay chosen by the recipient. Without a stay, open the map and return later to save it.

If delivery cannot be confirmed, retry from the same review screen: it retains the same delivery identity. If saving succeeds locally but the inbox update fails, retrying preserves the saved copy instead of adding a duplicate. There are no push notifications, read receipts, chat or live journal sync. The current limit is 20 recommendations per sender per rolling day, up to five to one person; an inbox holds 50.

Pending recommendations expire after 90 days and are removed at the next daily cleanup. **Dismiss recommendation** removes its cloud content. Removing a friend or blocking removes pending recommendations between both people; saved or exported copies remain independent.

## Report, block and manage your data

Open a recommendation's options to **Report** it. Reporting hides the item and keeps the selected shared content and reason for manual review. It does not attach your private journal or notify the sender. Report evidence has a 90-day retention period, followed by daily cleanup; there is no guaranteed response time.

**Block** ends the connection, removes pending requests/recommendations and prevents new requests or recommendations in either direction. Open **Friends → Blocked people** to unblock. This does not reconnect you or restore removed content.

Delete an account through **Settings → Account & forwarding → Delete account**, confirming with a fresh email code. This removes active account, forwarding, Friends, recommendation, report and block records. It leaves local stays, saved recommendations, recovery copies and downloaded reviews in place. Signing out does not delete the account, and neither action cancels a hotel reservation. Manage local records, exported backups and other shared copies separately.

## Get help

In the beta, use **Send Beta Feedback** in TestFlight to report a problem with its screenshot and build number. Remove unnecessary private booking details and never include sign-in codes. You can also open an issue in this support repository; **issues are public**, so do not post private confirmations, invitation codes, account details or personal data requests there.

For private help, an account/data-access question or a provider-deletion request, email **support@staymap.app**. Include the app version and a short description of what happened. Never include sign-in codes; send booking details or attachments only when needed for the issue and after removing unrelated personal information.

## Privacy Policy

[StayMap Privacy Policy](https://gist.github.com/satsdisco/314ec0ece5154b0453e3373584e86214)
