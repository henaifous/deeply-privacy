# Privacy Policy for Deeply

_Last updated: 8 October 2026_

## The short version

- **Deeply collects no personal data.** There are no accounts, no servers, no advertising and no analytics or tracking of any kind.
- **Everything stays on your Mac.** Your settings and statistics are stored locally and are never sent to the developer or to anyone else.
- **Deeply makes no network connections** and asks for no network permission.
- Deeply contains no third-party code or SDKs.

## What Deeply stores on your Mac

| What | Details | Where |
|---|---|---|
| Settings | Your break schedule, office hours, enforcement level, sounds, shortcuts, the apps you choose as "Deep Focus" apps (their name and identifier), and any automations you set up. | App preferences on your Mac |
| Daily statistics | Per day: seconds of focus and rest, how many breaks you took, skipped or snoozed, posture and blink nudges shown, the time and type of each break, the periods when Smart Pause held a break back and why (for example a call or a video), and seconds of focus per **broad app category** (for example "Developer Tools"). | `Application Support/Deeply/stats.json` on your Mac |

Apart from the Deep Focus apps you choose yourself, Deeply does **not** store the names of the apps you use. It does not store window titles, documents, screen contents, audio, video or keystrokes.

## What Deeply looks at, and does not keep

To avoid interrupting you at a bad moment, Deeply reads a few signals from macOS while it is running. They are used on the spot to decide whether to hold a break, and are not recorded or sent anywhere, apart from the summary figures listed above.

- **Whether a camera or microphone is in use.** This is a yes-or-no flag from macOS. Deeply never accesses the camera or microphone, or what they capture, and needs no permission for this.
- **Whether something is keeping the display awake**, such as a video or a presentation.
- **How long since your last keyboard or mouse input.** This is a single number of seconds. Deeply cannot see what you type or click.
- **Which app is in front, and whether a known meeting app is running.** Used to apply your Deep Focus rules and to count focus time per broad category.

## Permissions

- **Automation (Apple Events):** requested only if you add an AppleScript or Shortcut automation that controls another app. Deeply does nothing with this access on its own.

Deeply does not ask for access to your contacts, photos, location or calendar. The only file access is the standard dialog you use to pick a Deep Focus app, from which Deeply reads just the app's name and identifier.

## Automations

Deeply can run AppleScripts or Shortcuts that **you** configure when a break starts or ends. Those scripts run on your Mac with your permissions, and what they do, including any network access, is determined by what you wrote. Deeply does not read their output or send it anywhere.

## Third parties

Deeply does not share data with third parties, because it does not collect any. If you installed Deeply through the Mac App Store or TestFlight, Apple may give the developer aggregated, anonymous usage and crash information, but only if you chose to share analytics with app developers in your Mac's Privacy & Security settings. Apple's own privacy policy governs that.

## Children

Deeply is not directed at children and collects no personal data from anyone, including children.

## Your choices and deleting your data

Because your data lives only on your Mac, you control it entirely. To remove it, quit and delete Deeply, then delete its data folders: `~/Library/Application Support/Deeply` and the app's preferences, or for the Mac App Store and TestFlight versions, `~/Library/Containers/io.shobaizi.deeply`. The developer holds no copy, so there is nothing to request from us.

## Changes to this policy

If the app's handling of data ever changes, this file will be updated before the change ships, and the "Last updated" date above will change. The full history of this file is available in this repository.

## Contact

Questions about privacy? Please open an issue in this repository.
