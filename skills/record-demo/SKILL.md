---
name: record-demo
description: Use when asked to record, shoot or make a demo video, screencast or walkthrough of a flow in a web app — a feature just built ("record a video of the feature we just built", "make a demo of checkout") or any public site ("record searching Wikipedia"). Produces an MP4 on disk through Demoman's tools.
---

# Record a demo with Demoman

Demoman's tools run a script you write in a browser window of their own on
this machine, then render the take to an MP4.

1. Call the `recipe` tool and follow it. It is the whole procedure: the
   script format with examples, how to read each report, and what every
   refusal means. Do not write a script before reading it.
2. The browser is signed in to nothing. A page behind a login shows its
   sign-in page: tell the user, and spend no run on it.
3. When `export` answers `saved`, give the user `summary` and `file.path`.
