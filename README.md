# Melt9 AR Menu - simple pizza + smoke with NO border (v40)

Based on v39. No dome, no glass box, no cylinder - just
the pizza, appearing on the target photo, with smoke.

Border removed in v40:
- The smoke picture is a rectangle. Before, its alpha
  only faded at the top and bottom, so the left and right
  edges - and especially the corners - were still hard.
  When the smoke was dark grey and strong, those straight
  edges showed as a box / border around the smoke, like
  the smoke was trapped under a box.
- Now the picture is feathered in ALL directions: an
  oval mask, corners fully transparent, edges soft and
  wavy, so there is no straight edge left to show.
- The big cloud picture (smoke2) is REMOVED - it is the
  one that looked like a block. Only the thin wisps
  (smoke.jpg) are used now. That is the good smoke
  effect: thin, wavy, live.
- Every plane is rotated at a random angle (-25 to +25
  degrees), so no edge is straight vertical or horizontal.
- The wisps drift OUTWARDS as they rise, so the smoke
  spreads like a real cloud, not a straight box column.
- Opacity a little lower (0.60-0.70), so overlapping
  planes do not stack into a solid dark block.

Smoke: 7 wisps, 14 planes (7 vertical + 7 horizontal,
for flat and tilted), dark grey 175, delays 0-2.1 s,
speeds 5.2-6.6 s, rises to Y=1.20 and out to Z=0.95.
Still outside #spin / inside #tilt, so it stays on top
while the pizza spins, and tilts with the pizza.

Shadow: soft 1.10 / 0.65, dark 0.80 / 0.85 (v37).
No smoke under the pizza.

Kept: fixed AR label, Add to cart + Photo in AR,
1-second flash, auto-spin, self-hosted libs/ engine.
iOS (Quick Look) + Android (MindAR camera scan).
