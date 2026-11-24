# Introduction

A patch to improve rendering and memory cleanup in the Flutter iOS engine.

## Current Patches

| Area | Summary |
| --- | --- |
| Metal rendering | Present frames through a native CAMetalLayer and keep compositing settings fixed |
| Platform Views | Composite Flutter frames and native views in the same transaction |
| Memory cleanup | Release temporary objects after each task on Darwin |
