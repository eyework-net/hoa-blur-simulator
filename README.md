# Higher-Order Aberration Blur Simulator

A browser-based educational simulator that converts ocular aberration values into intuitive visual blur effects.

This tool is designed for clinicians, researchers, educators, and students who want to demonstrate how higher-order aberrations may affect perceived image quality.

---

## Features

- Real-time blur simulation using adjustable parameters
- Side-by-side comparison:
  - Original image
  - Simulated visual quality
- Adjustable inputs:
  - Pupil Size
  - Total Aberration
  - Coma
  - Trefoil
  - Tilt
- Multiple sample scenes:
  - Text Reading
  - Night Lights
  - Grid Pattern
  - Contrast Target
- Automatic interpretation:
  - Estimated Severity
  - Dominant Pattern
  - Clinical Comment

---

## Parameters

| Parameter | Effect |
|---|---|
| Pupil Size | Larger pupils increase visible aberration effects |
| Total Aberration | General blur and reduced contrast |
| Coma | Directional smearing / comet-tail effect |
| Trefoil | Three-directional ghosting |
| Tilt | Image displacement / asymmetry |

---

## Intended Use

This simulator is suitable for:

- Patient education
- Clinical counseling
- Optical teaching
- IOL discussion
- Research demonstration
- Visual quality concept explanation

---

## Important Limitation

This tool does **not** calculate a true optical Point Spread Function from full Zernike coefficients.

Instead, it uses simplified visual transformations based on selected aberration values.

It should be used for:

- Education
- Communication
- Demonstration

It should **not** be used for:

- Diagnosis
- Surgical planning
- Quantitative wavefront analysis
- Clinical decision-making

---

## How to Use

1. Open https://eyework-net.github.io/hoa-blur-simulator/
2. Select a sample scene
3. Adjust aberration sliders
4. Observe simulated visual quality changes
5. Review automatic interpretation

---

## Deployment

This project works as a single HTML file.

Suitable for:

- GitHub Pages
- Local browser use
- Teaching presentations
- Tablet demonstration in clinic

---

## Author

Created for ophthalmic and visual quality education.

---

## License

Free to use for educational and non-commercial purposes.
