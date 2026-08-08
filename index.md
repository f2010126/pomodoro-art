# Privacy Policy for Pomodoro Art

Last updated: 2026-08-08

Pomodoro Art ("the extension") is a focus timer that gradually reveals a
public-domain painting during each focus session. This policy explains what data
the extension does and does not collect.

## What Data We Collect

Pomodoro Art does not collect, store, or transmit any personal data, browsing
history, or user activity. There is no analytics, no tracking, and no advertising.

The only data the extension works with is:

- **Your timer settings** (focus/break durations, number of pomodoros, artwork
  source, cover color), stored in `chrome.storage.sync` so they can sync across the
  devices you are signed into with Chrome. This data lives in your Chrome profile
  and is managed by Chrome's own sync; the extension developer has no access to it.
- **Your current timer state** (which phase is running, when it ends, the currently
  selected painting), stored in `chrome.storage.local` on your device. This is never
  transmitted.
- **Folder handles** for your optional "My paintings folder" and music folder
  sources, stored in your browser's IndexedDB on your device. They are used only to
  read your chosen folders so the timer can reveal your paintings and play your
  music; the folders are never uploaded or transmitted.

## Third-Party Services

When you enable the optional **"Random museum artwork"** source, the extension makes
anonymous requests to public museum APIs to fetch a public-domain painting — the
Metropolitan Museum of Art's Open Access API and the Art Institute of Chicago's
public API. These requests contain no personal information and no data from your
device. If a request fails, the extension automatically falls back to the bundled
offline gallery.

- Metropolitan Museum of Art Open Access: <https://www.metmuseum.org/about-the-met/policies-and-documents/open-access>
- Art Institute of Chicago API: <https://api.artic.edu/docs>

## How Data Is Used

Timer settings and state are used solely to run the timer and reveal the painting on
your device. Nothing is used for any other purpose.

## Data Sharing

The extension does not share data with any third parties.

## Data Retention and Deletion

Settings and timer state remain in your Chrome profile until you change or reset them
in the extension's options page, or until you remove the extension from Chrome.
Removing the extension deletes this data and the stored folder handles.

## Changes to This Policy

If this policy changes, the update will be posted here with a new "Last updated" date.

## Contact

For privacy questions, contact: diptisende@gmail.com
