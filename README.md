@import url("https://accrazed.github.io/YoRHA-UI-BetterDiscord/font/stylesheet.css");
@keyframes pulsingBackground {
  0% {
    background-color: var(--color-low);
  }
  20% {
    background-color: var(--color-low);
    opacity: 100%;
  }
  50% {
    background-color: var(--color-low-trans);
    opacity: 75%;
  }
  80% {
    background-color: var(--color-low);
    opacity: 100%;
  }
  100% {
    background-color: var(--color-low);
  }
}
:root {
  --header-primary: var(--color-low) !important;
  --header-secondary: var(--color-low) !important;
  --text-normal: var(--color-low);
  --channels-default: var(--color-low);
  --interactive-normal: var(--color-low);
  --interactive-hover: var(--color-low);
  --interactive-active: var(--color-low);
  --text-link: var(--color-alert);
  --text-muted: var(--color-low);
  --interactive-muted: var(--color-mid);
  --background-primary: var(--color-high);
  --background-secondary: var(--color-high);
  --background-secondary-alt: var(--color-high);
  --background-tertiary: var(--color-high-trans);
  --background-accent: #4f545c;
  --background-floating: var(--color-high);
  --background-mobile-primary: #36393f;
  --background-mobile-secondary: #2f3136;
  --background-modifier-hover: var(--color-mid);
  --background-modifier-active: rgba(79, 84, 92, 0.24);
  --background-modifier-selected: rgba(79, 84, 92, 0.32);
  --background-modifier-accent: hsla(0, 0%, 100%, 0.06);
  --background-mentioned: var(--color-alert-trans);
  --background-mentioned-hover: var(--color-alert-trans);
  --background-message-hover: rgba(4, 4, 5, 0.07);
  --background-help-warning: rgba(250, 166, 26, 0.1);
  --background-help-info: rgba(0, 176, 244, 0.1);
  --scrollbar-thin-thumb: var(--color-low);
  --scrollbar-thin-track: transparent;
  --scrollbar-auto-thumb: var(--color-low);
  --scrollbar-auto-track: transparent;
  --scrollbar-auto-scrollbar-color-thumb: var(--color-low);
  --scrollbar-auto-scrollbar-color-track: transparent;
  --elevation-stroke: 0 0 0 1px rgba(4, 4, 5, 0.15);
  --elevation-low: 0 1px 0 rgba(4, 4, 5, 0.2), 0 1.5px 0 rgba(6, 6, 7, 0.05),
      0 2px 0 rgba(4, 4, 5, 0.05);
  --elevation-medium: 0 4px 4px rgba(0, 0, 0, 0.16);
  --elevation-high: 0 8px 16px rgba(0, 0, 0, 0.24);
  --logo-primary: var(--color-low);
  --focus-primary: var(--color-alert);
  --guild-header-text-shadow: 0 1px 1px rgba(0, 0, 0, 0.4);
  --channeltextarea-background: var(--color-high);
  --activity-card-background: #202225;
  --textbox-markdown-syntax: #8e9297;
  --deprecated-card-bg: var(--color-high);
  --deprecated-card-editable-bg: rgba(32, 34, 37, 0.3);
  --deprecated-store-bg: #36393f;
  --deprecated-quickswitcher-input-background: #72767d;
  --deprecated-quickswitcher-input-placeholder: hsla(0, 0%, 100%, 0.3);
  --deprecated-text-input-bg: rgba(0, 0, 0, 0.1);
  --deprecated-text-input-border: rgba(0, 0, 0, 0.3);
  --deprecated-text-input-border-hover: #040405;
  --deprecated-text-input-border-disabled: #202225;
  --deprecated-text-input-prefix: #dcddde;
}

.app-2rEoOp,
.bg-h5JY_x {
  background-color: transparent;
}

.wordmarkWindows-1v0lYD {
  color: transparent;
}

.winButtonClose-1HsbF-:hover {
  transition: background-color 0.2s, color 0.2s ease;
  color: var(--color-high);
  background: var(--color-alert);
}

.winButtonMinMax-PBQ2gm:hover {
  transition: background-color 0.2s, color 0.2s ease;
  color: var(--color-high);
  background: var(--color-low);
}

.emojiRowText-2j4TNM {
  color: var(--color-mid);
}

.theme-dark .emojiAliasPlaceholder-3H_iZA {
  color: var(--color-low);
}

.theme-dark .emojiAliasInput-1y-NBz .emojiInput-1aLNse,
.input-cIJ7To {
  background-color: var(--color-high);
  border-radius: 0;
  border: 2px solid var(--color-low);
  color: var(--color-low);
}
.theme-dark .emojiAliasInput-1y-NBz .emojiInput-1aLNse:hover,
.input-cIJ7To:hover {
  border-color: var(--color-mid);
}
.theme-dark .emojiAliasInput-1y-NBz .emojiInput-1aLNse.focused-1mmYsC, .theme-dark .emojiAliasInput-1y-NBz .emojiInput-1aLNse:focus,
.input-cIJ7To.focused-1mmYsC,
.input-cIJ7To:focus {
  border-color: var(--color-alert);
}
.theme-dark .emojiAliasInput-1y-NBz .emojiInput-1aLNse::placeholder,
.input-cIJ7To::placeholder {
  color: var(--color-mid);
}

.bd-modal-wrapper .footer button,
.theme-dark .button-2DhvE9,
.theme-dark .watchButton-2SbJEo,
.theme-dark .lookFilled-1Gx00P.colorPrimary-3b3xI6,
.lookInverted-2D7oAl.colorGreen-29iAKY,
.lookInverted-2D7oAl.colorBrand-3pXr91,
.container-UC8Ug1,
.lookOutlined-3sRXeN.colorGreen-29iAKY,
.lookOutlined-3sRXeN.colorBrand-3pXr91,
.lookFilled-1Gx00P.colorPrimary-3b3xI6,
.lookFilled-1Gx00P.colorGrey-2DXtkV,
.lookFilled-1Gx00P.colorBrand-3pXr91,
.lookFilled-1Gx00P.colorBrand-3pXr91:disabled {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-low);
  color: var(--color-high);
}
.bd-modal-wrapper .footer button:hover, .bd-modal-wrapper .footer button:active,
.theme-dark .button-2DhvE9:hover,
.theme-dark .button-2DhvE9:active,
.theme-dark .watchButton-2SbJEo:hover,
.theme-dark .watchButton-2SbJEo:active,
.theme-dark .lookFilled-1Gx00P.colorPrimary-3b3xI6:hover,
.theme-dark .lookFilled-1Gx00P.colorPrimary-3b3xI6:active,
.lookInverted-2D7oAl.colorGreen-29iAKY:hover,
.lookInverted-2D7oAl.colorGreen-29iAKY:active,
.lookInverted-2D7oAl.colorBrand-3pXr91:hover,
.lookInverted-2D7oAl.colorBrand-3pXr91:active,
.container-UC8Ug1:hover,
.container-UC8Ug1:active,
.lookOutlined-3sRXeN.colorGreen-29iAKY:hover,
.lookOutlined-3sRXeN.colorGreen-29iAKY:active,
.lookOutlined-3sRXeN.colorBrand-3pXr91:hover,
.lookOutlined-3sRXeN.colorBrand-3pXr91:active,
.lookFilled-1Gx00P.colorPrimary-3b3xI6:hover,
.lookFilled-1Gx00P.colorPrimary-3b3xI6:active,
.lookFilled-1Gx00P.colorGrey-2DXtkV:hover,
.lookFilled-1Gx00P.colorGrey-2DXtkV:active,
.lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.lookFilled-1Gx00P.colorBrand-3pXr91:active,
.lookFilled-1Gx00P.colorBrand-3pXr91:disabled:hover,
.lookFilled-1Gx00P.colorBrand-3pXr91:disabled:active {
  border-color: transparent !important;
  background-color: var(--color-mid) !important;
  color: var(--color-high) !important;
}

#bd-settingspane-container .bd-pfbtn,
.theme-dark .lookOutlined-3sRXeN.colorPrimary-3b3xI6,
.jumpButton-JkYoYK,
.button-1YfofB.buttonColor-7qQbGO.buttonActive-3FrkXp,
.lookFilled-1Gx00P.colorGreen-29iAKY,
.lookFilled-1Gx00P.colorRed-1TFJan,
.lookOutlined-3sRXeN.colorRed-1TFJan {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-alert);
  color: var(--color-high);
}
#bd-settingspane-container .bd-pfbtn:hover, #bd-settingspane-container .bd-pfbtn:active,
.theme-dark .lookOutlined-3sRXeN.colorPrimary-3b3xI6:hover,
.theme-dark .lookOutlined-3sRXeN.colorPrimary-3b3xI6:active,
.jumpButton-JkYoYK:hover,
.jumpButton-JkYoYK:active,
.button-1YfofB.buttonColor-7qQbGO.buttonActive-3FrkXp:hover,
.button-1YfofB.buttonColor-7qQbGO.buttonActive-3FrkXp:active,
.lookFilled-1Gx00P.colorGreen-29iAKY:hover,
.lookFilled-1Gx00P.colorGreen-29iAKY:active,
.lookFilled-1Gx00P.colorRed-1TFJan:hover,
.lookFilled-1Gx00P.colorRed-1TFJan:active,
.lookOutlined-3sRXeN.colorRed-1TFJan:hover,
.lookOutlined-3sRXeN.colorRed-1TFJan:active {
  border-color: transparent !important;
  background-color: var(--color-low) !important;
  color: var(--color-high) !important;
}

.lookOutlined-3sRXeN.colorWhite-rEQuAQ {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-alert);
  color: var(--color-high);
}
.lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover, .lookOutlined-3sRXeN.colorWhite-rEQuAQ:active {
  border-color: transparent !important;
  background-color: var(--color-high) !important;
  color: var(--color-low) !important;
}

.container-3auIfb[style="opacity: 1; background-color: rgb(114, 118, 125);"] {
  background: var(--color-mid) !important;
}
.container-3auIfb[style="opacity: 1; background-color: rgb(114, 118, 125);"] path {
  fill: var(--color-mid);
}

.container-3auIfb[style="opacity: 1; background-color: rgb(67, 181, 129);"] {
  background: var(--color-low) !important;
}
.container-3auIfb[style="opacity: 1; background-color: rgb(67, 181, 129);"] path {
  fill: var(--color-low);
}

.bd-switch {
  background-color: var(--color-mid);
}
.bd-switch::after {
  background-color: var(--color-high);
}

.bd-switch-checked {
  background-color: var(--color-low);
}

.item-26Dhrx {
  transition: color 0.2s, background-color 0.2s;
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-high);
  color: var(--color-low);
}
.item-26Dhrx:hover, .item-26Dhrx:active {
  border-color: transparent !important;
  background-color: var(--color-low) !important;
  color: var(--color-high) !important;
}
.item-26Dhrx[aria-checked=true] {
  background: var(--color-alert);
  color: var(--color-high);
}
.item-26Dhrx[aria-checked=true] .radioIconForeground-XwlXQN {
  color: var(--color-high);
}
.item-26Dhrx .radioBar-bMNUI- {
  border-radius: 0;
}

.css-1kj8ui-container div {
  border-radius: 0;
}
.css-1kj8ui-container .css-6fzn47-control {
  border: 2px solid var(--color-alert);
  background-color: var(--color-high);
}
.css-1kj8ui-container .css-17e1tep-control,
.css-1kj8ui-container .css-gvi9bl-control {
  border: 2px solid var(--color-low);
  background-color: var(--color-high);
}
.css-1kj8ui-container .css-o3gndj-placeholder,
.css-1kj8ui-container .css-1yz4bi9-option,
.css-1kj8ui-container .css-ku6vh5-indicatorContainer,
.css-1kj8ui-container .css-4h5swf-singleValue {
  color: var(--color-low);
}
.css-1kj8ui-container .css-3vaxre-menu {
  border: 2px solid var(--color-low);
  background-color: var(--color-high);
  box-shadow: none;
}
.css-1kj8ui-container .css-rzbxvl-option {
  background-color: var(--color-low);
  color: var(--color-high);
}
.css-1kj8ui-container .css-rzbxvl-option .colorStandard-2KCXvj,
.css-1kj8ui-container .css-rzbxvl-option .subtitle-2yP_Eh {
  color: var(--color-high);
}
.css-1kj8ui-container .css-1ba14n5-option {
  background-color: var(--color-alert);
  color: var(--color-high);
}

.barFill-23-gu- {
  background: var(--color-alert);
}

.theme-dark .bar-2Qqk5Z {
  background: var(--color-low);
}

