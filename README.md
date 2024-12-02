# web-highlighter.user.js
*An [userscript](https://en.wikipedia.org/wiki/Userscript) that allows the ability to highlight the selected text in the webpages.*

[Download](https://greasyfork.org/en/scripts/519563-web-highlighter) | [Demo](https://youtu.be/yyk4MGJROms?si=x4l-gi68d8un5-K7)

**Disclaimer:** It has only been tested in Safari using [Userscript App](https://github.com/quoid/userscripts) and for Wikipedia. Looking for contributors ;)

## What it does?

- [x] Automatically highlights the selected text.
- [x] Pop-up to select different highlighter colors.
- [x] Saves locally and reloads when refreshing the webpage
- [x] View all highlights in the present website. Use `Cmd+Shift+v` in Mac and `Ctrl+Shift+v` in Windows.
- [x] If the highlighted text is present on the webpage, it is indicated by adding yellow dots at the top right corner of the webpage. 
- [ ] Works in all websites
- [ ] Syncs across different devices.
- [ ] Import and export all highlights from various websites.
- [ ] Local webpage to display all highlights in one place; highlights from various websites.
- [ ] Works in all touchscreen devices (i.e. iPad, tablet and so on)
- [ ] Add hideable sticky notes

... *new ideas are welcome in the [discussion](https://github.com/physicslog/web-highlighter.user.js/discussions/)*


## Want to contribute?
*You can pick any one of the unfinished task from "What it does?" or fix the below bugs or refactor the userscript or any cosmetic changes, and submit the pull request.*

### Bugs & Improvements
- [ ] If the highlighted text contains tags like `<a>`, `<b>`, `<i>`, and so on, it doesn’t show up after refreshing the page. But show up in the "View all highlights in the present website.". 
- [ ] Only works for Wikipedia.
- [x] The newly created highlights don’t show up, and I have to refresh the page to see them.
  - [ ] Highlights also the popup which should not allow.
  - [x] Ability to delete highlights from this popup.
  - [ ] Refactoring is needed!

---

*I hope you find this userscript helpful and enjoyable. Cheers!*
