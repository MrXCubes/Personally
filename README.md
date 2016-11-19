Skip to content
This repository
Search
Pull requests
Issues
Gist
 @MrXCubes
 Watch 9
  Star 21
  Fork 43 cosmicsalad/Discord-Themes-and-Plugins
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Pulse  Graphs
Branch: master Find file Copy pathDiscord-Themes-and-Plugins/themes/DarkMatter/DarkMatter.theme.css
86ebc93  2 days ago
@cosmicsalad cosmicsalad Profile fixes
2 contributors @cosmicsalad @shinji257
RawBlameHistory     
1935 lines (1553 sloc)  40.7 KB
//META{"name":"Dark_Matter","description":"A cold, dark & frosty theme","author":"Hammock (CosmicSalad)","version":"1.5.1"}*//{}
@import url(https://fonts.googleapis.com/css?family=Karla);

/*
                     _                _                                   _ 
  __ _ _ __  _ __   | |__   __ _  ___| | ____ _ _ __ ___  _   _ _ __   __| |
 / _` | '_ \| '_ \  | '_ \ / _` |/ __| |/ / _` | '__/ _ \| | | | '_ \ / _` |
| (_| | |_) | |_) | | |_) | (_| | (__|   < (_| | | | (_) | |_| | | | | (_| |
 \__,_| .__/| .__/  |_.__/ \__,_|\___|_|\_\__, |_|  \___/ \__,_|_| |_|\__,_|
      |_|   |_|                           |___/                             
*/

/* Main background and settings background */
.app,
.callout-backdrop {
	background:url(http://i.imgur.com/2U46vm8.jpg) !important;
	background-size:cover !important;
}

/*
                           _                           _       
  ___ ___  _ __ ___    ___| | ___ _ __ ___   ___ _ __ | |_ ___ 
 / __/ _ \| '__/ _ \  / _ \ |/ _ \ '_ ` _ \ / _ \ '_ \| __/ __|
| (_| (_) | | |  __/ |  __/ |  __/ | | | | |  __/ | | | |_\__ \
 \___\___/|_|  \___|  \___|_|\___|_| |_| |_|\___|_| |_|\__|___/
*/

div>*:not(code) {
    font-family: 'Karla',Whitney,Helvetica Neue,Helvetica,Arial,Lucida Grande,sans-serif !important;
}

textarea {
	background:transparent !important;
}

.scroller-wrap .scroller::-webkit-scrollbar-thumb {
	border:3px solid rgba(255,255,255,0) !important;
	background-color:#1D6586 !important;
}

.scroller-wrap .scroller::-webkit-scrollbar-track-piece {
	border:3px solid rgba(255,255,255,0) !important;
	background-color:rgba(0,0,0,0.3) !important;
}

/*
 _     _     _      
| |__ (_) __| | ___ 
| '_ \| |/ _` |/ _ \
| | | | | (_| |  __/
|_| |_|_|\__,_|\___|
*/

.links,
.help-container {
	display: none;
}

/*
                 _         _                _                                   _     
 _ __ ___   __ _(_)_ __   | |__   __ _  ___| | ____ _ _ __ ___  _   _ _ __   __| |___ 
| '_ ` _ \ / _` | | '_ \  | '_ \ / _` |/ __| |/ / _` | '__/ _ \| | | | '_ \ / _` / __|
| | | | | | (_| | | | | | | |_) | (_| | (__|   < (_| | | | (_) | |_| | | | | (_| \__ \
|_| |_| |_|\__,_|_|_| |_| |_.__/ \__,_|\___|_|\_\__, |_|  \___/ \__,_|_| |_|\__,_|___/
                                                |___/                                 
*/

.links,
.chat,
.typing,
.content,
.guild-channels,
.private-channels,
.guild-header header,
.divider-red span,
.messages-wrapper,
#voice-connection {
	background: transparent !important;
}

/* Server list area */
.guilds-wrapper { background:rgba(0,0,0,0.6) !important }

/* Channels list area */
.channels-wrap { background:rgba(0,0,0,0.7) }

/* Chat area */
.content .flex-spacer { background:rgba(0,0,0,0.8) }

/* User list area */
.channel-members { background:rgba(0,0,0,0.9) !important }

/*
                                _ _     _                   _   _             
 ___  ___ _ ____   _____ _ __  | (_)___| |_   ___  ___  ___| |_(_) ___  _ __  
/ __|/ _ \ '__\ \ / / _ \ '__| | | / __| __| / __|/ _ \/ __| __| |/ _ \| '_ \ 
\__ \  __/ |   \ V /  __/ |    | | \__ \ |_  \__ \  __/ (__| |_| | (_) | | | |
|___/\___|_|    \_/ \___|_|    |_|_|___/\__| |___/\___|\___|\__|_|\___/|_| |_|
*/ 

.create-guild-container {
	background:none !important;
}

.create-guild-container .action {
	background:rgba(0,0,0,0.7);
}

.create-guild-container .create-or-join .actions .or {
	-webkit-filter:opacity(0.9) invert();
	color:#000;
}

.create-guild-container .action.create .action-icon,
.create-guild-container .action.join .action-icon {
	-webkit-filter:invert() hue-rotate(150deg);
}

.create-guild-container h5,
.create-guild-container .action.create .action-header {
	color:#25ACE8;
}

.create-guild-container .action.create .btn-primary {
	background-color:#25ACE8 !important;
}

.create-guild-container .action.create:hover .btn-primary {
	background-color:#1D6586 !important;
}

.create-guild-container .form-actions .btn-default {
	background: rgba(255,255,255,0.1);
    border: 0;
}

.create-guild-container .create-guild .guild-form .region-select {
	background: rgba(255,255,255,0.1);
}

.create-guild-container .create-guild .guild-form .region-select button {
	color:#000;
}

.create-guild-container .create-guild .guild-form .region-select:hover button {
	background-color:#25ACE8;
	border-color:#25ACE8;
	color:#fff;
}

.create-guild-container .create-guild .guild-form .region-select:hover .region-select-inner {
	border-color:#25ACE8;
}

.create-guild-container .create-guild .guild-form .region-select-name {
	color:#fff;
}

.avatar-uploader .avatar-uploader-inner {
	background-color: #25ACE8;
}

.region-select-modal {
	background:rgba(0,0,0,0.8);
}

.region-select-modal .region-select-modal-header {
	color:#25ACE8;
}

.region-select-modal .region-select-modal-option {
	background:rgba(255,255,255,0.1);
	border:2px solid rgba(255,255,255,0.1);
}

.region-select-modal .region-select-modal-option:hover {
	    border-color: #25ACE8;
}

.region-select-modal .region-select-modal-option .region-select-name {
	color:#fff;
}

.guild-header ul {
	background:#000 !important;
    opacity:0 !important;
    transition: transform .5s cubic-bezier(0.18, 0.89, 0.32, 1.28) !important;
    padding-top:100px;
    top:-56px;
}

.guild-header-open ul {
	opacity:1 !important;
}

.guilds-add {
    opacity:0.5;
    font-size:22px !important;
}

.platform-osx .guilds-wrapper {
    padding-top:30px;
}

.guilds-wrapper {
	border-right:1px solid rgba(0,0,0,0.4);
	box-shadow:inset -10px 0px 20px -10px rgba(0,0,0,0.2);
}

.guilds-wrapper .guild-separator {
	margin-top:5px;
    margin-bottom:5px;
	margin-left:-5px;
	display:none;
}

.guilds-wrapper .guild-separator:after {
	background:transparent;
}

.guild-header header span {
	margin-left:-7px;
}

.guild-header header {
	box-shadow:none !important;
	color:#ddd;
}

.guild-channels header h2 {
	padding:0 18px;
}

.guild-channels .channel-text .channel-name,
.guild-channels .channel-voice .channel-name {
	font-size:0.9em;
}

.guild-channels .channel-text a {
	padding:8px 6px 10px 18px;
}

.guild-channels header h2,
.guild-channels .channel a {
	color:#fff;
}

.guilds-wrapper .guilds {
	padding:18px 20px 85px 20px;
}

.guilds-add {
	font-size:30px;
	background:#000;
}

.guilds-wrapper .guilds .friends-online {
	
}

.guilds-wrapper .guilds .guild .guild-inner {
	background:#151515 !important;
}

.guilds-wrapper .guilds .guild.active:first-of-type .guild-inner {
	background:#25ACE8 !important;
}

.guilds-wrapper .guilds .guild .guild-inner:hover {
	background:#1D6586 !important;
}

.guilds-wrapper .guilds .guild .guild-inner a,
.guilds-wrapper .guilds .guild,
.guilds-wrapper .guilds .guild .avatar-small {
	width:40px;
	height:40px;
}

.guilds-wrapper .guilds .guild .avatar-small {
	width:40px;
	height:40px;
	background-size: 40px 40px;
}

.guilds-wrapper .guilds .guild .guild-inner {
	line-height:40px;
}

.guilds-wrapper .guilds .friends-icon {
	width:40px;
	height:40px;
	background-size:25px 19px;
}

.guilds-wrapper .guilds .friends-icon {
    background-color: rgba(0,0,0,0.3) !important;
    background-image: none !important;
    padding-top:0px;
}

.guilds-wrapper .guilds .friends-icon:after {
    display:block;
    width:40px;
    height:40px;
    content:'';
    background-image: url(https://i.imgur.com/cm6mEXd.gif) !important;
    background-size:110%;
    background-repeat:no-repeat;
    background-position:top center;
}

.guilds-wrapper .guilds .guild.audio .guild-inner:after {
	background-size:12px;
	background-color:rgba(0,0,0,0.8);
}

.guilds-wrapper .guilds .guild:before,
.guilds-wrapper .guilds .guild.unread:before,
.guilds-wrapper .guilds .guild.selected:before {
	left:-26px;
	transition:0.2s ease-in-out all;
}

.guilds-wrapper .guilds .guild.unread:not(.selected):before,
.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
	background:#25ACE8;
}

.guilds-wrapper .guilds .guild.active .guild-inner:before {
	background:#fff !important;
}

.guilds-wrapper .guilds .friends-online {
	color: #ccc;
    font-size: 9px;
    margin: 15px 0 15px -7px;
    line-height: 20px;
    width: 55px;
    height: 20px;
    border-radius: 25px;
    overflow: hidden;
    background: rgba(0,0,0,0.3);
}

.guilds-wrapper .guilds-error {
	width:40px;
	height:40px;
	line-height:36px;
}

.guild-channels header h2,
.private-channels header {
	opacity:.6;
}

.guild-channels .channel:hover {
	background:rgba(0,0,0,0.3) !important;
}

.private-channels .search-bar {
	background:rgba(10,13,16,0) !important;
}

.private-channels .search-bar input {
	background:rgba(0,0,0,0.8) !important;
}

.guild-channels .channel.selected,
.private-channels .channel.selected,
.private-channels .search-result.selected,
.private-channels .search-result:hover {
	background:rgba(0,0,0,0.6) !important;
}

.guild-channels ul .channel:not(.selected):hover,
.private-channels .channel:not(.selected):hover {
	background:rgba(0,0,0,0.3) !important;
}

.guild-channels .channel:not(.selected):before,
.guild-channels .channel.selected:before,
.guild-channels .channel.selected:hover:before,
.private-channels .channel:not(.selected):before,
.private-channels .channel.selected:before,
.private-channels .channel.selected:hover:before,
.private-channels .search-result.selected:before,
.private-channels .search-result:hover:before {
	border-left:2px solid #1D6586 !important;
}

.private-channels .channel .icon-friends {
	background-color:#151515 !important;
}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
	left:-8px;
}

