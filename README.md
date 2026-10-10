# PupDesk Harness


**Your Windows desktop workspace for AI chat and assisted coding.**


PupDesk Harness by **HJBCodeForge** connects local models and cloud AI providers with conversations, project folders, and tools in a native desktop application. Official compiled releases are **free to use**, including for internal business use. AI provider charges, if any, are separate.


This repository hosts documentation, release downloads, and issue tracking. The application source code is proprietary and is not published here.


## Download and install


Visit [Releases](https://github.com/HJBCodeForge/PupDesk_Harness/releases) and download the `PupDesk-Setup-<version>.exe` asset from the latest release. GitHub source archives are not installers.


- Platform: Windows, x64.
- Run the installer and choose the installation folder and shortcut options.
- Launch **PupDesk** from the Start menu or desktop shortcut.
- Updates: PupDesk 1.29.1 and later check this page and offer each new version (**New version available: Update** in the top bar, or About → Check for updates). On an older version, close PupDesk and run the newer official installer.
- Uninstall through Windows Settings → Apps. Back up any data you want to keep.


Use downloads from this repository. When a release includes `SHA256SUMS.txt`, compare the installer hash before running it:


```powershell
Get-FileHash .\PupDesk-Setup-<version>.exe -Algorithm SHA256
```


## First conversation


1. Open Settings and configure a provider and its connection details.
2. For a local model, start your model server (such as Ollama or LM Studio) and load a model. For a cloud provider, supply your own API key.
3. Find or add models in Settings → Models, then select a model for your chat.
4. Start a conversation. For coding, select the intended project/workspace folder and review tool permissions before allowing changes.


Model downloads and API credits are not included. Local model speed and memory requirements depend on your hardware and model.


## Features


| Capability | Use it for |
| --- | --- |
| Local and cloud providers | Connect compatible model servers or API accounts |
| Chat and coding workspace | Keep conversations alongside project work, with Search chats (Ctrl+K) |
| Projects | A page per project with its chats, instructions, files, memory and defaults |
| Routines | Run a prompt on a schedule, once or on demand; each run opens as its own chat |
| Kibble, your assistant | Direct it from the app or from Slack, connect Google Calendar, get reminders and daily briefings |
| Built-in browser | Let chats and Kibble browse in PupDesk's own browser while you watch and take over |
| Unsent messages kept | What you type stays in each chat's box until you send it, even after a restart |
| Tool permissions and plan mode | Review proposed actions and control tool access |
| Model Context Protocol (MCP) | Connect additional tools and services |
| Artifacts and documents | Work with generated content and previews |
| Usage tracking | Review recorded token and cost estimates |


Behavior depends on your provider, model, tools, and settings. AI output can be incorrect; review generated code and proposed actions.


## Data and privacy


PupDesk stores application data locally. Cloud requests send the conversation and included context to your selected service. Local models run through your configured server; connected tools and MCP servers may still communicate externally. Review each service’s policies. Keep API keys private and back up project files before allowing AI edits.


## Help and feedback


[Open an issue](https://github.com/HJBCodeForge/PupDesk_Harness/issues) for bugs or feature requests. Include the app version, Windows version, provider/model, reproduction steps, and expected versus actual behavior. Remove secrets and personal content from screenshots and logs. For sensitive reports, use the contact options on [HJBCodeForge](https://hjbcodeforge.com/).


## Support development


If PupDesk Harness helps you, optional contributions support continued development. [Buy me a coffee](https://buymeacoffee.com/hjbcodeforge). Using PupDesk does not require a donation.


## License


Copyright © 2026 **HJBCodeForge**. All rights reserved.


PupDesk Harness is proprietary software, not an open-source project. The [license](LICENSE.txt) permits free use of official compiled releases for personal and internal business use. It does not grant rights to modify, redistribute, sell, or publish the application source. Third-party components retain their own licenses. Share the official releases link with others.

