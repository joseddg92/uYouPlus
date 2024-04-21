# My own instructions

Instructions at:
https://github.com/qnblackcat/uYouPlus/discussions/1383

Copied here just in case:

This first part is for the folks who run the GitHub page for uYou and any other variations of it. I've got some suggestions. Freeloaders (like myself) skip down to Instructions. I want to preface this by saying that I got the decrypted IPA from the repository available through qnblackcat/Dat Nguyen, and that same IPA ended up working, so I know I did that part right. Google Drive links do not seem to work, however; I tried every imaginable link Google Drive gives you, and none of them worked. Switching to Dropbox and getting the download link from that site worked for me. We need more detailed instructions, so here's my little contribution.

Instructions:

Log in to GitHub or create an account and then sign in.
Search uYouPlus on Google > click "qnblackcat/uYouPlus - GitHub" > click "Fork" on the top right > Click the green "Create Fork" button. On the top left, you should now see "your user name / uYouPlus".
Go to the "Actions" tab near the top of the page. Click the green "I understand my workflows..." blah blah.
Click "Build and Release uYouPlus" on the left-hand side. Let this webpage sit as is and open a new tab.
Search qnblackcat on Google > Click the result that says "Nguyen Dat qnblackcat" > Click the "Decrypted-IPAs" repository > OneDrive > select the "YouTube" file.
Select your desired YouTube IPA. For the more recent ones, make sure to sort by "Newer to Older" under the "Modified" tab.
Download the IPA to your desktop or a place you'll remember.
Log in to Dropbox (Yes, it has to be Dropbox) or create a Dropbox account if you do not have one. Once again, yes, it has to be Dropbox.
8a) If you created a Dropbox account, be sure to verify your email shortly after creating it. This step is necessary!
Upload the decrypted IPA to Dropbox. On the icon for the IPA, click "Share" > make sure "Anyone with this link can view" shows up > click the blue "Copy Link" button.
Go back to the GitHub page and click "Run workflow" on the right-hand side.
Paste the link from Dropbox into the second box. At the end of the link, CHANGE "dl=0" to "dl=1". That is, just delete the 0 and type 1.
Run workflow and let sit until a green check appears.
Click the "uYouPlus" text on the top left > Click the bold text that says "Releases" on the right-hand side of the page. Your IPA should be there.
Edit: Messed up my numbers lol.


# uYouPlus

