**README**

# Image Understanding Model

This repository contains two approaches for developing a model to understand the content of screenshots.

## Approach 1: Gemini OCR

In this approach, we utilize the Gemini 1.0 Pro Vision model along with EasyOCR for content understanding. The process involves:

1. Performing Optical Character Recognition (OCR) on the screenshot using EasyOCR to extract text.
2. Utilizing the Gemini language model to generate a natural language understanding of the screenshot content, incorporating the OCR results.

### Screenshots
*Insert screenshot for Approach 1 here*

## Approach 2: Salesforce BLIP Image Captioning

The second approach involves using an open-source image captioning model from Hugging Face, specifically `Salesforce/blip-image-captioning-large`. The steps include:

1. Preprocessing the screenshot image.
2. Using the BLIP model to generate image captions, both conditionally and unconditionally.

### Screenshots
*Insert screenshot for Approach 2 here*

## Performance Evaluation

Among the two approaches, Approach 1 (Gemini OCR) showed better performance. However, both approaches are included for comparison purposes.

## Instructions for Usage

To use these approaches:

1. Ensure all necessary dependencies are installed.
2. Replace the image path or URL with the actual screenshot.
3. Run the respective Python script or function for each approach.

For detailed instructions and examples, refer to the individual scripts or functions.

## Note

Approach 1 leverages a combination of proprietary and open-source technologies, providing a comprehensive understanding of the screenshot content. Approach 2 relies solely on open-source tools, offering transparency and flexibility.

---

*Note: Add screenshots for both approaches.*
