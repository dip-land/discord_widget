An easy to use customizable Discord widget.

# Usage
Simply add `<script src="https://cdn.jsdelivr.net/gh/dip-land/discord_widget/index.js"></script>` to the body or head of your website then add `<discord-widget id=""></discord-widget>` wherever you want a widget.

## Parameters
| Attribute        | Description             | Required | Default Value                                                                              |
| ---------------- | ----------------------- | -------- | ------------------------------------------------------------------------------------------ |
| id               | Server ID               | [X]      | null                                                                                       |
| width            | Widget Width            | [ ]      | 350px                                                                                      |
| height           | Widget Height           | [ ]      | 500px                                                                                      |
| logo             | Widget Logo*            | [ ]      | https://cdn.jsdelivr.net/gh/dip-land/discord_widget/discord-logo-white.svg                 |
| footerText       | Footer Text             | [ ]      |                                                                                            |
| color            | Header Color            | [ ]      | #5865f2                                                                                     |
| buttonColor      | Join Button Color       | [ ]      | **                                                                                         |
| buttonHoverColor | Join Button Hover Color | [ ]      | ***                                                                                        |
| backgroundColor  | Main Background Color   | [ ]      | #0c0c0d                                                                                     |
| textColor        | Main Text Color         | [ ]      | #ffffff                                                                                     |
| statusColor      | User Status Text Color  | [ ]      | #858585                                                                                     |
* logo recommended size is 248x68 (can really be any size but css resizes it to 124x34)
** buttonColor is set to the same value of color if not set by user
*** buttonHoverColor will auto be generated based on buttonColor or color if its not manually set