---
title: "Notion Boost - Browser extension to make Notion more productive and less distractive"
desc: "Boost Notion productivity with 15+ customizations like outline,small text full width for all,back to top button,hide slash command menu etc"
date: "09-12-2020"
toc: true
---

import logo from "./img/logo.svg";
import boldertext from "./img/boldertext.gif";
import commenthide from "./img/commenthide.gif";
import disableslashmenu from "./img/disableslashmenu.gif";
import header from "./img/header.jpg";
import helpbtn from "./img/helpbtn.gif";
import hideslash from "./img/hideslash.gif";
import outline from "./img/outline.gif";
import firefox_icon from "./img/firefox_icon.png";
import scrollbtn from "./img/scrollbtn.gif";
import toggle from "./img/toggle.gif";
import showHoverText from "./img/showHoverText.gif";
import leftAlignImage from "./img/leftAlignImage.gif";
import hideHiddenColumns from "./img/hideHiddenColumns.gif";
import disablepopup from "./img/disablepopup.gif";
import hidebacklinks from "./img/hidebacklinks.gif";
import hidenotification from "./img/hidenotification.gif";
import moreheight from "./img/moreheight.gif";
import codelines from "./img/codelines.jpg";
import spellcheck from "./img/spellcheck.jpg";
import hideoutline from "./img/hideoutline.gif";
import openfullpage from "./img/openfullpage.gif";
import narrowspace from "./img/narrowspace.gif";
import indentation_lines from "./img/indentation_lines.jpg";
import rollup_clickable from "./img/rollup_clickable.jpg";

<Title logo={logo} txt="Notion Boost" homeURL = "/notion-boost" />

<span className="lead">
  Chrome and Firefox extension to make Notion more productive and less distractive. Add 15+ customizations to Notion like sticky
  outline, small text & full width by default,scroll to top button, hide slash
  command menu, and more.
</span>

<Badges/>

<br/>
<br/>

<NavbarNotion />

## ⬇ Download

