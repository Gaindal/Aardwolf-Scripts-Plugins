# Aardwolf Vorpal Tracker – Elegant Edition

**Version 2.0**  
Author: Gaindal  

A configurable, colour-aware vorpal tracker plugin for MUSHclient users playing Aardwolf MUD.

Tracks your decapitations with style.

---

## ✨ Features

- Session, Daily, and Lifetime vorpal tracking
- Automatic daily reset
- Configurable announcement channel
- Mute / unmute support
- Three message modes (Default, Brief, Custom)
- Colour-aware placeholders
- Live preview command
- Manual adjustment commands
- Persistent storage between sessions
- Lightweight and self-contained

---

## Installation

1. Download aardwolf_vorpal_tracker.xml
2. Place it in your Plugins folder
3. Open MUSHclient
4. Go to **File → Plugins**
5. Click **Add**
6. Select the XML file
7. Ensure the plugin is enabled

You should see:

Aardwolf Vorpal Tracker – Elegant Edition v2.0 loaded.

---

**Commands**

**vorpalhelp**    (shows the command list)

### Stats

**vorpalstats**		(displays session, daily, and lifetime totals)

**vorpalreset**		(gives a reset warning)
**vorpalreset confirm**	(resets all counters)

---

### Channel Control

**vorpalchan**		(shows current report channel and active/mute status)

**vorpalchan CHANNEL**	(sets report channel. e.g. vorpalchan gt, vorpalchan echo)

**vorpalchan mute**		(mutes reporting but does not stop the vorpal tracking)

**vorpalchan unmute**	(resumes reporting)


---

### Message Modes

**vorpalmessage**		(shows current message mode and preview)

**vorpalmessage default**	(sets the vorpal message to the default Duffle bag message) (classic mode).

**vorpalmessage brief**	(sets the vorpal message to a short, clean message)

**vorpalmessage new**	(shows custom message help)

**vorpalmessage new TEXT**	(sets a custom message)

**vorpaltest**		(displays exactly how your message will look without increasing totals)

### Custom Placeholders

Available placeholders for custom messages:

{session}
{today}
{lifetime}

You can use one, two or all three of these placeholders and in any order.

Example:

vorpalmessage new just claimed another head! That's {today} today and {lifetime} total...

will set you message to look like...

Player just claimed another head!  That's 36 today and 146 total...

Numbers automatically use the plugin's colour scheme.

---

### Manual Adjustment (Advanced)

**setsessionvorpals** #

**settodayvorpals** #

**setlifetimevorpals** #


Intended for correction or migration purposes.


Daily totals automatically reset based on your system date.


## 🛠 Requirements

- MUSHclient 4.94 or newer
- Designed for use with Aardwolf MUD

---

## 📜 License

Released for public use within the Aardwolf community.  
You are free to modify for personal use.

If redistributing modified versions, please credit the original author.

---

Enjoy watching those heads stack up.
