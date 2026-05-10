---
title: Privacy Policy
---

# Privacy Policy

**Last updated: 2026-05-10**

This policy explains how Pottr ("the app") handles your data. It is written in plain language because privacy should be readable.

## Summary

Pottr stores your pottery projects, photos, sketches, and notes **on your device** and **in your private iCloud account**. The developer cannot read any of this data.

The app does not contain advertising, analytics, crash reporters, or third-party SDKs.

## What data Pottr stores

When you use Pottr, the following are stored on your device and synced through your private iCloud:

- Projects (titles, notes, dimensions, weights, dates, stage history)
- Firing logs (temperatures, methods, notes)
- Decoration layers and the materials referenced
- Custom material library entries (clays, glazes, slips, underglazes, oxides, stains)
- Photos, videos, and sketches you add to projects
- App preferences (units, language override, filter selections)

This data lives in:

- The local SwiftData store on your device, and
- Your private iCloud Database (CloudKit container `iCloud.com.marcmelgosa.Pottr`), which is part of your personal Apple ID.

**The developer has no access to your private iCloud Database.** Apple does not provide the developer with read access to user iCloud accounts.

## What data Pottr sends to the developer

Two optional features write data to a **public** CloudKit database that the developer reviews. Both are explicitly opt-in.

### 1. Send Feedback (Settings → Send Feedback)

When you submit feedback, a record is written to the public CloudKit database containing:

- The text of your feedback
- An optional reply email (only if you choose to provide one)
- App version, iOS version, device model, and locale (used to reproduce bugs)

The developer reads these submissions via the CloudKit Dashboard to fix issues and improve the app. Submissions are not shared with third parties.

### 2. Tip Jar (Settings → Support Pottr)

If you choose to leave a one-time tip:

- The purchase is processed by **Apple**, not the developer. The developer never sees your payment information, billing address, or Apple ID.
- The total amount tipped across all users in the current year is written to a public CloudKit record so the in-app yearly progress bar can display community support. **No individual purchase, user identifier, or amount is recorded against any user.** Only the running aggregate total.
- Sandbox and Xcode-test purchases are excluded from this aggregate.

## What data Pottr does NOT collect

- No advertising identifiers
- No analytics or telemetry
- No crash reports
- No location data
- No contacts, calendars, or reminders
- No third-party SDKs of any kind

The app uses the camera and photo library only when you actively choose to add a photo or video to a project, and only with your explicit permission.

## Data retention and deletion

- Your projects and materials are stored entirely on your device and in your iCloud account. To delete them, delete the relevant projects in the app, or delete the app and remove the iCloud container in iOS Settings → [your name] → iCloud → Manage Account Storage → Pottr.
- Feedback submissions persist in the public CloudKit database until the developer manually deletes them. To request deletion of a feedback submission you sent, email the address below.

## Children

Pottr does not knowingly collect any data from children under 13. The app is rated 4+ and contains no objectionable content, but the developer is not the operator of any service that children directly interact with.

## Changes to this policy

If this policy changes materially, the date at the top will be updated. Continued use of the app after a change constitutes acceptance.

## Contact

For privacy questions or data deletion requests:

- Email: marc.melgosas@gmail.com
- GitHub issues: https://github.com/MarcMelgosa/Pottr/issues
