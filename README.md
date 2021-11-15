# PurE-KDE-Theme
This repo contains the PurE theme for KDE Plasma 5: Plasma global theme, Plasma style, color schemes, layout for Latte Dock, and more.

![PurE_Demo_Screen](https://user-images.githubusercontent.com/81539176/141725955-a526ff62-b651-4b3e-a523-860d81a10a56.png)

// What is the PurE KDE theme? //
--
PurE is a customizations series for the KDE Plasma 5 desktop. It aims to give Plasma users a new, modern, and visually attractive experience while still being useful for daily use. Inspired by a certain futuristic videogame (the namesake of this theme), this visual style mostly uses a variety of blue and blueish hues, similar to the default Breeze Light theme, but with more emphasis on transparency, rounded panels, and bold accent colors (mainly yellow and magenta).

// Why use PurE KDE theme? //
--
1. Open Source: Just like all the other themes for KDE Plasma and the Plasma desktop that makes it all possible, the entirety of the code of the theme is openly offered to anyone on the internet under the GPL v3 license. 

2. Based on modern Breeze theme releases: This theme is continuously updated to ensure compatibility with the latest stable Plasma releases.

3. Visually consistent: While the are many third-party themes that change Plasma's looks, few feel as integrated and polished as the default Breeze theme. PurE aims to achieve a level of consistency equal to the excellent default provided by the KDE Plasma team.

4. Made for daily use: I've been privately developing and testing this set of customizations for about one year and a half, to ensure it's optimal for daily use. The beautiful is the practical.

// Components of the repo //
--
The Global theme component ("look-and-feel") enables all the Plasma elements necessary with a single click (Except the Latte Dock and related applets). However, unlike the rest of the components, it's still not ready for release because it's necessary to use KDE Store integration for an optimal experience.

"desktoptheme" contains most of the theme. It defines which system tray icons, panels, widgets, dialogs, buttons, etc. will be used.

"color-schemes" contains the set of colors that Plasma will use.

"konsole" contains the color scheme for the Konsole terminal emulator.

"latte" contains the custom layout for Latte Dock v0.10 and newer.

// Dependencies //
--
To achieve the intended looks, it's necessary to install the following applications or Plasma addons:

Latte Dock - v0.10 or newer. Latte Dock provides panels and docks with advanced customization capabilities. The latest stable version is available from KDE Discover on KDE neon. If you are using a different distro, please check the official development page for more info: https://invent.kde.org/plasma/latte-dock

Lightly App and Window style: I recommend compiling the latest Git version of the master branch, as it has partially solved the infamous Korners issue. Lightly provides a cutting-edge visual style with rounded buttons, casted shadows, and transparency on Qt apps: https://github.com/Luwx/Lightly

Inverse-blue icons: You may install from the corresponding System Settings menu, or download from https://store.kde.org/p/1344791/. The Global theme will take care of automatically installing the icons on your system in the future.

WinStyle11 Indicator for Latte Dock: Used in PurE latte layout: https://store.kde.org/p/1621535

Event Calendar: Also used for the latte layout: https://www.pling.com/p/998901

Latte Separator: https://www.pling.com/p/1295376

Media Player/Controller +: https://www.pling.com/p/1317639

Window Buttons Applet: Don't install from the "Add Widgets/Get hot stuff" menu, compile from source instead: https://github.com/psifidotos/applet-window-buttons

// Special thanks and credits //
--
https://github.com/KDE/breeze - KDE: For providing the gorgeous and practical Plasma desktop and themes.
https://gitlab.com/jomada/moe-theme - Jorge/Jomada: For his amazing Moe theme, which serves both as a base and inspiration for multiple components on this theme.
https://github.com/varlesh/rounded - Varlesh: For their excellent system tray icons, used in this theme to achieve a more futuristic look.
https://www.opencode.net/adhe/neve4plasma - ADHE: For their beautiful Plasma splash, which is included and slightly modified for this theme.
https://unsplash.com/photos/nvmmUzpQcVs - Redd Angelo/reddalec: For the breathtaking photograph that was modified by me and used as wallpaper.