/*
      _                            _                     _   _             
  ___| |__   __ _ _ __  _ __   ___| |___   ___  ___  ___| |_(_) ___  _ __  
 / __| '_ \ / _` | '_ \| '_ \ / _ \ / __| / __|/ _ \/ __| __| |/ _ \| '_ \ 
| (__| | | | (_| | | | | | | |  __/ \__ \ \__ \  __/ (__| |_| | (_) | | | |
 \___|_| |_|\__,_|_| |_|_| |_|\___|_|___/ |___/\___|\___|\__|_|\___/|_| |_|
*/

.btn-hamburger {
	margin-right:-30px;
}

.btn-hamburger span {
	background:#fff;
}

.account {
	z-index:9;
	border-top:none !important;
	width:320px;
    margin-left:-80px;
	padding:0 15px !important;
	background:rgba(0,0,0,0.95);
	height:77px;
	box-sizing:border-box;
}

.account .status {
    border:2px solid rgba(0,0,0,1);
}

.account .btn {
	background:transparent;/*#000;*/
	box-shadow:none !important;
}

.account .btn:active {
	background:#000;
}

.account .btn-settings:after {
	opacity:0.3;
}

.account .btn-deafen,
.account .btn-mute {
    border-right:none;/*1px solid #101010;*/
}

