<!--
  The release notes for the NEXT desktop release. The release workflow renders this file into the
  GitHub Release body ({{VERSION}} becomes the tag without its "v", e.g. 1.3.1).

  EDIT THE FIRST PARAGRAPH BEFORE TAGGING. Everything below it is boilerplate and rarely changes.

  This page is public and is the first thing a customer reads. Write what CHANGED FOR THEM, in plain
  language — no commit messages, no file or function names, no internal tooling, never a secret.
-->

**Casting is cleaner and more dependable, and the app now tells you when macOS is in the way.** Audio sent to a TV could develop tiny gaps you heard as clicks or crackle — that is fixed, and what reaches your TV matches what is playing here. A TV or window that fell behind could go quiet for good until you restarted; it now catches back up on its own. On a Mac, individual apps like Spotify only appear in the source list once macOS has been given screen-recording access, so the app now says so, offers to ask for it, and reminds you that it has to be reopened before the change takes effect — instead of just showing a short list. Connecting to system audio also reports what went wrong rather than sitting there, picking a TV that has moved or switched off comes back quickly instead of hanging, the TV list keeps updating while you try, and your computer no longer keeps offering a cast it has already stopped. If you are subscribed, the watermark no longer lingers on your TV when your subscription becomes active mid-session.

### Which file do I need?

| Your computer | Download this |
|---|---|
| **Mac** (Apple Silicon or Intel) | `SYQEL.Art_{{VERSION}}_universal.dmg` |
| **Windows 10/11** | `SYQEL.Art_{{VERSION}}_x64-setup.exe` |

Open the downloaded file and follow the installer.

**Already have SYQEL Art?** You don't need to download anything — the app updates itself automatically.

<sub>The remaining files (`latest.json`, `.sig`, `.app.tar.gz`) belong to the app's built-in updater — you can ignore them.</sub>
