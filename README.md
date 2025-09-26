# zenedit
zen browser configurations
<br>
<hr>

<div align="center">
  
  ![GitHub last commit](https://img.shields.io/github/last-commit/arg387/zenedit)
  ![GitHub watchers](https://img.shields.io/github/watchers/arg387/zenedit)
  [![](https://img.shields.io/badge/Download-8A2BE2)](https://github.com/arg387/zenedit/archive/refs/heads/main.zip)
  ![visitors](https://visitor-badge.laobi.icu/badge?page_id=arg387.zenedit)
  
</div>



<br>
<hr>

## Macos style button right side
- [x] **Small window style**
<div align="center">
  <figure>
    <img src="https://github.com/arg387/zenedit/blob/main/macos-left-button-small.gif">
  </figure>
  <br>
  <figure><img src="https://img.shields.io/badge/Preview-a6da95"></figure>
</div>

- [x] **Full window style**
<div align="center">
  <figure>
    <img src="https://github.com/arg387/zenedit/blob/main/macos-left-button-full.gif">
  </figure>
  <br>
  <figure><img src="https://img.shields.io/badge/Preview-a6da95"></figure>
</div>

## Icons added
- [x] **Application Menu Button**
<div align="center">
   <figure>
    <img src="https://github.com/arg387/zenedit/blob/main/Screenshot%202025-05-22%20142023.png">
  </figure>
  <br>
  <figure><img src="https://img.shields.io/badge/Preview-a6da95"></figure>
</div>

## Instructions
- Make sure to add all the files in the chrome folder.
- Transparent background is only working for url interface,extension menu, bookmark sidebar, findbar, topbar and for application menu but not for others whether you are using `Mica For Everyone` App or not.
- If you want to add a new application menu icon first go to the chrome file and add the icon there. Then just go to the `userChrome.css` file and add the icon name in the quotation part of the code below `menu button added` comment.
- ![Screenshot 2025-05-22 163345](https://github.com/user-attachments/assets/f537d72b-eaaa-4455-ac8f-51ad066cf935) If you use keyboard for tab switching then use `Ctrl + position of the tab in descension order in number(including essential tabs and pinned tabs)`[This keyboard shortcut is for windows. As for macos check the keyboard shortcuts i am not a mac user so i don't know.]. For example- The keyboard shortcut of sound wave showing tab is `Ctrl + 7`.
- If you want to edit styles by yourself go to search bar and type `about:config` . Then you have to set `devtools.chrome.enabled` to `true` and `devtools.debugger.remote-enabled` to `true`. I don't know why we need to do this but zen may change this settings in the future. I will update it if i know. Please inform me about it if any of you know about any update on it in future.
- you can switch to compact mode by using `Ctrl+Alt+C`. For bookmarks hidden/show use `ctrl+shift+B`[For windows only, i am not a mac user. So mac might have something different for this. Check keyboard shortcuts in settings page for more info.]

## Previews
<div align="center">
  <figure>
    <img src="https://img.shields.io/badge/Updated-✓-8A2BE2"><img src="https://img.shields.io/badge/21_September_2025-blue">
  </figure>
</div>
<br>

![Screen Recording 2025-09-26 122433](https://github.com/user-attachments/assets/aadb581f-b5c6-4a81-8bfe-57ce41de7eca)
<br>



go to search bar and type `about:config` and click add button as boolean[We are creating new configs here]:
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
- ![[Config] Now playing indicator](https://github.com/benstone326/zen-mods?tab=readme-ov-file)
- ![download.bg](https://github.com/different55/download.bg)

**If you like it please give the repo a star. If you face any bugs or glich pls inform me in issue section by opening a new issue. [ Make sure to add proper descriptions and images, video or gif in the raised issue.].** 
<br>
<hr>


<div align="center">
    <a href="https://git.io/typing-svg">
        <img alt="thanks for your visit" src="https://readme-typing-svg.herokuapp.com?font=Roboto+Slab&color=%237E3ACE&size=24&center=true&vCenter=true&width=300&lines=Thanks+for+your+visit!" >
    </a>
</div>
                 
