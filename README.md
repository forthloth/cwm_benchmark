# CWM Benchmark visualization

Static five-case prompt-to-reference-to-video showcase. Open `index.html` or
serve the repository root as a GitHub Pages site.

The page shows the current prompt construction and RGB / Depth / Object-ID
references for five 5–60-second cases. Each reference can be compared with
available Wan3, Wan2.1-VACE-1.3B, and MiniMax-H3 outputs. Wan3 receives an ordinary reference video; VACE uses
its native video conditioning interface; H3 uses image and video references.
These are exploratory single-seed results, not a model ranking or
equalized-control comparison.

The project owner confirmed permission to publish the H3 outputs and the
VideoCoCo boiling source media on 2026-11-19. The available game_search H3 videos are partial older assemblies
(about 57 seconds for RGB/Depth and 52 seconds for Object-ID), not complete
60-second results. The VideoCoCo boiling case now includes H3 RGB, Depth, and
Object-ID outputs; Wan3 and VACE Depth/Object-ID outputs are not included in
this publication.

The COCO source image 351530 is attributed under CC BY-SA 2.0. ViZDoom/Freedoom
and WBench retain their source licenses. The project owner's confirmation
concerns public display of the VideoCoCo material in this showcase; it is
not a general license for third-party reuse.
