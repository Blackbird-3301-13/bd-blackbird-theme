# bd-blackbird-theme
Blackbird Theme for Better Discord.

/* Background */
.app {
    background-image: url(https://images-2.discordapp.net/eyJ1cmwiOiJodHRwOi8vaW1hZ2Vob3N0Ny5vbmxpbmUtaW1hZ2UtZWRpdG9yLmNvbS9vaWVfdXBsb2FkL2ltYWdlcy8xODMzMjIwaDYzT1Q3OXJ4L3B0V25zMGtCVXk4WC5qcGcifQ.IO5UqPQSCeKanHXge60DAL3J4hY.jpg);
    background-size: cover;
}
.account .avatar-small {
    opacity:1;
    right:-54px;
    top:-30px;
    border-radius: -1px;
}

/*Transparency*/
#voice-connection,
#friends,
#friends .btn,
.friends-header,
.friends-table,
.search-bar,
.guilds-wrapper,
.channels-wrap,
.guild-channels,
.account,
.links,
.messages-wrapper,
.title-wrap,
.content,
.chat-empty,
.message-group-blocked,
.private-channels,
.guild-header header,
.typing,
.divider-red span {
    background: transparent !important;
}

/*Guild area*/
.guild-inner:hover,
li.active .guild-inner {
    background-color: #000000 !important;
}

.guilds-wrapper {
    width: 80px;
}

.guilds {
    background: #000000;
}

.guilds li {
    margin-left: 1px;
}

/*Selected guild & unread messages*/
.guilds-wrapper .guilds .guild.unread:before {
    background-color: #FF0000;
}

.guilds-wrapper .guilds .guild.selected:before {
    background-color: #FFFFFF;
}

.guilds-wrapper .guilds .guild.selected:before,
.guilds-wrapper .guilds .guild.unread:before {
    width: 7.5px;
    height: 55px;
    margin-top: -28px;
    margin-left: 7.5px;
    transition: background-color .25s cubic-bezier(0.4,0,1,1);
}

/*Create new guild button*/
.guilds-add {
    opacity: .80;
    background-color: #FFFFFF
}

/*Guild name*/
.guild-header span {
    text-shadow: 1px 1.35px 1.5px #FF0000;
}

/*Guild settings*/
.guild-header ul {
    opacity: 0;
    background-color: #FF0000
    transition: transform .5s cubic-bezier(0.18,0.89,0.32,1.28);
}

.guild-header-open ul {
    opacity: 1;
}

.btn-hamburger span {
    background: #fff;
}

.guild-header header {
    box-shadow: none;
}

/*Channel area*/
.channel:not(.selected) {
    transition: background .3s ease-out;
    Bckground: #FFFFFF
}

.channel:not(.selected):hover {
    transition: background .5s ease-in;
    background: #000000;
}

.guild-channels .channel-text.selected:before,
.guild-channels .channel-text.selected:hover:before,
.guild-channels .channel-text:hover.channel-muted:before,
.guild-channels .channel-text:hover:not(.unread):before,
.private-channels .channel.selected:before,
.private-channels .channel:hover:before {
    border-left: 5px solid purple;
}

.private-channels .channel:hover:before {
    opacity: .25;
}

.guild-channels ul .channel-text.unread:not(.selected):not(.channel-muted):before {
    left: -11px;
}

.search-result,
.tab-bar-item:hover {
    background: #FFFFFF !important;
}

.friends-row:hover,
.search-result:hover,
.btn-friends.selected,
.search-result.selected,
.channel.selected.private,
div.channel.channel-text.selected {
    background: #000000 !important;
}

/*Voice panel*/
#voice-connection {
    border-top: none;
}

/*Buttons*/
#voice-connection .btn,
.account .btn {
    border: none;
    border-bottom: solid 3px #FF0000;
    opacity: .65;
    background: #000000
}

#voice-connection .btn-group,
.account .btn-group {
    box-shadow: .75px 1.5px 1px #14171b;
    border: none;
    background: #000000
}

/*Friends*/
.icon-friends {
	background-color: #000000 !important;
}

#friends .btn:hover {
	background-color: #000000 !important;
}

.friends-header {
	border-bottom-color: #000000 !important;
}

/*User settings*/
.account .username {
    font-size: 13px;
    font-weight: none;
    font-family: arial;
    text-shadow: 1.35px .75px 1px black;
}

.account {
    border-top: none;
}

.status {
    border-color: #000000 !important;
}

/*Popout menu*/
.popout header,
.slider-bar-fill {
    background-color: #06c;
}

.user-popout .user-popout-options .btn {
    background-color: #06c;
}

.user-popout .user-popout-options .btn:hover {
    background-color: #0080ff;
}

.user-popout .username {
    font-size: 16px;
}

/*Tooltips*/
.tooltip {
    background:#06c;
    color: #fff;
}