#voice-connection {
	z-index:9;
	border-top:none !important;
	/*width:285px;
    margin-left:-83px;*/
	padding:15px 20px 15px 18px !important;
}

#voice-connection .btn {
	background:#000;
	box-shadow:none !important;
}

.account .btn-deafen, .account .btn-settings {
	box-shadow:none !important;
}

.account .btn-group, #voice-connection .btn-group {
	border:none;
}

.account .avatar-small {
	margin:0 0 0 10px;
}

.message-group .comment {
	background:transparent !important;
	border:none !important;
}

/*
      _           _                   _   _             
  ___| |__   __ _| |_   ___  ___  ___| |_(_) ___  _ __  
 / __| '_ \ / _` | __| / __|/ _ \/ __| __| |/ _ \| '_ \ 
| (__| | | | (_| | |_  \__ \  __/ (__| |_| | (_) | | | |
 \___|_| |_|\__,_|\__| |___/\___|\___|\__|_|\___/|_| |_|
*/

.header-toolbar button.popout-open {
	background:#25ACE8;
}

.channel-pins-wrap {
    background: rgba(0,0,0,0.9) !important;
}

.channel-pins-wrap .header,
.channel-pins-wrap .footer {
    background-color: rgba(0,0,0,0.95) !important;
    box-shadow: none !important;
}

.channel-pins .message-group {
    background-color: rgba(0,0,0,0.7) !important;
}

.channel-pins .message-group:hover {
    box-shadow: 0 0 4px 5px rgba(37, 172, 232, 0.1);
    border-color: rgba(37, 172, 232, 0.47) !important;
}

.channel-pins .message-group .action-buttons {
	box-shadow: none !important;
    background: none !important;
}

.channel-pins .message-group .action-buttons .jump-button {
	background-color: rgba(255,255,255,0.15) !important;
}

.spinner-wandering-cubes .spinner-item {
	background-color:#25ACE8;
	width:15px;
	height:15px;
	border-radius:4px;
}

.chat .has-more button {
	color:#25ACE8 !important;
	background:rgba(255,255,255,0.1) !important;
	border:none !important;
	box-shadow:none !important;
}

.highlight {
	color:#25ACE8;
}

.emoji-picker {
	background:rgba(0,0,0,0.85) !important;
}

.emoji-picker .search-bar input {
	color:rgba(255,255,255,0.7);
	background:rgba(255,255,255,0.1);
}

.emoji-picker .search-bar-clear {
	background:rgba(0,0,0,0.7);
}

.emoji-picker .sticky-header,
.emoji-picker .search-bar {
	background:rgba(0,0,0,0.95) !important;
}

.emoji-picker .categories .item.selected {
	border-bottom-color:#25ACE8;
}

.title-wrap {
	border-bottom:1px solid rgba(0,0,0,0.3) !important;
	background:rgba(0,0,0,0.95) !important;
}

.header-toolbar button.active {
	background-color:rgba(255,255,255,0.1);
}

.bot-tag,
.need-help-modal .header {
	background:#25ACE8;
}

.form header {
	color:#25ACE8;
}

.markdown-modal,
.form .form-inner,
.form .form-header,
.form .form-actions,
.need-help-modal .footer,
.markdown-modal .markdown-modal-footer {
	background:rgba(0,0,0,0.85) !important;
}

.alert.form .form-inner .btn {
	padding: 0 !important;
	border: none !important;
}

.channel-notification-settings .content label,
.notification-settings-modal .mute-server .checkbox .label span {
	color:#fff;
}

.notification-settings-modal .notification-settings-modal-channel-settings-list {
	box-shadow:none !important;
}

.markdown-modal .markdown-modal-header {
	color:#fff;
}

.form .form-header,
.form .form-actions,
.need-help-modal .footer,
.channel-notification-settings,
.markdown-modal .markdown-modal-header,
.markdown-modal .markdown-modal-footer {
	border-color:rgba(255,255,255,0.2);
}

.modal-content .user-name {
	color:#fff;
}

.modal-content .form-inner p {
	color:rgba(255,255,255,0.7);
}

.chat .new-messages-bar {
	background-color:rgba(29,101,134,.9);
}

.chat .new-messages-bar:hover {
	background-color:rgba(29,101,134,1);
}

.chat .new-messages-bar button:last-child {
	color:rgba(255,255,255,0.5);
}

.chat-empty {
	background:rgba(20,23,27,0.95);
}

.chat>.title-wrap>.title .channel-name {
	color:rgba(255,255,255,0.8);
}

.chat>.title-wrap>.topic {
	font-size:12px;
	margin-top:5px;
	color:#656565 !important;
}

.markdown-modal .highlight,
.chat .title-wrap .topic .highlight {
	background-color:rgba(255,255,255,.1) !important;
}

.markdown-modal .highlight:hover,
.chat .title-wrap .topic .highlight:hover {
	background-color:rgba(255,255,255,.2) !important;
	color:#25ACE8 !important;
}

.chat .divider {
	height:25px;
	background:none;
}

.chat .divider>div {
	display:none !important;
}
.chat .divider:not(.divider-red)>div {
	background:rgba(255,255,255,0.2) !important;
}

.chat .divider:before {
	background:rgba(255,255,255,0.1) !important;
	height:25px;
}

.chat .divider.divider-red:before {
	background: rgba(240,71,71,.8) !important;
}

.chat .divider>span {
	background-color:transparent !important;
	font-size:12px;
	text-transform:uppercase;
	margin:10px 0px;
	border-radius: 0px;
	opacity: 1;
    padding: 8px 15px;
    line-height: 1px;
    width: 100%;
    text-align: center;
}

.chat .divider.divider-red>span {
    color: rgba(255,255,255,0.9) !important;
}

