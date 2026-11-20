# CWM Benchmark visualization

Static five-case prompt-to-reference-to-video showcase. Open `index.html` or
serve the repository root as a GitHub Pages site.

The page shows the current prompt construction and RGB / Depth / Object-ID
references for five 5–60-second cases. Each reference can be compared with
available Wan3, Wan2.1-VACE-1.3B, Wan2.2-VACE-Fun, and MiniMax-H3 outputs.
Wan3 receives an ordinary reference video; Wan2.1-VACE uses its native video
conditioning interface; H3 uses image and video references.
These are exploratory single-seed results, not a model ranking or
equalized-control comparison.

The project owner confirmed permission to publish the H3 outputs and the
VideoCoCo boiling source media on 2026-11-19. The available game_search H3 videos are partial older assemblies
(about 57 seconds for RGB/Depth and 52 seconds for Object-ID), not complete
60-second results. The VideoCoCo boiling case now includes H3 RGB, Depth, and
Object-ID outputs; Wan3 and VACE Depth/Object-ID outputs are not included in
this publication.

Wan2.2-VACE-Fun A14B is a single 5-second physics_boiling/RGB exploratory run
with the frozen RGB control video plus the original RGB start image, seed 17
and 50 steps. Its native video is `media/physics_boiling_wan22_vace_fun_rgb.mp4`
(SHA-256 `f177564783fcd196fa804b98425a3a9ffed4bb7ca67226af5a73003113ae63e9`).
The verified retry2 run produced 81 frames at 832x480/16 fps; full decoding and
representative-frame inspection passed. No other case or representation has a
Wan2.2-VACE-Fun output here.

The COCO source image 351530 is attributed under CC BY-SA 2.0. ViZDoom/Freedoom
and WBench retain their source licenses. The project owner's confirmation
concerns public display of the VideoCoCo material in this showcase; it is
not a general license for third-party reuse.

The unified-world-state section adds five reviewed agent-authored Blender
proxies. It includes aligned whitebox, box, and semantic-class checkpoints,
rig-derived skeleton checkpoints for the human case, plus the full-rate
per-frame state stream and verification report for each case. These are not
source-ground-truth 3D or executed game trajectories. A separate Wan3
whitebox-reference pilot for the five-second boiling case uses the existing
RGB anchor and a full-rate whitebox reference video; it is not a native 3D
control interface or a five-case evaluation.
