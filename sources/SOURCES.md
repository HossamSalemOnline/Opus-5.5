# Sources and capture log

Every original source behind the hub, with how it was captured. All captures used Apify.

## e001: Claude Opus 5.5 + 13 free GitHub repos = your own editing desk

| Source | Type | Author | Published (UTC) | Captured | Method |
|---|---|---|---|---|---|
| https://x.com/Y0urDumble/status/2123130575230042601 | X post (long-form note) | @Y0urDumble | 18 Nov 2026, 19:05 | 19 Nov 2026 | `xquik/x-tweet-scraper` (text + expanded links), `apidojo/tweet-scraper` (replies) |

## e002: How to build a 2.5D motion studio with Opus 5.5 (Full Course)

| Source | Type | Author | Published (UTC) | Captured | Method |
|---|---|---|---|---|---|
| https://x.com/Y0urDumble/status/2115164938884862375 | X Article | @Y0urDumble | 27 Oct 2026, 19:33 | 19 Nov 2026 | `xquik/x-article-scraper` (full content blocks) |
| https://x.com/claudeai/status/2102435511222890900 | Embedded post: Opus 5.5 launch | @claudeai | 22 Sep 2026, 16:31 | 19 Nov 2026 | `xquik/x-tweet-scraper` |
| https://x.com/alexalbert__/status/2102458348511879448 | Embedded post: Blender claymation | @alexalbert__ | 22 Sep 2026, 18:01 | 19 Nov 2026 | `xquik/x-tweet-scraper` |
| https://x.com/claudeai/status/2103515655760982273 | Embedded post: first-week highlights | @claudeai | 25 Sep 2026, 16:03 | 19 Nov 2026 | `xquik/x-tweet-scraper` |
| https://x.com/RyanSael/status/2102591147927654847 | Quoted inside the post above | @RyanSael | | 19 Nov 2026 | Text only, from the quoting post |

Replies to the article were not returned publicly by X.

## Media

29 files (14 videos and posters, 1 cover, 8 article images, embedded-post videos) are listed in [media-manifest.json](https://github.com/HossamSalemOnline/Opus-5.5/blob/main/sources/media-manifest.json) with their original X URLs and an Apify backup copy. The fetch-media workflow stores them all in `docs/media/`.

## Rights

All post text, prompts, images and videos belong to their authors (@Y0urDumble; @claudeai, @alexalbert__ and @RyanSael for the embedded posts). This archive is for personal reference.
