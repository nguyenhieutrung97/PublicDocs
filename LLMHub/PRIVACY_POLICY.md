# LLM Hub Privacy Policy

**Effective date:** October 4, 2026
**Contact:** trungnguyen19972707@gmail.com — a working email you check, e.g. privacy@yourdomain.com_

LLM Hub ("the app") is a client for AI model services that **you** connect
with your own API keys. This policy explains what data the app handles.
It is written for the Google Play "Data safety" section as well as for
end users.

## Summary

- **We do not collect anything.** The app has no developer-operated
  servers, no analytics, no advertising SDKs, and no crash-reporting
  service.
- All app data (provider settings, chat transcripts, usage statistics)
  is stored **on your device only**.
- API keys are stored in the device's secure credential storage
  (Android Keystore-backed secure storage) and are never included in
  backups unless you export them yourself, encrypted, as a backup file.

## Data the app stores on your device

| Data | Where it lives | Why |
| --- | --- | --- |
| Provider configuration (names, endpoints, enabled state) | Local app database on-device | To connect to the AI services you choose |
| API keys / credentials | Device secure storage | To authenticate your requests |
| Playground chat messages | Local app database on-device (persisted so conversations survive restarts); cleared by "New chat" | To run the conversation |
| Usage statistics (tokens, cost, request counts) | Local app database on-device | To show your spend and quota dashboards |

## Data sent to third parties

When you send a prompt, the app sends that request **directly from your
device to the AI provider you selected** (for example OpenRouter, Z.AI,
or another OpenAI-compatible endpoint you configured). The developer of
LLM Hub never sees this traffic.

Your prompts and the AI-generated responses are governed by the privacy
policy of the provider you chose. Flagged responses (via "Report
response") are marked **locally on your device only**; the app does not
upload flags or reports anywhere.

## Backups

Backup files are created only when you explicitly export one. They
contain your provider settings and, encrypted with your passphrase,
your API keys. The app cannot recover a backup without your passphrase.
You choose where the file is saved.

## Permissions

- **Internet** — to reach the AI providers you configure.
- **Storage (legacy, Android 9 and below only)** — to save an exported
  backup file to public storage when the system save dialog is not
  available.

## Children

LLM Hub is a developer tool and is not directed at children under 13.

## Changes

Changes to this policy will be published at the URL listed in the
Google Play listing with an updated effective date.

## Contact

_PLACEHOLDER — contact email / support URL_
