# Automation Portal — Privacy Policy

_Last updated: 9 November 2026_

Automation Portal ("the app") is an automation app for Windows. You build shortcuts and automations that run on your own PC.
This policy explains what information the app uses, where that information goes, and what control you have over it.

## The short version

- **Your shortcuts, automations, snippets and run history stay on your PC.** We don't run any servers that receive them.
- **No accounts, no ads, no analytics, no tracking.** The app sends no usage data, crash reports or identifiers to us.
- The app only connects to the internet when **a shortcut you run, or an automation you set up, uses an online action**,
  for example getting the weather or opening a web page. It connects only to the service that action needs.
- Anything sensitive the app works with (keystrokes, clipboard, location, microphone, files) is used **only to carry
  out what you asked it to do** and is processed on your PC.

## Information stored on your PC

The app saves the following in your Windows user profile, or in a folder you choose, such as a OneDrive folder if you
want your library synced:

- the shortcuts, folders, automations and text snippets you create
- app settings, saved values from your shortcuts, reminders and saved window layouts
- run history: when each shortcut ran, whether it worked, and short previews of each step's output. The app keeps the
  most recent 1,000 runs, and you can clear the history at any time in **Run History**
- notes created by the "Add to Note" action, saved in `Documents\Automation Portal Notes`
- your AI service key, if you add one. It is encrypted with Windows Data Protection so that only your Windows account
  can read it

Uninstalling the app removes the data stored in the app's own folders. Files you chose to save elsewhere, such as
notes, exported shortcuts or a library in OneDrive, stay where you put them.

## Permissions and sensitive features

| Feature | What it's used for | Where the information goes |
|---|---|---|
| **Keyboard** (typed-phrase triggers, text snippets, the click-and-keystroke recorder) | Spotting the abbreviations and phrases you set up, and recording steps while you have recording switched on | Processed in memory on your PC. Keystrokes aren't saved or sent anywhere. The app skips password fields. Recorded steps are saved only into the shortcut you're recording. |
| **Clipboard** | Clipboard actions, the Clipboard variable, and "when I copy something" automations | Stays on your PC unless one of your shortcuts sends it somewhere |
| **Location** | "Get Current Location", weather and sunrise/sunset actions and triggers | Used on your PC. If Windows location is unavailable, the app may estimate your area from your internet (IP) address using a location lookup service. A place name may be looked up via OpenStreetMap Nominatim. |
| **Microphone and camera** | Dictation and audio-recording actions. "When I'm in a call" automations check only *whether* the mic or camera is in use, as reported by Windows | Recordings are saved where your shortcut puts them. The app never records audio or video for any other purpose. |
| **Screen** | Screenshot, "Grab Text from Screen" and "Pick Color" actions | Captured images and recognised text stay on your PC unless your shortcut sends them somewhere |
| **Files and folders** | File, image, PDF and note actions, folder-watching automations | Only the files your shortcuts work with. The app never uploads files on its own. |
| **Other apps and windows** | Opening, switching, arranging and closing apps and windows; reading the current web page address from your browser | Stays on your PC |

## Online services the app may contact

These connections happen only when an action or automation you set up needs them:

| Service | When | What is sent |
|---|---|---|
| Open-Meteo (open-meteo.com) | Weather actions and weather automations | The location or place name you asked about |
| Frankfurter (frankfurter.app / frankfurter.dev) | Currency conversion | The currencies being converted |
| ipify (ipify.org) | "Get Public IP Address" | A standard web request |
| OpenStreetMap Nominatim, and an IP-location service | Location names, and approximate location when Windows location is unavailable | Coordinates or your IP address |
| ntfy (ntfy.sh) | "Send to My Phone" | The message, title and topic you set |
| The AI service you choose — Anthropic (Claude), OpenAI (ChatGPT), Google (Gemini), DeepSeek, Moonshot AI (Kimi), Microsoft Azure OpenAI, or another service you configure | AI actions, only after you add your own key for that service | The text, images or documents you send to the AI action, under that provider's own privacy terms. **Local AI** (Ollama, LM Studio) runs on your PC and sends nothing over the internet. |
| Any website or web service you name | "Get Contents of URL", web page, RSS, download and "a web page changes" actions | Whatever your shortcut sends to that address |
| Your calendar's .ics link | "Before a calendar event" automations | A standard request to the link you provide |
| Microsoft Outlook (classic) on your PC | Email and calendar actions | Drafts and events are created in your own Outlook |

Each of these services is run by a third party with its own privacy policy. Automation Portal doesn't send them anything
beyond what the action needs.

## Shortcuts you import or share

Exported `.autoportal` files contain only the shortcut itself (its actions and settings), never your run history,
settings or AI key. Before you add a shortcut someone else made, the app shows which powerful actions it contains.

## Children

Automation Portal isn't directed at children and doesn't knowingly collect personal information from anyone.

## Changes to this policy

If this policy changes, the new version will be published at this address with an updated date. Significant
changes will also be mentioned in the app's release notes.

## Contact

Questions about privacy: **mindthaapp@gmail.com**