.grabber-3mFHz2 {
  background: var(--color-high);
  border: 1px solid var(--color-low);
  border-radius: 0;
  box-shadow: none;
}

#app-mount,
.title-3sZWYQ,
.modeDefault-3a2Ph1,
.container-1r6BKw,
.titleBar-AC4pGV {
  cursor: url("https://accrazed.github.io/YoRHA-UI-BetterDiscord/Pointers/Hack_Normal_Select_v2.cur"), default !important;
}

.timestamp-3ZCmNB.latin24CompactTimeStamp-2V7XIQ,
.searchBar-3dMhjb,
.contents-2mQqc9,
textarea,
.textAreaSlate-1ZzRVj div div,
input {
  cursor: url("https://accrazed.github.io/YoRHA-UI-BetterDiscord/Pointers/Hack_Text_Select_v2.cur"), default !important;
}

a,
button,
.folder-21wGz3,
.item-3eFBNF,
.css-gvi9bl-control,
.css-rzbxvl-option,
.css-1ba14n5-option,
.css-ku6vh5-indicatorContainer,
.avatar-1BDn8e,
.fileInput-23-d-3,
.container-3auIfb,
.input-rwLH4i,
.profileBadge-2niAfJ,
.item-1tOPte,
.container-3baos1 .avatar-SmRMf2,
.wrapper-25eVIn,
.result-oB0z--,
.labelClickable-11AuB8,
.buttonWrapper-1ZmCpA,
[role=button],
[role=button] header,
[type=checkbox],
label,
.item-26Dhrx,
.additionalActionsIcon-1FoUlE,
.clickable-1JJAn8:hover .layout-2DM8Md,
.actionIcon-PgcMM2,
.clickable-3Ya1ho,
.friendsTable-133bsv .friendsRow-2yicud {
  cursor: url("https://accrazed.github.io/YoRHA-UI-BetterDiscord/Pointers/Hack_Link_Select_v2.cur"), default !important;
}

.grabber-3mFHz2 {
  cursor: url("https://accrazed.github.io/YoRHA-UI-BetterDiscord/Pointers/Hack_Horizontal_Resize_v2.cur"), default !important;
}

.disabled,
.innerDisabled-1YTFPN,
.disabled-BrLY9Y,
.disabled-2HSEFa,
.modeLocked-25wLHj,
.modeLocked-25wLHj .mainContent-u_9PKf {
  cursor: url("https://accrazed.github.io/YoRHA-UI-BetterDiscord/Pointers/Hack_Unavailable_v2.cur"), default !important;
}

.divider-3FBTu8,
.theme-dark .children-19S4PO:after,
.container-1r6BKw.themed-ANHk51 {
  background: transparent;
}

.platform-win .sidebar-2K8pFh {
  border-radius: 0;
}

.header-2o-2hj,
.content-yTz4x3:before,
.searchBar-6Kv8R2 {
  box-shadow: none;
}

.clickable-25tGDB .header-2V-4Sw:hover,
.selected-31Nl7x .header-2V-4Sw {
  background-color: var(--color-low);
  color: var(--color-high);
}

.name-3YKhmS,
.title-29uC1r {
  letter-spacing: 1px;
  text-shadow: 3px 4px 0 var(--color-mid);
  padding-right: 3px;
  margin: 0;
}

.colorStreamerMode-2SJAUN,
.akaBadge-1M-1Gw {
  box-shadow: none;
  background: var(--color-alert);
  color: var(--color-high);
}

.notice-3bPHh- {
  border-radius: 0;
}

.title-3qD0b- .children-19S4PO .iconWrapper-2OrFZ1 {
  margin: 0 5px;
}
.title-3qD0b- .children-19S4PO .icon-22AiRD {
  margin: 6px 0px;
  width: 16px;
  height: 16px;
  color: var(--color-high);
  background: var(--color-low);
}
.title-3qD0b- .children-19S4PO path:first-child {
  background-color: var(--color-low);
  fill: var(--color-low);
}

.topPill-30KHOu .themed-OHr7kt.item-PXvHYJ:hover,
.topPill-30KHOu .themed-OHr7kt.selected-3s45Ha.item-PXvHYJ {
  border-radius: 0;
  background-color: var(--color-low);
  color: var(--color-high);
}

