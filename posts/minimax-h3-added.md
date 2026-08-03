# MiniMax H3 is available

*Published 2026-08-03*

A new video bundle is on the **Media** page: **MiniMax H3**, an omni-modal model that generates picture and sound in one pass — the audio is not dubbed on afterwards, it comes out of the same generation as the video.

What is worth knowing before your first clip:

- **Sound is part of the model.** Describe what is heard the same way you describe what is seen, and it is generated with the shot. Stereo, no separate voice step.
- **Reference images, audio and video.** Attach them and point at them from the prompt; the model uses them to keep a subject or a look consistent across shots.
- **Clip length is not free.** H3 accepts lengths on a fixed lattice at 24 fps, so the workflow snaps whatever you ask for to the nearest legal value. 8, 25 and 42 seconds are the whole-second ones.
- **One prompt, many shots.** The model reads a shot list with cut times, so a single generation can contain several shots rather than one continuous take.

Open **Media** → Video → MiniMax H3 to start it.
