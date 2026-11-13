# Juxtematic

The redesign from Juxtopposed. Check out the original [video][design-video] & [design][design-figma].

> [!TIP]
> With [Stylus][stylus], you can use this theme as a userstyle. [Click here][userstyle] to install.

> [!NOTE]
> The design makes everything bigger, and, as a consequence, doesn't support smaller window sizes; it has only been tested on maximized windows where applicable.

![Main Window](https://github.com/ricewind012/juxtematic/raw/master/assets/preview/main-window.png)

## Roadmap

- [ ] Client
  - [x] Dialogs/modals/notifications
  - [ ] Friends & chat
  - [x] Library
  - [x] Overlay
  - [ ] Millennium
    - [ ] Options (maybe)
    - [x] Change Window Params (only system titlebar)
- [ ] Web
  - [ ] Account preferences
  - [x] App hub
  - [x] App page
  - [x] Dialogs/modals
  - [x] Forum
  - [x] Friend activity
  - [x] Group
  - [x] Guides
  - [x] Market
  - [ ] Points shop
  - [x] Profile
    - [x] Friends
    - [ ] Games
    - [ ] Inventory
    - [x] Settings
    - [x] Trade offers
  - [x] Shopping cart
  - [x] Store home
  - [x] Store menu
  - [ ] Store search
  - [ ] Wishlist
  - [x] Workshop

### Problems

| Where                       | Why                                         |
| --------------------------- | ------------------------------------------- |
| Web -> Account preferences  | Only old pages                              |
| Web -> Points shop          | idgaf                                       |
| Web -> Profile -> Inventory | Item info is not themed                     |
| Web -> Market (beta)        | New filter dialog & item info not yet done. |

Some things like the store menu appear only on new pages, since on the old ones the class names do not match, and require Valve to rewrite the old pages entirely in React to be themed.

[design-figma]: https://www.figma.com/community/file/1302616100790619521/steam-redesign
[design-video]: https://www.youtube.com/watch?v=cDY2p1CTkPo
[stylus]: https://add0n.com/stylus.html
[userstyle]: https://raw.githubusercontent.com/ricewind012/juxtematic/refs/heads/master/import_web.user.css
