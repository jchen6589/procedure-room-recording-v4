# procedure-room-recording-v4
## GCSI procedure room recording system v4
-Added MediaRecorder delay to accomodate older laptop web browsers

The Recording System has the following features: 
-	Requires minimal input from students to record and save videos.
-	Allows students to modify camera setup for different procedures.
-	Saves video recordings as .mp4 for simple playback on most video players.
-	Uses OBS Studio to allow for multiple camera angle streams.
-	Automatically names video files using students’ information for easy sorting by administrators.
-	Automatically deletes video recordings and student information from local storage after video is saved (prevents PII access between students).
-	Automatically encrypts saved videos using 7-Zip, extractable only by administrators (prevents PII access between students).
