Active Go — website (hileonapp.com/activego)
=============================================

WHAT'S HERE
  activego/
    index.html                  -> hileonapp.com/activego/
    privacy-policy/index.html    -> hileonapp.com/activego/privacy-policy/
    data-deletion/index.html     -> hileonapp.com/activego/data-deletion/
    assets/activego.css          (shared styles)

These are static files. No build step. Self-contained: the logo and the map
illustration are inline SVG, and the only external request is Google Fonts
(Plus Jakarta Sans). All internal links are relative, so the folder works at
any mount point.

DEPLOY (GitHub Pages, custom domain hileonapp.com)
  1. Copy the whole `activego/` folder into the root of your hileonapp Pages repo
     (the same repo that already serves hileonapp.com).
  2. Commit and push.
  3. It goes live at:
       https://hileonapp.com/activego/
       https://hileonapp.com/activego/privacy-policy/
       https://hileonapp.com/activego/data-deletion/

  Clean URLs work because each sub-page is its own folder with an index.html.

BEFORE YOU SHIP — one thing to fill in
  The "Get it on Google Play" buttons use href="#" as a placeholder.
  When the Play listing is live, search index.html for:
       href="#"
  and replace each with your Play Store URL. (There are two: the hero button
  and the bottom call-to-action.)

PLAY CONSOLE
  - Privacy policy URL:  https://hileonapp.com/activego/privacy-policy/
  - Data deletion URL:   https://hileonapp.com/activego/data-deletion/
  Add both in the Play Console listing + Data safety section.

CONTACT
  support@hileonapp.com is used on every page.