.chat .divider:not(.divider-red)>span {
	color:rgba(255,255,255,1) !important;
}

.chat .divider>div {
	display:none;
}

.chat form {
	border-top: none !important;
}

.messages .message-group:not(.has-divider) {
    border-bottom-color:hsla(0,0%,100%,.04) !important;
}

.messages .message-group {
	border-bottom: none !important;
}

.friends-table .messages .message-group .message-send-failed .markup,
.friends-table .messages .message-group .message-send-failed .markup a,
.messages .message-group .message-send-failed .markup,
.messages .message-group .message-send-failed .markup a {
	color:rgba(240,71,71,0.5) !important;
	font-style:italic;
}

.mentioned .message-text {
	border-radius: 0 !important;
	background: rgba(37,172,232,0.2) !important;
}

.mentioned .message-text:after {
	border-radius: 0 !important;
	border-color:#25ACE8 !important;
	background:rgba(37,172,232,0.2) !important;
}

.messages a {
	color:#25ACE8 !important;
}

.messages h2 .user-name {
	font-size:0.85em;
	color:rgba(255,255,255,0.8);
}

.messages h2 span {
	color:rgba(255,255,255,0.2) !important;
}

.messages h2 .bot-tag {
	color:rgba(255,255,255,0.8) !important;
}

.messages .markup {
	font-size:0.85em !important;
	line-height:1.4em !important;
}

.messages .markup:not([data-colour="true"]) {
	color:rgba(255,255,255,0.5) !important;
}

.markup pre {
	border-radius:0 !important;
	background:transparent !important;
    border-color:rgba(255,255,255,0.1) !important;
}

.markup pre code.hljs {
    background:rgba(255,255,255,0.1) !important;
    color:rgba(255,255,255,0.7) !important;
    padding:1em !important;
}

.modal-content .markup code.inline,
.markup code.inline {
	background:rgba(255,255,255,0.1) !important;
    color:rgba(255,255,255,0.7) !important;
	padding:0.3em 0.6em !important;
	border-radius:0 !important;
}

.messages .markup .highlight {
    background-color:rgba(29,101,134,.5) !important;
    color:#ddd !important;
	padding: 1px 4px;
    border-radius: 0;
}

.messages .markup .highlight:hover {
    background-color:rgba(29,101,134,1) !important;
    color:#fff !important;
}

.messages .invite-button {
	background: rgba(255,255,255,0.07) !important;
	border-color: rgba(255,255,255,0.1) !important;
}

.emotewrapper img {
	position: relative;
    top: 7px;
}

.channel-textarea-upload {
	border-right-color: hsla(0,0%,100%,.1) !important;
}

.channel-textarea-inner {
	border: 2px solid rgba(255,255,255,0.1) !important;
	background:rgba(0,0,0,0.6) !important;
}

.channel-textarea-autocomplete-inner {
	border:none !important;
	background:rgba(0,0,0,0.95) !important;
}

.channel-textarea-autocomplete-inner header {
	border:none !important;
	background: rgba(37,172,232,0.5) !important;
	color: rgba(255,255,255,0.9) !important;
}

.channel-textarea-autocomplete-inner ul li.active {
	background:rgba(255,255,255,0.1) !important;
}

.channel-textarea-guard button {
	background:#1D6586 !important;
}

.channel-textarea-guard button:hover {
	background:#25ACE8 !important;
}

.typing {
	font-size:11px;
}

.spoiler span {display:none;}
.spoiler:before {
    min-height:18px;
    padding-top:2px;
    border-radius:5px;
    background:rgba(25,25,25,0.7);
}

#twitchcord-button {
	background-size: 24px;
	background-position: 20px;
	background-color: transparent;
	opacity:0.4;
}

#twitchcord-button:hover,
#twitchcord-button.twitchcord-button-open {
	opacity:1;
}

#twitchcord-button-container {
	right:30px !important;
}

/*** COMPACT MODE ***/

.message-group.compact {
	margin-left:0;
}

.message-group.compact .timestamp {
	color:rgba(255,255,255,0.3) !important;
    position:relative;
    top:-1px;
}

.message-group.compact .message .markup .user-name {
    margin-right:8px;
    font-size:14px;
}

/*
  __      _                _       _ _     _   
 / _|_ __(_) ___ _ __   __| |___  | (_)___| |_ 
| |_| '__| |/ _ \ '_ \ / _` / __| | | / __| __|
|  _| |  | |  __/ | | | (_| \__ \ | | \__ \ |_ 
|_| |_|  |_|\___|_| |_|\__,_|___/ |_|_|___/\__|
*/

#friends .btn,
.add-friend-popout .btn,
.private-channels .channel.selected .icon-friends {
	background-color:#25ACE8 !important;
}

.add-friend-popout .btn:disabled {
	background-color:#1D6586 !important;
	opacity:0.4;
}

.private-channels .channel:hover:not(.selected) .icon-friends {
	background-color:#1D6586 !important;
}

.private-channels .channel.btn-friends .badge {
	margin-right:10px;
}

.private-channels .channel .close {
	margin-right:5px;
}

#friends {
	background:transparent !important;
}

.friends-header {
	background:rgba(0,0,0,0.95) !important;
}

.friends-table {
	background:rgba(0,0,0,0.85) !important;
	margin-top:0 !important;
}

.friends-header,
.friends-table .friends-table-header {
	border-bottom: 1px solid hsla(0,0%,100%,.1) !important;
}

.friends-header .tab-bar .tab-bar-separator,
.friends-table .friends-table-header .friends-column-separator {
	background-color:hsla(0,0%,100%,.1) !important;
}

.friends-table .friends-table-body {
	padding-top:20px !important;
}

.friends-table .friends-row:hover {
	background: rgba(0,0,0,0.7) !important;
}

/*
                       _ _     _                   _   _             
 _   _ ___  ___ _ __  | (_)___| |_   ___  ___  ___| |_(_) ___  _ __  
| | | / __|/ _ \ '__| | | / __| __| / __|/ _ \/ __| __| |/ _ \| '_ \ 
| |_| \__ \  __/ |    | | \__ \ |_  \__ \  __/ (__| |_| | (_) | | | |
 \__,_|___/\___|_|    |_|_|___/\__| |___/\___|\___|\__|_|\___/|_| |_|
*/

