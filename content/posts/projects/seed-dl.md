---
title: "My seedbox managing tool: seed-dl"
draft: false
weight: 1
url: "/projects/seed-dl"
---

# Overview

[Seed-dl](https://github.com/williameast/seed-dl) is a tool to make managing
torrent files easier when you use a seedbox. With a single command it can

- put your torrent files into the seedbox
- check if the torrent files have finished downloading
- download the files, throwing them into a directory depending on their file
  type

It keeps a register of your local .torrent files, so if you share a seedbox or a
server with a friend, you can download only your own files automatically. build
isolation with poetry means it runs on anything poetry runs.
