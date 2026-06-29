# dither& — Figma plugin

The full interactive dither lab, running inside Figma. Generate dithered
gradients and patterns, grow living reaction-diffusion fields, and even rebuild
your art as editable 3D terrain — then drop the result straight into your Figma
file as an image or vector.

> Design is not a job to me, it's a method of thought, the main facet of how I
> see the world. My operating thesis is that, at baseline, design is mind over
> matter: if it can be conceptualized, it can be actualized. With **dither&**,
> your designs can move mountains and render the impossible, one pixel at a time.

---

## What it does

### The gradient engine
- **Ten field types** — linear, radial, conic, spiral, diamond, waves, rays,
  rings, cross, and noise.
- **Unlimited color stops** you can drag, recolor, and reposition on a live
  gradient bar.
- **Eight built-in palettes** and **OKLab perceptual blending** for clean,
  even color transitions.
- **Eased stops** and **seamless tiling** with a 3×3 preview.
- Controls for **angle, center, warp, detail/twist, repeat,** and a
  **ping-pong mirror**.

### The dither core
**Fifteen algorithms**, grouped:
- **Ordered** — Bayer 2 / 4 / 8 and blue noise.
- **Error-diffusion** — Floyd–Steinberg, Atkinson, Jarvis, Stucki, Burkes, Sierra.
- **Print / halftone** — halftone dots, line screen, and a real **CMYK riso
  halftone** with rotated ink channels.
- **Other** — white noise and straight posterize.

Plus **pixel size**, **color levels** (2–8), and **dither strength**.

### Tone & color
Contrast, brightness, gamma, hue shift, saturation, noise, and invert.

### Texture & FX
Film grain (with grain size), paper, scanlines, vignette, RGB split,
bloom / glow, and glitch slices.

### Motion
The whole composition animates. **Play / pause, speed, evolve** (warp drift),
**spin,** and **flow** (color cycling) — so any still becomes a loop.

### Inputs beyond gradients
- **Image source** — upload any image as the dither source and auto-sample its
  palette.
- **Living field** — real **reaction-diffusion simulations** that grow,
  self-organize, and feed the dither (and the 3D) in real time.

### Compose
Blend a second generative field into the first with **multiply, screen, add,
darken, lighten, difference,** or **average**.

### Move mountains (the 3D model)
My favorite. It takes the current flat dither and rebuilds it as **editable
3D**, where each tonal band becomes a stacked slab — like turning a contour map
into a physical mountain range.

### Output
- **PNG** (1080px) and **transparent-alpha PNG**
- **Vector SVG** for print / Figma
- **Looping GIF** (with optional baked-in grain / fx)
- **MP4 / WebM** video recording
- **Contact sheet** of variations
- Copyable **recipe JSON** and **shareable links**

Plus full **undo / redo**, lockable parameters (shape / dither / color / fx),
**shuffle,** and **seed reroll** — and the **⊕ add to figma** button to drop the
current canvas straight into your document.