.theme-dark #bd-settings-sidebar .ui-tab-bar-item, .theme-dark #bd-settings-sidebar .ui-tab-bar-header {
  color: var(--color-low);
}
.theme-dark #bd-settings-sidebar .ui-tab-bar-separator {
  background-color: transparent;
}
.theme-dark #bd-settingspane-container .ui-switch-item h3,
.theme-dark #bd-settingspane-container .ui-switch-item .style-description,
.theme-dark #bd-settingspane-container h2.ui-form-title {
  border: none;
  color: var(--color-low);
}
.theme-dark .bd-select-options {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
  border: none;
}
.theme-dark .bd-select-options .bd-select-option {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-low);
  color: var(--color-high);
}
.theme-dark .bd-select-options .bd-select-option:hover, .theme-dark .bd-select-options .bd-select-option:active {
  border-color: transparent !important;
  background-color: var(--color-high) !important;
  color: var(--color-low) !important;
}
.theme-dark .bd-select-wrapper {
  color: var(--color-low-trans);
}
.theme-dark .bd-select-wrapper .bd-select {
  color: var(--color-low);
}
.theme-dark .bd-select-wrapper .bd-select-arrow {
  fill: var(--color-low);
}
.theme-dark .bd-select-wrapper label {
  opacity: 1;
}
.theme-dark .bd-addon-list a {
  color: var(--color-alert);
}
.theme-dark .bd-addon-list .bd-addon-card {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.theme-dark .bd-addon-list .bd-addon-card .bda-header,
.theme-dark .bd-addon-list .bd-addon-card .bda-description {
  color: var(--color-low);
  border: none;
}
.theme-dark .bd-search-wrapper {
  background-color: var(--color-low);
  border-radius: 0;
}
.theme-dark .bd-search-wrapper .bd-search {
  color: var(--color-high-trans);
}
.theme-dark .bd-search-wrapper .bd-search::placeholder {
  color: var(--color-high-trans);
}

.bd-modal-wrapper .tab-bar-container .tab-bar-item {
  color: var(--color-low) !important;
}

.wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9,
.wrapper-1BJsBx:hover .childWrapper-anI2G9,
.childWrapper-anI2G9 {
  background-color: transparent;
  color: transparent;
}

.homeIcon-tEMBK1,
.tutorialContainer-1v44GL .wrapper-25eVIn,
.tutorialContainer-1v44GL .svg-1X37T1 {
  height: 57px;
  width: 48px;
}

.tutorialContainer-1v44GL .svg-1X37T1 {
  animation-name: y-spin;
  animation-duration: 4s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
}

@keyframes y-spin {
  0% {
    transform: rotateY(0deg);
  }
  100% {
    transform: rotateY(360deg);
  }
}
.iconSize-2tmqqh {
  -webkit-mask: url("https://discord.com/assets/c30220448097b064286a8759a9b6c4af.svg");
          mask: url("https://discord.com/assets/c30220448097b064286a8759a9b6c4af.svg");
  background: var(--color-alert) !important;
}

foreignObject[mask="url(#svg-mask-status-dnd)"] .status-1AY8sU {
  background-color: var(--color-alert) !important;
}

.iconBadge-2wi9r4.participating-NBGDkr,
.iconBadge-qZ4Ksk {
  background-color: var(--color-alert);
}

.strikethrough-1n4ekb {
  color: var(--color-alert);
}

.theme-dark .overlayToggleIconOn-3UNmty .fill-1ugeBG,
.overlayToggleIconOff-1kT42w .fill-1ugeBG,
[fill*="#F04747"],
[fill*="#7289da"] {
  fill: var(--color-alert) !important;
}

[style*="background-color: rgb(240, 71, 71);"] {
  background-color: var(--color-alert) !important;
}

[style*="color: rgb(114, 137, 218);"] {
  color: var(--color-alert) !important;
}

[style*="background-color: rgb(114, 137, 218);"] {
  background-color: var(--color-low) !important;
}

.theme-dark .avatarUploaderIndicator-2G-aIZ {
  background-color: var(--color-mid);
  border: 2px solid var(--color-low);
}

.theme-dark .actionButton-VzECiy {
  color: var(--color-low);
}

.pointerEvents-2zdfdO[mask="url(#svg-mask-status-dnd)"] {
  fill: var(--color-alert);
}

path[d="M14 8C14 7.44772 13.5523 7 13 7H9.76001L10.3657 3.58738C10.4201 3.28107 10.1845 3 9.87344 3H8.88907C8.64664 3 8.43914 3.17391 8.39677 3.41262L7.76001 7H4.18011C3.93722 7 3.72946 7.17456 3.68759 7.41381L3.51259 8.41381C3.45905 8.71977 3.69449 9 4.00511 9H7.41001L6.35001 15H2.77011C2.52722 15 2.31946 15.1746 2.27759 15.4138L2.10259 16.4138C2.04905 16.7198 2.28449 17 2.59511 17H6.00001L5.39427 20.4126C5.3399 20.7189 5.57547 21 5.88657 21H6.87094C7.11337 21 7.32088 20.8261 7.36325 20.5874L8.00001 17H14L13.3943 20.4126C13.3399 20.7189 13.5755 21 13.8866 21H14.8709C15.1134 21 15.3209 20.8261 15.3632 20.5874L16 17H19.5799C19.8228 17 20.0306 16.8254 20.0724 16.5862L20.2474 15.5862C20.301 15.2802 20.0655 15 19.7549 15H16.35L16.6758 13.1558C16.7823 12.5529 16.3186 12 15.7063 12C15.2286 12 14.8199 12.3429 14.7368 12.8133L14.3504 15H8.35045L9.41045 9H13C13.5523 9 14 8.55228 14 8Z"] + path[d="M21.025 5V4C21.025 2.88 20.05 2 19 2C17.95 2 17 2.88 17 4V5C16.4477 5 16 5.44772 16 6V9C16 9.55228 16.4477 10 17 10H19H21C21.5523 10 22 9.55228 22 9V5.975C22 5.43652 21.5635 5 21.025 5ZM20 5H18V4C18 3.42857 18.4667 3 19 3C19.5333 3 20 3.42857 20 4V5Z"],
path[d="M14 8C14 7.44772 13.5523 7 13 7H9.76001L10.3657 3.58738C10.4201 3.28107 10.1845 3 9.87344 3H8.88907C8.64664 3 8.43914 3.17391 8.39677 3.41262L7.76001 7H4.18011C3.93722 7 3.72946 7.17456 3.68759 7.41381L3.51259 8.41381C3.45905 8.71977 3.69449 9 4.00511 9H7.41001L6.35001 15H2.77011C2.52722 15 2.31946 15.1746 2.27759 15.4138L2.10259 16.4138C2.04905 16.7198 2.28449 17 2.59511 17H6.00001L5.39427 20.4126C5.3399 20.7189 5.57547 21 5.88657 21H6.87094C7.11337 21 7.32088 20.8261 7.36325 20.5874L8.00001 17H14L13.3943 20.4126C13.3399 20.7189 13.5755 21 13.8866 21H14.8709C15.1134 21 15.3209 20.8261 15.3632 20.5874L16 17H19.5799C19.8228 17 20.0306 16.8254 20.0724 16.5862L20.2474 15.5862C20.301 15.2802 20.0655 15 19.7549 15H16.35L16.6758 13.1558C16.7823 12.5529 16.3186 12 15.7063 12C15.2286 12 14.8199 12.3429 14.7368 12.8133L14.3504 15H8.35045L9.41045 9H13C13.5523 9 14 8.55228 14 8Z"] + path[d="M19.8914 3.80204L22.2438 8.55654C22.5726 9.22119 22.0891 9.99999 21.3475 10L16.6179 10C15.8745 10 15.391 9.21769 15.7235 8.55279L18.1007 3.79829C18.4701 3.05951 19.5251 3.06172 19.8914 3.80204ZM18.4998 5H19.4999V7.5H18.4999L18.4998 5ZM18.4998 8.49887C18.4998 8.77589 18.7238 9 18.9998 9C19.2759 9 19.4999 8.77589 19.4999 8.49887C19.4999 8.22224 19.2759 7.99773 18.9998 7.99773C18.7238 7.99773 18.4998 8.22224 18.4998 8.49887Z"] {
  transform: translateX(-108%) translateY(0%) scale(2);
}

.unread-2lAfLh,
.panels-j1Uci_,
.wrapper-2jXpOf:hover .content-1x5b-n,
.modeSelected-346R90 .content-1x5b-n,
.modeSelected-346R90:hover .content-1x5b-n,
.container-3w7J-x {
  background: transparent;
}

.header-2V-4Sw {
  box-shadow: none;
}

.unread-1xRYoj {
  color: var(--color-high);
  background: var(--color-alert);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.button-14-BFJ {
  border-radius: 0;
  border-color: transparent;
  background-color: transparent;
  color: var(--color-low);
}
.button-14-BFJ:hover, .button-14-BFJ:active {
  border-color: transparent !important;
  background-color: var(--color-low) !important;
  color: var(--color-high) !important;
}

.wrapper-2jXpOf {
  height: 30px;
  margin-bottom: 4px;
}
.wrapper-2jXpOf.modeLocked-25wLHj, .wrapper-2jXpOf.modeMuted-onO3r- {
  opacity: 50%;
}
.wrapper-2jXpOf.modeLocked-25wLHj .icon-1DeIlz,
.wrapper-2jXpOf.modeLocked-25wLHj .name-23GUGE, .wrapper-2jXpOf.modeMuted-onO3r- .icon-1DeIlz,
.wrapper-2jXpOf.modeMuted-onO3r- .name-23GUGE {
  color: var(--color-low);
}
.wrapper-2jXpOf.modeLocked-25wLHj {
  cursor: disabled;
}
.wrapper-2jXpOf .icon-1DeIlz {
  transition: color 0.2s, background-color 0.2s;
  height: 12px;
  width: 12px;
  z-index: 1;
  background-color: var(--color-low);
}
.wrapper-2jXpOf .icon-1DeIlz path[d="M33 34.5833V7.49998H35V36.6666H9C6.791 36.6666 5 34.801 5 32.5V7.49998C5 5.19894 6.791 3.33331 9 3.33331H31V30.4166H9C7.8955 30.4166 7 31.3485 7 32.5C7 33.6515 7.8955 34.5833 9 34.5833H33ZM23.9718 9.99998L15.8889 17.9915L12.7086 14.8441L10 17.5058L15.8885 23.3333L26.6667 12.6669L23.9718 9.99998Z"],
.wrapper-2jXpOf .icon-1DeIlz path[d="M19.1 4V5.12659L4.85 8.26447V18.1176C4.85 18.5496 5.1464 18.9252 5.5701 19.0315L9.3701 19.9727C9.4461 19.9906 9.524 20 9.6 20C9.89545 20 10.1776 19.8635 10.36 19.6235L12.7065 16.5242L19.1 17.9304V19.0588H21V4H19.1ZM9.2181 17.9944L6.75 17.3826V15.2113L10.6706 16.0753L9.2181 17.9944Z"],
.wrapper-2jXpOf .icon-1DeIlz path[d="M15 12C15 12.0007 15 12.0013 15 12.002C15 12.553 14.551 13.002 14 13.002V15.002C15.654 15.002 17 13.657 17 12.002C17 12.0013 17 12.0007 17 12H15ZM19 12C19 12.0007 19 12.0013 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 12.0013 21 12.0007 21 12H19ZM10.293 3.29604C10.579 3.01004 11.009 2.92504 11.383 3.07904C11.757 3.23204 12 3.59904 12 4.00204V20.002C12 20.407 11.757 20.772 11.383 20.927C11.009 21.082 10.579 20.996 10.293 20.71L6 16.002H3C2.45 16.002 2 15.552 2 15.002V9.00204C2 8.45304 2.45 8.00204 3 8.00204H6L10.293 3.29604Z"],
.wrapper-2jXpOf .icon-1DeIlz path[d="M21.025 5V4C21.025 2.88 20.05 2 19 2C17.95 2 17 2.88 17 4V5C16.4477 5 16 5.44772 16 6V9C16 9.55228 16.4477 10 17 10H19H21C21.5523 10 22 9.55228 22 9V5.975C22 5.43652 21.5635 5 21.025 5ZM20 5H18V4C18 3.42857 18.4667 3 19 3C19.5333 3 20 3.42857 20 4V5Z"],
.wrapper-2jXpOf .icon-1DeIlz path[d="M19.8914 3.80204L22.2438 8.55654C22.5726 9.22119 22.0891 9.99999 21.3475 10L16.6179 10C15.8745 10 15.391 9.21769 15.7235 8.55279L18.1007 3.79829C18.4701 3.05951 19.5251 3.06172 19.8914 3.80204ZM18.4998 5H19.4999V7.5H18.4999L18.4998 5ZM18.4998 8.49887C18.4998 8.77589 18.7238 9 18.9998 9C19.2759 9 19.4999 8.77589 19.4999 8.49887C19.4999 8.22224 19.2759 7.99773 18.9998 7.99773C18.7238 7.99773 18.4998 8.22224 18.4998 8.49887Z"],
.wrapper-2jXpOf .icon-1DeIlz path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"] {
  fill: var(--color-high);
}
.wrapper-2jXpOf .content-1x5b-n {
  height: 28px;
  top: 1px;
  margin-left: 0;
  border-radius: 0;
}
.wrapper-2jXpOf .name-23GUGE,
.wrapper-2jXpOf .actionIcon-PgcMM2 {
  transition: color 0.2s;
}
.wrapper-2jXpOf .mainContent-u_9PKf:before {
  transition: width 0.4s;
  position: absolute;
  animation-name: pulsingBackground;
  animation-duration: 1.5s;
  animation-iteration-count: infinite;
  width: 0%;
}
.wrapper-2jXpOf.modeConnected-3IsKId, .wrapper-2jXpOf.modeSelected-346R90, .wrapper-2jXpOf:hover {
  box-shadow: 0 1px var(--color-low), 0 -1px var(--color-low);
}
.wrapper-2jXpOf.modeConnected-3IsKId .mainContent-u_9PKf:before, .wrapper-2jXpOf.modeSelected-346R90 .mainContent-u_9PKf:before, .wrapper-2jXpOf:hover .mainContent-u_9PKf:before {
  width: 100%;
}
.wrapper-2jXpOf.modeConnected-3IsKId .icon-1DeIlz, .wrapper-2jXpOf.modeSelected-346R90 .icon-1DeIlz, .wrapper-2jXpOf:hover .icon-1DeIlz {
  color: var(--color-high);
  background-color: var(--color-high);
}
.wrapper-2jXpOf.modeConnected-3IsKId .icon-1DeIlz path[d="M33 34.5833V7.49998H35V36.6666H9C6.791 36.6666 5 34.801 5 32.5V7.49998C5 5.19894 6.791 3.33331 9 3.33331H31V30.4166H9C7.8955 30.4166 7 31.3485 7 32.5C7 33.6515 7.8955 34.5833 9 34.5833H33ZM23.9718 9.99998L15.8889 17.9915L12.7086 14.8441L10 17.5058L15.8885 23.3333L26.6667 12.6669L23.9718 9.99998Z"],
.wrapper-2jXpOf.modeConnected-3IsKId .icon-1DeIlz path[d="M19.1 4V5.12659L4.85 8.26447V18.1176C4.85 18.5496 5.1464 18.9252 5.5701 19.0315L9.3701 19.9727C9.4461 19.9906 9.524 20 9.6 20C9.89545 20 10.1776 19.8635 10.36 19.6235L12.7065 16.5242L19.1 17.9304V19.0588H21V4H19.1ZM9.2181 17.9944L6.75 17.3826V15.2113L10.6706 16.0753L9.2181 17.9944Z"],
.wrapper-2jXpOf.modeConnected-3IsKId .icon-1DeIlz path[d="M15 12C15 12.0007 15 12.0013 15 12.002C15 12.553 14.551 13.002 14 13.002V15.002C15.654 15.002 17 13.657 17 12.002C17 12.0013 17 12.0007 17 12H15ZM19 12C19 12.0007 19 12.0013 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 12.0013 21 12.0007 21 12H19ZM10.293 3.29604C10.579 3.01004 11.009 2.92504 11.383 3.07904C11.757 3.23204 12 3.59904 12 4.00204V20.002C12 20.407 11.757 20.772 11.383 20.927C11.009 21.082 10.579 20.996 10.293 20.71L6 16.002H3C2.45 16.002 2 15.552 2 15.002V9.00204C2 8.45304 2.45 8.00204 3 8.00204H6L10.293 3.29604Z"],
.wrapper-2jXpOf.modeConnected-3IsKId .icon-1DeIlz path[d="M21.025 5V4C21.025 2.88 20.05 2 19 2C17.95 2 17 2.88 17 4V5C16.4477 5 16 5.44772 16 6V9C16 9.55228 16.4477 10 17 10H19H21C21.5523 10 22 9.55228 22 9V5.975C22 5.43652 21.5635 5 21.025 5ZM20 5H18V4C18 3.42857 18.4667 3 19 3C19.5333 3 20 3.42857 20 4V5Z"],
.wrapper-2jXpOf.modeConnected-3IsKId .icon-1DeIlz path[d="M19.8914 3.80204L22.2438 8.55654C22.5726 9.22119 22.0891 9.99999 21.3475 10L16.6179 10C15.8745 10 15.391 9.21769 15.7235 8.55279L18.1007 3.79829C18.4701 3.05951 19.5251 3.06172 19.8914 3.80204ZM18.4998 5H19.4999V7.5H18.4999L18.4998 5ZM18.4998 8.49887C18.4998 8.77589 18.7238 9 18.9998 9C19.2759 9 19.4999 8.77589 19.4999 8.49887C19.4999 8.22224 19.2759 7.99773 18.9998 7.99773C18.7238 7.99773 18.4998 8.22224 18.4998 8.49887Z"],
.wrapper-2jXpOf.modeConnected-3IsKId .icon-1DeIlz path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"], .wrapper-2jXpOf.modeSelected-346R90 .icon-1DeIlz path[d="M33 34.5833V7.49998H35V36.6666H9C6.791 36.6666 5 34.801 5 32.5V7.49998C5 5.19894 6.791 3.33331 9 3.33331H31V30.4166H9C7.8955 30.4166 7 31.3485 7 32.5C7 33.6515 7.8955 34.5833 9 34.5833H33ZM23.9718 9.99998L15.8889 17.9915L12.7086 14.8441L10 17.5058L15.8885 23.3333L26.6667 12.6669L23.9718 9.99998Z"],
.wrapper-2jXpOf.modeSelected-346R90 .icon-1DeIlz path[d="M19.1 4V5.12659L4.85 8.26447V18.1176C4.85 18.5496 5.1464 18.9252 5.5701 19.0315L9.3701 19.9727C9.4461 19.9906 9.524 20 9.6 20C9.89545 20 10.1776 19.8635 10.36 19.6235L12.7065 16.5242L19.1 17.9304V19.0588H21V4H19.1ZM9.2181 17.9944L6.75 17.3826V15.2113L10.6706 16.0753L9.2181 17.9944Z"],
.wrapper-2jXpOf.modeSelected-346R90 .icon-1DeIlz path[d="M15 12C15 12.0007 15 12.0013 15 12.002C15 12.553 14.551 13.002 14 13.002V15.002C15.654 15.002 17 13.657 17 12.002C17 12.0013 17 12.0007 17 12H15ZM19 12C19 12.0007 19 12.0013 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 12.0013 21 12.0007 21 12H19ZM10.293 3.29604C10.579 3.01004 11.009 2.92504 11.383 3.07904C11.757 3.23204 12 3.59904 12 4.00204V20.002C12 20.407 11.757 20.772 11.383 20.927C11.009 21.082 10.579 20.996 10.293 20.71L6 16.002H3C2.45 16.002 2 15.552 2 15.002V9.00204C2 8.45304 2.45 8.00204 3 8.00204H6L10.293 3.29604Z"],
.wrapper-2jXpOf.modeSelected-346R90 .icon-1DeIlz path[d="M21.025 5V4C21.025 2.88 20.05 2 19 2C17.95 2 17 2.88 17 4V5C16.4477 5 16 5.44772 16 6V9C16 9.55228 16.4477 10 17 10H19H21C21.5523 10 22 9.55228 22 9V5.975C22 5.43652 21.5635 5 21.025 5ZM20 5H18V4C18 3.42857 18.4667 3 19 3C19.5333 3 20 3.42857 20 4V5Z"],
.wrapper-2jXpOf.modeSelected-346R90 .icon-1DeIlz path[d="M19.8914 3.80204L22.2438 8.55654C22.5726 9.22119 22.0891 9.99999 21.3475 10L16.6179 10C15.8745 10 15.391 9.21769 15.7235 8.55279L18.1007 3.79829C18.4701 3.05951 19.5251 3.06172 19.8914 3.80204ZM18.4998 5H19.4999V7.5H18.4999L18.4998 5ZM18.4998 8.49887C18.4998 8.77589 18.7238 9 18.9998 9C19.2759 9 19.4999 8.77589 19.4999 8.49887C19.4999 8.22224 19.2759 7.99773 18.9998 7.99773C18.7238 7.99773 18.4998 8.22224 18.4998 8.49887Z"],
.wrapper-2jXpOf.modeSelected-346R90 .icon-1DeIlz path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"], .wrapper-2jXpOf:hover .icon-1DeIlz path[d="M33 34.5833V7.49998H35V36.6666H9C6.791 36.6666 5 34.801 5 32.5V7.49998C5 5.19894 6.791 3.33331 9 3.33331H31V30.4166H9C7.8955 30.4166 7 31.3485 7 32.5C7 33.6515 7.8955 34.5833 9 34.5833H33ZM23.9718 9.99998L15.8889 17.9915L12.7086 14.8441L10 17.5058L15.8885 23.3333L26.6667 12.6669L23.9718 9.99998Z"],
.wrapper-2jXpOf:hover .icon-1DeIlz path[d="M19.1 4V5.12659L4.85 8.26447V18.1176C4.85 18.5496 5.1464 18.9252 5.5701 19.0315L9.3701 19.9727C9.4461 19.9906 9.524 20 9.6 20C9.89545 20 10.1776 19.8635 10.36 19.6235L12.7065 16.5242L19.1 17.9304V19.0588H21V4H19.1ZM9.2181 17.9944L6.75 17.3826V15.2113L10.6706 16.0753L9.2181 17.9944Z"],
.wrapper-2jXpOf:hover .icon-1DeIlz path[d="M15 12C15 12.0007 15 12.0013 15 12.002C15 12.553 14.551 13.002 14 13.002V15.002C15.654 15.002 17 13.657 17 12.002C17 12.0013 17 12.0007 17 12H15ZM19 12C19 12.0007 19 12.0013 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 12.0013 21 12.0007 21 12H19ZM10.293 3.29604C10.579 3.01004 11.009 2.92504 11.383 3.07904C11.757 3.23204 12 3.59904 12 4.00204V20.002C12 20.407 11.757 20.772 11.383 20.927C11.009 21.082 10.579 20.996 10.293 20.71L6 16.002H3C2.45 16.002 2 15.552 2 15.002V9.00204C2 8.45304 2.45 8.00204 3 8.00204H6L10.293 3.29604Z"],
.wrapper-2jXpOf:hover .icon-1DeIlz path[d="M21.025 5V4C21.025 2.88 20.05 2 19 2C17.95 2 17 2.88 17 4V5C16.4477 5 16 5.44772 16 6V9C16 9.55228 16.4477 10 17 10H19H21C21.5523 10 22 9.55228 22 9V5.975C22 5.43652 21.5635 5 21.025 5ZM20 5H18V4C18 3.42857 18.4667 3 19 3C19.5333 3 20 3.42857 20 4V5Z"],
.wrapper-2jXpOf:hover .icon-1DeIlz path[d="M19.8914 3.80204L22.2438 8.55654C22.5726 9.22119 22.0891 9.99999 21.3475 10L16.6179 10C15.8745 10 15.391 9.21769 15.7235 8.55279L18.1007 3.79829C18.4701 3.05951 19.5251 3.06172 19.8914 3.80204ZM18.4998 5H19.4999V7.5H18.4999L18.4998 5ZM18.4998 8.49887C18.4998 8.77589 18.7238 9 18.9998 9C19.2759 9 19.4999 8.77589 19.4999 8.49887C19.4999 8.22224 19.2759 7.99773 18.9998 7.99773C18.7238 7.99773 18.4998 8.22224 18.4998 8.49887Z"],
.wrapper-2jXpOf:hover .icon-1DeIlz path[d="M11.383 3.07904C11.009 2.92504 10.579 3.01004 10.293 3.29604L6 8.00204H3C2.45 8.00204 2 8.45304 2 9.00204V15.002C2 15.552 2.45 16.002 3 16.002H6L10.293 20.71C10.579 20.996 11.009 21.082 11.383 20.927C11.757 20.772 12 20.407 12 20.002V4.00204C12 3.59904 11.757 3.23204 11.383 3.07904ZM14 5.00195V7.00195C16.757 7.00195 19 9.24595 19 12.002C19 14.759 16.757 17.002 14 17.002V19.002C17.86 19.002 21 15.863 21 12.002C21 8.14295 17.86 5.00195 14 5.00195ZM14 9.00195C15.654 9.00195 17 10.349 17 12.002C17 13.657 15.654 15.002 14 15.002V13.002C14.551 13.002 15 12.553 15 12.002C15 11.451 14.551 11.002 14 11.002V9.00195Z"] {
  fill: var(--color-low);
}
.wrapper-2jXpOf.modeConnected-3IsKId .actionIcon-PgcMM2,
.wrapper-2jXpOf.modeConnected-3IsKId .name-23GUGE, .wrapper-2jXpOf.modeSelected-346R90 .actionIcon-PgcMM2,
.wrapper-2jXpOf.modeSelected-346R90 .name-23GUGE, .wrapper-2jXpOf:hover .actionIcon-PgcMM2,
.wrapper-2jXpOf:hover .name-23GUGE {
  z-index: 1;
  color: var(--color-high);
}
.wrapper-2jXpOf.modeConnected-3IsKId .wrapper-2tAnRe, .wrapper-2jXpOf.modeSelected-346R90 .wrapper-2tAnRe, .wrapper-2jXpOf:hover .wrapper-2tAnRe {
  z-index: 1;
}
.wrapper-2jXpOf.modeUnread-1qO3K1 .icon-1DeIlz {
  color: var(--color-alert);
  background-color: var(--color-alert);
}
.wrapper-2jXpOf.modeUnread-1qO3K1 .name-23GUGE {
  color: var(--color-alert);
}

.wrapper-2tAnRe {
  border-radius: 0;
  border: 1px solid var(--color-mid);
  height: 18px;
}
.wrapper-2tAnRe .users-3kndPl {
  padding-left: 4px;
  z-index: 1;
}
.wrapper-2tAnRe .total-i6us2n {
  background-color: var(--color-alert);
  color: var(--color-high);
  z-index: 2;
}
.wrapper-2tAnRe .total-i6us2n::after {
  border-right-color: var(--color-alert);
}

.base-PmTxvP {
  border-radius: 0;
}

.theme-dark .form-2fGMdU:before,
.chat-3bRxxu {
  background: transparent;
}

.mentioned-xhSam7:before {
  width: 0;
}

.divider-JfaTT5 {
  border-color: var(--color-alert);
}

.auto-Ge5KZx::-webkit-scrollbar,
.auto-Ge5KZx::-webkit-scrollbar-thumb,
.auto-Ge5KZx::-webkit-scrollbar-track {
  border-radius: 0;
  width: 6px;
}

.cozyMessage-3V1Y8y .header-23xsNx {
  border-radius: 0;
  display: inline-block !important;
  padding: 4px 5px 4px 6px;
  background: var(--color-high);
  margin-left: 13px;
  box-shadow: 2px 2px 0 var(--color-mid), -3px 0 0 var(--color-low), -9px 0 0 var(--color-high), -21px 0 0 var(--color-low), -18px 2px 0 var(--color-mid);
}

.full-motion .avatar-1BDn8e.clickable-1bVtEA {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}
.full-motion .avatar-1BDn8e.clickable-1bVtEA:hover {
  filter: none;
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-alert);
}

