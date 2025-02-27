---
title: Use existing players to playback your content - Azure | Microsoft Docs
description: This article lists existing players that you can use to playback your content.
services: media-services
documentationcenter: ''
author: IngridAtMicrosoft
manager: femila
editor: ''
ms.assetid: 7e9fcf89-0fb6-4fa4-96cb-666320684d69
ms.service: media-services
ms.workload: media
ms.tgt_pltfrm: na
ms.topic: article
ms.date: 03/10/2021
ms.author: inhenkel
---
# Playing your content with existing players

[!INCLUDE [media services api v2 logo](./includes/v2-hr.md)]

Azure Media Services supports many popular streaming formats, such as Smooth Streaming, HTTP Live Streaming, and MPEG-Dash. This topic points you to existing players that you can use to test your streams.

## The Azure portal Media Services content player

The **Azure** portal provides a content player that you can use to test your video.

Click on the desired video (make sure it was [published](media-services-portal-publish.md)) and click the **Play** button at the bottom of the portal.

Some considerations apply:

* The **MEDIA SERVICES CONTENT PLAYER** plays from the default streaming endpoint. If you want to play from a non-default streaming endpoint, use another player. For example, [Azure Media Player](https://aka.ms/azuremediaplayer).

### Azure Media Player

Use [Azure Media Player](https://aka.ms/azuremediaplayer) to playback your content (clear or protected) in any of the following formats:

* Smooth Streaming
* MPEG DASH
* HLS
* Progressive MP4

### Flash Player

#### PlayReady with Token

[http://reference.dashif.org/dash.js/nightly/samples/dash-if-reference-player/index.html](http://reference.dashif.org/dash.js/nightly/samples/dash-if-reference-player/index.html)

### DASH Players

[dash player](http://players.akamai.com/players/dashjs)

[https://dashif.org](https://dashif.org)

### Other

To test HLS URLs you can also use:

* **Safari** on an iOS device or
* **3ivx HLS Player** on Windows.

## Media Services learning paths

[!INCLUDE [media-services-learning-paths-include](../../../includes/media-services-learning-paths-include.md)]

## Provide feedback

[!INCLUDE [media-services-user-voice-include](../../../includes/media-services-user-voice-include.md)]
