# CWM Benchmark visualization

Static five-case prompt-to-reference-to-video showcase. Open `index.html` or
serve the repository root as a GitHub Pages site.

The page shows the current prompt construction and RGB / Depth / Object-ID
references for five 5–60-second cases. For the four cases with cleared source
terms, each reference can be compared with existing Wan3, Wan2.1-VACE-1.3B,
and MiniMax-H3 outputs. Wan3 receives an ordinary reference video; VACE uses
its native video conditioning interface; H3 uses image and video references.
These are exploratory single-seed results, not a model ranking or
equalized-control comparison.

The project owner confirmed permission to publish the H3 outputs on
2026-11-19. The available game_search H3 videos are partial older assemblies
(about 57 seconds for RGB/Depth and 52 seconds for Object-ID), not complete
60-second results. The VideoCoCo boiling case retains previously published
RGB outputs, but additional model outputs remain withheld pending separate
source-rights review.

The COCO source image 351530 is attributed under CC BY-SA 2.0. ViZDoom/Freedoom
and WBench retain their source licenses. VideoCoCo source terms remain under
review; the boiling case is marked accordingly. Do not reuse the media without
checking its source rights.
