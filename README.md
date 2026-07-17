# Frontend-Studio

A collection of premium front-end web experiences.

## Shoes Website

Cinematic scroll-driven product showcase for **VELOCITY-X** athletic footwear. Frame-by-frame animations powered by GSAP ScrollTrigger + HTML Canvas.

```
Shoes Website/
├── code.html                       # Single-file website (HTML + CSS + JS)
├── DESIGN.md                       # Design system tokens & guidelines
├── Refrence_Image/
│   └── Best.png                    # Exploded anatomy hero image
└── ShoeShowcasing/
    └── Frames/
        ├── frame_1_shoe_floating/  # 300 PNGs — Hero scroll sequence
        └── frame_2_/              # 300 PNGs — Anatomy scroll sequence
```

### Stack

- **Tailwind CSS** — utility styling
- **GSAP + ScrollTrigger** — scroll-driven pinning & animation
- **Lenis** — smooth scroll
- **Canvas API** — 60 FPS frame rendering

### Run

```bash
npx http-server "Shoes Website" -p 8080
```

Open `http://localhost:8080/code.html`

## License

See [LICENSE](LICENSE).