.channel-members .invite-btn {
	background:#1D6586;
}

.channel-members .invite-btn:hover {
	background:#25ACE8;
}

.channel-members .member:hover {
	background:rgba(255,255,255,0.07) !important;
}

.channel-members .member .member-username {
	font-size:12px;
}

.channel-members .member .member-game {
	font-size:10px;
}

.channel-members .avatar-small .status {
    border-color:rgba(0,0,0,0.7) !important;
}

.channel-members h2 {
	background: rgba(0,0,0,0);
    padding-top: 10px;
    padding-bottom: 10px;
}

.channel-members .member+h2 {
	margin-top:12px;
}

.channel-members h2:first-of-type {
	margin-top:0px !important;
}

/*
                       _        __                                       _   
 _   _ ___  ___ _ __  (_)_ __  / _| ___    _ __   ___  _ __   ___  _   _| |_ 
| | | / __|/ _ \ '__| | | '_ \| |_ / _ \  | '_ \ / _ \| '_ \ / _ \| | | | __|
| |_| \__ \  __/ |    | | | | |  _| (_) | | |_) | (_) | |_) | (_) | |_| | |_ 
 \__,_|___/\___|_|    |_|_| |_|_|  \___/  | .__/ \___/| .__/ \___/ \__,_|\__|
                                          |_|         |_|                    
*/

.user-popout .header {
	background:#25ACE8 !important;
}

.user-popout .avatar-wrapper .avatar-popout {
	border:4px solid rgba(0,0,0,0.9);
    background-color:rgba(0,0,0,0.9);
}

.user-popout .body {
	background:rgba(0,0,0,0.8);
	border-left:1px solid rgba(255,255,255,0.2);
	border-right:1px solid rgba(255,255,255,0.2);
}

.user-popout .footer {
	background:rgba(0,0,0,0.8);
    border-top:1px solid rgba(255,255,255,0.2);
    border-left:1px solid rgba(255,255,255,0.2);
	border-right:1px solid rgba(255,255,255,0.2);
	border-bottom:1px solid rgba(255,255,255,0.2);
}

.user-popout .footer .quick-message-wrapper .input {
	background:rgba(255,255,255,0.1);
	border-color:rgba(255,255,255,0.2);
	color:rgba(255,255,255,0.9);
}

.user-popout .username-wrapper .game,
.user-popout .username-wrapper.hasNickname .discriminator,
.user-popout .username-wrapper.hasNickname .username {
	color:rgba(0,0,0,0.7);
}

.popout header,
.slider-bar-fill {
	background-color:#25ACE8;
	border:1px solid #25ACE8;
}

.user-popout .user-popout-options .btn {
	background-color:#1D6586;
	border:1px solid #1D6586;
}

.user-popout .user-popout-options .btn:hover {
	background-color:#25ACE8;
	border:1px solid #25ACE8;
}

/* Admin buttons */
.user-popout .user-popout-options .btn.btn-server {
    color: rgba(255,255,255,0.7);
    background: rgba(240,71,71,0.4);
	border: none !important;
}

.user-popout .user-popout-options .btn.btn-server:hover {
	color: rgba(255,255,255,1);
    background: rgba(240,71,71,1);
	border: none !important;
}

/*
 _              _ _   _           
| |_ ___   ___ | | |_(_)_ __  ___ 
| __/ _ \ / _ \| | __| | '_ \/ __|
| || (_) | (_) | | |_| | |_) \__ \
 \__\___/ \___/|_|\__|_| .__/|___/
                       |_|        
*/

.tooltip {
    background:#1D6586;
    color:#e0e0e0;
}

.tooltip.tooltip-right:after {
    border-right-color:#1D6586;
}

.tooltip.tooltip-top:after {
    border-top-color:#1D6586;
}

.tooltip.tooltip-bottom:after {
    border-bottom-color:#1D6586;
}

/*
           _       _                 _                       _      
 _ __ ___ (_)_ __ (_)_ __ ___   __ _| |  _ __ ___   ___   __| | ___ 
| '_ ` _ \| | '_ \| | '_ ` _ \ / _` | | | '_ ` _ \ / _ \ / _` |/ _ \
| | | | | | | | | | | | | | | | (_| | | | | | | | | (_) | (_| |  __/
|_| |_| |_|_|_| |_|_|_| |_| |_|\__,_|_| |_| |_| |_|\___/ \__,_|\___|
*/

/* SERVER LIST */
.bd-minimal .channel-text a,
.bd-minimal .guild-channels ul .channel-voice {
	padding:5px 5px 5px 10px !important;
}

.bd-minimal .guilds-wrapper .guilds {
	padding-left:10px !important;
}

.bd-minimal .guilds-wrapper .guilds .friends-icon {
	background-size:60% !important;
}

.bd-minimal .guilds-wrapper .guilds .guild:before {
	width:10px;
    height:25px;
    border-radius:5px;
    margin-top:-13px;
	left:-16px;
}

.bd-minimal .guilds-wrapper .guilds .guild.unread:before {
	height:10px;
	margin-top:-5px;
}

.bd-minimal .guilds-wrapper .guilds .guild.selected:before {
	border-radius:5px;
	height:25px;
	margin-top:-13px;
}

.bd-minimal .guilds-wrapper .guilds .guild,
.bd-minimal .guilds-wrapper .guilds .guild .guild-inner,
.bd-minimal .guilds-wrapper .guilds .guild .guild-inner .avatar-small,
.bd-minimal .guilds-wrapper .guilds .guild .guild-inner .friends-icon {
	width:25px;
    height:25px;
    line-height:25px;
    background-size:25px 25px;
    font-size:10px !important;
}

.bd-minimal .guilds-wrapper .guilds .friends-online {
    font-size: 10px;
    word-spacing: 50px;
    line-height: 20px;
    margin-left: 0px;
    width: 25px;
    height: 20px;
    border-radius: 20px;
    overflow: hidden;
    background: rgba(0,0,0,0.5);
}

.bd-minimal .guilds-wrapper .guild-separator {
	width:25px;
	margin-left:0;
}

/* CHAT */
.bd-minimal .chat>.title-wrap>.title {
    font-size: 16px;
}

.bd-minimal .theme-dark .comment {
	border-left:none !important;
	padding-left:10px;
}

