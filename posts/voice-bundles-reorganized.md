# Voice bundles reorganized

*Published 2026-07-28*

The four voice bundles now have one clear job each, one shared set of workflow names, and they start faster.

- **Fish Audio S2 — the dubbing pick.** Text-to-speech and voice cloning across 80+ languages, with voice-to-SRT and SRT-to-voice that keep the original timing.
- **CosyVoice 3 — the change-voice pick.** Native voice conversion keeps the original words, pauses and delivery and swaps only the timbre, with no transcription step in between.
- **Qwen3-TTS — the all-Qwen bundle.** Three-second voice cloning plus voice design, and the only bundle that ships Qwen3-ASR as a second transcription engine.
- **WhisperX is now the transcription engine everywhere.** It is the more accurate one in real use, and dropping the second engine from the other three bundles removed about 3.7 GB from each pod, so voice pods are ready sooner.
- **Two workflows you did not have before.** `common-align-script-to-srt` is in every voice bundle now — paste a script with a blank line between sections and it aligns them to your narration as an SRT. CosyVoice 3 also gained a proper `cosyvoice3-voice-clone`.

Some workflow names changed in the `_examples` folder, so look for the new ones: `*-tts-clone` is now `*-voice-clone`, `*-audio-to-srt` is now `common-audio-to-srt`, and `qwen3tts-change-voice` is now `qwen3tts-redub-voice` — it transcribes and re-speaks the words rather than converting the voice, so use CosyVoice 3 when you want the delivery kept.

The **Docs** page now lists every bundle with its models and every workflow it ships, each with the same notes you see on the ComfyUI canvas.
