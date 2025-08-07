# Chaotic Image Encryption and Decryption using 2D Logistic & Duffing Maps
This project implements a grayscale image encryption and decryption system using chaotic maps—specifically, the 2D Logistic Map and Duffing Map—to perform pixel-level scrambling and substitution. The system ensures high security, unpredictability, and robustness against statistical and differential attacks, evaluated using standard image encryption metrics.
📖 Abstract:
In the field of secure image transmission, chaotic systems have emerged as efficient tools for designing lightweight, fast, and secure encryption algorithms. This project explores a hybrid chaotic encryption technique that combines the 2D Logistic Map and Duffing Map for confusion and diffusion processes. The system incorporates SHA-512 hashing of the input image to generate key parameters, thereby enhancing the encryption's sensitivity.
⚙️ Functional Overview
🧠 Workflow:
1.Image Preprocessing:
  --Resizing to 512×512
  --Converting to grayscale
2.Key Generation:
  --Compute SHA-512 hash of the image
  --Derive initial conditions and control parameters for chaotic maps
3.Encryption:
  --Confusion: Scrambling image pixels using chaotic sequences
  --Substitution: XOR with another chaotic sequence
4.Decryption:
  --Reverse substitution and de-scrambling using the same keys
5.Evaluation:
  --Histogram Analysis
  --NPCR & UACI
  --Entropy
  --PSNR & SSIM

📌 Key Features
  --Lightweight encryption using chaotic maps (no external hardware dependencies)
  --SHA-512-based dynamic key generation
  --Robust encryption quality metrics

✅ Plotting and visualization of all stages

✅ Easily extensible to color or medical images