.bd-minimal .message-group {
	padding:10px 5px;
}

.bd-minimal .avatar-large {
	border-radius:100%;
}

.bd-minimal .message-group .edit-message .edit-container-outer {
    margin-left:50px;
}

.bd-minimal .message-group .edit-message .edit-container-inner {
	margin-left:10px;
}

/* MEMBERS */
.bd-minimal .channel-members h2 {
	margin-top:10px;
    margin-bottom:3px;
    padding-left:20px;
}

.bd-minimal .channel-members h2:first-of-type {
	margin-top:0px;
    margin-bottom:3px;
}

.bd-minimal .channel-members .member {
    padding:5px 15px 8px 20px;
}

/* CHANNELS */
.bd-minimal .guild-header header span {
	margin-left:-7px;
	font-size:14px;
}

.bd-minimal .guild-channels .channel-text .channel-name {
	padding-left:5px;
}

.bd-minimal .guild-channels header:first-of-type {
	margin-top:5px;
}

.bd-minimal .guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
	top:9px;
    width:10px;
    height:10px;
}

.bd-minimal .guild-channels h2 {
	margin-left:15px;
}

/* ACCOUNT BAR */
.bd-minimal #voice-connection {
	width:176px;
    margin-left:-46px;
}

.bd-minimal .account {
	width:206px;
    margin-left:-46px;
}

.bd-minimal .account .avatar-small {
	display:block !important;
	margin-left:2px;
}

.bd-minimal .account .username {
	display:none;
}

.bd-minimal .account .btn-group {
	margin-left:10px;
}

.bd-minimal .account .btn-group .btn {
	width:30px;
}

/*
          _   _   _                 
 ___  ___| |_| |_(_)_ __   __ _ ___ 
/ __|/ _ \ __| __| | '_ \ / _` / __|
\__ \  __/ |_| |_| | | | | (_| \__ \
|___/\___|\__|\__|_|_| |_|\__, |___/
                          |___/     
*/

.context-menu {
    background: rgba(0,0,0,0.95) !important;
}

.context-menu .item:hover,
.context-menu .item-subMenu {
	background-color:rgba(255,255,255,0.05) !important;
}

.avatar-uploader a {
	color:#25ACE8;
}

.avatar-uploader a:hover {
	color:#1D6586;
}

.settings .settings-header {
	background:#1a1d20 !important;
}

.form .btn-primary {
	background-color:#1D6586;
}

.form .btn-primary:hover {
	background-color:#25ACE8;
}

.user-settings-modal a {
	color:#1D6586;
}

.user-settings-modal a:hover {
	color:#25ACE8;
}

.channel-notification-settings .content .content-inner {
	background:transparent !important;
}

.callout-backdrop {
	opacity:0.55;
}

.tab-bar.SIDE {
    margin-right: -17px;
}

.tab-bar.SIDE .tab-bar-item.selected {
	background: rgba(0,0,0,0.7) !important;
}

.tab-bar.SIDE .tab-bar-item.selected:before {
	border-color:#25ACE8;
}

.tab-bar.SIDE .tab-bar-item:before {
	border-color:#1D6586;
}

.popout header,
.slider-bar-fill {
	border:none !important;
}

.slider-handle,
.Select-control {
	border:none !important;
}

.slider-bar {
	background: rgba(255,255,255,0.5);
}

.settings .settings-header {
	background:rgba(0,0,0,0.88) !important;
}

.settings .settings-inner,
.settings .settings-actions {
	background:rgba(0,0,0,0.75);
}

.settings .settings-actions {
	border-top:none !important;
}

.form .radio-group .radio,
.form .checkbox-group .checkbox,
.checkbox .checkbox-inner+span {
	color:rgba(255,255,255,0.7) !important;
	font-size: 0.95em;
}

.form .control-group input[type=email],
.form .control-group input[type=password],
.form .control-group input[type=text],
.form .control-group textarea {
	padding:5px 10px 5px 10px;
	border-radius:5px;
	box-sizing:border-box;
	border:1px solid rgba(255,255,255,0.1);
	background:rgba(0,0,0,0.5);
	color:rgba(255,255,255,0.5);
	font-size:14px;
}

.form .control-group input[type=email]:focus,
.form .control-group input[type=password]:focus,
.form .control-group input[type=text]:focus,
.form .control-group textarea:focus {
	border-color:rgba(255,255,255,0.3);
	background:rgba(0,0,0,0.7);
	color:rgba(255,255,255,1);
	font-size:14px;
}

.form .Select-control,
.form .Select-option {
	border:1px solid rgba(255,255,255,0.1) !important;
	background:rgba(0,0,0,0.5);
	color:rgba(255,255,255,0.5);
	font-size:14px;
}

.form .Select-option {
	border-top:none !important;
	background:rgba(0,0,0,0.7);
	color:rgba(255,255,255,0.4);
}

.form .Select-option.is-focused {
	border-top:none !important;
	background:rgba(0,0,0,1);
	color:rgba(255,255,255,1);
}

.Select-menu-outer {
	background:rgba(0,0,0,0.5);
	border:none !important;
}

.has-value>.Select-control>.Select-placeholder {
	color:rgba(255,255,255,0.8);
}

.form .btn-default {
	padding:10px 0 !important;
	width: 75px;
    height: 35.5px;
    border-radius: 3px;
}

.form hr,
.form .control-groups.control-separator,
.instant-invites .instant-invites-header,
.guild-settings-modal-integrations .guild-settings-modal-integrations-header,
.guild-settings-modal-members .guild-settings-modal-members-header,
.guild-settings-modal-members .guild-settings-modal-list .member+.member,
.guild-settings-modal-members .guild-settings-modal-members-footer,
#settings-roles .roles header,
#user-profile-modal .tab-bar {
	border-color:rgba(255,255,255,0.2);
	box-shadow:none;
}

.form .control-group input[type=email]:disabled,
.form .control-group input[type=password]:disabled,
.form .control-group input[type=text]:disabled,
.form .control-group textarea:disabled {
	background:rgba(255,255,255,0.2) !important;
}

.guild-settings-modal-members {
	background:none !important;
}

#settings-roles .roles {
	border-right:1px solid rgba(255,255,255,0.2);
}

