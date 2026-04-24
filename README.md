# Skiovox on 141
## The skiovox exploit for ChromeOS version 141

if you know what you're doing then you can [Open a skiovox window](https://skiovox-141.pages.dev/open) here.

# steps
1. Find a **website kiosk** (one that *shows the url* while its loading.)
2. Find some way to navigate away from the main page and to a search engine, like google.
    - if you cannot find a webview for your kiosk join the [crosbreaker discord server](https://discord.gg/nrMVY29MUb) and go to the exploit thread, ping **@xz8f** and I will try to find a webview for you.
3. after getting on google (or any search engine) find some sort of text field, most likely the search bar.
4. in the text field type the following HTML: ```<script>window.open("javascript:alert();");</script>``` and copy it to the clipboard.
5. now get to [Real-time HTML editor](https://htmledit.squarefree.com/)
6. Paste the HTML you copied and it should open a chrome window.

# Common ways to navigate to google
1. Google Privacy and terms.
  - Scroll all the way down and click the grey google hyperlink at the bottom.
2. XSS shit
  - a lot of educational websites are badly designed leading to xss. You can try just messing with random text input fields and seeing if you get anything.
3. Captchas
  - Google captchas have a privacy and terms hyperlink, click it then follow method 1

more will be added eventually.

## Join the [discord server](https://discord.gg/nrMVY29MUb) if you need any help or have questions.
## also check out [crosbreaker.com](https://crosbreaker.com)

:3

# Helper extension
You need to use [the new manifest v3 extension](https://github.com/AceOfSpades1061/skiovox-helper_mv3)
### github.com is blocked :(
Use `https://cdn.crosbreaker.dev/skiovox-helper_mv3-main.zip` instead, this is a complete copy of [the repo](https://github.com/AceOfSpades1061/skiovox-helper_mv3) rehosted.
