# MVP

## Vision

The MVP `shirley` product will only consist of the video-processing aspect and a way to present the results. Note that the MVP is *agnostic* of how/where the video was recorded. 

Functionality will include:

- A end-to-end video processing pipeline that takes a POV-recording of a biological experiment and programmatically produces a transcript of performed procedures
  - [Reach] Provide interface to trace back procedure steps to parts of the video
- A web-app platform to upload videos to that begins the video-processing pipeline

## Materials needed

1. Something to film with
    - GoPro?
    - Meta Smart Ray-Ban Glasses?
    - (Worst case) Just film through your phone/laptop

## Ideas

- Does prompt engineering work for GPT-V with video?
- Is this basically a "video summarization" task?
- How to handle low resolution recordings?
- For the reach goal of tracing back procedure to video, use a similar UI as the Zoom recording transcript, where you can interactively click on the step and the recording will move back to the spot.