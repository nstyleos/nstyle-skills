---
name: shorts-composition
description: Check vertical 9:16 framing before you shoot or generate a short-form image or video (YouTube Shorts, Reels, TikTok). Use when the user is about to take a photo with a phone, generate an image for a vertical video, crop existing footage to 9:16, or asks why their shorts look cramped, cut off, or amateurish. Covers real-camera framing and AI-generated framing separately, because the rules are opposite.
---

# Vertical (9:16) Composition Check

**The first question is always: real camera, or AI-generated?**
Most checklists mix the two. They must not be mixed — the rule for where to put the subject is **opposite** in each case.

| | Real camera | AI-generated |
|---|---|---|
| Subject placement | **Dead center** | **On a thirds line, NOT center** |
| Why | Phone main lens is ~24mm wide. Only the center cell is undistorted; edges stretch faces and bodies. | There is no lens. Nothing is distorted, so composition is free — use it. |

Pick the branch, then run the checklist.

---

## A. Real camera (phone)

1. **Wipe the lens.** Costs two seconds, fixes more shots than any edit.
2. **Turn on the grid. Put the face in the center cell.** Edges of a 24mm frame stretch — a face there bulges.
3. **Anything tighter than a full shot: use 2–3× zoom.** Less facial distortion, and the background compresses so the subject separates.
4. **Longer legs: flip the phone upside down.** The lens drops near the ground, giving a low angle without crouching. Keep the face in the center cell and tilt only slightly — overdo it and it reads as fake.
5. **Never cut joints.** Knees, ankles, waist. And watch the one people miss: **"cutting the neck"** — a horizon or skyline passing right behind someone's neck.
6. **Go tighter than feels comfortable.** For a face shot, don't leave headroom above the forehead. What makes a portrait compelling is showing what people don't normally get to see.
7. **Landscape: thirds.** Sky 1/3, ground 1/3, subject 1/3. Put something in the foreground to frame through.
8. **Sky: tap to meter on the sky.** A blown-out sky has no color left and cannot be recovered in editing. A dark subject can.
9. **Backlight for trees and people.** Light coming from behind the subject beats light from the front.
10. **Food: match the angle to the shape.** Three-dimensional food at eye level, flat food from above. If the light is a ceiling fixture, skip the overhead shot — the shadow kills it.
11. **Keep them talking.** Pre-frame the shot, then shoot mid-conversation. A posed "1, 2, 3" face is the worst face they have.

---

## B. AI-generated

**Never crop 16:9 down to 9:16. Generate 9:16 natively.**
Cropping is how faces and key objects get sliced off. If you are cropping, the problem is not the crop — it is that no composition was specified when the image was made.

Four rules, all four in every prompt:

1. **Subject on a rule-of-thirds line, not dead center.**
2. **Whole head inside the frame with headroom above; eyes near the upper-third line.**
3. **Lead room** — open space in the direction the subject faces or looks.
4. **Keep the lower fifth calm and uncluttered.** Shorts/Reels UI (captions, handle, action buttons) covers it. Anything important there is already lost.

Plus: **never crop a face, head, or the key object out of frame.**

### Two failures that repeat
- **Full-body shots come out squashed** when generated at 1:1 or 16:9 and then fitted to vertical. Generate full-body at 9:16 directly.
- **Subject size drifts between shots** when only a *face* reference is supplied. Add a **body/proportion reference** as well — a face sheet locks the face, not the scale.

---

## C. Both branches

> **Photography is subtraction, not addition.**

Before framing, ask what to **remove**, not what to include. If a viewer cannot tell in one second what the shot is of, there is too much in it.

Corollary: **don't show all of it.** A shot is compelling partly because something is left outside the frame.

---

## D. Pre-publish gate

Run this before the file ships. Any ✗ means fix it, not ship it.

- [ ] Generated/shot **9:16 natively** — not cropped down from wide
- [ ] Face, head, and key object **fully inside** the frame
- [ ] **No joint cut** at knee / ankle / waist, and no horizon line behind the neck
- [ ] **Lower fifth** free of anything that matters
- [ ] Subject placement matches the branch — **center** if real camera, **thirds line** if generated
- [ ] Sky (if present) still has color in it
- [ ] Removed at least one thing that was not needed

---

## Why this split exists

The two branches disagree because the constraint is different, not because one is wrong.

A phone's main lens is a wide angle. Wide angles stretch whatever sits near the edge of the frame — so the center is the only place a face stays a face. That is a **lens** constraint, and it overrules composition.

A generated image has no lens and no distortion. The constraint is gone, so the thirds line — which is better composition — is available. Applying the real-camera rule here wastes it: dead-center generated subjects look static and leave no lead room.

Mixing the two is the common mistake. Ask which branch you are in first.

---

*Maintained by NStyle. The vertical-generation rules in section B came out of a production post-mortem: shorts were being cropped from 16:9 masters and faces kept getting sliced. The fix was not a better crop — it was generating 9:16 from the start. Cropping was the symptom; the absence of composition was the disease.*
