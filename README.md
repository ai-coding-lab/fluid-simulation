# Fluid Simulation

Interactive fluid simulation in the browser using Navier-Stokes approximation.

マウスでかき回せるインタラクティブな流体シミュレーション。Navier-Stokes方程式の近似解法により、リアルな流体挙動を再現。

## Features

- Real-time fluid dynamics with diffusion and advection
- Mouse/touch interaction to stir the fluid
- Multiple color palettes
- Adjustable viscosity and diffusion parameters
- Reset functionality

## Quick Start

```bash
docker compose up -d
```

Open http://localhost:8888

## Controls

- **Drag**: Stir the fluid
- **Color Palette**: Select visual theme
- **Viscosity**: Adjust fluid thickness
- **Diffusion**: Adjust color spread rate
- **Reset**: Clear all fluid

## Technology

- Vanilla JavaScript (no external libraries)
- HTML5 Canvas for rendering
- Jos Stam's stable fluid solver algorithm

## License

MIT
