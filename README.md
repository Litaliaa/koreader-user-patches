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
- Selecting the random image option searches for a `book_receipt_background` folder under the `koreader` folder and randomly picks one of its images as the background; if the folder is missing, the background defaults to transparent. (Note: this feature may be broken as I changed the original 'book receipt' name to 'minimal book stats' and haven't tested this feature)

**Modifications in this fork:**
- Renamed from "book receipt" to "minimal book stats"
- Removed chapter stats section
- Removed book stats section
- Added extra stats (reading time, page progress, pages left, time left, number of highlights and notes)
- Tweaked styling for a cleaner look
- Made progress % larger
- Modified code to work with default UI font (no need to edit the code). This pairs nicely with [2--ui-font.lua](https://github.com/sebdelsol/KOReader.patches/blob/0a2a57b44847f23e5db5db5edcc7a1cc0fc94dd0/2--ui-font.lua) to choose what font you want for your UI. Note that I'm not the developer of 2--ui-font.lua so I can't guarantee it will work for you.