.tooltip.tooltip-right:after {
    border-right-color:#06c;
}

.tooltip.tooltip-top:after {
    border-top-color:#06c;
}

/*Info links*/
.links {
    display: none;
}

/*Channel info*/
.flex-spacer .title-wrap {
    -webkit-box-shadow: none;
    -moz-box-shadow: none;
    box-shadow: none;
    border-top: none;
    border-style: solid;
    border-color: #000000 !important;
}

/*Channel title*/
.topic {
    color: #FFFFFF;
}

/*Chat area*/
.chat .flex-spacer {
    background: rgba(255,255,255,0.05);
    border-top-left-radius: 29px;
    border-bottom-left-radius: 29px;
}
.chat .flex-spacer {
    background: rgba(255,255,255,0.05);
    border-top-right-radius: 29px;
    border-bottom-right-radius: 29px;
}

/*Unread messages*/
.chat .new-messages-bar {
    background-color: #FFFFFF;
}

.chat .new-messages-bar:hover {
    background-color: rgba(204,97,61,1);
}

.chat .new-messages-bar button:last-child {
    color: rgba(255,255,255,0.5);
}

/*Mention*/
.markup .highlight {
    background-color: rgba(255,255,255,.1) !important;
    color: #ddd;
    border-radius: 10%;
}

.markup .highlight:hover {
    background-color: rgba(255,255,255,.2) !important;
    color: #ddd;
    border-radius: 10%;
}

/*URLs*/
.message-group a span {
    color: #5af;
    text-shadow: 1px 1px 0 #001a33;
}

/*Code blocks*/
.chat .markup code {
    background: #000000 !important;
}

.chat .markup pre {
    background: none !important;
    border: 1px solid #FF0000 !important;
}

/*Spoiler tags*/
.chat .has-more button,
.message-group-blocked-btn,
.message-group-blocked.revealed {
    background-color: rgba(0,0,0,0.3) !important;
}

.message-group-blocked,
.message-group-blocked.revealed {
    border: none !important;
}

/*Scrolling bar*/
.scroller-wrap .scroller::-webkit-scrollbar-thumb {
    border: 3px solid #FFFFFF !important;
}

.scroller-wrap .scroller::-webkit-scrollbar-track-piece {
    border: 3px solid #000000 !important;
    background-color: #FF0000 !important;
}

/*Message area*/
.channel-textarea .channel-textarea-inner {
    background: #000000;
}
.channel-textarea .channel-textarea-inner {
    border: 5px solid #FF0000;
}

/*Twitch emotes button*/
#twitchcord-button {
    background-size: 24px;
    background-position: 20px;
    background-color: transparent;
}

/*Typing status*/
.typing {
    font-size: 13px;
}

/*Settings panel*/
.settings .settings-header {
    background: #000000;
}

.form .btn-primary {
    background-color: #000000;
}

.form .btn-primary:hover {
    background-color: #FF0000;
}

.user-settings-modal a {
    color: #FF0000;
}

.user-settings-modal a:hover {
    color: #FF0000;
}

/*Channel members*/
.channel-members {
    background: #000000 !important;
}

.member-username {
    text-shadow: 0 0 0 rgba(255,255,255,0.255);
}

.channel-members-wrap .member-inner div {
    -webkit-filter: none !important;
}

.channel-members .invite-btn {
    background: #06c;
    transition: background .3s ease-out;
}

.channel-members .invite-btn:hover {
    background: #39f;
    transition: background .2s ease-in;
}

.channel-members .member:hover,
.channel-members .popout-open {
    background: rgba(255,255,255,0.07) !important;
}
.avatar-large:hover {
    transform: scale(3);
    opacity: 1 !important;
    border-radius: 1px;
    left: 25px;
    transition: border-radius 0.2s, transform 0.1s;
    animation: slide 0.3s;
    z-index: 9999;
}

@keyframes slide {
    0% { left: 0px;}
    40% {left: 25px;}
    100% { left: 25px;}

    /*Drag And Drop Module*/
.upload-drop-modal .bgScale {
    background: rgba(30, 30, 30, 0.78);
}
.upload-drop-modal .inner {
    border: 2px dashed #9f0000;
}
.upload-drop-modal .inner .title {
    color: #9f0000;
}
.upload-drop-modal .inner .instructions {
    color: hsla(0, 0%, 100%, 0.6);
}
.upload-drop-modal .inner .icon.one {
    background-image: url(/assets/60c3eaf0d7173c929482362ea1d2543a.svg);
}
.upload-drop-modal .inner .icon.two {
    background-image: url(/assets/4ab2ee5027741df387151ca717ae5614.svg);
}
.upload-drop-modal .inner .icon.three {
    background-image: url(/assets/a4ef7d20760cef4c165825770fd12ac7.svg);
}
    
