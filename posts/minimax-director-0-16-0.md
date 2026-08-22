# MiniMaxDirector 0.16.0: everything the H3 guides ask for

*Published 2026-08-22*

The node I released in August has had 264 commits since, and **0.16.0** collects them. The idea is unchanged — you lay a film out on a timeline instead of cramming it into one prompt box — but far more of what H3 actually reads now comes out of it.

- **Everyone and everything gets a card.** A person, a prop, a costume, a place, a look: one card each, holding the picture it came from, its description and its voice. It is the only place a file is described, so nothing is repeated on a block.
- **The voices come out of the same pass as the picture.** Write the line, pick the face, and it compiles in the exact form H3 was trained on — including a line that crosses a cut, or one cut off by the end of the clip.
- **A face can be carried onto somebody else.** A card can also take its motion from a video and its timbre from a recording, and each of those is cited inside the subject it belongs to rather than left floating.
- **Every file the clip carries sits in one list.** Drag one onto a track to place it, or leave it clip-wide for a look that has to hold throughout. A file that has gone missing says so, and the run is refused instead of quietly producing the wrong thing.
- **A live linter** checks the rules the guides state outright: clip length, reference clips outside 2–15 seconds, a marker that cannot do what it is being asked to do.
- **The node is as tall as whatever you have open**, and the whole piece exports as one JSON.

Full notes: [the 0.16.0 release](https://github.com/imbutus/ComfyUI-MiniMaxDirector/releases/tag/v0.16.0).

**It is already on your GPU.** Start the MiniMax H3 bundle and open **Docs** → Media → MiniMax H3 → the MiniMaxDirector workflow. The bundle loads the newest release from GitHub, so there is nothing for you to update.

On your own machine, clone [github.com/imbutus/ComfyUI-MiniMaxDirector](https://github.com/imbutus/ComfyUI-MiniMaxDirector) into `custom_nodes/`, or install `minimax-director` from the ComfyUI registry once 0.16.0 clears review there. Needs ComfyUI 0.31.0 or newer. MIT licensed.
