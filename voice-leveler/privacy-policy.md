# Voice Leveler Privacy Policy

**Effective date:** October 6, 2026

Voice Leveler processes audio from a browser tab selected by the user. This policy describes data handled by the Voice Leveler 1.9.1 candidate for Microsoft Edge and Chrome.

## Audio and settings

When the user starts processing, the extension captures audio from the selected tab and processes it locally in the browser, including while offline. Audio is not uploaded, transmitted to the publisher or Lemon Squeezy, or sent to an analytics or advertising service. The extension does not record or store audio and does not include telemetry.

Audio preferences, including equalizer, amplification, stereo, and Pro settings, are stored using the extension's local storage. The extension does not use browser sync storage. While processing is active, the selected tab and session identifiers are held in session storage and removed when processing stops or ends.

## Trial and license information

If the user starts the optional trial, the extension stores the trial start time and a last-seen time locally to enforce the seven-day period. When the user explicitly activates a new Lemon Squeezy license, the extension sends the license key and the constant instance name “Voice Leveler browser” to Lemon Squeezy's License API over HTTPS. Lemon Squeezy returns the activation instance ID. When the user explicitly revalidates or removes that activation, the extension sends the license key and that instance ID. There is no background polling. The API response may include customer or order metadata, but the extension does not store the buyer's name, email, or order data. Its minimum local cache contains the license key, instance ID, store/product/variant IDs, verification time, expiry, test-mode flag, and a generic label. Initial activation and revalidation require an internet connection; audio processing works offline once started. Existing signed VL1 keys continue to be verified locally. Their signed customer label may contain the purchaser's email address and is shown in the license interface; the extension does not send a VL1 key to a server. Remote revocation of a Lemon key is reflected when the user revalidates it; there is no periodic polling.

## Access, controls, and deletion

The user controls when tab audio processing starts and stops. The user can change or reset preferences in the extension, remove the locally activated license from its license controls, or remove the extension from the browser. Removing the extension or clearing its stored data deletes the extension's locally stored preferences, trial state, license key, and active-session records. An installation-local trial may therefore be reset by clearing extension storage or reinstalling.

## Changes and contact

Voice Leveler's use of information received through browser APIs complies with the Chrome Web Store User Data Policy, including its Limited Use requirements. Tab audio is used only for local audio processing. License information is used only for Lemon Squeezy license activation/status or local VL1 verification. It is not sold, used for advertising, creditworthiness, or lending decisions, or shared with analytics services.

This policy will be updated if the extension's data practices change. Contact the publisher at the address for the store where you obtained Voice Leveler.

**Microsoft Edge support and privacy:** [stormedboy200@outlook.com](mailto:stormedboy200@outlook.com)

**Chrome Web Store support and privacy:** [ctsjedidias2000@gmail.com](mailto:ctsjedidias2000@gmail.com)