#settings-roles .roles li:hover:before {
	background:#1D6586;
}

#settings-roles .roles li:hover:not(.selected) {
	background:rgba(0,0,0,0.9) !important;
}

#settings-roles .roles li.selected {
	background:rgba(0,0,0,0.5) !important;
}

#settings-roles .roles li.selected:before {
	background:#25ACE8;
}

.btn-help {
	font-size: 11px;
	background: rgba(255,255,255,0.3);
}

.btn-help:hover,
.radio:hover span:after {
	background:#1D6586;
}

.radio .radio-inner span:after {
	background:#25ACE8;
}

.user-settings-modal-keybinds .user-settings-modal-keybinds-header {
	border-bottom:1px solid rgba(255,255,255,0.2);
}

.user-settings-modal .voice-settings .reset-voice-settings {
	color:#1D6586;
}

.user-settings-modal .voice-settings .reset-voice-settings:hover {
	color:#1D6586;
	opacity:0.6;
}

.checkbox .checkbox-inner input[type=checkbox]:checked+span {
	background:#25ACE8;
	border-color:#25ACE8;
}

.user-settings-modal-connections .user-settings-modal-accounts-list .connect-container .name {
	color:rgba(255,255,255,0.8);
}

.user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-integrations.no-integrations {
	color:rgba(255,255,255,0.8);
}

.user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-integrations {
	border-color:#643DA7 !important;
}

.user-settings-modal-connections .user-settings-modal-connections-list {
	box-shadow: 0 -1px rgba(255,255,255,0.2);
}

.tab-bar.TOP {
	border-color:rgba(255,255,255,0.2);
}

.tab-bar.TOP .tab-bar-item.selected {
	border-color:#25ACE8;
	color:#25ACE8;
}

.user-settings-streamer-mode {
	background:none;
}

.user-settings-modal-games {
	background:rgba(255,255,255,0.05) !important;
	border:none !important;
}

.user-settings-modal-games .games-table .games-row .item-game,
.user-settings-modal-games .games-table .games-row .item-overlay {
	border-color:rgba(255,255,255,0.2) !important;
}

.user-settings-modal-games .games-table .games-row .item-game .game-input,
.user-settings-modal-games .games-table .games-row .item-game .game-name {
	color:#fff;
}

.user-settings-modal-games .games-table .games-row .item-game .last-played {
	color:rgba(255,255,255,0.5);
}

.now-playing {
	background:#25ACE8 !important;	
}

.now-playing.no-detection {
	background: rgba(0,0,0,0.8);
}

.bd-g-table tbody tr,
.bd-g-table thead th,
.bd-g-table tbody tr:nth-child(odd) {
	background:transparent !important;
}

.bd-g-table textarea {
	color: rgba(255,255,255,0.4) !important;
	background: rgba(255,255,255,0.2) !important;
	padding: 8px 10px !important;
	box-sizing:border-box;
}

#bd-pane .scroller-wrap div[style*="background:#2E3136; color:#ADADAD; height:30px; position:absolute; bottom:0; left:0; right:0;"] {
	background:rgba(0,0,0,0.95) !important;
}

.CodeMirror {
	background: rgba(255,255,255,0.15) !important;
    border-radius: 0px;
    color: rgba(255,255,255,0.8) !important;
}

.CodeMirror-gutters {
	background: rgba(255,255,255,0.25) !important;
	border:none !important;
}

.CodeMirror-linenumber {
	color: #fff !important;
}

.cm-s-neat span.cm-builtin {
	color:#25ACE8;
}

.cm-s-neat span.cm-atom,
.cm-s-neat span.cm-number {
	color:#25ACE8;
}

.member-roles .member-role {
	background-color: rgba(255,255,255,0.1);
	border:none;
	padding: 6px 8px;
	color: #fff;
}

.popout section {
	background:rgba(0,0,0,0.95) !important;
}

.popout.popout-bottom header:before {
	border-bottom-color:#1D6586;
}

#autocomplete-popout .row.selected,
#autocomplete-popout .row:hover {
	background:rgba(255,255,255,0.2) !important;
}

#permissions .permission-actions {
	color:rgba(255,255,255,0.7) !important;
}

#autocomplete-popout .empty h4,
#permissions .permissions-helpdesk,
.guild-settings-modal-members .guild-settings-modal-members-footer a {
	color:#25ACE8;
}

#permissions .permissions-helpdesk:hover,
.guild-settings-modal-members .guild-settings-modal-members-footer a:hover {
	color:#1D6586;
}

/*#user-profile-modal .header,*/
#user-profile-modal .btn {
	background:#25ACE8;
}

#user-profile-modal .btn:hover {
	background:#1D6586;
}

#user-profile-modal .guilds .section .connected-accounts .connected-account {
	border: 1px solid rgba(255, 255, 255, 0.15);
	background: rgba(0, 0, 0, 0.65);
}

#user-profile-modal .sub-header,
#user-profile-modal .tab-bar-container,
#user-profile-modal .scroller,
#user-profile-modal .empty,
#user-profile-modal footer {
	background:rgba(0,0,0,0.85) !important;
}

#user-profile-modal .tab-bar-container {
	border-bottom: 1px solid rgba(240, 240, 240, 0.15) !important;
}

#user-profile-modal .guilds .section+.section {
	border-top: 1px solid rgba(240, 240, 240, 0.15) !important;
}

#user-profile-modal .guilds .guild:hover {
	background:rgba(255,255,255,0.2) !important;
	color:rgba(255,255,255,0.7);
}

#user-profile-modal .avatar-profile {
    width: 126px !important;
    height: 126px !important;
}

#user-profile-modal .header .header-info .header-info-inner .discord-tag {
	font-size: 22px !important;
	font-weight: bold !important;
}

#user-profile-modal .avatar-wrapper {
	background-color: transparent;
}

#bd-customcss-attach-controls {
	background:rgba(0,0,0,0.85);
	border:none;
	box-shadow:none;
    padding:5px 10px 10px 10px;
}

#bd-customcss-attach-controls .checkbox > span {
	font-size:14px;
	margin-right:8px;
	margin-left:5px;
}

.bda-slist li {
	background:rgba(0,0,0,0.65) !important;
	border-top:1px solid rgba(255,255,255,0.2) !important;
	border-bottom:none;
}

