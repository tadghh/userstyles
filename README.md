# Description
The following user style modifies Firefox's design language. Repurposing the area for the tab's favicon into an action zone, reducing the amount of actions that appear on tabs, while also aiming to reduce overall eye movement. The idea is this will result in less distractions, by having less buttons for your eyes to track. Additionally leveraging transitions and animations in an effort to sustain focus and follow through with their actions.

## Features
- Favicon changes have been smoothed out
- Tab close icon is only shown on hover
    - Replaces favicon
- When the tab's title overflows a marquee effect will be applied
    - Animation starts after hovering over the tab for 600 ms
- CSS Variables to customize delays/durations

## Notes
- This was created using Firefox 124.0.2
- Legacy customization needs to be enabled [⦗Guide⦘](https://winaero.com/enable-loading-userchrome-css-usercontent-css-firefox/)
- Set the UI density to compact for the best experience [⦗Guide⦘](https://winaero.com/mozilla-decided-to-keep-compact-density-in-firefox-but-hide-it-by-default/)

## Preview
| Title             |            Preview             |
| :---------------- | :----------------------------: |
| Favicon tab close | ![favicon tab close preview](./previews/tab-favicon-actions-1.gif) |
| Media Icons       | ![media icon effects preview](./previews/tab-favicon-actions-2.gif) |
| Marquee           | ![marquee effect preview](./previews/tab-favicon-actions-3.gif)  |