![Image 2](https://github.com/qnblackcat/uYouPlus/assets/77606385/c1a1c58a-5d4d-48a6-bb98-d00086719ccc)
<!--![Image](https://github.com/therealFoxster/uYouPlus/assets/77606385/eb34d3e3-a679-45d0-b2e5-01fdd459ce63)-->

***

<p align="center">
    <img src="https://img.shields.io/badge/Platform-iOS%20%7C%20iPadOS%2014.0%2B-yellow" alt="Badge"/>
    <a href="https://github.com/qnblackcat/uYouPlus/wiki/FAQs"><img src="https://img.shields.io/badge/Question%3F-FAQ-yellow" alt="Badge"></img></a>
    <a href="https://github.com/qnblackcat/uYouPlus/wiki/FAQs"><img src="https://custom-icon-badges.demolab.com/badge/translate-blue.svg?logo=translate&logoColor=white" alt="Badge"></img></a>
</p>

<p align="center">
    <a href="https://github.com/qnblackcat/uYouPlus/releases/latest"><img src="https://custom-icon-badges.demolab.com/github/v/release/qnblackcat/uYouPlus?color=brightgreen&label=Latest%20release" alt="Badge"></img></a>
    <a href="https://github.com/qnblackcat/uYouPlus/releases/latest"><img src="https://img.shields.io/github/downloads/qnblackcat/uYouPlus/total?label=Download" alt="Badge"></img></a>
    <a href="https://github.com/qnblackcat/uYouPlus/commit"><img src="https://custom-icon-badges.demolab.com/github/last-commit/qnblackcat/uYouPlus?logo=history&logoColor=white&label=Last commit" alt="Badge"></img></a>
    <a href="https://github.com/qnblackcat/uYouPlus/issues"><img src="https://custom-icon-badges.demolab.com/github/issues-raw/qnblackcat/uYouPlus?logo=issue-opened&label=Issues" alt="Badge"></img></a>

</p>

<p align="center">
   <img src="https://img.shields.io/github/stars/qnblackcat/uYouPlus?style=social" alt="Badge"/>
   <img src="https://img.shields.io/github/forks/qnblackcat/uYouPlus?style=social" alt="Badge"/>
   <a href="https://github.com/qnblackcat/uYouPlus#support-the-developers"><img src="https://img.shields.io/badge/-Support-lightgrey?style=social&logo=paypal" alt="Badge"></img></a>
</p>

> [!NOTE]
> uYouPlus is a **modified version** of uYou. **Please DO NOT bother MiRO92 with issues unrelated to uYou!**

## Table of contents

* [Download](#download)
* [Installation](#installation)
* [Features](#features)
* [Credits](#credits)
* [Support the developers!](#support-the-developers)
* [FAQs](#faqs)
* [Building](#building)

## Download

- The latest version of **uYouPlus** can be found under [Releases](https://github.com/qnblackcat/uYouPlus/releases/latest).
- **Compatibility:** Requires iOS/iPadOS 14.0 or later.
- For AltStore user: 

  - My official AltStore repo: https://qnblackcat.github.io/AltStore/

  - [Open in AltStore (v19.08.2-3.0.3)](http://tinyurl.com/4vzwk5hx) - It will take a while to install because AltStore needs to download the IPA first.

<details>
  <summary>Version information (last updated: Feb 27, 2024)</summary>

| **Tweaks/App** | **Developer** | **Version** | **Open source** |
| - | - | :-: | :-:  |
| **YouTube** | Google Inc | 19.08.2 | ✖︎ |
| [uYou](https://github.com/MiRO92/uYou-for-YouTube) | [MiRO92](https://twitter.com/miro92) | 3.0.3 | ✖︎ |
| **Open in YouTube** | [CokePokes](https://github.com/CokePokes) | 1.2 | [✔︎](https://github.com/CokePokes/YoutubeExtensions) |
| **iSponsorBlock** | [Galactic-Dev](https://github.com/Galactic-Dev) | 1.2.2 | [✔︎](https://github.com/Galactic-Dev/iSponsorBlock) |
| **BigYTMiniPlayer** | [Galactic-Dev](https://github.com/Galactic-Dev) | 1.0-1 | [✔︎](https://github.com/Galactic-Dev/BigYTMiniPlayer) |
| **YTNoHoverCards** | [level3tjg](https://twitter.com/level3tjg) | 0.0.3 | [✔︎](https://github.com/level3tjg/YTNoHoverCards) |
| **YTMiniplayerEnabler** | [level3tjg](https://twitter.com/level3tjg) | 0.0.2 | [✔︎](https://github.com/level3tjg/YTMiniplayerEnabler) |
| **DontEatMyContent** | [therealFoxster](https://github.com/therealFoxster) | 1.1.4 | [✔︎](https://github.com/therealFoxster/DontEatMyContent) |
| **YTSpeed** | [Lyvendia](https://github.com/Lyvendia) | 1.0.1 | [✔︎](https://github.com/Lyvendia/YTSpeed) |
| **Alderis Color Picker** | [HASHBANG Productions](https://github.com/hbang) | 1.2.3 | [✔︎](https://github.com/hbang/Alderis) |
| **YTUHD** | [PoomSmart](https://twitter.com/poomsmart) | 1.4.3 | [✔︎](https://github.com/PoomSmart/YTUHD) |
| **YouPiP** | [PoomSmart](https://twitter.com/poomsmart) | 1.8.4 | [✔︎](https://github.com/PoomSmart/YouPiP) |
| **IAmYouTube** | [PoomSmart](https://twitter.com/poomsmart) | 1.3.0 | [✔︎](https://github.com/PoomSmart/IAmYouTube) |
| **YTABConfig** | [PoomSmart](https://twitter.com/poomsmart) | 1.7.0 | [✔︎](https://github.com/PoomSmart/YTABConfig) |
| **YTReExplore** | [PoomSmart](https://twitter.com/poomsmart) | 1.0.2 | [✔︎](https://github.com/PoomSmart/YTReExplore) |
| **NoYTPremium** | [PoomSmart](https://twitter.com/poomsmart) | 1.0.4 | [✔︎](https://github.com/PoomSmart/NoYTPremium) |
| **YTNoPaidPromo** | [PoomSmart](https://twitter.com/poomsmart) | 1.0.0 | [✔︎](https://github.com/PoomSmart/YTNoPaidPromo) |
| **YouRememberCaption** | [PoomSmart](https://twitter.com/poomsmart) | 1.0.0 | [✔︎](https://poomsmart.github.io/repo/depictions/youremembercaption.html) |
| **Return YouTube Dislike** | [PoomSmart](https://twitter.com/poomsmart) | 1.11.6 | [✔︎](https://github.com/PoomSmart/Return-YouTube-Dislikes) |
| **YouMute** | [PoomSmart](https://twitter.com/poomsmart) | 1.2.1-3 | [✔︎](https://github.com/PoomSmart/YouMute) |
| **YouQuality** | [PoomSmart](https://twitter.com/poomsmart) | 1.1.4-2 | [✔︎](https://github.com/PoomSmart/YouQuality) |
| **YTVideoOverlay** | [PoomSmart](https://twitter.com/poomsmart) | 1.1.6 | [✔︎](https://github.com/PoomSmart/YTVideoOverlay) |

</details>

## Installation

See [Installation - Wiki](https://github.com/qnblackcat/uYouPlus/wiki/Installation).

## Features

1. **[uYou](https://miro92.com/repo/depictions/?p=com.miro.uyou):** Enhance your YouTube experience.

2. **[iSponsorBlock](https://github.com/Galactic-Dev/iSponsorBlock):** A jailbreak tweak that implements the SponsorBlock API to skip sponsorships in YouTube videos.

3. **[YouPiP](https://poomsmart.github.io/repo/depictions/youpip):** Enable **native PiP** in iOS YouTube app.

4. **[YTUHD](https://poomsmart.github.io/repo/depictions/ytuhd):** Unlock 1440p (2K) and 2160p (4K) resolutions in iOS YouTube app.

<details>
  <summary>And many more!</summary>

5. **[YTClassicVideoQuality](https://poomsmart.github.io/repo/depictions/ytclassicvideoquality):** Revert to the original video quality selector in YouTube app.

6. **[YTNoHoverCards](https://level3tjg.me/repo/depictions/?p=com.level3tjg.ytnohovercards):** Disable overlay at the end of YouTube videos.

7. **[YouRememberCaption](https://poomsmart.github.io/repo/depictions/youremembercaption)**: Make YouTube remember your video caption setting, if not already.

8. **[NoYTPremium](https://poomsmart.github.io/repo/depictions/noytpremium)**: Remove YouTube Premium upsell alerts.

9. **[YTSpeed](http://cydia.saurik.com/package/com.lyvendia.ytspeed/)**: Simple playback speed tweak for the YouTube app on jailbroken iOS/iPadOS devices.

10. **[YTMiniplayerEnabler](https://level3tjg.me/repo/depictions/?p=com.level3tjg.ytminiplayerenabler)**: Enable Miniplayer for all YouTube videos.

11. **[DontEatMyContent](https://github.com/therealFoxster/DontEatMyContent)**: Prevent the notch/Dynamic Island from munching on 2:1 video content in YouTube.

12. **[YTABConfig](https://poomsmart.github.io/repo/depictions/ytabconfig)**: Configure A/B settings in iOS YouTube app.

13. **[YouMute](https://poomsmart.github.io/repo/depictions/youmute)**: Mute/unmute videos in iOS YouTube directly.

14. **[YouQuality](https://poomsmart.github.io/repo/depictions/youquality)**: View and change video quality in YouTube app from the video overlay.

</details>

## Credits

- Special thanks to all the developers who have contributed to uYouPlus! 

<table id='credits'>
<tr align='center'>
    <td id='miro92'>
        <a href='https://github.com/MiRO92'>
            <img src='https://github.com/MiRO92.png' width='140px;' style='border-radius: 99999px;'>
        </a>
        <br>
        <a href='https://twitter.com/miro92'>MiRO92</a>
    </td>
    <td id='poomsmart'>
        <a href='https://github.com/PoomSmart'>
            <img src='https://github.com/PoomSmart.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/poomsmart'>PoomSmart</a>
    </td>
    <td id='level3tjg'>
        <a href='https://github.com/level3tjg'>
            <img src='https://github.com/level3tjg.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/level3tjg'>level3tjg</a>
    </td>
    <td id='bandarHL'>
        <a href='https://github.com/BandarHL'>
            <img src='https://github.com/BandarHL.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/bandarhl'>BandarHelal</a>
    </td>
    <td id='galactic-dev'>
        <a href='https://github.com/Galactic-Dev'>
            <img src='https://github.com/Galactic-Dev.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/dev_galactic'>galactic</a>
    </td>
</tr>
    
<tr align='center'>
    <td id='julioverne'>
        <a href='https://github.com/julioverne'>
            <img src='https://github.com/julioverne.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/ijulioverne'>julioverne</a>
    </td>
    <td id='hbang'>
        <a href='https://github.com/hbang'>
            <img src='https://github.com/hbang.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/hashbang'>HASHBANG</a>
    </td>
    <td id='lyvendia'>
        <a href='https://github.com/Lyvendia'>
            <img src='https://github.com/Lyvendia.png' width='140px;'>
        </a>
        <br>
        <a href='https://github.com/Lyvendia'>Lyvendia</a>
    </td>
    <td id='foxster'>
        <a href='https://github.com/therealFoxster'>
            <img src='https://github.com/therealFoxster.png' width='140px;'>
        </a>
        <br>
        <a href='https://github.com/therealFoxster'>Foxster</a>
    </td>
    <td id='ichitaso'>
        <a href='https://github.com/ichitaso'>
            <img src='https://github.com/ichitaso.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/ichitaso'>ichitaso</a>
    </td>
</tr>
  
<tr align='center'>
    <td id='ahmed-bafkir'>
        <a href='https://github.com/AhmedBafkir'>
            <img src='https://github.com/AhmedBafkir.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/Peaceful_0'>Ahmed Bafkir</a>
    </td>
    <td id='cokepokes'>
        <a href='https://github.com/CokePokes'>
            <img src='https://github.com/CokePokes.png' width='140px;'>
        </a>
        <br>
        <a href='https://twitter.com/cokepokes'>CokePokes</a>
    </td>
    <td id='isnackable'>
        <a href='https://github.com/ISnackable'>
            <img src='https://github.com/ISnackable.png' width='140px;'>
        </a>
        <br>
        <a href='https://isnackable.me/'>Tommy Teo</a>
    </td>
    <td id='theos-team'>
        <a href='https://github.com/theos/theos'>
            <img src='https://github.com/theos.png' width='140px;'>
        </a>
        <br>
        <a href='https://theos.dev'>theos</a>
    </td>
    <td id='qnblackcat'>
        <a href='https://github.com/qnblackcat'>
            <img src='https://github.com/qnblackcat.png' width='140px;'>
        </a>
        <br>
        <a href='https://https://twitter.com/t70438299'>qnblackcat</a>
    </td>
</tr>
</table>

## Support the developers!

- **MiRO92**: https://github.com/MiRO92/uYou-for-YouTube#support
- **PoomSmart**: https://poomsmart.github.io
- **level3tjg**: https://ko-fi.com/level3tjg
- **BandarHL**: https://www.paypal.com/paypalme/BandarHL
- **julioverne**: https://www.patreon.com/julioverne
- **Galactic-Dev**:   
  - Paypal: https://www.paypal.com/paypalme/DBrett684 
  - Venmo: https://venmo.com/u/DavidBrett

## FAQs

See [FAQs - Wiki](https://github.com/qnblackcat/uYouPlus/wiki/FAQs).

## Building

See [Building - Wiki](https://github.com/qnblackcat/uYouPlus/wiki/Building).
