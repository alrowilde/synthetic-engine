# Synthetic Engine
Generate documents and invoices for VLM/OCR model training quickly.

## Don't spend too much time reading the text, just look at the showcases.

**Business-Oriented Synthetic OCR Dataset Generator**

Generate photorealistic business documents with annotations — ready for use in OCR and VLM training.

<h2 style="color: red;">
    <strong>
    * This project is not a demo — it is a complete, logically self-consistent, highly mature, and fully reproducible methodology.
    </strong>
</h2>

### Updates
- **2026/05/28** — Added an Arabian example.
- **2026/05/30** — Added a [Question and Answer (Q&A) module](./questions/README.md) to this project.

### Why It Matters
In FinTech, Logistics, and Healthcare, real business documents are often scarce, highly sensitive, or expensive to label. Synthetic Engine solves this by producing high-fidelity synthetic images that closely match real-world conditions while automatically providing accurate, structured annotations.

The result: enterprises can rapidly build robust document AI systems without compromising data privacy or waiting months for labeled data.

### What It Builts
- **Photorealistic business images** — invoices, receipts, contracts, forms, delivery notes, medical records, and other complex layouts captured in natural scenes.
- **Built-in annotations** designed for easy conversion to PaddleOCR, Tesseract, or Vision-Language Model formats.
- As you know, even the latest ControlNet models still struggle with annotation and text errors when generating business or professional images. My solution effectively solves these problems and can run locally on a personal PC.

### Key Benefits for Enterprises
- Dramatically reduce manual labeling costs and time
- Overcome data scarcity and privacy constraints (fully on-premise, no data leaves your environment)
- Accelerate model improvement on hard cases: small text, merged table columns, complex layouts, and imbalanced fields
- Achieve faster time-to-market for new document types
- GDPR-aligned and audit-friendly — complete control over data and outputs
- Multi-language synthesis

### Showcases

**Examples of generated business images (with Annotations):**


<div style="max-width: 1100px; margin: 30px auto;">
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 24px;">
    <!-- Example_0 -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_0.jpeg" alt="Example_0" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Bank Statement</div>
    </div>
    
    <!-- Example_1 -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_1.jpeg" alt="Example_1" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Receipt Example</div>
    </div>
    
    <!-- Example_2 -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_2.jpeg" alt="Example_2" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Complex Form</div>
    </div>
    
    <!-- Example_3 - Arabian -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_3.jpeg" alt="Arabian Example" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Arabic Document</div>
    </div>
    
    <!-- Example_4 -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_4.jpeg" alt="Example_4" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Retail Receipt</div>
    </div>
    
    <!-- Example_5 -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_5.jpeg" alt="Example_5" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Global Multilingual Contract</div>
    </div>
    
    <!-- Example_6 -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_6.jpeg" alt="Example_6" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Beverage Label</div>
    </div>
    
    <!-- Example of Vietnamese -->
    <div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
      <img src="./examples/Example_of_Vietnamese.jpg" alt="Example of Vietnamese" style="width: 100%; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.12);">
      <div style="margin-top: 10px; font-weight: 600; font-size: 15px; color: #222;">Example of Vietnamese</div>
    </div>
  </div>
</div>


#### *All of those images were generated by my tool because the item names and specifications do not match. These items do not exist in real-world business.



### Designed for
- **FinTech** — invoices, bank statements, tax documents
- **Logistics** — waybills, customs forms, delivery notes
- **Healthcare** — medical records, prescriptions, insurance forms
- **And more industry companies**

### Compliance & Security First
- Runs entirely on-premise — no cloud dependency, no external API calls
- No data collection or sharing
- Fully owned and auditable outputs
- Architected for GDPR and regulatory requirements

**This is not a generic image generator.**  
It is a specialized synthetic data engine built specifically for enterprise document AI challenges.

---

**Interested in partnering or exploring a pilot?**

We work with forward-thinking enterprises looking to build a sustainable advantage in Document AI.

Contact: hi@support.alrowilde.com  
Or open an issue on this repository.

*Synthetic Engine — Turning data scarcity into a competitive advantage.*
