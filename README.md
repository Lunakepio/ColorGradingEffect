# 🎨 ColorGradingEffect for @react-three/postprocessing

A powerful and customizable color grading effect for React Three Fiber using the `@react-three/postprocessing` ecosystem. This effect includes fine control over channel mixing, HSL adjustment per hue range, tone mapping, exposure, temperature, and much more.

## ✨ Features

- RGB Channel Mixer
- Per-hue HSL adjustments (Red, Orange, Yellow, Green, Aqua, Blue, Purple, Magenta)
- Global controls for:
  - Brightness, Contrast, Saturation, Vibrancy, Gamma, Exposure
  - Hue rotation and Chromatic Aberration
  - Kelvin-based white balance (temperature)
  - Split toning with shadow/highlight tint
- Built-in filmic tone mapping
- GPU-accelerated fragment shader implementation

---

## 🚀 Installation

```bash
npm install three leva @react-three/fiber @react-three/postprocessing
```

Add the `ColorGradingEffect.jsx' file to your project.

---
## 🎨 Usage

```jsx
import { EffectComposer } from "@react-three/postprocessing";
import { ColorGrading } from "./ColorGradingEffect";

function Scene() {
  return (
    <>
      {/* Your scene contents here */}

      <EffectComposer>
        <ColorGrading />
      </EffectComposer>
    </>
  );
}
```
