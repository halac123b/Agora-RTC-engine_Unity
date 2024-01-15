# Call quality best practice

Customer satisfaction for your Agora Video SDK integrated app depends on the quality of video and audio it provides. Quality of audiovisual communication through your app is affected by the following factors:

- Bandwidth of network connection: Bandwidth is the volume of information that an Internet connection can handle per unit of time. When the available bandwidth is not sufficient to transmit the amount of data necessary to provide the desired video quality, your users see jerky or frozen video along with audio that cuts in and out.

- Stability of network connection: Network connections are often unstable with the network quality going up and down. Users get temporarily disconnected and come back online after an interruption. These issues lead to a poor audiovisual experience for your users unless your app is configured to respond to these situations and take remedial actions.

- Hardware quality: The camera and microphone used to capture video and audio must be of sufficiently good quality. If the user's hardware does not capture the audiovisual information in suitably high definition, it limits the quality of audio and video that is available to the remote user.

- Video and audio settings: The sharpness, smoothness, and overall quality of the video is directly linked to the frame rate, bitrate and other video settings. Similarly, the audio quality depends on the sample rate, bitrate, number of channels and other audio parameters. If you do not choose proper settings, the audio and video transmitted are of poor quality. On the other hand, if the settings are too demanding, the available bandwidth quickly gets choked, leading to suboptimal experience for your users.

- Echo: Echo is produced when your audio signal is played by a remote user through a speakerphone or an external device. This audio is captured by the remote user's microphone and sent back to you. Echo negatively affects audio quality, making speech difficult to understand.

- Multiple users in a channel: When multiple users engage in real-time audio and video communication in a channel, the available bandwidth is quickly used up due to several incoming audio and video streams. The device performance also deteriorates due to the excessive workload required to decode and render multiple video streams.

- Latency: Latency is the time it takes for a single video frame to transfer from the sender's camera to the receiver's display. Network routers are the most common cause of latency on the end-to-end path. Satellite communication also adds significant latency to audio and video streaming.

This sample project shows you how to use Video SDK features to account for these factors and ensure optimal audio and video quality in your app.

## Understand the code

For context on this sample, and a full explanation of the essential code snippets used in this project, read the **Call quality best practice** document for your product of interest:

* [Video calling](https://docs.agora.io/en/video-calling/develop/ensure-channel-quality?platform=unity)
* [Voice calling](https://docs.agora.io/en/voice-calling/develop/ensure-channel-quality?platform=unity)
* [Interactive live Streaming](https://docs.agora.io/en/interactive-live-streaming/develop/ensure-channel-quality?platform=unity)
* [Broadcast streaming](https://docs.agora.io/en/broadcast-streaming/develop/ensure-channel-quality?platform=unity)

For the UI implementation of this example, refer to [`EnsureCallQuality.cs`](./EnsureCallQuality.cs).

## How to run this example

To see how to run this example, refer to the [README](../../README.md) in the root folder or one of the complete product guides.
