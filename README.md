# Aero-Discord-Theme
Experimental mishmash of various public themes and CSS. Use with Vencord or Equicord.

These theme files are intended to be used with light mode.
----
#### Installation:
1. Put the following in your Quick CSS:
```
@import url("https://raw.githubusercontent.com/axberu/vencord-css-snippets/main/hide_store_nitro_tabs.css");

/* Hide Titlebar */
/*
.c38106a3f0c3ca76-bar {
    display: none;
}*/

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
    margin-top: -50px;
    
    
}


div[aria-label="Channels"] > div > div[style*="84px"] {
    display: none !important;
}
```
2. Install all files locally and enable them. **Importing any of these local files, and online theming, does not work completely for a reason I am unsure of.**
3. Enable the following as online themes:
```
https://raw.githubusercontent.com/numoder/DSN7/refs/heads/master/dsn7.theme.css
https://raw.githubusercontent.com/KrstlSkll69/vc-snippets/main/OtherStuff/better-social-links.css
```
----
