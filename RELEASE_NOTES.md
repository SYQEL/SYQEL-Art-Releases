<!--
  The release notes for the NEXT desktop release. The release workflow renders this file into the
  GitHub Release body ({{VERSION}} becomes the tag without its "v", e.g. 1.3.1).

  EDIT THE FIRST PARAGRAPH BEFORE TAGGING. Everything below it is boilerplate and rarely changes.

  This page is public and is the first thing a customer reads. Write what CHANGED FOR THEM, in plain
  language — no commit messages, no file or function names, no internal tooling, never a secret.
-->

**Fixes system audio.** In 1.3.0 the visuals could stop responding to what was playing shortly after you started — this release restores it. Casting to your TV is also far more reliable: SYQEL Art now re-finds your TV at the moment you pick it, so one that moved or restarted still connects; it works on networks that hand out only IPv6 addresses; and a slow TV can no longer stutter the audio on the computer sending it. Choosing a visual straight after launch works properly too — it used to be ignored if you were quick.

### Which file do I need?

| Your computer | Download this |
|---|---|
| **Mac** (Apple Silicon or Intel) | `SYQEL.Art_{{VERSION}}_universal.dmg` |
| **Windows 10/11** | `SYQEL.Art_{{VERSION}}_x64-setup.exe` |

Open the downloaded file and follow the installer.

**Already have SYQEL Art?** You don't need to download anything — the app updates itself automatically.

<sub>The remaining files (`latest.json`, `.sig`, `.app.tar.gz`) belong to the app's built-in updater — you can ignore them.</sub>
