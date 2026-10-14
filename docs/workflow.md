# Workflow

1. **Cast first.** One locked reference image per character (and per environment) before any scene is generated. Faces, hairstyles, costumes, and key props are locked and re-verified against the references for every take.
2. **One scene at a time.** Each scene gets a text prompt, the relevant reference images, and its dialogue. The generator produces ~10-second clips.
3. **Voices stay separate.** Each character speaks only their own lines, recorded as separate performances. The generator bakes voices in, so every take is ear-checked; bad takes (mixed roles, dropped lines, drifted faces) are killed before delivery, never fixed in post.
4. **No generated text.** Posters, signs, and UI cards stay blank in the generated footage; all readable text is added in CapCut (or composited onto the clip before assembly).
5. **Assembly in CapCut.** Clips are trimmed and ordered per `docs/capcut-assembly.md`. Dialogue and ambient audio are extracted from the video files themselves.
6. **Inserts.** Close-up inserts (the *B/*C scenes) are generated the same way as main scenes and cut into the timeline at the marked points.
