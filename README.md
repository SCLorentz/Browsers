# Browsers
Just a list of browsers with some metrics

Speed metrics:
https://browserbench.org/Speedometer3.1/ (no custom flags, MacOS 27, M3 macbook air)

<!-- DRM -> Yes: 1 | No: 0
OSS -> Yes: 1 | No: 0
Status -> Fast Pacing: 1 | Slow Development: 1 > x > 0 | Discontinued: 0

(DRM + Speed / Best + OSS) * Status -->

🍎 - Apple \
🤖 - Android \
🐧 - Linux \
🪟 - Windows \
✳️ - Proprietary desktop (MacOS and Windows) \
❇️ - All proprietary platforms (IOS, MacOS, Windows and Android) \
💾 - Unix platforms (mostly MacOS, Linux and BSD) \
💻 - All desktop platforms \
✅ - All major platforms

! - Not applicable: The browser is based on the webview of the system (if it includes DRM, then it does support)

| Browser                  | Engine             | Widevine DRM | Paid / Premium  | Support  | AI featured | Speed  | Open Source | Status       | Score |
|--------------------------|--------------------|--------------|-----------------|----------|-------------|--------|-------------|--------------|-------|
| [Aloha](#aloha)          | Blink              | No           | No              | ✅       | …           |        | No          | …            |       |
| [Angelfish](#angelfish)  | QtWebEngine        | No           | No              | 🐧       | …           |        | Yes         | …            |       |
| [Arc](#arc)              | Blink              | L3           | No              | ❇️       | …           |        | No          | Discontinued |       |
| [Aside](#aside)          | Blink              | L3           | Yes             | ✳️       | ChatGPT     |        | No          | …            |       |
| [Atlas](#atlas)          | Blink              | L3           | No              | ✳️       | ChatGPT     |        | No          | Discontinued |       |
| [Basilisk](#basilisk)    | Goanna             | No           | No              | 💻       | …           |        | Yes         | …            |       |
| [Blanc](#blanc)          | Blink              | No           | No              | 💻       | …           |        | Yes         | …            |       |
| [Brave](#brave)          | Blink              | Config       | No              | ✅       | Leo         | 48.9   | Yes         | …            |       |
| [Brave Origin](#brave)   | Blink              | Config       | Yes             | ✅       | …           | 48.9   | Yes         | …            |       |
| [Chrome](#chrome)        | Blink              | L3           | No              | ✅       | Gemini      |        | No          | …            |       |
| Chromium                 | Blink              | No           | No              | ✅       | Gemini      |        | Yes         | …            |       |
| [Crest](#crest)          | Webview            | !            | No              | 🍎       | …           |        | Yes         | …            |       |
| [Dia](#dia)              | Blink              | No           | No              | ✳️       | Dia         | 48.3   | No          | …            |       |
| [DDG](#duckduckgo)       | Webview            | !            | No              | ❇️       | Duck AI     |        | Yes         | …            |       |
| [Edge](#edge)            | Blink              | Flag         | No              | ✅       | Copilot     | 39.7   | No          | …            |       |
| [Epiphany](#epiphany)    | WebKitGTK          | No           | No              | 🐧       | …           |        | Yes         | …            |       |
| [Falkon](#falkon)        | QtWebEngine        | No           | No              | 🐧       | …           |        | Yes         | …            |       |
| [Firefox](#firefox)      | Gecko              | Plugin       | No              | ✅       | Local       |        | Yes         | …            |       |
| [Floorp](#floorp)        | Gecko              | Plugin       | No              | 💻       | …           |        | Yes         | …            |       |
| [Flow](#flow)            | Blink              | No           | No              | 💻       | …           |        | Yes         | …            |       |
| [Glass](#glass)          | Blink              | No           | No              | ✅       | No          |        | Yes         | Discontinued |       |
| [Growser](#growser)      | Blink              | No           | No              | ✅       | No          | 50.1   | Yes         | …            |       |
| [Helium](#helium)        | Blink              | No           | No              | 💻       | No          | 49.1   | Yes         | …            |       |
| [Ladybird](#ladybird)    | LibWeb             | No           | No              | 💾       | No          |        | Yes         | Early Dev.   |       |
| [LibreWolf](#librewolf)  | Gecko              | Plugin       | No              | 💻       | No          |        | Yes         | …            |       |
| [NetSurf](#netsurf)      | NetSurf            | No           | No              | 💻       | …           |        | Yes         | …            |       |
| [Opera](#opera)          | Blink              | L3           | No              | ✅       | ChatGPT     |        | No          | …            |       |
| [Opera Air](#opera_air)  | Blink              | L3           | No              | ✅       | ChatGPT     |        | No          | …            |       |
| [Opera GX](#opera_gx)    | Blink              | L3           | No              | ✅       | ChatGPT     | 36.3   | No          | …            |       |
| [Opera Neon](#opera_neon)| Blink              | L3           | No              | ✅       | ChatGPT     |        | No          | …            |       |
| [Orion](#orion)          | Webkit             | …            | No              | 💻       | …           |        | ?           | …            |       |
| [Phi](#phi)              | Blink              | No           | No              | ✳️       | Multiple    |        | Yes         | …            |       |
| [Phoebe](#phoebe)        | Webkit             | No           | No              | 💻       | …           |        | ?           | …            |       |
| [Polypane](#polypane)    | Blink              | …            | Yes             | 💻       | …           |        | No          | …            |       |
| [Servo](#servo)          | Servo              | No           | No              | 💻       | …           |        | Yes         | …            |       |
| [Shift](#shift)          | Blink              | No           | Yes             | ✳️       | …           |        | No          | …            |       |
| [Safari](#safari)        | Webkit             | L3           | No              | 🍎       | …           | 50.7   | No          | …            |       |
| [SigmaOS](#sigmaos)      | Webkit             | …            | Yes             | 🍎       | …           |        | No          | …            |       |
| [Surf](#surf)            | Blink              | No           | No              | 💻       | Surf        |        | Yes         | …            |       |
| [Tor](#tor)              | Gecko              | No           | No              | ✅       | …           |        | Yes         | …            |       |
| [Ulaa](#ulaa)            | Blink              | No           | No              | ✅       | …           |        | No          | …            |       |
| [Ungoogled](#ungoogled)  | Blink              | No           | No              | 💻       | …           | 51.4   | Yes         | …            |       |
| [Vivaldi](#vivaldi)      | Blink              | Yes          | No              | ✅       | …           |        | Yes         | …            |       |
| [Yab](#yab)              | Webview            | !            | No              | 🍎       | Multiple    | 16.6   | No          | …            |       |
| [Yandex](#yandex)        | Blink              | No           | No              | ✅       | …           |        | No          | …            |       |
| [Zen](#zen)              | Gecko              | Plugin       | No              | 💻       | …           | 40.6   | Yes         | …            |       |
| [Zephium](#zephium)      | Webview            | !            | No              | 🍎       | Multiple    | 45.2   | Yes         | …            |       |

## Aloha

![aloha overview](./images/aloha/image1.avif)

### General Info:

- Based on chromium

![Aloha size](./images/aloha/size.avif)

## Angelfish

### General Info:

- Qt based

## Arc

![arc overview](./images/arc/overview.avif)

### General Info:

- Closed source
- Only security updates nowadays
- Based on chromium

### Systems Avaliable:

- MacOS
- Windows
- Android
- IOS

### Author's Overview

It was nice while it lasted. The browser modernized browsing for many with a new design philosophy.

## Aside

![aside overview](./images/aside/overview.avif)

### General Info

- Closed source
- Based on chromium

## Atlas

![atlas overview](./images/atlas/overview.avif)

### General Info:

- Closed source
- AI focused browser
- Removed about://urls support
- Based on chromium

### Author's Overview

The browser that made google stock share fall 4% and promised: “You control what it remembers about you, how your data is used, and the privacy settings that apply while you browse.”, what was actually promised was "You control what it remembers about you _when it's talking to you_". This is not a browser that reinvents the web or the first that allows the user to create a "sexy firefighter calendar picture" (see below) of themselves. It does the same thing that most browsers already do, and as always, using chromium as their base.

<img width="409" alt="x post screenshot of a 'slop' image created by Sam Altman (OpenAI CEO)" src="https://github.com/user-attachments/assets/2184a840-08b9-4300-96bd-02fe5211ef30" />

see more at:
https://www.theguardian.com/technology/2025/oct/21/openai-chatgpt-web-browser-atlas?ref=cupure

## Basilisk

![basilisk overview](./images/basilisk/overview.avif)

### General Info:

- Open Source
- Goanna rendering engine
- Java support
- Flash support

### Author's Overview

It is in fact a solid browser, not for "normal", as in "non-experienced" or "non-developers" users, but a niche for the indie-web. The team behind it's keeping a lot of legacy features alive while still supporting modern browser features.

## Blanc

![blanc overview](./images/blanc/overview.avif)

### General Info:

- Based on chromium
- Uses electron
- Minimalistic

![Blanc size](./images/blanc/size.avif)

## Brave

![brave overview](./images/brave/overview.avif)

### General Info:

- Tor protocol support
- Unstoppable domains support
- Custom local AI models support
- AI featured browser
- Integrated VPN
- Integrated ad-blockers
- Based on chromium
- Open source

## Origin
This is a custom build of brave with the flag `--gn-gen-args='is_brave_origin_branded=true'`. A "premium" version of Brave with strip down features. Paid on most platforms except on linux.

### Avaliable Systems:

- MacOS
- Linux
- Windows
- Android
- IOS

## Chrome
Google Chrome

![google chrome](./images/chrome/overview.avif)

### General Info:

- Closed source
- AI featured browser
- Based on Chromium
- Vertical tabs

### Avaliable Sistems:

- MacOS
- Linux
- Windows
- Android
- IOS

### Author's Overview

The browser from the company that is banking the web. Mozilla wouldn't exist if it wasn't for google's donations. Google chrome is the best option for somewhone who just wants their job done. Of course, they are also responsible to control how the web works since they control 68% of the browser market share and other browsers comply or get behind ([for example, the manifest v3 situation](https://developer.chrome.com/docs/extensions/develop/migrate/what-is-mv3))

## Crests

![Crest](./images/crest/overview.avif)

### General Info:

- Open source

![Crest size](./images/crest/size.avif)

## Dia

![Dia overview](./images/dia/overview.avif)

### General Info:

- Closed source
- AI focused browser
- Based on Chromium

### Author's Overview

This is just bad. The size is colossal, it has memory leaks, the design had a glow down since last time I tested and, in general, it performed poorly

![Dia size](./images/dia/size.avif)

## Duckduckgo

![Duckduckgo overview](./images/duckduckgo/overview.avif)

### General Info:

- AI featured browser
- Based on chromium

## Edge

![Edge overview](./images/edge/overview.avif)

### General Info:

- Closed source
- AI featured browser
- Based on chromium

### Avaliable Systems:

- MacOS
- Linux
- Windows
- Android
- IOS

### Author's Overview

Doing the https://www.browserbench.org/Speedometer3.1/ was, for some reason, painfully slow; It also pinned itself in the middle of my dock without asking; And, for some reason, there was a password protected `launchctl service com.microsoft.EdgeUpdater.wake` that I needed to disable before I could uninstall.

## Epiphany

! having problems with compilation on macos

## Falkon

! having problems with compilation on macos

### General Info:

- Qt engine

## Firefox

![Firefox overview](./images/firefox/overview.avif)

### General Info:

- Open source
- AI featured browser
- gecko engine

### Avaliable Systems:

- MacOS
- Linux
- Windows
- Android
- IOS

## Floorp

![Floorp overview](./images/floorp/overview.avif)

### General Info:

- Based on Firefox
- Open Source

## Flow

there is a browser named flow based on chromium avaliable for use on linux/mac/windows
![Flow overview](./images/flow/overview.avif)

https://flow-browser.com/

### General Info:

- Open source
- Vertical tabs
- Based on chromium
- Disabled `about:urls`

... but there is also a browser engine/ browser named flow avaliable on the site:

https://www.ekioh.com/flow-browser/

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ac06c65f-0bc6-415b-bc75-8463044154b2" />
avaliable on https://www.ekioh.com/blog/, accessed on Sat 21 Feb

A proprietary browser that "draws HTML elements directly on the GPU" accordingly to it's official website.

The second browser impressed me way more than the first one since creating a browser engine from scratch isn't a simple thing, but it's more used for embedded systems and it's closed source. The binaries are only avaliable for raspberry pi.

## Glass

https://glassapp.dev/

![Glass Overview](./images/glass/overview.avif)

### General Info:
- Open Source
- IDE, Terminal and Browser
- Based on Zed IDE

### Author's Overview

With limited testing time, I strongly belive that this can be a great tool. Personally, I feel appealed for this app core idea.

### Growser

![Growser Overview](./images/growser/overview.avif)

### General Info:

## Helium

![Helium overview](./images/helium/overview.avif)

### General Info:

- Open source
- Based on chromium

### Patches:

- Ungoogled Chromium
- Bromite
- Brave
- Inox
- debian
- iridium-browser

![Helium size](./images/helium/size.avif)

## Ladybird

![Ladybird overview](./images/ladybird/overview.avif)

### General Info:

- Needs to be compiled manually
- Not for daily usage
- Open source
- Libweb engine

### Systems Avaiable:

- MacOS
- Linux
- SerenityOS

## Librewolf

![Librewolf overview](./images/librewolf/overview.avif)

### General Info:

- Based on firefox
- Open source

### Patches:

- Improved security

## Opera

![Opera overview](./images/opera/overview.avif)

### General Info:

- Closed source
- AI featured browser
- Based on chromium

## Opera Air

![Opera air overview](./images/opera_air/overview.avif)

### General Info:

- Closed source
- AI featured browser
- Based on chromium

## Opera GX

![Opera GX overview](./images/opera_gx/overview.avif)

### General Info:

- Closed source
- AI featured browser
- Based on chromium

### Self description:

A browser for gamers

## Orion

![Orion overview](./images/orion/overview.avif)

### General Info:

- Webkit engine

## Phi

![Phi overview](./images/phi/overview.avif)

### General Info:

![Phi size](./images/phi/size.avif)

## Phoebe

![Phoebe overview](./images/phoebe/overview.avif)

## Polypane

![Polypane overview](./images/polypane/overview.avif)

### General Info:

- Paid to use
- Closed source
- Not for daily usage
- Based on chromium

## Safari

![Safari overview](./images/safari/overview.avif)

### General Info:

- Only avaliable for apple sowftware
- Closed source
- Webkit engine

## Servo

![Servo overview](./images/servo/overview.avif)

### General Info:

- Open Source
- Not viable for daily usage
- Has it's own engine, Servo

## Shift

![Shift overview](./images/shift/overview.avif)

### General Info:

- Closed source
- Based on Chromium

## SigmaOS

![SigmaOS ovweview](./images/sigmaOS/overview.avif)

### General Info:

- Avaliable only for MacOS
- Closed source
- Has a paid subscription
- Webkit engine

## Surf

![Surf overview](./images/surf/overview.avif)

### General Info:

- Open source
- AI focused browser

## Tor

![Tor overview](./images/tor/overview.avif)

### General Info:

- Tor protocol support (obviously)
- Open source
- Based on firefox

### Patches:

- Tor protocol
- Improved security

![Tor size](./images/tor/size.avif)

## Ulaa

![Ulaa ovewview](./images/ulaa/overview.avif)

## Ungoogled

![Ungoogled Chromium overview](./images/ungoogled_chromium/overview.avif)

### General Info:

- Based on chromium

### Patches:

- Removal of google services
- Removal of proprietary blobs

## Vivaldi

![Vivaldi overview](./images/vivaldi/overview.avif)

## General Info:

- Baded on chromium

## Waterfox

![Waterfox overview](./images/waterfox/overview.avif)

### General Info:

## Yab

![Yab Overview](./images/yab/overview.avif)

### General Info:

- Electron webview

## Yandex

![yandex overview](./images/yandex/overview.avif)

### General Info:

- Closed source
- Based on chromium

## Zen

![zen overview](./images/zen/overview.avif)

### General Info:

- Mods support ([native](https://zen-browser.app/mods/) or [sine](https://github.com/CosmoCreeper/Sine))
- Vertical tabs
- Based on firefox
- Open source

### Patches:

- betterfox.js
- custom chrome
- memory leak fixes

![Zen size](./images/zen/size.avif)

### Author's Overview

built by the community for the community

## Zephium

![Zephium overview](./images/zephium/overview.avif)

### General Info:

- Tauri webview

![Zephium size](./images/zephium/size.avif)
