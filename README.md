# Hide YouTube Playables and Shorts

A small CSS-only extension for Chrome and Edge. It hides YouTube's Playables
shelf by matching the /playables link inside the shelf header.
It also hides Shorts shelves containing /shorts/ video links.
The CSS also applies to shelves YouTube inserts after page navigation or scrolling.
Contains no JavaScript, analytics, or network requests.

## Install

1. Open //extensions
2. Enable Developer mode.
3. Click Load unpacked and select this folder.
4. Refresh your YouTube tab.

For an existing installation, replace the extension files, click Reload on its
extensions-page card, and refresh YouTube.

Disable or remove the extension from the extensions page to restore the shelves.

## Scope and limitations

Targets desktop https://www.youtube.com only.
It does not block game downloads, remove sidebar links, or block direct Shorts playback.
If YouTube changes its shelf markup, the CSS selector may need an update.