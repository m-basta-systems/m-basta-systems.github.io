[BASTA Systems](#high-performance-systems--media-engineering) | [Tech Stack](#tech-stack) | [Services](#services) | [Contact](#ready-to-build)

## High-Performance Systems & Media Engineering

I build reliable, low-latency software for demanding environments, from GStreamer media pipelines on embedded Linux to multithreaded Rust and C++ backends where correctness and performance are non-negotiable.

Typical results:

* Eliminate dropped frames and pipeline stalls
* Reduce latency and improve throughput
* Stabilize multithreaded systems under load
* Build complex video streaming pipelines from scratch
* Integrate Rust into existing C/C++ codebases

[Tell me about your project](mailto:office@bastasystems.com)

---

### Services

| Systems Programming | Media & Streaming Pipelines |
|---|---|
| Rust and C++ development | Design and debuggin of GStreamer pipelines |
| Multithreaded, memory-safe applications | Dynamic audio/video streaming systems |
| Perfomance optimization and profiling | Custom plugin development |
| Application development on embedded devices | Audio engines |
| Low-latency backends | Real-time processing under load |

I also take on Python automation, scripting, and web backend work.
Reach out if you have something that doesn't fit neatly into the above.

---

## Tech Stack

**Primary:**

Rust | C++ | GStreamer | Linux

**Supporting:**

Python | Django | PostgreSQL | FFmpeg | Qt | FMOD

## Case Studies

### Gapless Audio Playback on Embedded Hardware

> Fixing hardware limitations with software

Audio streaming engine | GStreamer | Embedded Linux | C | C++

A consumer audio product required a robust streaming engine capable of playing music from a variety of sources with no audible artifacts. Dropouts, glitches, or gaps between tracks were customer-facing failures with no tolerance.

The engine used complex, dynamic GStreamer pipelines that were assembled and modified at runtime. My task was achieving true gapless CD playback on hardware whose CD drive had no native gapless support. This required precise pipeline-level buffering and timing control to eliminate the inter-track silence that the drive would otherwise introduce.

The result was a stable, artifact-free engine shipped in a commercial product.

---

### Dynamic Video Streaming Pipeline on NVIDIA Jetson TX2

> Dynamic pipelines, static guarantees

GStreamer | Rust | Embedded Linux | REST API

An industrial device required a video streaming pipeline that could be fully reconfigured at runtime without crashing or requiring a restart: sources, sinks, resolution, framerate, and other stream parameters were all adjustable on the fly.

I built the pipeline in Rust with GStreamer, with the focus on correctness and stability under continuous dynamic reconfiguration. The pipeline was wrapped in a RESTful service to allow external control of all configuration options over the network.

The deliverable was a stable, controllable pipeline suitable for deployment on resource-constrained embedded hardware.

---

## Ready to Build?

Whether you're designing a new streaming architecture, chasing a latency bottleneck, or integrating Rust into an existing C++ codebase, I'd like to hear about it.

Book a short technical call:
[Proton Calendar](https://calendar.proton.me/bookings#r6hmvGL8aJBB4imHOf36EMYC8wJH6C04nwt9kOSit-g=) | [Google Meet](https://calendar.app.google/VZwZqgb4UhaNemzTA)

Or email directly: [office@bastasystems.com](mailto:office@bastasystems.com)

---

© 2026 BASTA Systems | [GitHub](github.com/m-basta-systems) | [Impressum]()
