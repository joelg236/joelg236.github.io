---
title: My Workflow
layout: post
---

![](/img/full-desktop.png)

I've had a few years to get where I am now in terms of workflow on my laptop (Dell Inspiron 174 n7110 with 128gb SSD installed). Here's what I've got.

# Operating System
I use a single-boot [crunchbang](http://crunchbang.org/) install.

Special things about my install:
- Kernel 3.9.1 from Debian testing mostly for battery performance tweaks (there's a bug from 2.x days that makes battery on it 30% worse)
- Pulseaudio and libc6 updated from Debian testing for headphone jack support an FRC plugin support (32 bit)

### Applications
I use a lot of applications. These are the main ones

- Geany for text editing (everything except Java)
- Terminator for terminal
- Thunar for file management
- Netbeans for Java development
- GIMP for photo editing
- Rhythmbox for music
- VLC for video and streams
- Xfburn for CD/DVD burning
- EasyTag for MP3 tagging
- Chromium as main browser - iceweasel as backup (still have opera installed - waiting for 15)
- gFTP for ftp
- Transmission for torrents
- Libreoffice for word and excel files
- Redshift for keeping my eyes alive

### Configuration
My configuration files that differ from defaults of crunchbang can be found [here](https://github.com/joelg236/my-config).

# Web
I currently use chromium as my main web browser. I've carefully tuned my settings so that it doesn't track me or save passwords or anything sensitive. My only worry is the webpages I visit.

### Browsing
I currently use the internet with google calendar and gmail as pinned tabs. They send notifications when events happen or emails are received. It's nicer than something like Thunderbird because it's built-in to the application I use everyday.

I have bookmarks set up for all of my most-used sites.
![](/img/bookmarks.png)

### Extensions
My extensions:

- Adblock Plus
- Disconnect
- Docs PDF/Powerpoint Viewer (by Google)
- goo.gl URL Shortener
- Google Analytics Opt-out Add-on (by Google)
- Hacker News
- Hangouts call
- Imgur Uploader
- LastPass
- Reddit Enhancement Suite
- Right-Click Search Wikipedia
- Stay Focusd
- Terms of Service; Didn't Read
- The Old Reader Notifier
- Youtube Feed
- Youtube Options
- Youtube Ratings Preview

I'll talk about the ones I find very useful.

**LastPass** is the one thing I'd recommend that everyone get. And once you have it, generate new, secure passwords for every site you currently use. It's invaluable - I've never had a single problem with it.

**Stay Focusd** is a recent addition. It's been great - my focus has actually gotten much better. And when I need a break, I don't overdo it. The challenge to change settings is also very clever and useful.

**Terms of Service; Didn't Read** is a great extension for privacy-minded people. It tells you what you want to know about the sites you visit and use.

# Development
For Java development, I use Netbeans. Honestly, I'd like to get to know IntelliJ, but FRC plugins are for Netbeans and I'm already very used to it. It fits my workflow, so I use it.

For python, html, markdown and other development, I use geany. It might not be totally efficient, but its more powerful and has better plugins than most text editors, and works better on my systems versus gedit. When doing terminal work, I prefer nano. I guess I'm not elite enough to know vim and emacs. I guess I just haven't put in the time.

# Keyboard Shortcuts
My current shortcuts, as seen in [rc.xml](https://github.com/joelg236/my-config/blob/master/rc.xml)

![](/img/shortcuts.png)
