# Sound Assets for Focus Tools

This directory should contain the following sound files:

## Required Sound Files:

1. **session_complete.mp3** - A success/celebration sound that plays when a focus session is completed
   - Duration: 2-3 seconds
   - Style: Positive, encouraging, not too loud
   - Format: MP3

2. **reminder.mp3** - A gentle notification sound that plays for focus reminders
   - Duration: 1-2 seconds  
   - Style: Soft, attention-getting, not jarring
   - Format: MP3

3. **session_stopped.mp3** - A shorter, less celebratory sound that plays when a session is stopped early
   - Duration: 1-2 seconds
   - Style: Neutral, informative, not disappointing
   - Format: MP3

4. **system_notification.mp3** - A fallback system notification sound (optional)
   - Duration: 1 second
   - Style: Standard system notification
   - Format: MP3

## Fallback Behavior:
- If sound files are not found, the app will use haptic feedback instead
- Session completion: Heavy impact haptic
- Session stopped: Light impact haptic
- Reminders: Medium impact haptic
- The app will also try to play a system notification sound as a secondary fallback

## Adding Your Own Sounds:
1. Place your MP3 files in this directory
2. Ensure they are named exactly as specified above
3. Keep file sizes reasonable (< 100KB each)
4. Test the sounds to ensure they're appropriate for the context

## Note:
The app will automatically fall back to haptic feedback if the audio files cannot be loaded, ensuring the user always gets some form of notification.
