# shirley

Smart assistant for wet-lab researchers that documents your experiments in fine detail and offers quick help for your lab work. Delivered through [Ray-Ban Meta smart glasses](https://www.ray-ban.com/canada/en/ray-ban-meta-smart-glasses).

## How to use

Just say:

`Hey shirley, start experiment`.

## Core Features

### Experiment Recording/Tracking

`shirley` can automatically record and upload your experiment through the AR glasses lens, providing a lightweight way to track your past work. Experiment recordings will also be "transcribed" into a manuscript which contains your procedure and equipment, and specific steps can be traced back to certain timestamps in the video.

### Procedure Extraction

Using experiment logs, `shirley` can extract a dynamic, step-by-step procedure for your experiments (with video!). These procedures can be used for training and quality assurance within the lab or beyond.

### Personal Helper

`shirley` can also help with common and quick calculations required during your experiment, like dilution volumes and unit conversions. You can also set multiple timers and reminders with a simple voice command to `shirley`.

### Build Institutional Knowledge

One major challenge for research labs is that knowledge comes and goes with *the person who did the research*. `shirley` can create a catalogue of past experiments, making everything traceable and searchable. Some example applications:

- If a researcher wanted to investigate what went wrong with a irregular sample, they can look up the logs & video of how they prepped that *exact* sample and debug much easier.
- If a newly-joined researcher wanted to learn from how others performed a certain step, they can search through other experiments and find some past examples.
- If a researcher found an improvement to some experimental step, they could "commit" the change (similar to in `git`), provide reasoning & additional information, and the procedure history would track this change and be referenceable in the future.

## Extended Features

### Real-time Suggestions

You can instruct `shirley` to start an existing experiment, and it will use previous logs and procedures to guide you through in real time. Some examples include:

- Voice commands (e.g. "now, spin your tubes in the centrifuge for 5 mins at 300RPM")
- Mixed-reality projections (e.g. an arrow that points to the slot you should put your tube back into once you are done pipetting)
- Real-time advice (e.g. "it looks like you have set 3.5µg, not 35µg, on the pipette tip. Please check again")

### Livestreaming

The ability to livestream and share "what I am seeing" in a lab can help increasing flexibility in research work. For example, if you cannot physically make it to the lab, you could instruct someone else through a livestream with the glasses on. Communicating lab work would no longer be greatly complicated by distance & remote work.

