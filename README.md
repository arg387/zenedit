# zenedit
zen browser configurations
<br>
<hr>

![GitHub last commit](https://img.shields.io/github/last-commit/arg387/zenedit)
![GitHub watchers](https://img.shields.io/github/watchers/arg387/zenedit)
[![](https://img.shields.io/badge/Download-8A2BE2)](https://github.com/arg387/zenedit/archive/refs/heads/main.zip)
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

## Icons added
- [x] **Application Menu Button**
<div align="center">
   <figure>
    <img src="https://github.com/arg387/zenedit/blob/main/Screenshot%202025-05-22%20142023.png">
  </figure>
</div>

## Instructions
- Make sure to add all the files in the chrome folder.
- Transparent background is only working for url interface,extension menu, bookmark sidebar, findbar and for application menu but not for others whether you are using `Mica For Everyone` App or not.
- If you want to add a new application menu icon first go to the chrome file and add the icon there. Then just go to the `userChrome.css` file and add the icon name in the quotation part of the code below `menu button added` comment.
- ![Screenshot 2025-05-22 163345](https://github.com/user-attachments/assets/f537d72b-eaaa-4455-ac8f-51ad066cf935) Make sure to click around the space of the sound wave icon showing here if you want to change from any tab to the sound wave showing tab. If you use keyboard for tab switching then use `Ctrl + position of the tab in descension order in number(including essential tabs and pinned tabs)`[This keyboard shortcut is for windows as for macos check the keyboard shortcuts i am not a mac user so i don't know.]. For example- The keyboard shortcut of sound wave showing tab is `Ctrl + 7`.
- If you want to edit styles by yourself you need to set `devtools.chrome.enabled` to `true`. I don't know why we need to do this but zen may change this settings in the future. I will update it if i know. Please inform me about it if any of you know about any update on it in future.

## Previews
[![](https://img.shields.io/badge/updated_21_May_2025-8A2BE2)](https://github.com/arg387/zenedit/releases/tag/first)
<br>
![Recording 2025-05-21 195810(1)](https://github.com/user-attachments/assets/c505db34-802b-4a1b-9199-67f8862b6951)


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
- ![Zen Catppuccin](https://github.com/catppuccin/zen-browser)

**If you like it please give the repos a star.** 
<br>
<hr>


<div align="center">
    <a href="https://git.io/typing-svg">
        <img alt="thanks for your visit" src="https://readme-typing-svg.herokuapp.com?font=Roboto+Slab&color=%237E3ACE&size=24&center=true&vCenter=true&width=300&lines=Thanks+for+your+visit!" >
    </a>
</div>
                 
