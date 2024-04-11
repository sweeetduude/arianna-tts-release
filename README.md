# ARIANNA TTS

Welcome to Arianna TTS!

## Installation

### Prerequisites

Before you start using ARIANNA TTS, make sure you have the following installed:

-   **Windows**: Arianna TTS only works on Windows OS.
-   **FFMPEG**: Essential for handling audio playback. You can download FFMPEG from [here](https://ffmpeg.org/download.html). Ensure that `ffplay` is accessible from your system's PATH.
-   **TTS Token**: Required for accessing the TTS service. Visit [arianna.gg/tts](https://arianna.gg/tts) to obtain your token. Currently only available for Tier 3 subscribers.

### Download

The latest version of ARIANNA TTS can be found [here](https://github.com/sweeetduude/arianna-tts-release/releases). Download the `.zip` file and unpack it to any location.

## Configuration

Upon first launch, you will be prompted to enter your TTS token. Follow these steps to complete the setup:

1. Start ARIANNA TTS.
2. A prompt will appear asking for a TTS token. If you don't have one, click on the link to be redirected to [arianna.gg/tts](https://arianna.gg/tts) where you can obtain it. Currently only available for Tier 3 subscribers.
3. Enter your token in the provided field and click "Save Token".
4. The application is now ready for use.

## Custom TTS with embedded sounds and Brian TTS

To embed custom sounds within the TTS, use the following format: `###sound_name###` or `{sound_name}`. Replace `sound_name` with the name of the sound. A full list of available sounds can be found within the tool.

Copy and paste this text as an example:

```
Hi there I'm Arianna {burp} Nice to meet you!
```

To embed Brian TTS, use the following format: `###Brian TTS text###` or `{Brian TTS text}`. Replace `Brian TTS text` with the text you want to generate. If the text is exactly the same as a sound_name then the sound will be played instead. Add a space infront of the sound name `### sound_name###` and the text will be generated as Brian TTS.

Copy and paste this as an example:

```
{Knock knock}
Who’s there?
{Luke.}
Luke who?
{Luke through the peep hole and find out.}
```


Have fun! 

Developed with ❤️ by Sweeetduude
