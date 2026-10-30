# zenedit
zen browser configurations
compatible with zen browser latest Version 1.24b
<br>
<hr>

<div align="center">
  
  ![GitHub last commit](https://img.shields.io/github/last-commit/arg387/zenedit)
  ![GitHub watchers](https://img.shields.io/github/watchers/arg387/zenedit)
  [![](https://img.shields.io/badge/OLD-Download-8A2BE2)](https://github.com/arg387/zenedit/releases/tag/v1.2)
  ![visitors](https://visitor-badge.laobi.icu/badge?page_id=arg387.zenedit)
  
</div>


<br>
<hr>

## Macos style button right side

<div align="center">
  
  <img width="228" height="78" alt="Recording 2026-10-28 212341" src="https://github.com/user-attachments/assets/1a8c08b7-d5d7-432e-856c-c4648c4f5cf1" />
  <br>  
</div>
<br>
<div align="center">
  <img width="310" height="104" alt="Recording 2026-10-28 210132" src="https://github.com/user-attachments/assets/51263248-2f3a-4eaa-bb00-b801a98996b5" />
  <br>
  <img src="https://img.shields.io/badge/Preview-a6da95">
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
- Transparent background is only working for url interface,extension menu, findbar and for application menu. I don't recommend you to use third party apps for transparency since i am also not using it. It's your own choice if you want to.
- If you want to add a new application menu icon first go to the chrome file and add the icon there. Then just go to the `userChrome.css` file and add the icon name in the quotation part of the code below `menu button added` comment.


## Previews
<div align="center">
    <br>
    <img width="345" height="362" alt="Screenshot 2025-11-04 184534" src="https://github.com/user-attachments/assets/453936ca-b0da-4ebe-a939-6f80bd7b567d" />
    <img width="1919" height="1072" alt="Screenshot 2026-03-21 172716" src="https://github.com/user-attachments/assets/ec5a11d8-0075-4359-9fe6-776352b16438" />
    <img width="1916" height="1048" alt="image" src="https://github.com/user-attachments/assets/663ae51c-1493-45f7-b29c-d042add7aadf" />
    <img width="1912" height="1048" alt="image" src="https://github.com/user-attachments/assets/9eeec3af-195c-49a7-b18b-decf8e1c9926" />
    <img width="1917" height="1042" alt="image" src="https://github.com/user-attachments/assets/01098f76-190f-4412-81b7-79dba02f1c80" />
  </figure>
</div>
<br>

<img width="692" height="388" alt="Recording 2026-05-05 155530" src="https://github.com/user-attachments/assets/10a0c23e-1f01-42f5-b1df-d267443d20a8" />



<br>


### Important Tweak
Make sure to follow these steps below especially important one to ensure the theme works fine.
go to search bar and type `about:config` and click add button as boolean[We are creating new configs here]:

| Name   | Set                  | Description                                             |
| ---        | -------------            | -------------                                     |
| `bubble.clean.hide-single-toolbar-icon`       | `true`                | Hide icons in urlbar (single toolbar)|
| `bubble.clean.show-titlebar`       | `true`                | Show titlebar in hover|
| `bubble.clean.pinned-grid`       | `true`                |Change pinned tab to grid style|
| `bubble.clean.show-workspace-name`       | `true`                |Show workspace name indicator|
| `devtools.debugger.remote-enabled`       | `true`                |enable the Browser Developer Tools|
| `devtools.chrome.enabled`       | `true`                |enable the Browser Developer Tools|
| `toolkit.legacyUserProfileCustomizations.stylesheets`       | `true`                |This will enable userChrome.css file|

#### 💠 Optional Tweak
Go to `about:config` and set:
| Name   | Set                  | Description                                             |
| ---        | -------------            | -------------                                     |
| `browser.tabs.groups.enabled`       | `true`                | Enable tab group|
| `zen.theme.content-element-separation`       | `4`                | Thinner web view borders|
| `browser.tabs.allow_transparent_browser`       | `true`                | Allow transparency|
| `widget.windows.mica`       | `true`                | Allow transparency|




## Made with the help of
- ![bubble Clean Zen](https://github.com/nieffka/bubble-clean-zen/)
- ![Zen Catppuccin](https://github.com/catppuccin/zen-browser)

**If you like it please give the repo a star. If you face any bugs or glich pls inform me in issue section by opening a new issue. [ Make sure to add proper descriptions and images, video or gif in the raised issue.].** 
<br>
<hr>


<div align="center">
    <a href="https://git.io/typing-svg">
        <img alt="thanks for your visit" src="https://readme-typing-svg.herokuapp.com?font=Roboto+Slab&color=%237E3ACE&size=24&center=true&vCenter=true&width=300&lines=Thanks+for+your+visit!" >
    </a>
</div>
                 