- [Chrome / Brave / Edge extension](#chrome--brave--chromium)
- [Firefox addon](#firefox)

## ✅ Currently added features

<details>
  <summary> <h4>Show sticky outline</h4></summary>
  
Show sticky outline (table of contents) for pages that have headings or sub-headings. The outline will be shown on the right side of the page. Very useful for navigating a page with lots of content.

<Img src={outline} type="ss" />

You can also temporarily hide the outline on the current page (until the page refresh)

<Img src={hideoutline} type="ss" />

</details>

<details>
  <summary> <h4>Set small text for all pages</h4></summary>

Set small text for all pages by default. This locally adjusts the text without clicking on the Notion page toggles.

</details>
<details>
  <summary> <h4>Set full width for all pages</h4></summary>

Set full width for all pages by default. This locally adjusts the width without clicking on the Notion page toggles.

</details>
<details>
  <summary> <h4>'Scroll to top' button</h4></summary>

Added button at the bottom-right corner of page for scrolling back to top. Quite useful for lengthy pages. The button will be visible only when the page has scrolled down a bit.

<Img src={scrollbtn} type="ss" />
</details>
<details>
  <summary> <h4>Show full text on hover</h4></summary>

Show full text in table cells on mouse hover.

<Img src={showHoverText} type="ss" />
</details>
<details>
  <summary> <h4>Close Slash command menu after space</h4></summary>

Slash command menu which appears when pressing '/' key will be closed back by pressing the space key.

<Img src={hideslash} type="ss" />
</details>
<details>
  <summary> <h4>Don't show Slash command menu when pressing '/'</h4></summary>

Don't show the Slash command menu when pressing '/' key. Slash command menu will still be shown by clicking + ⁝⁝ icon. This setting can't be enabled along with 'Close Slash command menu after space' and vice-versa.

<Img src={disableslashmenu} type="ss" />
</details>
<details>
  <summary> <h4>Hide floating help button from all pages</h4></summary>

This button is located on the bottom-right corner of pages.

<Img src={helpbtn} type="ss" />
</details>
<details>
  <summary> <h4>Hide 'Hidden columns' in board view</h4></summary>

Truly hide 'Hidden columns' in Kanban board view.

<Img src={hideHiddenColumns} type="ss" />
</details>
<details>
  <summary> <h4>Left align media</h4></summary>

Align document images and videos to left instead of center.

<Img src={leftAlignImage} type="ss" />
</details>
<details>
  <summary> <h4>Bolder text in dark mode</h4></summary>

Fix poorly recognizable bold text when using Notion in dark mode

<Img src={boldertext} type="ss" />
</details>
<details>
  <summary> <h4>Hide comments section from all pages</h4></summary>

Comment section is useless when working solo

<Img src={commenthide} type="ss" />
</details>
<details>
  <summary> <h4>Show code line numbers</h4></summary>

Show line numbers for code blocks

<Img src={codelines} type="ss" />
</details>
<details>
  <summary> <h4>Enable spellcheck inside code blocks</h4></summary>

Show squiggly red lines for any spelling mistakes inside code blocks

<Img src={spellcheck} type="ss" />
</details>
<details>
  <summary> <h4>Don't show popup menu when pasting external links</h4></summary>

Don't show popup menu i.e (dismiss, create bookmark, create embed) when pasting external URLs

<Img src={disablepopup} type="ss" />
</details>
<details>
  <summary> <h4>Hide backlinks</h4></summary>

Hide backlinks section from all pages

<Img src={hidebacklinks} type="ss" />
</details>
<details>
  <summary> <h4>Hide notification icon</h4></summary>

Hide red notification icon from sidebar when it's in closed state and hide notification number from tab title

_(It's a `pro` feauture. [learn more](https://gourav.io/notion-boost/whats-new#announcement))_

<Img src={hidenotification} type="ss" />
</details>
<details>
  <summary> <h4>Add more height to page</h4></summary>

Add more height to page by hiding top padding, image cover, & icon

_(It's a `pro` feauture. [learn more](https://gourav.io/notion-boost/whats-new#announcement))_

<Img src={moreheight} type="ss" />
</details>

<details>
  <summary> <h4>Open full pages instead of preview</h4></summary>

Bypass preview and open full pages of a table, board, etc. by default.

<Img src={openfullpage} type="ss" />
</details>

<details>
  <summary> <h4>Narrow spacing between list items</h4></summary>

Fit more content on screen by reducing space between items in a list, i.e., bullet, checkbox, toggle list, etc.

_(It's a `pro` feauture. [learn more](https://gourav.io/notion-boost/whats-new#announcement))_

<Img src={narrowspace} type="ss" />
</details>

<details>
  <summary> <h4>Add indentation lines to lists</h4></summary>

Add vertical indentation lines to bullet and to-do lists.

<Img src={indentation_lines} type="ss" />
</details>

<details>
  <summary> <h4>Make Rollup URLs clickable</h4></summary>

Make URLs in Rollup property clickable. Works for both: table and as page properties.

_(It's a `pro` feauture. [learn more](https://gourav.io/notion-boost/whats-new#announcement))_

<Img src={rollup_clickable} type="ss" />
</details>

> Missing something? suggest / feedback on [Github](https://github.com/GorvGoyl/Notion-Boost-browser-extension/issues/new)

<span>See{" "}<Link href="/notion-boost/whats-new"><a className="" title="https://gourav.io/notion-boost/whats-new">what's new</a></Link> in the latest update ✨</span>

## ⚙ How to use

#### Chrome / Brave / Chromium

1. Install [Notion Boost Chrome extension](https://chrome.google.com/webstore/detail/notion-boost/eciepnnimnjaojlkcpdpcgbfkpcagahd).
2. Visit any notion page.
3. Click on the extension icon (clickable **only** when you are on a notion page).
4. A popup menu will appear, you can toggle features from there.

#### Microsoft Edge

1. Visit [Notion Boost Chrome extension](https://chrome.google.com/webstore/detail/notion-boost/eciepnnimnjaojlkcpdpcgbfkpcagahd).
2. Allow Edge to add extension from Chrome Web Store.
3. Install Notion Boost extension.
4. Visit any notion page.
5. Click on the extension icon (clickable **only** when you are on a notion page).
6. A popup menu will appear, you can toggle features from there.

#### Firefox

1. Install [Notion Boost Firefox addon](https://addons.mozilla.org/en-US/firefox/addon/notion-boost/).
2. Visit any notion page.
3. Click on the extension icon (it will be visible **inside URL bar** only when you are on a notion page).
4. A popup menu will appear, you can toggle features from there.

<Img src={firefox_icon} type="ss" />

---

### 🖤 Support

<Social />

---

## Who made this?

Notion Boost is made by Gourav Goyal (https://gourav.io). I am a tech founder and productivity freak who relies heavily on Notion to organize things and manage work. I made this extension to make Notion more productive (and less distractive) by filling the gaps which I feel are lacked in the product. I hope you find this extension helpful :)

## Support

Please file a new issue on [Github](https://github.com/GorvGoyl/Notion-Boost-browser-extension/issues/new) in case you have any feedback or suggestions.

## Privacy Policy

Notion Boost extension is an [open-source](https://github.com/GorvGoyl/Notion-Boost-browser-extension) project and has no ads, no analytics, no trackers, and no use of cookies. Furthermore, Notion Boost extension **does not store or send any data** from your Notion account.
