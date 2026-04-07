# How to Generate Images with Nano Banana Pro

## Steps for each image:

1. Open **Nano Banana Pro** (Gemini app with "Thinking" model, or Google AI Studio)
2. Copy the entire JSON from each file below
3. Paste with the instruction: **"Render this specification as a high-fidelity image"**
4. Save the generated image to this `images/` folder with the matching name

## Files to generate:

| File | Save As | Used In |
|------|---------|---------|
| `01-hero-image.json` | `hero-ai.png` | Hero section background |
| `02-problem-section.json` | `problem-visual.png` | Problem/pain section |
| `03-solution-section.json` | `solution-visual.png` | Solution section |
| `04-process-section.json` | `process-visual.png` | Process/timeline section |
| `05-cta-contact.json` | `cta-background.png` | Contact/CTA section background |

## After generating:

Update the `index.html` file to reference the new images where needed.
The hero image (`hero-ai.png`) is already referenced in the HTML.

## Tips:
- If the result isn't perfect, try adding: "Make it more cinematic" or "Increase the contrast"
- You can modify specific sections of the JSON to iterate (e.g., change only lighting or camera angle)
