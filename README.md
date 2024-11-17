# Abema-TV-EPG
XML EPG for Abema TV channels

## Overview

This repository contains the XML EPG (Electronic Program Guide) for Abema TV channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/Abema-TV-EPG/refs/heads/main/abema.xml

## Features

- XML formatted EPG for Abema TV channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/Abema-TV-EPG/refs/heads/main/abema.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/Abema-TV-EPG/refs/heads/main/abema.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id            | Channel Name               |
|-------------------|----------------------------|
| abema-news        | ABEMA NEWSチャンネル       |
| news-plus         | ABEMA NEWS会見チャンネル    |
| abema-special     | ABEMA SPECIALチャンネル    |
| special-plus      | ABEMA SPECIAL 2チャンネル  |
| special-plus-2    | ABEMA SPECIAL 3チャンネル  |
| abema-anime       | ABEMA アニメチャンネル    |
| abema-anime-2     | ABEMA アニメチャンネル2   |
| drama             | ドラマ映画チャンネル       |
| drama-2           | ドラマ映画チャンネル2      |
| 80s-anime-1       | なつかしアニメ80's         |
| special-plus-7    | アニメSPECIALチャンネル   |
| 90s-anime-1       | なつかしアニメ90's         |
| 00s-anime-1       | なつかしアニメ00's         |
| precure           | プリキュアチャンネル       |
| atashinchi        | あたしンちチャンネル       |
| family-anime-1    | ファミリーアニメ           |
| family-anime-2    | ファミリーアニメ２         |
| asia-drama        | 韓国・中国ドラマチャンネル |
| asia-love-comedy  | 韓国ラブコメディ           |
| asia-loveromance  | 韓国ラブロマンス           |
| asia-historical   | 韓国時代劇                 |
| asia-drama-2      | 韓国・中国ドラマチャンネル2|
| anime-special-2   | アニメSPECIAL2チャンネル  |
| k-world           | K WORLDチャンネル          |
| anime-live        | アニメLIVEチャンネル       |
| isekai-anime      | 異世界・ファンタジーアニメチャンネル |
| isekai-anime-2    | 異世界・ファンタジーアニメ2チャンネル |
| lovecomedy-anime  | ラブコメアニメチャンネル   |
| dailylife-anime   | 日常・青春アニメチャンネル |
| late-night-anime  | 深夜アニメチャンネル       |
| mahjong           | 麻雀チャンネル             |
| shogi             | 将棋チャンネル             |
| world-sports      | SPORTSチャンネル           |
| sumo              | 大相撲チャンネル           |
| fighting-sports   | 格闘チャンネル             |
| hiphop            | HIPHOPチャンネル           |
| commercial        | CMチャンネル               |
| keirin-auto       | 競輪・オートレースチャンネル |