.bda-slist li:nth-child(odd),
.bda-slist .bda-description {
	border:none;
}

.bda-slist li:first-of-type {
	border-top:none !important;
}

.bda-slist .bda-name {
	color:rgba(255,255,255,0.8);
	letter-spacing: .3px;
}

.bda-slist .bda-left {
	width:380px;
	padding:10px;
	box-sizing:border-box;
}

.bda-slist .bda-right .bda-plugin-reload {
	margin-top:25px;
}

.bda-slist .bda-right .btn {
	margin-left:-5px;
}

.bda-slist .bda-right .btn:disabled {
	opacity:0.3;
}

.bda-slist .checkbox {
	margin-left:10px;
	position:relative;
	top:8px;
}

.bda-slist {
	margin-bottom:25px;
}

.bda-slist-top {
    height: 35px;
}

#bd-themes-pane .bda-plugin-reload {
	margin-top:60px;
}

#bda-qem-favourite-container,
#bda-qem-twitch-container,
.emoji-picker {
	background-color: rgba(0,0,0,0.95) !important;
    border: 0px solid rgba(255,255,255,0.1) !important;
    border-top: none !important;
}

.emoji-picker .category {
	background-color: rgba(0,0,0,0.7) !important;
    border: 0px solid rgba(255,255,255,0.2) !important;
    border-top: none !important;
}

#bda-qem {
	padding-right: 0px !important;
    border-bottom: 0px solid rgba(0,0,0,0.5) !important;
    background: rgba(0,0,0,0.95) !important;
}

#bda-qem button {
	background: rgba(255,255,255,0.1) !important;
	box-shadow: rgba(0,0,0,0.5) 1px 0 0 0 !important;
}

#bda-qem button:hover {
    background: rgba(0,0,0,0.6) !important;
}

#bda-qem button.active {
    background: rgba(0,0,0,1) !important;
}

/* Scrollbar drag bar */
.emoji-picker .scroller::-webkit-scrollbar-thumb,
#bda-qem-twitch-container .scroller::-webkit-scrollbar-thumb,
#bda-qem-favourite-container .scroller::-webkit-scrollbar-thumb {
    background:rgba(255,255,255,0.4) !important;
    border-color:rgba(255,255,255,0) !important;
}

/* Scrollbar background */
.emoji-picker .scroller::-webkit-scrollbar,
.emoji-picker .scroller::-webkit-scrollbar-track,
.emoji-picker .scroller::-webkit-scrollbar-track-piece,
#bda-qem-favourite-container .scroller::-webkit-scrollbar,
#bda-qem-favourite-container .scroller::-webkit-scrollbar-track,
#bda-qem-favourite-container .scroller::-webkit-scrollbar-track-piece,
#bda-qem-twitch-container .scroller::-webkit-scrollbar,
#bda-qem-twitch-container .scroller::-webkit-scrollbar-track,
#bda-qem-twitch-container .scroller::-webkit-scrollbar-track-piece {
	background:rgba(255,255,255,0.1) !important;
    border-color:rgba(255,255,255,0) !important;
}

.instant-invite-modal {
	background: none;
}

#instant-invite-modal .copy {
	background-color: #25ACE8;
}

#instant-invite-modal .clipboard-input-inner input {
	color: #25ACE8;
}

.popout-menu {
	background: transparent !important;
}

.popout-menu.status-picker {
	background: transparent;
    width: 322px !important;
    margin-left: 0px !important;
    margin-bottom: 0 !important;
}

.popout-menu .popout-menu-separator {
    border-bottom: 1px solid rgba(255,255,255,0.2) !important;
}

.popout-menu .popout-menu-item {
    background: rgba(0,0,0,0.95) !important;
}

.popout-top .popout-menu .popout-menu-item {
    color: rgba(255,255,255,0.8) !important;
}

.popout-menu .popout-menu-item:hover {
    background-color: #1d6586 !important;
    color: rgba(255,255,255,0.8) !important;
}

.popout-top {
	top: auto !important;
	bottom: -126px !important;
}

.themed-popout {
    background-color: rgba(0, 0, 0, 0.95) !important;
    border: 1px solid rgba(255,255,255,.1) !important;
}

.themed-popout .header, .themed-popout .footer {
	background-color: #000 !important;
}

.themed-popout .messages-popout .message-group {
    border-color: rgba(28,36,43,0) !important;
    background-color: rgba(255, 255, 255, 0.07) !important;
}

.themed-popout .messages-popout .message-group:hover .action-buttons {
    box-shadow: 0 0 6px 4px rgba(255, 255, 255, 0.03) !important;
    background-color: rgba(255, 255, 255, 0.03) !important;
}

/*
             _     _ _        _     _     _   
 _ __  _   _| |__ | (_) ___  | |   (_)___| |_ 
| '_ \| | | | '_ \| | |/ __| | |   | / __| __|
| |_) | |_| | |_) | | | (__  | |___| \__ \ |_ 
| .__/ \__,_|_.__/|_|_|\___| |_____|_|___/\__|
|_|                                           
*/

#slist,
#pubs-container {
	background-color:rgba(0,0,0,0.7) !important;
	border-radius:5px 5px 0 0;
}

#pubs-header {
	padding:10px;
	background-color:#25ACE8 !important;
	border-radius:5px 5px 0 0;
}

#pubs-header input {
	padding-left:10px;
}

#pubs-footer {
	padding:10px;
    font-size:12px;
	background:rgba(0,0,0,0.8) !important;
	border-radius:0 0 5px 5px;
}

.server-icon {
	width:50px;
    height:50px;
	border-radius:100%;
}

.server-row {
	padding:10px 10px 8px 10px;
}

.server-info {
	line-height:50px;
}

.server-info button {
	background-color:#1D6586 !important;
	width:70px;
    height:40px;
    margin-top:4px;
    margin-right:4px;
}

.server-info button:hover {
	background-color:#25ACE8 !important;
}

#slist span {
	color:white !important;
}

.server-row:nth-child(2n+1) {
	background-color:rgba(255,255,255,0.06) !important;
}

.server-row:nth-child(2n+2) {
	background-color:rgba(0,0,0,0) !important;
}
Contact GitHub API Training Shop Blog About
© 2016 GitHub, Inc. Terms Privacy Security Status Help
