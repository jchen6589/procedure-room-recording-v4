# procedure-room-recording-v4
## GCSI procedure room recording system v4
- Prevent “Start Recording” button click until 15 seconds after page loads (to account for Windows 10 PC browser limitations)\
- Changed “real_time_encrypt.ps1” script to reset every 10 seconds to ensure webm files are being read as they are downloaded
- Download as .mp4 instead of .webm (added new codecs to allow audio playback as mp4)
- Cleaner github URL (removed “.html”)
- Removed unnecessary CSS bloat copied from website template


The Recording System has the following features: 
-	Requires minimal input from students to record and save videos.
-	Allows students to modify camera setup for different procedures.
-	Saves video recordings as .mp4 for simple playback on most video players.
-	Uses OBS Studio to allow for multiple camera angle streams.
-	Automatically names video files using students’ information for easy sorting by administrators.
-	Automatically deletes video recordings and student information from local storage after video is saved (prevents PII access between students).
-	Automatically encrypts saved videos using 7-Zip, extractable only by administrators (prevents PII access between students).