.username-1A8OIy.clickable-1bVtEA {
  color: var(--color-low) !important;
}

.isUnread-3Ef-o9 .content-1o0f9g,
.unreadPill-2HyYtt,
.content-1o0f9g {
  border-radius: 0;
  background-color: var(--color-alert);
  color: var(--color-high);
}

.unreadPillCapStroke-7rkHbg {
  color: var(--color-alert);
  fill: var(--color-alert);
}

.blockquoteContainer-U5TVEi .blockquoteDivider-2hH8H6 {
  border-radius: 0;
  background-color: var(--color-low);
}

.emptyChannelIcon-cc932w {
  background-image: url("https://svgur.com/i/RGT.svg");
  -webkit-mask: url("https://svgur.com/i/RGT.svg");
          mask: url("https://svgur.com/i/RGT.svg");
  background: var(--color-mid) !important;
  margin: auto;
  width: 403px !important;
  height: 353px !important;
}

.theme-dark .mentioned-xhSam7 .mention.interactive:hover {
  color: var(--color-high);
}

.wrapper-3WhCwL {
  background: var(--color-alert-trans);
  color: var(--color-high);
}
.wrapper-3WhCwL:hover {
  color: var(--color-alert);
  background: var(--color-high);
}

.mouse-mode.full-motion .replying-1x3H0T, .mouse-mode.full-motion .replying-1x3H0T:hover {
  background-color: var(--color-alert-trans);
}
.mouse-mode.full-motion .replying-1x3H0T:before {
  background-color: var(--color-alert);
}

.backgroundFlash-24qWLN {
  transition: background-color 0.1s;
  background-color: var(--color-alert-trans) !important;
}

[style="background-color: rgba(114, 137, 218, 0);"] {
  background-color: transparent !important;
  transition: background-color 0.5s;
}

.colorBrand-2tjs5J {
  color: var(--color-alert);
}

.repliedMessage-VokQwo:before {
  border-left: var(--spine-width) solid var(--color-low);
  border-bottom: 0 solid var(--color-low);
  border-right: 0 solid var(--color-low);
  border-top: var(--spine-width) solid var(--color-low);
  border-radius: 0;
}

.replyBadge-r1su3o {
  border-radius: 0;
  border: 1px solid var(--color-low);
}

.newMessagesBar-265mhP,
.jumpToPresentBar-G1R9s6 {
  box-shadow: none;
  background-color: var(--color-alert);
  border-radius: 0;
}
.newMessagesBar-265mhP button,
.jumpToPresentBar-G1R9s6 button {
  color: var(--color-high);
}

