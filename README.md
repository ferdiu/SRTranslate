# SRTranslate

Translate a subtitles `*.srt` file to any language using Google Translate API.

## Installation

Just move `srtranslate` file in a directory in your `PATH`.

Do not forget to `chmod +x` it.

## Usage

```
srtranslate <source language> <target language> PATH_TO_FILE.srt
```

#### Example

Executing this in a directory containing the file `video.srt`:

```
srtranslate en it video.srt
```

will produce the file `video_it.srt`.