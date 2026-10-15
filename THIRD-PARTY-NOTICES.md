# Third-party components

Rabbit Downloader uses the following. Their licences apply to those parts.

| Component | Licence | Used for |
|---|---|---|
| [.NET 8](https://github.com/dotnet/runtime) | MIT | the runtime |
| [FFmpeg](https://ffmpeg.org/) | GPL 3 (BtbN build) | turning .ts videos into .mp4 and joining picture and sound |
| [aria2](https://github.com/aria2/aria2) | GPL 2 | torrents and magnet links |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | Unlicense | site videos |
| [Deno](https://github.com/denoland/deno) | MIT | running site players' code for yt-dlp |

FFmpeg, aria2, yt-dlp and Deno are separate programs. They are not part of the download:
Setup or Settings fetches them unmodified from their official GitHub releases
when you ask, and Rabbit Downloader runs them as they are. Their source is
available at the links above.
