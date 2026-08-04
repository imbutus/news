# MiniMaxDirector: a timeline for H3

*Published 2026-08-04*

I wrote a ComfyUI node for MiniMax H3 and released it as open source: **MiniMaxDirector**. Instead of packing an entire film into one prompt box, you lay it out on a timeline — what happens on screen, how the camera moves, what is heard — and it compiles that into the single structured prompt H3 actually reads.

What it does for you:

- **Three tracks.** Shots, camera and audio, each segment with its own text and its own span.
- **Cut times are computed**, so the model is told exactly when each shot begins.
- **Legal lengths only.** The clip is snapped to a duration H3 accepts, so a run cannot fail on arithmetic.
- **Attach a file to a segment** and it becomes a numbered reference in the prompt automatically — no tokens to type by hand.

**It is already installed on your GPU.** Start the MiniMax H3 bundle and open **Docs** → Media → MiniMax H3 → the MiniMaxDirector workflow; the graph is ready to run, nothing to install.

On your own machine, it is on the ComfyUI registry as `minimax-director` — searchable in the ComfyUI Manager, or `comfy node install minimax-director`. Source and issues: [github.com/imbutus/ComfyUI-MiniMaxDirector](https://github.com/imbutus/ComfyUI-MiniMaxDirector). MIT licensed.
