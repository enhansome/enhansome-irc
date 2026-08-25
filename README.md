# Awesome IRC with stars

> A curated list of awesome [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) resources.

A list of tools, software & other resources related to the Internet Relay Chat (IRC) protocol.

IRC (Internet Relay Chat) is an open source protocol that can be used for multi-user text based communication through channels.

## Contents

<!--lint disable awesome-list-item-->

<!--lint ignore awesome-toc double-link-->

* [Clients](#clients)
* [Bouncers](#bouncers)
  * [Hosted](#hosted)
  * [Self-hosted](#self-hosted)
* [Daemons](#daemons)
* [Services](#services)
* [Bots](#bots)
* [Encryption](#encryption)
* [Frameworks](#frameworks)
  * [Bridges](#bridges)
* [Channels](#channels)
  * [Discovery](#discovery)
  * [Platforms](#platforms)
* [Networks](#networks)
* [Articles](#articles)
* [Guides](#guides)
* [Protocol](#protocol)
* [Miscellaneous](#miscellaneous)

## Clients

*You use these to connect to IRC.*

* [![HexChat-icon](https://user-images.githubusercontent.com/15098724/56874706-b28a8200-69f0-11e9-9ca7-27c8779134e0.png) HexChat](https://hexchat.github.io) - Based on XChat, easy to use, spell check & multiple languages. ([source](https://github.com/hexchat/hexchat) ⚠️ Archived) `Windows` `macOS` `Linux`
* [![Textual-icon](https://user-images.githubusercontent.com/15098724/56874954-680a0500-69f2-11e9-87ec-d4015ce54af5.png) Textual](https://www.codeux.com/textual/) - Very customizable, ZNC integration, iCloud sync ($4.99). ([source](https://github.com/Codeux-Software/Textual) ⚠️ Archived) `macOS`
* [![LimeChat-icon](https://user-images.githubusercontent.com/15098724/56875043-04cca280-69f3-11e9-8e1f-285e54784fe4.png) LimeChat](http://limechat.net/mac/) - One window for multiple servers, keyboard shortcuts, fast & stable. ([source](https://github.com/psychs/limechat) ⭐ 1,582 | 🐛 197 | 🌐 Objective-C | 📅 2021-11-22) `macOS` `iOS`
* [![KiwiIRC-icon](https://user-images.githubusercontent.com/15098724/56875143-a7852100-69f3-11e9-8b33-2035c156c016.png) Kiwi IRC](https://kiwiirc.com) - Powerful modern IRC messenger for the web. ([source](https://github.com/kiwiirc/kiwiirc) ⭐ 982 | 🐛 194 | 🌐 Vue | 📅 2026-06-19, [demo](https://kiwiirc.com/nextclient/)) `Web`
* [![Quassel-icon](https://user-images.githubusercontent.com/15098724/56875264-84a73c80-69f4-11e9-807c-75db09db0ec5.png) Quassel](https://quassel-irc.org) - Distributed (clients can attach to and detach from a central core that stays permanently online. ([source](https://github.com/quassel/quassel) ⭐ 791 | 🐛 24 | 🌐 C++ | 📅 2026-06-27) `Linux` `macOS` `Windows`
* [![RevolutionIRC-icon](https://user-images.githubusercontent.com/15098724/56876444-4f065180-69fc-11e9-8200-b244b6a86e94.png) Revolution IRC](https://github.com/MCMrARM/revolution-irc) ⭐ 613 | 🐛 197 | 🌐 Java | 📅 2024-01-01 - Feature-full, actively maintained Android IRC client. `Android`
* [![Circe-icon](https://user-images.githubusercontent.com/15098724/56875558-a3a6ce00-69f6-11e9-92da-2e4d8c7b4a53.png) Circe](https://github.com/emacs-circe/circe) ⭐ 443 | 🐛 87 | 🌐 Emacs Lisp | 📅 2026-05-25 - For use in Emacs, sane defaults. `Emacs`
* [![CIRC-icon](https://user-images.githubusercontent.com/15098724/56875201-1498b680-69f4-11e9-91ff-ae3b674c82be.png) CIRC](https://flackr.github.io/circ/) - Uses the chrome.sockets APIs to connect directly to IRC servers without needing a proxy. ([source](https://github.com/flackr/circ) ⭐ 385 | 🐛 172 | 🌐 JavaScript | 📅 2022-03-29) `Chrome`
* [![KvIRC-icon](https://user-images.githubusercontent.com/15098724/56874636-1d878900-69f0-11e9-856e-719c4c822e25.png) KvIRC](https://www.kvirc.net) - Free, portable, based on Qt GUI toolkit. ([source](https://github.com/kvirc/KVIrc) ⭐ 303 | 🐛 213 | 🌐 C++ | 📅 2026-06-13) `Linux` `macOS` `Windows`
* [ObsidianIRC](https://hello.obby.world/) - Modern WebSocket IRC client with Discord-like UI. ([source](https://github.com/obbyworld/obby) ⭐ 227 | 🐛 52 | 🌐 TypeScript | 📅 2026-08-24) `Linux` `Windows` `macOS` `Android` `iOS` `Web`
* [![Smuxi-icon](https://user-images.githubusercontent.com/15098724/56875672-2f205f00-69f7-11e9-8cac-5721602234bb.png) Smuxi](https://smuxi.im) - User-friendly, based on GNOME / GTK+. ([source](https://github.com/meebey/smuxi) ⭐ 187 | 🐛 38 | 🌐 C# | 📅 2025-12-29) `Linux` `Windows` `macOS`
* [MERK](https://github.com/nutjob-laboratories/merk) ⭐ 74 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - Open source, multiple-document interface GUI client with a rich plugin framework supporting 40+ events; plugins created directly inside the app. `Windows` `macOS` `Linux` `Python`
* [![Konversation-icon](https://user-images.githubusercontent.com/15098724/56876024-609a2a00-69f9-11e9-91dd-196f310776d7.png) Konversation](https://konversation.kde.org) - User-friendly client built on the KDE Platform. ([source](https://github.com/KDE/konversation) ⭐ 57 | 🐛 0 | 🌐 C++ | 📅 2026-08-24) `Linux`
* [Iridium](https://appcenter.elementary.io/com.github.avojak.iridium/) - Friendly IRC client built in Vala and GTK, designed for elementary OS. ([source](https://github.com/avojak/iridium) ⭐ 57 | 🐛 29 | 🌐 Vala | 📅 2023-03-12) `Linux`
* [gamja](https://sr.ht/~emersion/gamja/) - A simple IRC web client. ([source](https://git.sr.ht/~emersion/gamja)) `Web`
* [![sic-icon](https://user-images.githubusercontent.com/15098724/56876157-457bea00-69fa-11e9-94f5-11dcd0bfb00c.png) sic](https://tools.suckless.org/sic/) - **S**imple **I**RC **c**lient - a terminal client in less than 250 lines of C. `Linux` `macOS`
* [![irssi-icon](https://user-images.githubusercontent.com/15098724/56876266-0c904500-69fb-11e9-85a9-00796373cf88.png) irssi](https://irssi.org) - Terminal client, multi-protocol friendly for module authors, GPLv2. `Linux` `macOS` `Cygwin` `BSD`
* [![AdiIRC-icon](https://user-images.githubusercontent.com/15098724/56632956-0e2fc680-6611-11e9-949e-c79c21f465a0.png) AdiIRC](https://adiirc.com) - Never has a client offered such granular settings for every aspect of the IRC experience. `Windows` `WINE`
* [![IRCforAndroid-icon](https://user-images.githubusercontent.com/15098724/56655816-b3b25c80-6648-11e9-92e1-12ca4587d9eb.png) IRC for Android™](https://www.countercultured.net/android/) - Android/Chrome OS client for power users, with ZNC built-ins, notification logic, reliable DCC, keybinds for hardware keyboards, etc. `Android` `ChromeOS`
* [mIRC](https://www.mirc.co.uk) - One of the most popular IRC clients for Windows, with a built-in scripting language. `Windows`
* [XChat](https://xchat.org) - Precursor to HexChat, multi-platform graphical IRC client. `Windows` `Linux`
* [ircII](http://www.eterna23.net/ircii/) - One of the oldest IRC clients, initially released in 1989. `Linux` `macOS`
* [BitchX](https://bitchx.sourceforge.net/) - Terminal-based client popular on Unix-like systems. ([screenshots](https://bitchx.sourceforge.net/category/screenshots.html)) `Linux` `macOS` `Windows`
* [Goguma](https://sr.ht/~emersion/goguma/) - An IRC client for mobile devices, from the creator of soju. `Android` `Linux`

<!--lint ignore double-link-->

*More? Clients that include bouncers are found [below](#bouncers).*

## Bouncers

*Useful for disconnecting and reconnecting without losing the chat session.*

### Hosted

* [![IRCCloud-icon](https://user-images.githubusercontent.com/15098724/56879253-ba581f80-6a0c-11e9-8f6b-8461c10ed149.png) IRCCloud](https://www.irccloud.com) - Group chat for teams, friends, and communities. stay connected, chat from anywhere, and never miss a message (+client) (£0-£3.50/month).
  * [Android App](https://github.com/irccloud/android) ⭐ 310 | 🐛 32 | 🌐 Java | 📅 2026-04-28 - Official. `Java`
  * [iOS App](https://github.com/irccloud/ios) ⭐ 300 | 🐛 24 | 🌐 Objective-C | 📅 2026-04-21 - Official. `Objective-C`
  * [Nimbus](https://github.com/jnordberg/irccloudapp) ⭐ 152 | 🐛 5 | 🌐 Objective-C | 📅 2016-12-17 - Standalone client. `macOS` `Objective-C`

### Self-hosted

* [![TheLounge-icon](https://user-images.githubusercontent.com/15098724/56899491-6b2fe000-6a48-11e9-9f01-1ed2cfb86b09.png) TheLounge](https://thelounge.chat) - Responsive, self-hosted & support for multiple users. ([source](https://github.com/thelounge/thelounge) ⭐ 6,319 | 🐛 316 | 🌐 TypeScript | 📅 2026-08-18, [demo](https://demo.thelounge.chat/)) `JavaScript` `Node.js` `Web`
* [![WeeChat-icon](https://user-images.githubusercontent.com/15098724/56876389-e028f880-69fb-11e9-82d6-8084e17f2f04.png) WeeChat](https://weechat.org) - A fast, light and extensible chat client. ([source](https://github.com/weechat/weechat) ⭐ 3,371 | 🐛 443 | 🌐 C | 📅 2026-08-23) `Linux` `macOS`
* [![ZNC-icon](https://user-images.githubusercontent.com/15098724/56879721-d8268400-6a0e-11e9-8b74-c2c748d15c4a.png) ZNC](https://wiki.znc.in/ZNC) - Most popular. many different plugins. ([source](https://github.com/znc/znc) ⭐ 2,122 | 🐛 389 | 🌐 C++ | 📅 2026-08-21) `C++`
* [![Convos-icon](https://user-images.githubusercontent.com/15098724/56879497-d8724f80-6a0d-11e9-844d-7a5380b4524b.png) Convos](https://convos.chat) - Always online web IRC client. ([source](https://github.com/convos-chat/convos) ⭐ 1,190 | 🐛 56 | 🌐 Go | 📅 2026-08-23) `Perl` `JavaScript` `Web`
* [sms-webhook](https://github.com/terminaldweller/sms-webhook) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2026-02-10 - A simple webhook to receive SMS messages on IRC. `Go`
* [![BIP-icon](https://user-images.githubusercontent.com/15098724/56899123-89491080-6a47-11e9-8513-4c8d09be32d9.png) BIP IRC Proxy](https://packages.debian.org/sid/bip) - Always online, lightweight and secure Open Source IRC proxying with backlogging. ([source](https://salsa.debian.org/debian/bip)) `C`
* [soju](https://codeberg.org/emersion/soju) - A user-friendly IRC bouncer. `Go`
* [psyBNC](https://psybnc.org/) - Multi-user, permanent IRC bouncer with encryption support. `Linux`

## Daemons

*Used for running your own IRC server or network.*

* [Ergo](https://ergo.chat/) - Modern server that's portable and designed around specifications (bleeding-edge IRCv3 support). ([source](https://github.com/ergochat/ergo) ⭐ 3,307 | 🐛 200 | 🌐 Go | 📅 2026-08-23)
* [InspIRCd](https://www.inspircd.org) - Modular, stable, written from scratch. ([source](https://github.com/inspircd/inspircd) ⭐ 1,341 | 🐛 112 | 🌐 C++ | 📅 2026-08-24)
* [ngIRCd](https://ngircd.barton.de) - Portable and lightweight for small or private networks. ([source](https://github.com/ngircd/ngircd) ⭐ 574 | 🐛 31 | 🌐 C | 📅 2026-07-12)
* [ircd.js](https://github.com/alexyoung/ircd.js) ⭐ 531 | 🐛 12 | 🌐 JavaScript | 📅 2021-05-31 - Server will allow clients to connect, join channels, change topics; basic stuff.
* [UnrealIRCd](https://www.unrealircd.org) - Modular, advanced IRCd serving thousands of networks since 1999. ([source](https://github.com/unrealircd/unrealircd) ⭐ 522 | 🐛 6 | 🌐 C | 📅 2026-08-17)
* [miniircd](https://github.com/jrosdahl/miniircd) ⭐ 450 | 🐛 5 | 🌐 Python | 📅 2025-02-12 - Very simple and limited.
* [RobustIRC](https://robustirc.net) - IRC server without netsplits. ([source](https://github.com/robustirc/robustirc/) ⭐ 195 | 🐛 6 | 🌐 Go | 📅 2026-05-24)

## Services

*Used to provide user accounts and bots like NickServ/ChanServ to your network.*

* [Atheme](https://atheme.github.io) - Designed for large networks with high scalability requirements. ([source](https://github.com/atheme/atheme) ⭐ 428 | 🐛 151 | 🌐 C | 📅 2026-08-18)
* [anope](https://www.anope.org) - Designed for flexibility and ease of use. ([source](https://github.com/anope/anope) ⭐ 363 | 🐛 49 | 🌐 C++ | 📅 2026-08-17)

## Bots

*IRC users which provide services for humans, e.g. integrations or information.*

* [wayback](https://github.com/wabarc/wayback) ⭐ 2,227 | 🐛 60 | 🌐 Go | 📅 2026-08-14 - An archiving tool with an IRC interface integrated with various archiving services.
* [Sopel](https://sopel.chat) - Tonnes of ready made features, tutorial, fully documented. ([source](https://github.com/sopel-irc/sopel) ⭐ 981 | 🐛 167 | 🌐 Python | 📅 2026-08-18) `Python`
* [Limnoria](https://github.com/ProgVal/Limnoria) ⭐ 671 | 🐛 254 | 🌐 Python | 📅 2026-07-23 - Robust, user friendly, developer friendly. `Python`
* [Eggdrop](https://www.eggheads.org) - Oldest IRC bot still in active development. Feature rich, uses Tcl scripting. ([source](https://github.com/eggheads/eggdrop) ⭐ 579 | 🐛 250 | 🌐 C | 📅 2026-08-02) `C`
* [Twitch Plays](https://github.com/aidanrwt/twitch-plays) ⭐ 276 | 🐛 4 | 🌐 Python | 📅 2014-02-22 - Takes input from the chat and presses the corresponding key. `Python`
* [Skybot](https://github.com/rmmh/skybot) ⭐ 248 | 🐛 15 | 🌐 Python | 📅 2026-07-17 - Main goals are simplicity and power. `Python`
* [geordi](https://github.com/Eelis/geordi) ⭐ 182 | 🐛 2 | 🌐 Haskell | 📅 2022-10-05 - Compiles and runs C++ code snippets. `C++`
* [CloudBot](https://github.com/TotallyNotRobots/CloudBot) ⭐ 182 | 🐛 24 | 🌐 Python | 📅 2026-08-23 - Simple, fast, expandable. `Python`
* [lazybot](https://github.com/Raynes/lazybot) ⭐ 153 | 🐛 16 | 🌐 Clojure | 📅 2015-06-17 - User-friendly and powerful. `Clojure`
* [BitBot](https://github.com/bitbot-irc/bitbot) ⭐ 149 | 🐛 94 | 🌐 Python | 📅 2025-01-10 - Modular, event-driven bot featuring a REST API, individual user settings and much more. ([bitbot.dev](https://bitbot.dev)) `Python`
* [Cardinal](https://github.com/JohnMaguire/Cardinal) ⭐ 104 | 🐛 19 | 🌐 Python | 📅 2026-07-27 - Python Twisted IRC bot with a focus on ease of plugin development. `Python`
* [pyHoneybot](https://pyhoneybot.github.io/honeybot-store/) - Python Twisted IRC bot with a focus on ease of plugin development. ([source](https://github.com/pyhoneybot/honeybot) ⭐ 81 | 🐛 10 | 🌐 Python | 📅 2026-07-06) `Python`
* [helga](https://github.com/shaunduncan/helga) ⭐ 48 | 🐛 56 | 🌐 Python | 📅 2026-06-02 - Pluggable chat bot supporting multiple protocols. `Python`
* [yossarian-bot](https://github.com/woodruffw/yossarian-bot) ⚠️ Archived - Large default plugin set, Cinch-based. `Ruby`
* [milla](https://github.com/terminaldweller/milla) ⭐ 18 | 🐛 3 | 🌐 Go | 📅 2026-05-22 - New generation LLM-powered bot with lua scripting support. `Go`
* [EveIRC](https://github.com/Inspyre-Technologies/EveIRC) ⭐ 9 | 🐛 18 | 🌐 Ruby | 📅 2019-11-14 - Extendable chat/channel/server-managenent service-providing bot. Using the [Cinch Framework](https://github.com/cinchrb/cinch) ⚠️ Archived. `Ruby`
* [IRC-BF](https://gitlab.com/ddevault/bf-irc-bot) - `Brainfuck`
* [MansionNET Bot Suite](https://github.com/MansionNET) - Collection of self-hostable IRC bots: AI chat assistant, real-time weather, privacy-focused search, YouTube metadata, and AI-powered trivia. `Python`

## Encryption

*Plugins and tools for encrypting IRC messages.*

* [irssi-otr](https://github.com/cryptodotis/irssi-otr) ⭐ 185 | 🐛 27 | 🌐 C | 📅 2017-09-01 - Off-the-Record (OTR) messaging plugin for irssi. `C`
* [weechat-otr](https://github.com/mmb/weechat-otr) ⭐ 135 | 🐛 19 | 🌐 Python | 📅 2018-03-27 - Off-the-Record (OTR) messaging plugin for WeeChat. `Python`
* [FiSH-irssi](https://github.com/falsovsky/FiSH-irssi) ⭐ 129 | 🐛 3 | 🌐 C | 📅 2026-02-18 - Blowfish encryption in ECB/CBC modes with Diffie-Hellman key exchange for irssi. `C`

## Frameworks

*Helpful to write bots or integrate IRC with applications.*

* [goirc](https://github.com/fluffle/goirc) ⭐ 516 | 🐛 4 | 🌐 Go | 📅 2026-07-03 - Event-based, stateful, lacking documentation. `Go`
* [go-ircevent](https://github.com/thoj/go-ircevent) ⭐ 498 | 🐛 14 | 🌐 Go | 📅 2023-03-07 - Event-based. `Go`
* [Hubot IRC Adapter](https://github.com/nandub/hubot-irc) ⭐ 299 | 🐛 14 | 🌐 CoffeeScript | 📅 2021-11-24 - The IRC adapter for hubot. `JavaScript`
* [PircBotX](https://github.com/pircbotx/pircbotx) ⭐ 229 | 🐛 20 | 🌐 Java | 📅 2026-06-12 - Event based IRC Library with a straightforward API (updated fork of [PircBot](https://www.jibble.org/pircbot.php)). `Java`
* [slate-irc](https://github.com/slate/slate-irc) ⭐ 209 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-30 - Plugin system, simple api, arbitrary input stream, debug support. `JavaScript`
* [node-irc](https://github.com/Throne3d/node-irc) ⚠️ Archived `JavaScript`
* [IRC::Client](https://github.com/lizmat/IRC-Client) ⭐ 16 | 🐛 31 | 🌐 Raku | 📅 2026-02-02 - `Perl6` based extendable IRC client framework.
* [irccd](https://projects.malikania.fr/irccd/index.html) - Flexible IRC bot customizable with JavaScript. `C++`.

### Bridges

*Sends messages back and forth.*

* [matterbridge](https://github.com/42wim/matterbridge) ⭐ 7,553 | 🐛 342 | 🌐 Go | 📅 2024-12-12 - IRC ↔ Mattermost ↔ Discord ↔ XMPP ↔ Gitter ↔ Slack ↔ Discord ↔ Telegram ↔ etc. `Go`
* [discord-irc](https://github.com/reactiflux/discord-irc) ⭐ 1,226 | 🐛 75 | 🌐 JavaScript | 📅 2023-11-25 - Discord ↔ IRC. `JavaScript`
* [slack-irc](https://github.com/ekmartin/slack-irc) ⭐ 589 | 🐛 29 | 🌐 JavaScript | 📅 2022-10-12 - Slack ↔ IRC. `JavaScript`
* [Appservice-IRC](https://github.com/matrix-org/matrix-appservice-irc) ⭐ 505 | 🐛 505 | 🌐 TypeScript | 📅 2026-04-02 - Gateway and bridge Matrix ↔ IRC `Javascript`
* [Heisenbridge](https://github.com/hifi/heisenbridge) ⭐ 309 | 🐛 85 | 🌐 Python | 📅 2025-10-04 - Bouncer-style Matrix IRC bridge `Python`
* [matterircd](https://github.com/42wim/matterircd) ⭐ 307 | 🐛 6 | 🌐 Go | 📅 2026-08-24 - Matterbridge ↔ IRC, Slack ↔ IRC, Mastodon ↔ IRC. `Go`
* [irc-slack](https://github.com/insomniacslk/irc-slack) ⭐ 206 | 🐛 24 | 🌐 Go | 📅 2026-08-24 - Slack ↔ IRC. `Go`
* [teleirc](https://github.com/RITlug/teleirc) ⭐ 159 | 🐛 39 | 🌐 Go | 📅 2026-01-11 - Telegram ↔ IRC. `JavaScript`
* [Dis4IRC](https://github.com/zachbr/Dis4IRC) ⭐ 117 | 🐛 21 | 🌐 Kotlin | 📅 2026-05-10 - Discord ↔ IRC. `Kotlin`
* [toxirc](https://github.com/e0ff/toxirc) ⭐ 22 | 🐛 2 | 🌐 C | 📅 2024-02-17 - Tox ↔ IRC. `C`
* [dibridge](https://github.com/OpenTTD/dibridge) ⭐ 21 | 🐛 8 | 🌐 Python | 📅 2026-08-04 - Discord ↔ IRC (with puppets) `Python`
* [skyweb2irc](https://github.com/ProgVal/skyweb2irc) ⚠️ Archived - Skype (webclient API) ↔ IRC. `Javascript`
* [BitlBee](https://www.bitlbee.org/main.php/news.r.html) - XMPP, Jabber, Google Talk, MSN Messenger, Yahoo! Messenger, AIM, ICQ, Twitter API, HipChat ↔ IRC. `C`

## Channels

*IRC channels.*

### Discovery

* [netsplit.de Search](https://netsplit.de/channels/) - Searches 563 different networks.
* [KiwiIRC Search](https://kiwiirc.com/search) - Searches 318 different networks.

### Platforms

* [#Ubuntu](https://wiki.ubuntu.com/IRC/ChannelList)@Libera.Chat - Official Ubuntu support channel. ([rules](https://wiki.ubuntu.com/IRC/Guidelines))

## Networks

*A collection of IRC servers is known as a network.*

* [Libera.Chat](https://libera.chat) - Network mostly focused on free and open source projects, run by former freenode staff.
* [MansionNET](https://inthemansion.com) - Privacy-focused community network running UnrealIRCd with Anope services; open to all, no tracking, no ads. (`irc.inthemansion.com:6697`, webchat at `webirc.inthemansion.com`)
* [Snoonet](https://snoonet.org) - Community of redditors and subreddits. ([rules](https://snoonet.org/rules/))
* [OFTC](https://oftc.net) - Community for free and open source software communities.
* [LibertaCasa](https://liberta.casa) - Privacy endorsing community serving as a safe and open space for the discussion of various topics.

## Articles

*Articles and blog posts about IRC.*

* [Please don't use Slack for FOSS projects](https://drewdevault.com/2015/11/01/Please-stop-using-slack.html) - Drew DeVault's Blog.
* [IRC is dead, long live IRC](https://www.pingdom.com/blog/irc-is-dead-long-live-irc/) - Pingdom.
* [IRC Has Lost 60% Of Its Users Since 2003, But Life As A Robot Is Just Beginning](https://techcrunch.com/2013/01/06/irc-has-lost-60-of-its-users-since-2003-but-life-as-a-robot-is-just-beginning/) - Alex Williams (TechCrunch).

## Guides

*How-to's, documentation and books.*

* [#irchelp](https://www.irchelp.org) - A vast amount of reasonably up-to-date information.

## Protocol

*Information and resources about the IRC protocol itself.*

* [Modern IRC Documents](https://modern.ircdocs.horse) - An attempt to write an update to the original IRC protocol. documentation ([source](https://github.com/ircdocs/modern-irc) ⭐ 230 | 🐛 47 | 🌐 Sass | 📅 2026-08-22)
* [IRCv3 Working Group](https://ircv3.net) - A group of IRC software authors working to enhance, improve, maintain and standardize the IRC protocol. ([source](https://github.com/ircv3/ircv3.github.io) ⭐ 102 | 🐛 13 | 🌐 HTML | 📅 2026-08-07)
* [IRC Definition Files](https://defs.ircdocs.horse) - Lists of numerics, modes, ISUPPORT tokens and other protocol details. ([source](https://github.com/ircdocs/irc-defs) ⭐ 65 | 🐛 15 | 🌐 HTML | 📅 2025-03-14)
* [grawity's IRC docs](https://github.com/grawity/irc-docs) ⭐ 63 | 🐛 0 | 🌐 HTML | 📅 2022-07-18 - Collection of misc IRC protocol documentation.
* [IRC Parser Tests](https://github.com/ircdocs/parser-tests) ⭐ 48 | 🐛 13 | 🌐 Go | 📅 2023-05-29 - A CC0 set of test suites, to ensure IRC message parsers are consistent.
* [Protocol Statistics](https://stats.ircdocs.horse) - Statistics around the server software in use on networks today. ([source](https://github.com/ircdocs/irc-stats) ⭐ 7 | 🐛 16 | 🌐 HTML | 📅 2022-07-21)

## Miscellaneous

*Items that belong on the list but defy classification.*

* [superseriousstats](https://github.com/tommyrot/superseriousstats) ⭐ 104 | 🐛 0 | 🌐 PHP | 📅 2026-08-02 - Fast and efficient program to create statistics out of various types of chat logs. `PHP` `Web`
* [img2src](https://github.com/waveplate/img2irc) ⭐ 46 | 🐛 1 | 🌐 Rust | 📅 2026-01-13 - Convert images to halfblock ANSI or IRC, with a bunch of post-processing filters. `Rust`

## Use

The best ways to use this list are:

* By browsing the [contents](#contents)
* By using <kbd>command</kbd> + <kbd>F</kbd> to search the contents

This list also uses tags to help when searching the contents:

* **Language** - `Python`, `Java`, `C++`, `Go`, `JavaScript`, `Ruby`, `C` etc.
* **Platform** - `Web`, `macOS`, `Windows`, `Linux`, `Chrome` etc.

## Credits

By [Craig Davison](https://davison.io) and contributors.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