.scrollableContainer-2NUZem {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.theme-dark .operations-36ENbA {
  color: var(--color-low);
}
.theme-dark .operations-36ENbA > a {
  color: var(--color-alert);
}

.codeBlockSyntax-2i-tMA,
.syntaxAfter-hcA4AH,
.syntaxBefore-1YQ9lW {
  color: var(--color-alert);
}

.compact-T3H92H .headerText-3Uvj1Y {
  border-right: 2px dashed var(--color-alert);
}

.compact-T3H92H .timestamp-3ZCmNB,
.cozy-3raOZG .timestamp-3ZCmNB.alt-1uNpEt {
  margin-right: 0;
  width: auto;
}

.channelTextArea-2VhZ6z {
  width: auto;
}

.channelTextArea-rNsIhG {
  border-radius: 0;
  margin-left: 21px;
  box-shadow: -3px 0 0 var(--color-low), -9px 0 0 var(--color-high), -21px 0 0 var(--color-low), -18px 3px 0 var(--color-mid), 3px 3px 0 var(--color-mid);
}

.placeholder-37qJjk {
  color: var(--color-mid);
}

.cooldownWrapper-3joyFc {
  color: var(--color-low) !important;
}

.attachButton-2WznTc {
  padding-left: 10px;
  padding-right: 10px;
}
.attachButton-2WznTc:hover .attachButtonPlus-jWVFah {
  transition: fill 0.1s ease-in-out;
  fill: var(--color-mid);
}

.embedFull-2tM8--,
.messageContent-2qWWxC pre {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.embedFull-2tM8-- > code,
.messageContent-2qWWxC pre > code {
  border-radius: 0;
  margin-left: 13px;
  margin-bottom: 4px;
  box-shadow: -3px 0 0 var(--color-low), -9px 0 0 var(--color-high), -21px 0 0 var(--color-low), -18px 4px 0 var(--color-mid);
}

.attachment-33OFj0 {
  margin-left: 13px;
  border-radius: 0;
  box-shadow: -3px 0 0 var(--color-low), -9px 0 0 var(--color-high), -21px 0 0 var(--color-low), -18px 3px 0 var(--color-mid), 3px 3px 0 var(--color-mid);
}
.attachment-33OFj0 .metadata-3WGS0M {
  color: var(--color-low);
}

.imageWrapper-2p5ogY:not(.embedImage-2W1cML) {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.wrapper-2TxpI8,
.video-8eMOth {
  border-radius: 0;
}

.theme-dark .invite-18yqGF {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
  border: none;
}
.theme-dark .invite-18yqGF .header-Hg_qNF,
.theme-dark .invite-18yqGF .partyStatus-6AjDud {
  color: var(--color-low);
}
.theme-dark .invite-18yqGF .textLink-3aPthL {
  color: var(--color-alert);
}

.reaction-1hd86g {
  border: 1px solid var(--color-low);
  border-radius: 0;
  background-color: transparent;
}
.reaction-1hd86g .reactionCount-2mvXRV {
  color: var(--color-low);
}
.reaction-1hd86g:hover {
  background: var(--color-mid);
  border-radius: 0;
  box-shadow: 2px 2px 0 var(--color-mid);
}
.reaction-1hd86g:hover .reactionCount-2mvXRV {
  color: var(--color-high);
}

.reaction-1hd86g.reactionMe-wv5HKu {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 2px 2px 0 var(--color-mid);
}
.reaction-1hd86g.reactionMe-wv5HKu .reactionCount-2mvXRV {
  color: var(--color-high);
}

::placeholder,
body,
button,
input,
select,
textarea {
  font-family: var(--nier-font), Arial, Helvetica, sans-serif;
}

strong {
  font-family: Arial, Helvetica, sans-serif;
}

.markup-2BOw-j {
  font-size: 11pt;
}

.wrapper-1Rf91z,
.theme-dark .pageWrapper-1PgVDX,
.scroller-2TZvBN {
  background-color: transparent;
}

.guildSeparator-3s64Iy {
  height: 0;
}

.listItem-2P_4kh .svg-1X37T1 foreignObject {
  -webkit-mask: none;
          mask: none;
}

.expandedFolderBackground-2sPsd- {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.scroller-2TZvBN > div[aria-label=Servers] > .listItem-2P_4kh foreignObject {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.folderIconWrapper-226oVY {
  border-radius: 0;
}

.acronym-2mOFsV {
  color: var(--color-low) !important;
}

.item-2hkk8m {
  width: 11px;
  transition: background-color 0.2s;
  background-color: var(--color-low);
  border-radius: 0;
  height: 48px !important;
}

.item-2hkk8m[style="opacity: 1; height: 8px; transform: none;"] {
  background-color: var(--color-alert);
}

.iconBadge-2wi9r4 {
  background-color: var(--color-low);
}

.mention-1f5kbO {
  background: var(--color-alert);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-low);
}

.numberBadge-2s8kKX {
  background-color: var(--color-alert) !important;
  color: var(--color-high) !important;
  border-radius: 0;
}

.circleIconButton-jET_ig {
  color: var(--color-alert);
}
.circleIconButton-jET_ig.selected-ugP_am {
  background-color: var(--color-alert);
  color: var(--color-high);
}

.theme-dark .card-3DjzTQ,
.theme-dark .iconMask-3b8GzQ {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 5px 5px 0 var(--color-mid);
}

.scroller-1JbKMe,
.sidebar-2K8pFh,
.privateChannels-1nO12o {
  background: transparent;
}

.scroller-1IIF0A,
.scroller-9moviB,
.applicationStore-1pNvnv,
.nowPlayingColumn-2sl4cE,
.theme-dark .inset-3sAvek,
.theme-dark .container-1D34oG {
  background-color: transparent;
}

.peopleListItem-2nzedh.active-rhSpJJ,
.peopleListItem-2nzedh:hover {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.theme-dark .text-GwUZgS,
.theme-dark .title-2BxgL2 {
  color: var(--color-low);
}

.theme-dark .feature-2w65J5,
.banner-WELp4M,
.wrapper-3D2qGf {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.theme-dark .feature-2w65J5 .inset-3sAvek,
.banner-WELp4M .inset-3sAvek,
.wrapper-3D2qGf .inset-3sAvek {
  border: 1px solid var(--color-mid);
  border-radius: 0;
}
.theme-dark .feature-2w65J5 .partyMemberOverflow-lXnzvu,
.banner-WELp4M .partyMemberOverflow-lXnzvu,
.wrapper-3D2qGf .partyMemberOverflow-lXnzvu {
  color: var(--color-high);
  background: var(--color-low);
}
.theme-dark .feature-2w65J5:hover,
.banner-WELp4M:hover,
.wrapper-3D2qGf:hover {
  background-color: var(--color-low) !important;
}
.theme-dark .feature-2w65J5:hover .partyMemberOverflow-lXnzvu,
.banner-WELp4M:hover .partyMemberOverflow-lXnzvu,
.wrapper-3D2qGf:hover .partyMemberOverflow-lXnzvu {
  color: var(--color-low);
  background: var(--color-high);
}
.theme-dark .feature-2w65J5:hover .base-1x0h_U,
.theme-dark .feature-2w65J5:hover .colorHeaderSecondary-3Sp3Ft,
.theme-dark .feature-2w65J5:hover .colorStandard-2KCXvj,
.banner-WELp4M:hover .base-1x0h_U,
.banner-WELp4M:hover .colorHeaderSecondary-3Sp3Ft,
.banner-WELp4M:hover .colorStandard-2KCXvj,
.wrapper-3D2qGf:hover .base-1x0h_U,
.wrapper-3D2qGf:hover .colorHeaderSecondary-3Sp3Ft,
.wrapper-3D2qGf:hover .colorStandard-2KCXvj {
  color: var(--color-high);
}

.theme-dark .emptyWumpus-12J3jI,
.image-1GzsFd {
  -webkit-mask: url("https://svgur.com/i/RGT.svg");
          mask: url("https://svgur.com/i/RGT.svg");
  background: var(--color-low) !important;
  width: 403px !important;
  height: 353px !important;
}
.theme-dark .emptyWumpus-12J3jI + div .text-GwUZgS,
.image-1GzsFd + div .text-GwUZgS {
  visibility: hidden;
  justify-content: center;
}
.theme-dark .emptyWumpus-12J3jI + div .text-GwUZgS::before,
.image-1GzsFd + div .text-GwUZgS::before {
  visibility: visible;
  content: "Nothing to see here, friend! *rolls away*";
}

.children-gzQq2t {
  z-index: 1;
}

.actionButton-uPB8Fs:hover {
  transition: background-color 0.2s ease-in-out;
  background-color: var(--color-low);
}
.actionButton-uPB8Fs:hover .icon-35-fSh {
  transition: color 0.1s ease-in-out;
  color: var(--color-high);
}

.scroller-2XE8rp {
  background: transparent;
}

.theme-dark .installationPath-3cStrB {
  box-shadow: none;
}

.theme-dark .usageInfo-2WQAwr,
.theme-dark .rowTitle-1KYtY7,
.theme-dark .rowBody-3dJTTZ {
  color: var(--color-low);
}

.clickable-1JJAn8:hover .layout-2DM8Md,
.members-1998pB,
.members-1998pB > div {
  background: transparent;
}

.container-2Pjhx- {
  transition: color 0.2s;
  max-width: none;
  border-radius: 0;
  height: 44px;
  margin: 5px 0 5px 0;
}
.container-2Pjhx- .layout-2DM8Md {
  background-color: transparent !important;
  height: 36px;
  margin: 3px 0 0 0;
  border-radius: 0;
}
.container-2Pjhx- .layout-2DM8Md:before {
  content: "";
  position: absolute;
  left: 0;
  top: 2px;
  bottom: 2px;
  transition: width 0.4s;
  animation-name: pulsingBackground;
  animation-duration: 1.5s;
  animation-iteration-count: infinite;
  width: 0%;
}
.container-2Pjhx-.selected-aXhQR6, .container-2Pjhx-:hover {
  color: var(--color-high) !important;
  box-shadow: 0 1px var(--color-low), 0 -1px var(--color-low);
}
.container-2Pjhx-.selected-aXhQR6 .name-uJV0GL span,
.container-2Pjhx-.selected-aXhQR6 .activity-2Gy-9S,
.container-2Pjhx-.selected-aXhQR6 .muted-3mU76i, .container-2Pjhx-:hover .name-uJV0GL span,
.container-2Pjhx-:hover .activity-2Gy-9S,
.container-2Pjhx-:hover .muted-3mU76i {
  color: var(--color-high) !important;
}
.container-2Pjhx-.selected-aXhQR6 .layout-2DM8Md:before, .container-2Pjhx-:hover .layout-2DM8Md:before {
  width: 100%;
}
.container-2Pjhx-.selected-aXhQR6 .linkButtonIcon-Mlm5d6,
.container-2Pjhx-.selected-aXhQR6 .content-3QAtGj, .container-2Pjhx-:hover .linkButtonIcon-Mlm5d6,
.container-2Pjhx-:hover .content-3QAtGj {
  z-index: 1;
}

.botTagRegular-2HEhHi {
  background-color: var(--color-alert);
  color: var(--color-high);
}

#app-mount:after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: url("https://i.ibb.co/Fq9Jt09/Nie-R-Lattice.png");
  z-index: 10000;
  opacity: 0.03;
  -webkit-user-select: none;
          user-select: none;
  pointer-events: none;
}

.message-2qnXI6 .role-2irmRk {
  border-radius: 0;
  padding: 4px 0;
  transition: all 0.3s ease;
  border: none;
}
.message-2qnXI6 .role-2irmRk .roleCircle-3xAZ1j {
  border: 1px solid var(--color-low);
  border-radius: 0;
  margin: 0;
}
.message-2qnXI6 .role-2irmRk .roleName-32vpEy {
  color: var(--color-low);
  transition: all 0.3s ease;
  margin: 0;
  width: 0;
}
.message-2qnXI6 .role-2irmRk:hover .roleName-32vpEy {
  margin-left: 3px;
  width: 100%;
}

.wrapper-2Gsate {
  background: transparent;
}

.header-ykumBX,
.header-8ilj5e {
  box-shadow: none;
}

.popoutContainer-1MXdqN {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.full-motion .wrapper-2aW0bm:hover,
.wrapper-2aW0bm {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}
.full-motion .wrapper-2aW0bm:hover .button-1ZiXG9,
.wrapper-2aW0bm .button-1ZiXG9 {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-low);
  color: var(--color-high);
}
.full-motion .wrapper-2aW0bm:hover .button-1ZiXG9:hover, .full-motion .wrapper-2aW0bm:hover .button-1ZiXG9:active,
.wrapper-2aW0bm .button-1ZiXG9:hover,
.wrapper-2aW0bm .button-1ZiXG9:active {
  border-color: transparent !important;
  background-color: var(--color-high) !important;
  color: var(--color-low) !important;
}

.messagesPopoutWrap-1MQ1bW {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.username-1A8OIy {
  color: var(--color-low) !important;
}

.theme-dark .header-2-Imhb .tabBar-1kuXvJ .tab-ck0077.active-1MbGPa {
  background-color: var(--color-alert);
  color: var(--color-high);
}

.emojiPicker-3PwZFl {
  border: 1px solid var(--color-low);
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.emojiItem-14v6tW.emojiItemSelected-1aLkfV {
  background: var(--color-low);
  border-radius: 0;
}

.theme-dark .contentTitle-2tG_sM strong,
.theme-dark .content-Qb0rXO {
  color: var(--color-low);
}
.theme-dark .divider-23swzi {
  background-color: var(--color-low);
}
.theme-dark .autocomplete-1vrmpx {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.theme-dark .autocomplete-1vrmpx .descriptionDiscriminator-3vUOCc {
  color: var(--color-mid);
}
.theme-dark .autocomplete-1vrmpx .description-11DmNu,
.theme-dark .autocomplete-1vrmpx .descriptionUsername-J_75O8,
.theme-dark .autocomplete-1vrmpx .contentTitle-2tG_sM {
  color: var(--color-low);
}
.theme-dark .selected-1Tbx07 {
  background-color: var(--color-low);
  border-radius: 0;
}
.theme-dark .selected-1Tbx07 .colorStandard-2KCXvj,
.theme-dark .selected-1Tbx07 .content-Qb0rXO,
.theme-dark .selected-1Tbx07 .description-11DmNu,
.theme-dark .selected-1Tbx07 .descriptionUsername-J_75O8,
.theme-dark .selected-1Tbx07 .contentTitle-2tG_sM {
  color: var(--color-high);
}

.autocompleteRow-2OthDa {
  padding: 0;
}

.theme-dark .quickSelectPopout-X1hvgV {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}
.theme-dark .quickSelectPopout-X1hvgV .quickSelectPopoutOption-opKBx9 {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-low);
  color: var(--color-high);
}
.theme-dark .quickSelectPopout-X1hvgV .quickSelectPopoutOption-opKBx9:hover, .theme-dark .quickSelectPopout-X1hvgV .quickSelectPopoutOption-opKBx9:active {
  border-color: transparent !important;
  background-color: var(--color-high) !important;
  color: var(--color-low) !important;
}
.theme-dark .quickSelectPopout-X1hvgV .quickSelectPopoutOption-opKBx9 .regionSelectName-c5qL8O {
  color: var(--color-high);
}
.theme-dark .quickSelectPopout-X1hvgV .quickSelectPopoutOption-opKBx9:hover .regionSelectName-c5qL8O {
  color: var(--color-low);
}
.theme-dark .quickSelectPopout-X1hvgV .quickSelectPopoutOption-opKBx9 .check-2by_h9 {
  -webkit-mask: url("https://discord.com/assets/6acb20d5e709b34b6a7f36ec13648666.svg");
          mask: url("https://discord.com/assets/6acb20d5e709b34b6a7f36ec13648666.svg");
  background: var(--color-alert) !important;
  -webkit-mask-repeat: no-repeat;
          mask-repeat: no-repeat;
}

.menu-3sdvDG,
.theme-dark .tooltipBlack-PPG47z {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}
.menu-3sdvDG .scroller-3BxosC,
.theme-dark .tooltipBlack-PPG47z .scroller-3BxosC {
  padding: 0;
}
.menu-3sdvDG .colorDefault-2K3EoJ,
.theme-dark .tooltipBlack-PPG47z .colorDefault-2K3EoJ {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-low);
  color: var(--color-high);
  color: var(--color-high);
}
.menu-3sdvDG .colorDefault-2K3EoJ:hover, .menu-3sdvDG .colorDefault-2K3EoJ:active,
.theme-dark .tooltipBlack-PPG47z .colorDefault-2K3EoJ:hover,
.theme-dark .tooltipBlack-PPG47z .colorDefault-2K3EoJ:active {
  border-color: transparent !important;
  background-color: var(--color-high) !important;
  color: var(--color-low) !important;
}

.item-1tOPte {
  border-radius: 0;
  margin: 0;
}

.colorDanger-2qLCe1,
.colorDanger-2qLCe1 .checkbox-3s5GYZ,
.colorDanger-2qLCe1 .radioSelection-1HmrQS {
  color: var(--color-alert) !important;
}

.clickCTA-2B6Kbs {
  color: var(--color-mid);
}

.theme-dark .tooltip-2QfLtc,
.theme-dark .listItemTooltip-CDcY8J {
  color: var(--color-high);
}

.separator-2I32lJ,
.theme-dark .tooltipBlack-PPG47z .tooltipPointer-3ZfirK {
  border: none;
}

.theme-dark .autocompleteShadow-iiGWFU {
  border: 1px solid var(--color-low);
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.theme-dark .autocompleteArrow-Zxoy9H,
.theme-dark .header-2bNvm4 {
  background-color: transparent;
  box-shadow: none;
}

.theme-dark .addGamePopout-2RY8Ju .cancelButton-10XRsm,
.theme-dark .empty-3hoe1g .noResultsHeader-pqW4H-,
.theme-dark .empty-3hoe1g p,
.theme-dark .container-VSDcQc .input-1ppKdn {
  color: var(--color-low);
}
.theme-dark .addGamePopout-2RY8Ju .cancelButton-10XRsm::placeholder,
.theme-dark .empty-3hoe1g .noResultsHeader-pqW4H-::placeholder,
.theme-dark .empty-3hoe1g p::placeholder,
.theme-dark .container-VSDcQc .input-1ppKdn::placeholder {
  color: var(--color-mid);
}

.row-rrHHJU.selected-1pIgLL .rowInner-1vvRiF {
  background-color: var(--color-low);
  border-radius: 0;
}
.row-rrHHJU.selected-1pIgLL .rowInner-1vvRiF span {
  color: var(--color-high) !important;
}

.tabBarContainer-1s1u-z {
  border: none;
}

.separator-2I32lJ {
  margin: 0;
}

.headerStreaming-2FjmGz,
.headerXbox-3G-4PF,
.theme-dark .headerNormal-T_seeN,
.theme-dark .body-3iLsc4,
.topSectionPlaying-1J5E4n,
.topSectionSpotify-1lI0-P,
.headerSpotify-zpWxgT,
.headerPlaying-j0WQBV,
.theme-dark .footer-1fjuF6 {
  background: transparent;
}

.theme-dark .activityProfile-2bJRaP .content-3JfFJh,
.theme-dark .activityProfile-2bJRaP .details-38sfDr,
.theme-dark .activityProfile-2bJRaP .headerText-1HLrL7,
.theme-dark .activityProfile-2bJRaP .name-29ETJS,
.theme-dark .activityUserPopout-2yItg2 .content-3JfFJh,
.theme-dark .activityUserPopout-2yItg2 .details-38sfDr,
.theme-dark .activityUserPopout-2yItg2 .headerText-1HLrL7,
.theme-dark .activityUserPopout-2yItg2 .name-29ETJS {
  color: var(--color-high);
}
.theme-dark .body-3iLsc4,
.theme-dark .footer-1fjuF6 {
  color: var(--color-low);
}

[style*="border-color: rgb(255, 255, 255);"] {
  border-color: var(--color-alert) !important;
}

.top-28JiJ- .item-PXvHYJ {
  color: var(--color-mid) !important;
}

.activityHeader-1PExlk,
.customStatusText-39gdCI,
.colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O),
.colorDefault-2K3EoJ.focused-3afm-j,
.nameNormal-2lqVQK,
.text-AOoUen,
.nameWrap-3Z4G_9,
.activityName-1IaRLn {
  color: var(--color-high);
}

.customStatus-1bh2V9,
.additionalActionsIcon-1FoUlE,
.discriminator-xUhQkU,
.username-3gJmXY,
.headerName-fajvi9,
.headerTag-2pZJzA,
.headerTagUsernameNoNickname-2_H881 {
  color: var(--color-low);
}

.bar-3urHkF,
.headerFill-adLl4x,
.colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O),
.colorDefault-2K3EoJ.focused-3afm-j,
.activity-11LB_k {
  background: var(--color-low);
}

.barInner-3NDaY_ {
  background: var(--color-high);
}

.gameIcon-gg34Dz,
.assetsLargeImage-eYwpTX {
  border-radius: 0;
  border: 1px solid var(--color-high);
}

.root-SR8cQa,
.theme-dark .colorPickerCustom-2CWBn2,
.userPopout-3XzG_A {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 5px 5px 0 var(--color-mid);
  border-color: var(--color-low);
}

.searchResult-9tQ1uo:before,
.searchResult-9tQ1uo:after,
.channelName-1JRO3C,
.searchResultsWrap-3-pOjs,
.theme-dark .option-96V44q:after {
  background: transparent;
}

.searchHeader-2XoQg7,
.searchResultMessage-1fxgXh.hit-1fVM9e {
  box-shadow: none;
}

.searchBar-3dMhjb {
  border-radius: 0;
  background: var(--color-high-trans);
}

.theme-dark .searchAnswer-3Dz2-q,
.theme-dark .searchFilter-2ESiM3 {
  color: var(--color-high);
  background-color: var(--color-low);
}
.theme-dark .elevationBorderHigh-2WYJ09,
.theme-dark .container-3ayLPN {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.theme-dark .queryContainer-RKFJW- {
  color: var(--color-low);
  border: none;
}
.theme-dark .queryContainer-RKFJW- strong {
  color: var(--color-low);
}
.theme-dark .queryContainer-RKFJW-.focused-2bY0OD {
  color: var(--color-high);
  background-color: var(--color-low);
}
.theme-dark .queryContainer-RKFJW-.focused-2bY0OD strong {
  color: var(--color-high);
}
.theme-dark .resultsGroup-r_nuzN .header-2N-gMV,
.theme-dark .resultsGroup-r_nuzN .searchClearHistory-2cSSMO,
.theme-dark .resultsGroup-r_nuzN .searchLearnMore-3SQUAj a {
  color: var(--color-low);
}
.theme-dark .resultsGroup-r_nuzN .plusIcon-v0BTrL {
  color: var(--color-high);
}
.theme-dark .resultsGroup-r_nuzN::before {
  border: none;
}
.theme-dark .option-96V44q {
  margin: 0;
}
.theme-dark .option-96V44q.user-O3Czj0 .displayUsername-Qekxml, .theme-dark .option-96V44q.user-O3Czj0 .displayedNick-3xxvzU,
.theme-dark .option-96V44q .searchResultChannelCategory-1l0lSn,
.theme-dark .option-96V44q .searchResultChannelIcon-1DnTme,
.theme-dark .option-96V44q strong,
.theme-dark .option-96V44q .nonText-3CRkO0,
.theme-dark .option-96V44q .filter-3Y_im-,
.theme-dark .option-96V44q .answer-1n6g43 {
  color: var(--color-low);
}
.theme-dark .option-96V44q.selected-rZcOL- {
  background: var(--color-low);
  border-radius: 0;
}
.theme-dark .option-96V44q.selected-rZcOL-::after {
  background: transparent;
}
.theme-dark .option-96V44q.selected-rZcOL-.user-O3Czj0 .displayUsername-Qekxml, .theme-dark .option-96V44q.selected-rZcOL-.user-O3Czj0 .displayedNick-3xxvzU,
.theme-dark .option-96V44q.selected-rZcOL- strong,
.theme-dark .option-96V44q.selected-rZcOL- .nonText-3CRkO0,
.theme-dark .option-96V44q.selected-rZcOL- .filter-3Y_im-,
.theme-dark .option-96V44q.selected-rZcOL- .answer-1n6g43 {
  color: var(--color-high);
}
.theme-dark .option-96V44q.selected-rZcOL- .searchResultChannelCategory-1l0lSn,
.theme-dark .option-96V44q.selected-rZcOL- .searchResultChannelIcon-1DnTme {
  color: var(--color-high);
}

.searchResult-9tQ1uo.expanded-w_LCGl,
.searchResultMessage-1fxgXh.hit-1fVM9e {
  border: 1px solid var(--color-low);
  border-radius: 0;
}

.backdrop-1wrmKB,
.backdropWithLayer-3_uhz4 {
  opacity: 0.4 !important;
}

.theme-dark .separator-2-RRj_,
.theme-dark .footer-3mqk7D,
.theme-dark .footer-2gL1pp {
  background-color: transparent;
  box-shadow: none;
}

.theme-dark .root-1gCeng {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.art-347BZj {
  background-image: none;
}

.header-3C6qT5 {
  padding-top: 0;
}

.h5-18_1nd,
.footer-2gL1pp,
.uploadIcon-2IFzZU,
.colorMuted-HdFt4q,
.colorHeaderPrimary-26Jzh-,
.colorHeaderSecondary-3Sp3Ft {
  color: var(--color-low);
}

.anchor-3Z-8Bb {
  color: var(--color-alert);
}

.theme-dark .uploadModal-2ifh8j {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 6px 6px 0 var(--color-mid);
}
.theme-dark .uploadModal-2ifh8j .scrollableContainer-2NUZem {
  box-shadow: none;
  border: 3px solid var(--color-low);
}

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-3nWsbo .instructions-2Du9gG,
.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-3nWsbo {
  border: none;
  color: var(--color-low);
}
.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .bgScale-1otPtc {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.theme-dark .checkbox-1ix_J3 {
  border: 2px solid var(--color-high);
  border-radius: 0;
}
.theme-dark .checkbox-1ix_J3.checked-3_4uQ9 {
  border: 2px solid var(--color-low) !important;
  background-color: var(--color-high);
}
.theme-dark .checkbox-1ix_J3.checked-3_4uQ9 path {
  fill: var(--color-low) !important;
}

.theme-dark.authBox-hW6HRx {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 6px 6px 0 var(--color-mid);
}
.theme-dark.authBox-hW6HRx,
.theme-dark.authBox-hW6HRx .colorHeaderPrimary-26Jzh-,
.theme-dark.authBox-hW6HRx .colorHeaderSecondary-3Sp3Ft,
.theme-dark.authBox-hW6HRx .h5-18_1nd {
  color: var(--color-low);
}
.theme-dark.authBox-hW6HRx .lookLink-9FtZy-.colorBrand-3pXr91 {
  color: var(--color-alert);
}
.theme-dark.authBox-hW6HRx .qrCodeContainer-3sXarj,
.theme-dark.authBox-hW6HRx .qrCodeOverlay-qgtlTP {
  border: 1px solid var(--color-low);
}

.quickswitcher-3JagVE {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 5px 5px 0 var(--color-mid);
}
.quickswitcher-3JagVE .input-2VB9rf {
  color: var(--color-high);
  background: var(--color-low);
  border-radius: 0;
  box-shadow: none;
}
.quickswitcher-3JagVE .icon-30q1Or {
  height: 13px;
  width: 13px;
  background-color: var(--color-low);
}
.quickswitcher-3JagVE .resultFocused-3aIoYe {
  background: var(--color-low);
  border-radius: 0;
}
.quickswitcher-3JagVE .resultFocused-3aIoYe .note-S--UP5,
.quickswitcher-3JagVE .resultFocused-3aIoYe .misc-1CT3G7,
.quickswitcher-3JagVE .resultFocused-3aIoYe .contentUnread-3gTHvA,
.quickswitcher-3JagVE .resultFocused-3aIoYe .contentDefault-16dKSY {
  color: var(--color-high);
}
.quickswitcher-3JagVE .resultFocused-3aIoYe .icon-30q1Or {
  background-color: var(--color-high);
}
.quickswitcher-3JagVE .resultFocused-3aIoYe .icon-30q1Or path {
  fill: var(--color-high);
}

.theme-dark .lookLink-9FtZy-.colorGrey-2DXtkV,
.theme-dark .footerText-2a7NxZ {
  color: var(--color-low);
}
.theme-dark .inviteRow-2L02ae {
  border-radius: 0;
}
.theme-dark .inviteRow-2L02ae .inviteRowName-1tVaxu {
  color: var(--color-low);
}
.theme-dark .inviteRow-2L02ae:hover {
  background: var(--color-low);
}
.theme-dark .inviteRow-2L02ae:hover .lookLink-9FtZy-.colorGrey-2DXtkV,
.theme-dark .inviteRow-2L02ae:hover .inviteRowName-1tVaxu {
  color: var(--color-high);
}

.bd-modal-wrapper .bd-modal-inner {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 5px 5px 0 var(--color-mid);
  border: none;
}
.bd-modal-wrapper .header {
  color: var(--color-high);
  background-color: var(--color-low);
}
.bd-modal-wrapper .footer-2gL1pp,
.bd-modal-wrapper .bd-modal-body {
  color: var(--color-low);
  background-color: transparent;
}
.bd-modal-wrapper .tab-bar-container {
  background-color: transparent;
  box-shadow: none;
}
.bd-modal-wrapper .tab-bar-container .tab-bar-item {
  color: var(--color-low);
}
.bd-modal-wrapper .tab-bar-container .tab-bar-item.selected {
  border-color: var(--color-low);
}
.bd-modal-wrapper .error,
.bd-modal-wrapper .table-header {
  color: var(--color-low);
  border-color: var(--color-low);
}
.bd-modal-wrapper .error-link {
  color: var(--color-alert);
}

.theme-dark .modal-yWgWj- {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.theme-dark .reactors-Blmlhw,
.theme-dark .scroller-1-nKid {
  background: transparent;
}
.theme-dark .reactorDefault-1IUqMZ {
  box-shadow: none;
}
.theme-dark .remove-3V-yj8,
.theme-dark .discriminator-byOsvi {
  color: var(--color-low);
}
.theme-dark .reactionSelected-1pqISm,
.theme-dark .reactionDefault-GBA58K:hover {
  background: var(--color-low);
  border-radius: 0;
}
.theme-dark .reactionSelected-1pqISm .colorStandard-2KCXvj,
.theme-dark .reactionDefault-GBA58K:hover .colorStandard-2KCXvj {
  color: var(--color-high);
}

.layer-3QrUeG,
.scroller-305q3I,
.contentRegion-3nDuYy,
.sidebarRegionScroller-3MXcoP,
.side-8zPYf6 .separator-gCa7yv,
.contentRegionScroller-26nc1e,
.standardSidebarView-3F1I7i {
  background-color: transparent;
}

.theme-dark .row-2okwlC,
.theme-dark .item-3eFBNF {
  box-shadow: none;
}

.theme-dark .divider-3wNib3 {
  border: none;
}

.theme-dark .markValue-2DwdXI,
.theme-dark .keybind-KpFkfr {
  color: var(--color-low);
}
.theme-dark .closeButton-1tv5uR {
  transition: background-color 0.2s;
  border-color: var(--color-low);
}
.theme-dark .closeButton-1tv5uR:hover {
  background-color: var(--color-alert-trans);
}
.theme-dark .closeButton-1tv5uR path {
  fill: var(--color-low);
}

.theme-dark .auditLog-3jNbM6 {
  color: var(--color-mid);
  border: none;
}
.theme-dark .auditLog-3jNbM6:hover .expandForeground-1nZ4VR {
  stroke: var(--color-mid);
}
.theme-dark .auditLog-3jNbM6 .expandForeground-1nZ4VR {
  stroke: var(--color-low);
}
.theme-dark .auditLog-3jNbM6 .icon-RTGJu3 {
  background-color: var(--color-low);
  border-radius: 25%;
}
.theme-dark .auditLog-3jNbM6 div {
  color: var(--color-mid);
}
.theme-dark .auditLog-3jNbM6 strong,
.theme-dark .auditLog-3jNbM6 span {
  color: var(--color-low);
}
.theme-dark .auditLog-3jNbM6 > div {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.card-3Qj_Yx {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.bd-button {
  border-radius: 0;
  border-color: transparent;
  background-color: var(--color-low);
  color: var(--color-high);
}
.bd-button:hover, .bd-button:active {
  border-color: transparent !important;
  background-color: var(--color-mid) !important;
  color: var(--color-high) !important;
}
.bd-button.bd-button-danger {
  background-color: var(--color-alert);
}

.bd-addon-views .bd-view-button.selected {
  background-color: var(--color-alert);
}

.bd-addon-list .bd-addon-card {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.bd-addon-header svg {
  fill: var(--color-low);
}

.socialLinks-3jqNFy svg path {
  fill: var(--color-low) !important;
}
.socialLinks-3jqNFy svg:hover path {
  fill: var(--color-alert) !important;
}

.theme-dark .payment-xT17Mq,
.theme-dark .paginator-166-09 {
  background: transparent;
}
.theme-dark .codeRedemptionRedirect-1wVR4b,
.theme-dark .divider-3WKGWk,
.theme-dark .paymentHeader-3QlZQi,
.theme-dark .bottomDivider-1K9Gao {
  border: none;
}
.theme-dark .pageIndicator-1gAbyA,
.theme-dark .activeBreadcrumb-p6aw-F,
.theme-dark .breadcrumbWrapper-WmDjgG,
.theme-dark .giftIcon-3DRGI6,
.theme-dark .summaryInfo-2QFKUg,
.theme-dark .sectionHeader-1068cF,
.theme-dark .descriptionWrapper-1YBY_J,
.theme-dark .description-HxwDO4 {
  color: var(--color-low);
}
.theme-dark .pageIndicator-1gAbyA {
  border-bottom: 2px solid var(--color-low);
  border-top: 2px solid var(--color-low);
}
.theme-dark .pageButtonNext-V2kUq0,
.theme-dark .pageButtonPrev-1Y-47D {
  border-radius: 0;
  border: 2px solid var(--color-low);
  border-color: var(--color-low);
}
.theme-dark .defaultIndicator-G3c16x {
  background-color: var(--color-alert);
  border-radius: 0;
  color: var(--color-high);
}
.theme-dark .codeRedemptionRedirect-1wVR4b,
.theme-dark .paymentPane-3bwJ6A {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
  color: var(--color-low);
}
.theme-dark .expandedInfo-3kfShd {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.theme-dark .expandedInfo-3kfShd .paymentText-2vaF7U,
.theme-dark .expandedInfo-3kfShd .paymentHeader-3QlZQi {
  color: var(--color-high);
}
.theme-dark .paymentHeader-3QlZQi {
  margin-top: 0;
  padding-top: 10px;
}
.theme-dark .hoverablePayment-Yc6mK7 .giftIcon-3DRGI6,
.theme-dark .hoverablePayment-Yc6mK7 .summaryInfo-2QFKUg {
  color: var(--color-low);
}
.theme-dark .hoverablePayment-Yc6mK7:hover {
  background-color: var(--color-low);
}
.theme-dark .hoverablePayment-Yc6mK7:hover .giftIcon-3DRGI6,
.theme-dark .hoverablePayment-Yc6mK7:hover .summaryInfo-2QFKUg {
  color: var(--color-high);
}

.theme-dark .content-s2SEQO ol,
.theme-dark .content-s2SEQO p,
.theme-dark .content-s2SEQO ul li {
  color: var(--color-low);
}
.theme-dark .date-1k6kG2 {
  color: var(--color-mid);
}
.theme-dark .socialLink-3n2n25 {
  color: var(--color-low);
}

.accountList-33MS45,
.connection-1fbD7X {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.theme-dark .inner-2Y6JuD:hover {
  background-color: var(--color-low);
  border-radius: 0;
}

.theme-dark .nowPlaying-284llR,
.theme-dark .notDetected-33MY4s {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.theme-dark .nowPlaying-284llR .overlayStatusText-L2IACa,
.theme-dark .nowPlaying-284llR .gameName-1RiWHm,
.theme-dark .nowPlaying-284llR .lastPlayed-3bQ7Bo,
.theme-dark .notDetected-33MY4s .overlayStatusText-L2IACa,
.theme-dark .notDetected-33MY4s .gameName-1RiWHm,
.theme-dark .notDetected-33MY4s .lastPlayed-3bQ7Bo {
  color: var(--color-high);
}
.theme-dark .game-1ipmAa {
  box-shadow: none;
}
.theme-dark .member-1q7VfX .name-8yzEIY,
.theme-dark .member-1q7VfX .roleWrapper-1Hde_V,
.theme-dark .css-hsd1lu-singleValue,
.theme-dark .nowPlayingAdd-1Kdmh_,
.theme-dark .gameName-1RiWHm,
.theme-dark .lastPlayed-3bQ7Bo {
  color: var(--color-low);
}
.theme-dark .card-FDVird:before {
  background: transparent;
  border: none;
}
.theme-dark .card-FDVird:hover:before {
  border: none;
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}
.theme-dark .card-FDVird:hover .flex-1xMQg5 div,
.theme-dark .card-FDVird:hover .flex-1xMQg5 span,
.theme-dark .card-FDVird:hover .css-hsd1lu-singleValue,
.theme-dark .card-FDVird:hover .input-1UhAnY,
.theme-dark .card-FDVird:hover .description-3_Ncsb,
.theme-dark .card-FDVird:hover .labelDescriptor-1PqHgD,
.theme-dark .card-FDVird:hover .h5-18_1nd,
.theme-dark .card-FDVird:hover .gameName-1RiWHm,
.theme-dark .card-FDVird:hover .lastPlayed-3bQ7Bo,
.theme-dark .card-FDVird:hover .actionButton-VzECiy,
.theme-dark .card-FDVird:hover .tag-1YGWN9,
.theme-dark .card-FDVird:hover .roleWrapper-1Hde_V,
.theme-dark .card-FDVird:hover .overlayStatusText-L2IACa {
  color: var(--color-high);
}
.theme-dark .card-FDVird:hover .gameNameInput-385LoS:focus,
.theme-dark .card-FDVird:hover .gameNameInput-385LoS:hover {
  border-radius: 0;
  background: var(--color-high);
  color: var(--color-low);
}
.theme-dark .card-FDVird:hover .actionButton-VzECiy {
  border-color: var(--color-high);
}

.ghostPill-2-KUPM {
  border-radius: 0;
  background-color: var(--color-alert);
  color: var(--color-high);
}

.item-3eFBNF .checkbox-1ix_J3 {
  border-color: var(--color-low);
}
.item-3eFBNF:hover {
  background-color: var(--color-low);
}
.item-3eFBNF.selected-2DeaDa {
  background-color: var(--color-alert);
}
.item-3eFBNF:hover .checkbox-1ix_J3, .item-3eFBNF.selected-2DeaDa .checkbox-1ix_J3 {
  border-color: var(--color-high);
}
.item-3eFBNF:hover .description-3_Ncsb,
.item-3eFBNF:hover .labelDescriptor-1PqHgD,
.item-3eFBNF:hover .labelText-2kBs7x, .item-3eFBNF.selected-2DeaDa .description-3_Ncsb,
.item-3eFBNF.selected-2DeaDa .labelDescriptor-1PqHgD,
.item-3eFBNF.selected-2DeaDa .labelText-2kBs7x {
  color: var(--color-high);
}

.background-1QDuV2 {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 6px 6px 0 var(--color-mid);
}

.userSettingsSecurity-3IYeMF .isEnabled-24g9qA,
.theme-dark .lookLink-9FtZy-.colorPrimary-3b3xI6 {
  color: var(--color-low);
}

.wrapper-3jrx9n {
  background-color: var(--color-high);
  border-radius: 0;
  border-color: var(--color-alert);
}

.option-n0icdO {
  background: var(--color-low);
  border-radius: 0;
  box-shadow: 2px 2px 0 var(--color-mid);
}
.option-n0icdO:hover {
  box-shadow: 2px 2px 0 var(--color-mid);
  background: var(--color-low);
}
.option-n0icdO.selected-mKYnfr {
  background: var(--color-alert);
}

.wrapper-3jrx9n.disabledSelected-2Kf0yZ {
  border-color: var(--color-alert);
}

.disabled-3I9jyo {
  color: var(--color-mid);
}
.disabled-3I9jyo.selected-mKYnfr, .disabled-3I9jyo:hover {
  color: var(--color-alert);
}

.theme-dark .elevationHigh-1PneE4 {
  background-color: var(--color-high) !important;
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}
.theme-dark .elevationHigh-1PneE4 .contents-18-Yxp span,
.theme-dark .elevationHigh-1PneE4 .message-c9-HCF {
  color: var(--color-low) !important;
}

.cardPrimary-1Hv-to {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 4px 4px 0 var(--color-mid);
}

.css-118dehu-control,
.container-1nZlH6,
.lookGhost-2Fn_0-.colorGrey-2DXtkV {
  color: var(--color-high);
  border-radius: 0;
  border: 1px solid var(--color-mid);
  background-color: transparent;
}

.draggable-1EOU8o {
  padding: 1px 0;
}

.theme-dark #bd-settings-sidebar .ui-tab-bar-item,
.side-8zPYf6 .item-PXvHYJ {
  transition: color 0.2s;
  border-radius: 0;
  margin: 2px 0;
}
.theme-dark #bd-settings-sidebar .ui-tab-bar-item .themed-OHr7kt.selected-3s45Ha, .theme-dark #bd-settings-sidebar .ui-tab-bar-item:hover.themed-OHr7kt, .theme-dark #bd-settings-sidebar .ui-tab-bar-item,
.side-8zPYf6 .item-PXvHYJ .themed-OHr7kt.selected-3s45Ha,
.side-8zPYf6 .item-PXvHYJ:hover.themed-OHr7kt,
.side-8zPYf6 .item-PXvHYJ {
  background-color: transparent !important;
  height: 32px;
}
.theme-dark #bd-settings-sidebar .ui-tab-bar-item:before,
.side-8zPYf6 .item-PXvHYJ:before {
  z-index: -1;
  content: "";
  position: absolute;
  left: 0;
  top: 2px;
  bottom: 2px;
  transition: width 0.4s;
  animation-name: pulsingBackground;
  animation-duration: 1.5s;
  animation-iteration-count: infinite;
  width: 0%;
}
.theme-dark #bd-settings-sidebar .ui-tab-bar-item[style*="color: rgb(255, 255, 255);"], .theme-dark #bd-settings-sidebar .ui-tab-bar-item.selected, .theme-dark #bd-settings-sidebar .ui-tab-bar-item.selected-3s45Ha, .theme-dark #bd-settings-sidebar .ui-tab-bar-item:hover,
.side-8zPYf6 .item-PXvHYJ[style*="color: rgb(255, 255, 255);"],
.side-8zPYf6 .item-PXvHYJ.selected,
.side-8zPYf6 .item-PXvHYJ.selected-3s45Ha,
.side-8zPYf6 .item-PXvHYJ:hover {
  color: var(--color-high) !important;
  box-shadow: 0 1px var(--color-low), 0 -1px var(--color-low);
}
.theme-dark #bd-settings-sidebar .ui-tab-bar-item[style*="color: rgb(255, 255, 255);"]:before, .theme-dark #bd-settings-sidebar .ui-tab-bar-item.selected:before, .theme-dark #bd-settings-sidebar .ui-tab-bar-item.selected-3s45Ha:before, .theme-dark #bd-settings-sidebar .ui-tab-bar-item:hover:before,
.side-8zPYf6 .item-PXvHYJ[style*="color: rgb(255, 255, 255);"]:before,
.side-8zPYf6 .item-PXvHYJ.selected:before,
.side-8zPYf6 .item-PXvHYJ.selected-3s45Ha:before,
.side-8zPYf6 .item-PXvHYJ:hover:before {
  width: 100%;
}
.theme-dark #bd-settings-sidebar .ui-tab-bar-item[style*="color: rgb(255, 255, 255);"] path, .theme-dark #bd-settings-sidebar .ui-tab-bar-item.selected path, .theme-dark #bd-settings-sidebar .ui-tab-bar-item.selected-3s45Ha path, .theme-dark #bd-settings-sidebar .ui-tab-bar-item:hover path,
.side-8zPYf6 .item-PXvHYJ[style*="color: rgb(255, 255, 255);"] path,
.side-8zPYf6 .item-PXvHYJ.selected path,
.side-8zPYf6 .item-PXvHYJ.selected-3s45Ha path,
.side-8zPYf6 .item-PXvHYJ:hover path {
  fill: var(--color-high);
}
.theme-dark #bd-settings-sidebar .ui-tab-bar-item[style="color: rgb(240, 71, 71); background-color: rgba(240, 71, 71, 0.1);"], .theme-dark #bd-settings-sidebar .ui-tab-bar-item[style="color: rgb(240, 71, 71);"],
.side-8zPYf6 .item-PXvHYJ[style="color: rgb(240, 71, 71); background-color: rgba(240, 71, 71, 0.1);"],
.side-8zPYf6 .item-PXvHYJ[style="color: rgb(240, 71, 71);"] {
  color: var(--color-alert) !important;
}

.theme-dark .passthroughSelected-1Eq0Kl {
  background: var(--color-low);
}
.theme-dark .item-3T2z1R {
  border: 1px solid var(--color-low);
  border-radius: 0;
}

.gradientContainer-10lXLB,
.wrapper-2qzCYF.minimum-28Z35l,
.wrapper-2qzCYF {
  background-image: none;
  background-color: transparent;
}

.tile-2naSqK {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 5px 5px 0 var(--color-low-trans);
}

.container-1giJp5 {
  border-bottom: none;
  padding-bottom: 0;
}

.colorable-1bkp8v.white-3GPOIp {
  background: var(--color-high);
  color: var(--color-low);
}
.colorable-1bkp8v.white-3GPOIp:hover {
  background: var(--color-mid);
}
.colorable-1bkp8v.white-3GPOIp.active-1QRrIS {
  background: var(--color-high);
}
.colorable-1bkp8v.white-3GPOIp .centerIcon-2G6o-T {
  color: var(--color-low);
}
.colorable-1bkp8v.primaryDark-3mSFDl {
  background: var(--color-low);
  color: var(--color-high);
}
.colorable-1bkp8v.primaryDark-3mSFDl:hover {
  background: var(--color-mid);
}
.colorable-1bkp8v.primaryDark-3mSFDl .centerIcon-2G6o-T {
  color: var(--color-high);
}
.colorable-1bkp8v.red-33-Lnk, .colorable-1bkp8v.red-33-Lnk:hover {
  background: var(--color-alert);
}
.colorable-1bkp8v.red-33-Lnk .centerIcon-2G6o-T, .colorable-1bkp8v.red-33-Lnk:hover .centerIcon-2G6o-T {
  color: var(--color-high);
}

.clickable-3rdHwn .icon-22AiRD:hover,
.icon-22AiRD:hover,
.controlIcon-35oS15:hover {
  color: var(--color-mid);
}

.quickSelect-3BxO0K,
.quickSelectLabel-2r3iJ_,
.playingText-3KIkt6,
.controlIcon-35oS15,
.clickable-3rdHwn .icon-22AiRD,
.icon-22AiRD,
.name-3YKhmS,
.title-29uC1r {
  color: var(--color-low);
}

.status-254fhp {
  color: var(--color-low);
  background: var(--color-high-trans);
  border-radius: 0;
}

.overlayTitle-8IcS01 {
  border-radius: 0;
  background: var(--color-low-trans);
  color: var(--color-high);
}

.status-254fhp,
.border-3dQmSY.speaking-WDn8Wm,
.avatarSpeaking-3MqCHL {
  box-shadow: inset 0 0 0 2px var(--color-alert);
}

.slash-33-IMF,
.colorDefault-2K3EoJ .checkbox-3s5GYZ,
.colorDefault-2K3EoJ .radioSelection-1HmrQS {
  color: var(--color-alert);
}

.base-PmTxvP,
.liveLarge-3zs2Zq {
  border-radius: 0;
  background: var(--color-alert) !important;
  color: var(--color-high);
}

.theme-dark .quickSelectArrow-1QublR {
  -webkit-mask: url("https://discord.com/assets/f58cf3b8fc79e9d671ab649ab37651a9.svg");
          mask: url("https://discord.com/assets/f58cf3b8fc79e9d671ab649ab37651a9.svg");
  background: var(--color-low) !important;
  -webkit-mask-repeat: no-repeat;
          mask-repeat: no-repeat;
}

.theme-dark .tooltipGrey-1hnvTt {
  color: var(--color-low);
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}
.theme-dark .tooltipGrey-1hnvTt .tooltipPointer-3ZfirK {
  border: none;
}

.draggable-2E_4tJ {
  height: 29px;
  margin: 1px 0 1px 0;
}
.draggable-2E_4tJ .clickable-1lCRLF {
  height: 28px;
  border-radius: 0;
}
.draggable-2E_4tJ .clickable-1lCRLF .icons-1dXQdz svg,
.draggable-2E_4tJ .clickable-1lCRLF .avatarSmall-1PJoGO,
.draggable-2E_4tJ .clickable-1lCRLF .username-3KYl0N,
.draggable-2E_4tJ .clickable-1lCRLF .icons-1dXQdz {
  z-index: 1;
  transition: color 0.2s;
}
.draggable-2E_4tJ .clickable-1lCRLF .content-1Wq3SX {
  height: 28px;
  background-color: transparent !important;
  border-radius: 0;
}
.draggable-2E_4tJ .clickable-1lCRLF .content-1Wq3SX:before {
  content: "";
  position: absolute;
  left: 0;
  top: 1px;
  bottom: 1px;
  transition: width 0.3s;
  animation-name: pulsingBackground;
  animation-duration: 1.5s;
  animation-iteration-count: infinite;
  width: 0%;
}
.draggable-2E_4tJ .clickable-1lCRLF.selected-3t3Csj .content-1Wq3SX, .draggable-2E_4tJ .clickable-1lCRLF:hover .content-1Wq3SX {
  box-shadow: 0 1px var(--color-low), 0 -1px var(--color-low);
}
.draggable-2E_4tJ .clickable-1lCRLF.selected-3t3Csj .content-1Wq3SX .icons-1dXQdz svg,
.draggable-2E_4tJ .clickable-1lCRLF.selected-3t3Csj .content-1Wq3SX .avatarSmall-1PJoGO,
.draggable-2E_4tJ .clickable-1lCRLF.selected-3t3Csj .content-1Wq3SX .username-3KYl0N,
.draggable-2E_4tJ .clickable-1lCRLF.selected-3t3Csj .content-1Wq3SX .icons-1dXQdz, .draggable-2E_4tJ .clickable-1lCRLF:hover .content-1Wq3SX .icons-1dXQdz svg,
.draggable-2E_4tJ .clickable-1lCRLF:hover .content-1Wq3SX .avatarSmall-1PJoGO,
.draggable-2E_4tJ .clickable-1lCRLF:hover .content-1Wq3SX .username-3KYl0N,
.draggable-2E_4tJ .clickable-1lCRLF:hover .content-1Wq3SX .icons-1dXQdz {
  color: var(--color-high);
  z-index: 1;
}
.draggable-2E_4tJ .clickable-1lCRLF.selected-3t3Csj .content-1Wq3SX:before, .draggable-2E_4tJ .clickable-1lCRLF:hover .content-1Wq3SX:before {
  width: 100%;
}

.theme-dark .streamPreview-2-WUWT {
  background: var(--color-high);
  border-radius: 0;
  box-shadow: 3px 3px 0 var(--color-mid);
}

.theme-dark .activityStreamPreview-3r3GiX .activityName-1IaRLn,
.theme-dark .activityStreamPreview-3r3GiX .content-3JfFJh,
.theme-dark .activityStreamPreview-3r3GiX .details-38sfDr,
.theme-dark .activityStreamPreview-3r3GiX .name-29ETJS {
  color: var(--color-low);
}
