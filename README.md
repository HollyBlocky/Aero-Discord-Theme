# Aero-Discord-Theme
Experimental mishmash of various public themes and CSS. Use with Vencord or Equicord.

These theme files are intended to be used with light mode.
----
#### Installation:
1. Put the following in your Quick CSS:
```
/* @import url("https://epos05.github.io/cleaner-discord-theme/theme.css"); */
@import url("https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/hide_store_nitro_tabs.css");
@import url('https://raw.githubusercontent.com/moonself/Vencord-Repos/refs/heads/main/Message%20Actions%20Hover');
@import url('https://raw.githubusercontent.com/moonself/Vencord-Repos/refs/heads/main/Profile%20Popout%20Actions%20Hover');
@import url("https://rdf1337.github.io/DiscordSnippets/DisableActivity/main.css");
@import url("https://raw.githubusercontent.com/MEWPASCO/discord-ui-tweaks/refs/heads/main/tweaks.css");
@import url("https://cdn.jsdelivr.net/gh/Overimagine1/old-discord-font/OldDiscordFont.theme.css");

/* Discriminator Plugin */
:root{
  --Discriminator-ShowBoth: "#4722"
}

/* Hide Titlebar */
/*
.c38106a3f0c3ca76-bar {
    display: none;
}*/
/*
.edbb22df99c39831-title {
  display: none !important;
}

:root {
    --custom-app-top-bar-height: 0px;
}

/*div.trailing_c38106
{
  display: none;
}*/
/*
nav.wrapper_ef3116
{
  padding-top: 0px;
  padding-bottom: 0px;
}
*/

/* Server Banner */
div[class*="bannerVisible"] img[class^="bannerImg-"] {
    display: none;
}

div[class*="bannerVisible"] div[class*="animatedContainer"] {
    /* display: none; */
    position: static;
    margin-top: 0px;
    
    
}

div[aria-label="Channels"] > div > div[style*="84px"] {
    display: none !important;
}

/* RolesBorder */
.roleName_af3987 {
  color: hsl(0,0%,95%) !important;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.3) !important;
}

/* Hide Arrows */
/* Target the container and hide it. the random numbers at the end may be a problem. they likely change it for each update*/
.backForwardButtons__63abb {
    display: none !important;
}
/* Hides any div where the class starts with 'backForwardButtons' */
div[class^="backForwardButtons"] {
    display: none !important;
}
```
2. Install all files in the theme folder locally and enable them. **Importing any of these local files, and online theming, does not work completely for a reason I am unsure of.**
3. If your friends list looks weird (entirely blue) then you should try reenabling the local themes in a different order
----
