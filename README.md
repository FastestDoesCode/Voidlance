<div align="center">

# VOIDLANCE

**A neon navy arcade shooter built in C# and WPF**

![C#](https://img.shields.io/badge/C%23-1A3063?style=for-the-badge&logo=csharp&logoColor=C9D6FF)
![.NET 8](https://img.shields.io/badge/.NET_8-1A3063?style=for-the-badge&logo=dotnet&logoColor=C9D6FF)
![WPF](https://img.shields.io/badge/WPF-1A3063?style=for-the-badge&logo=windows&logoColor=C9D6FF)
![License: MIT](https://img.shields.io/badge/license-MIT-1A3063?style=for-the-badge)

Hold the line against endless waves, survive the OVERSEER every fifth wave, and chase the high score.
Every sound effect and the whole soundtrack are synthesized live in code.

</div>

---

## Download and play

1. Open the [**Releases**](../../releases) page.
2. Download `VoidLance.exe` from the latest release.
3. Double-click it. No install needed.

Windows 10 or 11, 64-bit. If Windows SmartScreen warns you, click **More info**, then **Run anyway**. This happens with most new, unsigned games.

---

## How to play

- Survive as many waves as you can.
- You have **3 lives**, and each life has **3 shield pips**. Every hit removes a pip.
- Every **5th wave** the **OVERSEER** boss attacks.
- Quick kills build a **combo** that multiplies your score. Getting hit resets it.

New players get a short tutorial on their first run, plus tips the first time something new appears. **How to Play** in the menu explains everything at a glance.

### Controls

| Key | Action |
|-----|--------|
| `W A S D` or arrows | move |
| `Space` (hold) | shoot |
| `Shift` (hold) | focus: slower, tighter shots, shows your hitbox |
| `X` | bomb: wipes every enemy bullet and damages everything |
| `P` or `Esc` | pause |
| `Tab` | skip the tutorial |
| `F11` | fullscreen |

### Enemies

| Enemy | Behaviour |
|-------|-----------|
| Drone | drifts down and fires aimed shots |
| Weaver | snakes side to side and fires three-way spreads |
| Dart | swoops in from the sides, red arrows warn you where |
| Tank | parks at the top, fires bullet rings, always drops a pickup |
| Overseer | boss with spirals, fans and rings across 3 phases |

### Pickups

| Gem | Effect |
|-----|--------|
| Weapon | adds guns, up to 4 levels |
| Shield | repairs one shield pip |
| Bomb | adds a bomb, up to 5 |

---

## Features

- Endless waves that get faster and tougher
- Boss fight every 5 waves with three escalating phases
- Particle explosions, screen shake, glitch text, scanlines and a scrolling hex-code background
- Live-synthesized chiptune soundtrack with menu, battle and boss tracks
- Synthesized sound effects, no audio files
- Tutorial, contextual tips and a How to Play screen
- Encrypted high score save
- Scales to any window size, with fullscreen on F11

---

## License

MIT, copyright (c) 2026 Fastest. See [LICENSE](LICENSE).

Uses [NAudio](https://github.com/naudio/NAudio) (MIT) for audio output.

<div align="center">

**made by [Fastest](https://github.com/FastestDoesCode)**

</div>
