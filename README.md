
# 🎨 Color Correction Toolkit

> **Note:** The "asdfghjkl" is just a placeholder due to some naming difficulties.

This package is designed to perform color correction on images using the Color Checker Classic 24 Patch card. It provides a robust solution for ensuring accurate color representation in your images.

## 🛠️ How It Works

1. **Input Requirements**:
   - An image containing the Color Checker Classic 24 Patch card (referred to as the color checker).
   - A reference image of the color checker.

2. **Process**:
   - The package computes a color correction matrix based on the input image and reference image.
   - This matrix can then be used to correct the colors of the input image or other images with the same color profile.

   **Workflow**:
   ```
   Input Image + Reference Image -> Color Correction Matrix -> Corrected Image
   ```

3. **Advanced Usage**:
   - For multiple images, it’s recommended to preprocess the images using white balance before calculating the color correction matrix. This ensures that all images are in the same color profile, leading to a more accurate correction matrix.

   **Enhanced Workflow**:
   ```
   Input Images -> White Balance -> Compute (Input Image with Color Checker, Reference Image) -> Color Correction Matrix -> Corrected Images
   ```

## 📈 Benefits
- **Consistency**: Ensure uniform color correction across multiple images.
- **Accuracy**: Leverage the color correction matrix for precise color adjustments.
- **Flexibility**: Adaptable for various image sets with different color profiles.

---

Happy Color Correcting! 🌟