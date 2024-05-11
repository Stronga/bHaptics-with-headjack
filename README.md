# bHaptics-with-headjack
Creating a haptic event for 360 videos using headjack CMS and bHaptic plugin in Unity.

#mappings.json file
this is where nappings will be loaded from.
```
{
  "Mappings": [
    { "VideoID": "your_videoID", "HapticPattern": "event_name" },
     { "VideoID": "your_videoID", "HapticPattern": "event_name" },
    // Add more mappings
  ]
}
```
Ensure each video ID is mapped to the correct haptic pattern name as defined in your bHaptics developer window.

# ConfigLoader.cs
This script is responsible for loading the mappings from the JSON file into a usable form within your Unity.

# getting Started 
