# JJ Cute Couple — media

Finished puppy-video output, hosted publicly here purely so Metricool can
pull them by URL for scheduling (Metricool's post tools require a public
media URL, not a file upload). This repo is media storage, not the build
method — for how these are made, see
[Viral-Cartoon-Video](https://github.com/Chubyilo92/Viral-Cartoon-Video).

## Layout

```
videos/YYYY-MM-DD-<script-slug>-instagram.mp4
videos/YYYY-MM-DD-<script-slug>-tiktok.mp4
```

Each script produces two files — same body, different end card (Instagram
quiz ending vs. TikTok follow ending; see the build repo's
`docs/GROWTH-STRATEGY.md`).

## Getting a Metricool-ready URL

Once a file is pushed to `main`, its public URL is:

```
https://raw.githubusercontent.com/Chubyilo92/JJCutecouple/main/videos/<filename>
```

That's the URL to pass as Metricool's `media` field.
