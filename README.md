# J-s-Detection
**J's Detection is a self-created pixel analyzing algorithm for pixel trends and edges.**

# The first question i may ask is, What is edge?



![image](https://github.com/user-attachments/assets/1169d34b-8454-43ca-9a68-68f804b90634)

![image](https://github.com/user-attachments/assets/1867ccab-00ef-40f9-a9c7-87496b4ad7db)

![image](https://github.com/user-attachments/assets/f4fa9fa6-fa33-45f9-ac29-213be9ee4cc2)

## On Lemin CAPTCHA: 95% Success Rate
<div align="center">
  <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; width: 33%;">
    <img width="100%" src="https://github.com/user-attachments/assets/38123bf6-259e-4c92-9269-99c015f6603f" alt="Screenshot 1">
    <img width="100%" src="https://github.com/user-attachments/assets/7f24dafd-995c-4ed9-bb61-aba07c90eae8" alt="Screenshot 2">
    <img width="100%" src="https://github.com/user-attachments/assets/8fad8aaa-7e52-47b2-a526-c24a3f88ad6b" alt="Screenshot 3">
  </div>
</div>

## J's
![image](https://github.com/user-attachments/assets/60e76c2f-37e2-4247-a4e8-055337edf29e)
![image](https://github.com/user-attachments/assets/8213152c-a228-455e-820a-e3ac5d9796ef)

## GussianBlur + Canny
![image](https://github.com/user-attachments/assets/704ead93-7667-4176-b8e3-e873d7ef7b90)


## Current Use Example
### Lemin Puzzle 99% success rate. I don't recall technical terms, here is what AI says.
  1. **Random Noise Layers**
    - Gaussian/Additive Noise: Random pixel variations (static-like grain).
    - Salt-and-Pepper Noise: Black/white speckles disrupting edges.
    - Distortion: Warping, blurring, or interlacing patterns over the puzzle.
     
  2. **Pixel Splitting (Edge Obfuscation)**
     - Edge Fragmentation: Breaking object outlines into discontinuous pixels.
     - Pixel Displacement: Shifting individual pixels to misalign shapes.
     - Visual Adversarial Attacks: Tiny perturbations undetectable to humans but that break ML models.

  3. **Object Covering (Occlusion)**
     Technical terms:
     - Image Occlusion: Overlaying shapes (rectangles, circles) on key puzzle areas.
     - Adversarial Overlays: Adding "decoy" objects (e.g., lines, grids) to confuse segmentation.
     - Dynamic Obstruction: Moving or flickering overlays (e.g., smoke, watermarks).

![Screenshot 2023-07-28 115126](https://github.com/user-attachments/assets/38123bf6-259e-4c92-9269-99c015f6603f)

![Screenshot 2023-07-28 113518](https://github.com/user-attachments/assets/7f24dafd-995c-4ed9-bb61-aba07c90eae8)

![Screenshot 2023-07-28 113839](https://github.com/user-attachments/assets/8fad8aaa-7e52-47b2-a526-c24a3f88ad6b)

![Screenshot 2023-07-28 114005](https://github.com/user-attachments/assets/565d90a1-7fc0-498c-8e25-dcf9910d0e56)


### Capy Puzzle 80% success rate

![Screenshot 2023-07-28 130157](https://github.com/user-attachments/assets/8c34f456-e7fd-43c8-8a80-6a6a2cad6e65)

![Screenshot 2023-07-28 130258](https://github.com/user-attachments/assets/e7adc9c9-1688-4ff2-a612-1184c0d94e17)

![Screenshot 2023-07-28 130344](https://github.com/user-attachments/assets/41481b55-c97a-459c-80ef-7f5140136f41)


