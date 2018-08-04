# HTTP server from gRPC with Gateway

📆 June 8th, 2017

🗺️ Wrocław, 🇵🇱

🏛️ [GoWroc #18](https://www.meetup.com/gowroc/events/240417065/)

## Description

Building a gRPC service is not that complicated, even if we want to add some security, custom interceptors and complex request or response messages. Unfortunately, it’s still not as popular as we’d like, and most of the time we need to support HTTP as well. Building two identical APIs seems like a terrible idea, but this is where gRPC Gateway steps in.
