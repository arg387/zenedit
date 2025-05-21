# zenedit
zen browser configurations
<br>
<hr>

![GitHub last commit](https://img.shields.io/github/last-commit/arg387/zenedit)
![GitHub watchers](https://img.shields.io/github/watchers/arg387/zenedit)
[![](https://img.shields.io/badge/Download-8A2BE2)](https://github.com/arg387/zenedit/releases/tag/first)
<br>
<hr>

## Macos style button right side
- [x] **Small window style**
<div align="center">
  <figure>
    <img src="https://github.com/arg387/zenedit/blob/main/macos-left-button-small.gif">
  </figure>
  <p>$${\color{lightgreen}**Preview**}$$<p>
</div>

- [x] **Full window style**
<div align="center">
  <figure>
    <img src="https://github.com/arg387/zenedit/blob/main/macos-left-button-full.gif">
  </figure>
  <p>$${\color{lightgreen}**Preview**}$$<p>
</div>

## Instructions
- Make sure to add all the files in the chrome folder.

go to `about:config`, type and click add button as boolean:
| Name   | Set                  | Description                                             |
| ---        | -------------            | -------------                                     |
| `bubble.clean.hide-single-toolbar-icon`       | `true`                | Hide icons in urlbar (single toolbar)|
| `bubble.clean.show-titlebar`       | `true`                | Show titlebar in hover|
| `bubble.clean.pinned-grid`       | `true`                |Change pinned tab to grid style|
| `bubble.clean.show-workspace-name`       | `true`                |Show workspace name indicator|

#### 💠 Optional Tweak
Go to `about:config` and set:
| Name   | Set                  | Description                                             |
| ---        | -------------            | -------------                                     |
| `browser.tabs.groups.enabled`       | `true`                | Enable tab group|
| `zen.theme.content-element-separation`       | `4`                | Thinner web view borders|
| `browser.tabs.allow_transparent_browser`       | `true`                | Allow transparency|
| `widget.windows.mica`       | `true`                | Allow transparency|

For `v1.8b` above if you're transparency not working
go to `about:config` and set:
| Name   | Set                  |
| ---        | -------------            |
| `zen.widget.windows.acrylic`       | `false`                |


## Made with the help of
- ![bubble Clean Zen](https://github.com/nieffka/bubble-clean-zen/)
- ![Zen Catpuccine](https://github.com/catppuccin/zen-browser)
