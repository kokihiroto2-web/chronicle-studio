# chronicle-studio

**EN** — chronicle-studio is a private, single-user command-line tool (Python) that
automates the management of the developer's own YouTube channels. It has exactly two
functions:

1. **Upload**: uploads the developer's own finished videos to the developer's own
   YouTube channels as *private* videos and sets the title, description, tags and
   thumbnail written by the developer (`videos.insert`, `thumbnails.set`). Every video
   is reviewed by the developer in YouTube Studio before being published manually.
2. **Performance check**: once per day, reads the public statistics (view count,
   like count) and comments of the developer's *own* published videos to improve
   future videos (`videos.list`, `commentThreads.list`).

The tool is used **only by the developer**. It is not distributed, sold, or offered
as a service. It never accesses, collects, or stores data of any other user or
channel. This repository hosts the public documentation (including the
[Privacy Policy](./PRIVACY.md)) for the YouTube API Services compliance audit.

**JP** — chronicle-studio は、開発者本人のYouTubeチャンネル運営を自動化する
私的なコマンドラインツール（Python製・利用者は開発者1名のみ）です。機能は
「自作動画の非公開アップロード（公開は毎回手動で確認）」と「自分の公開動画の
統計・コメントの1日1回の読み取り」の2つだけです。第三者への配布・販売は行わず、
他のユーザーやチャンネルのデータへのアクセス・収集・保存は一切行いません。

- Privacy Policy: [PRIVACY.md](./PRIVACY.md)
- YouTube channels operated by the developer:
  - https://www.youtube.com/channel/UCnV_R2UCX-qhbbpoOh8LSlA
  - https://www.youtube.com/channel/UCYoxwNaaht8um6b9Mkjuu2A
