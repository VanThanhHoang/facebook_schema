| Description                 | Command                                                                                                        |
|-----------------------------|---------------------------------------------------------------------------------------------------------------|
| Create reels                | `adb shell am start -n com.facebook.katana/com.facebook.katana.IntentUriHandler -d "https://www.facebook.com/reelscomposer"` |
| Create story                | `adb shell am start -n com.facebook.katana/com.facebook.katana.IntentUriHandler -d "https://www.facebook.com/storiescomposerforadscampaign"` |
| Open a reel by ID           | `adb shell am start -n com.facebook.katana/com.facebook.katana.IntentUriHandler -d "https://www.facebook.com/reel/{video_id}"` |
| Open a live, group, or post by link | `adb shell am start -n com.facebook.katana/com.facebook.katana.IntentUriHandler -d "{post_link}"` |
| Open settings               | `adb shell am start -n com.facebook.katana/com.facebook.katana.IntentUriHandler -d "https://www.facebook.com/settings"` |
| Open my profile             | `adb shell am start -n com.facebook.katana/com.facebook.katana.IntentUriHandler -d "https://www.facebook.com/profile.php"` |
