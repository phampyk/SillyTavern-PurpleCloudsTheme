# SillyTavern-PurpleCloudsTheme
A SillyTavern theme inspired by soft pastel purples, and probably my love for sailor moon.

![Main page](/.github/img/screenshot-main.png)

My first theme! I was really excited the moment I knew I could add themes. I was inspired by [Selenis' Lavander blossoms theme](https://discord.com/channels/1100685673633153084/1344396649245577307) I installed it first and started tinkering... until I made it look completely different. It has the same type of tones, I darkened them slightly and matched them to the backgrounds. I also have to thank her for the [original Info Board](https://discord.com/channels/1100685673633153084/1344396649245577307/1344396685983350884) and I adapted it for a more cozy/slice of life theme. I have both regex for her original plus the one I edited. It really helps the AI keep more track and consistency on the RP.

## How to use
First of all you need the extension [Custom theme style inputs](https://github.com/IceFog72/SillyTavern-CustomThemeStyleInputs) and [CCS snippets](https://github.com/LenAnderson/SillyTavern-CssSnippets) so all the colors, fonts and CSS load properly, but it gives you more control to edit the theme, if you want to adapt it more to your liking. All the colors can be changed, except for some hardcoded colors on the info board.

Once you have both extensions downloaded, in the **"User Settings"** tab import the theme from the folder `theme` called `Purple Clouds.json` and on the **"Custom CSS"** section there's a new button ![css snippet button](/.github/img/CSSsnippetbutton.png). It will open a window where you can import the file `CSSsnippet-[Purple_Clouds].json`. The theme is fully installed now!

![Settings page](/.github/img/screenshot-settings.png)

In the screenshot you can see the extra three colors, and you can change the placement of the QR buttons, and having the default fonts if you're not keen into the cutesy ones I added. The CSS has some annotations too, in case you want to change something like the banner or remove the rainbow avatar frame, which by the way, adapts to all avatar styles!

## Info Board

![chat page](/.github/img/screenshot-chat.png)

To use the info board, you need to be using the **"Chat Completion"** API, import the [extra prompt](https://discord.com/channels/1100685673633153084/1344396649245577307/1344496317438890044) on the **"AI Response Configuration"** and the regex file from the folder `info board` goes into the **"Extensions"** tab.

In the `info board` folder is the default regex for Selenis' original prompt called `regex-[info_board]__default.json` or you can find my edited prompt ready to import at `prompt-[info_board]__cozy.json` and the regex to import is `regex-[info_board]__cozy.json`

> [!NOTE]
> All the credit goes to @Selenis, I only edited the prompt slightly. Find Selenis' themes and prompt in SillyTavern discord

### Sources and credits
- @Selenis for making the theme that inspired this, and [Rivelle](https://github.com/RivelleDays) for hyping me up when I shared screenshots on discord.
- [IceFog](https://github.com/IceFog72/) for the handy [Custom theme style inputs](https://github.com/IceFog72/SillyTavern-CustomThemeStyleInputs) and the input on the theme.
- [LenAnderson](https://github.com/LenAnderson) for the [CSS snippet extension](https://github.com/LenAnderson/SillyTavern-CssSnippets)
- [qwerasd205](https://github.com/qwerasd205) for the most adorable monospaced font ever [Annotation Mono](https://qwerasd205.github.io/AnnotationMono/).
- [Looney patterns](https://looneypatterns.com/) for the stars SVG background on the info board.
- [RawPixel](https://www.rawpixel.com/image/18423757/png-pastel-kawaii-divider-flowers-background-purple) for the header png.
- [Ana Tudor](https://codepen.io/thebabydino/pen/bGPMOpJ) for the css rainbow border.
- [Comehope](https://codepen.io/comehope/pen/YLqbXy) for the css stripes border.
- 480 Design for their [Solar icon set](https://icon-sets.iconify.design/solar/?suffixes=Bold%20Duotone)

### Disclaimer
The backgrounds were generated with ComfyUI by me, you can use them if you want, or if you prefer something else... it's totally up to you. The one I use in the captures is `Purple_Clouds_05.png`.
