# Optics Simulator

An interactive Python-based optics simulator for visualising image formation by ideal thin lenses, concave and convex spherical mirrors, and a real-time anamorphic projection mapped onto a cylindrical surface.

---

## Features

- **Import any image** as the object.
- Visualise:
  - Real and virtual images in a **thin lens** system
  - Image formation by **concave and convex mirrors**
  - **Anamorphic transformation** of the image onto a unit circle sector
- **Interactive dragging** of both the object and the lens/mirror
- **Switch modes** with a radio button interface
- **Reset button** for restoring the default layout

---

## Requirements

- Python 3.7+
- `numpy`
- `matplotlib`
- `Pillow`

Install with:

```bash
pip install numpy matplotlib pillow
```

---

## Usage

1. Replace `'your_image_file.jpg'` In the last line of the script, with your own image path.
2. Run the script:

```bash
python optics_simulator.py
```

---

## Scientific Background

### Thin Lens Formula

\(\frac{1}{f} = \frac{1}{d_o} + \frac{1}{d_i}\)

- \(f\): focal length
- \(d_o\): object distance
- \(d_i\): image distance

### Mirror Equation (Concave & Convex)

Similar to the lens, but for **a convex lens**, it is **negative**.

### Magnification

\(M = -\frac{d_i}{d_o}\)

### Anamorphic Mapping

Maps an image from a **unit circle** to a **radial fan-shaped sector** such that when viewed through a cylindrical mirror, the original shape appears restored in 3D.

---

## Acknowledgements

Developed with Matplotlib, Pillow and NumPy.&#x20;

