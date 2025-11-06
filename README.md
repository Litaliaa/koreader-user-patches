# KOReader User Patches

## 2-minimal-book-stats-screensaver.lua
A clean, minimalist KOReader screensaver showing key reading statistics.
Displays progress, pages left, time left, highlights, notes, and battery percentage.

See visual example [here](https://github.com/Litaliaa/koreader-user-patches/blob/26bca80498134863d2a637f16877e89a9e2b5708/Example%20of%20screensaver.JPG)

Based on the Book Receipt plugin by [Omer Faruq](https://github.com/omer-faruq).
Modified and redesigned for a minimalist style by me (and mostly ChatGPT).
**Original code:** Created by Reddit user [hundredpercentcocoa](https://www.reddit.com/user/hundredpercentcocoa/)

**Features:**
- Can be set as screensaver/sleep screen (Settings > Screen > Sleep Screen > Wallpaper > Show minimal book stats on sleep screen)
- When added as wallpaper, it provides background color options (white/black/transparent/random image)
- Selecting the random image option searches for a `book_receipt_background` folder under the `koreader` folder and randomly picks one of its images as the background; if the folder is missing, the background defaults to transparent

**Modifications in this fork:**
– Renamed from "book receipt" to "minimal book stats"
- Removed chapter stats section
- Removed book stats section
- Added extra stats (reading time, page progress, pages left, time left, number of highlights and notes)
- Tweaked styling for a cleaner look
- Made progress % larger
