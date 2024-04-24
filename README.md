# yt-dlp Cheatsheet

## Video Download

```
yt-dlp "<URL>"
```

#### Example:

```
yt-dlp "https://www.youtube.com/watch?v=UbQgXeY_zi4"
```

### Download video in a specific file format

```
yt-dlp --recode-video mp4 "<URL>"
```

#### Example:

```
yt-dlp --recode-video mp4 "https://www.youtube.com/watch?v=UbQgXeY_zi4"
```

## Audio Download

```
yt-dlp -x --audio-format mp3 "<URL>"
```

#### Example:

```
yt-dlp -x --audio-format mp3 "https://www.youtube.com/watch?v=UbQgXeY_zi4"
```

## Documentation

- [Official GitHub Repository](https://github.com/yt-dlp/yt-dlp)
- [Supported Sites](https://github.com/yt-dlp/yt-dlp/blob/master/supportedsites.md)
