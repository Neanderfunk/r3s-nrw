---
title: "Streams"
categories:
  - Streams
description: Streams der R3S
date: 2020-12-18T14:50:34+01:00
draft: false
---

## Twitch
{{< rawhtml >}}
<script src= "https://player.twitch.tv/js/embed/v1.js"></script>
<div class="mediaplayer" id="twitch-player"></div>
<script type="text/javascript">
  var options = {
    width: "100%",
    height: "500",
    channel: "RemoteRheinRuhrStage",
    // only needed if your site is also embedded on embed.example.com and othersite.example.com
    //parent: ["embed.example.com", "othersite.example.com"]
  };
  var player = new Twitch.Player("twitch-player", options);
  player.setVolume(0.5);
</script>
{{< /rawhtml >}}
