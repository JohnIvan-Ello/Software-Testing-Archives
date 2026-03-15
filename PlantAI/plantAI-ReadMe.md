# 🌿 PlantAI: AI Model Validation & Data Quality
**Domain:** Agriculture Technology (AgriTech) | Computer Vision | AI Training

PlantAI is an advanced image recognition platform designed to identify crop varieties and detect agricultural diseases using drone and field imagery. My role as a QA Specialist focused on **Ground Truth Verification**, ensuring that the AI model's inferences aligned with real-world botanical data.

---

## 🛠️ My Role & Responsibilities
I served as the "Human-in-the-Loop" for the AI development lifecycle. My primary responsibility was to audit and validate the model's ability to distinguish between target crops (e.g., Native Tobacco) and environmental noise.

### 🔍 Key QA Focus Areas:
* **Inference Accuracy Audit:** Manually validated AI-generated bounding boxes and classifications against raw field imagery to identify false positives/negatives.
* **Crop Variety Identification:** Verified the system's ability to accurately distinguish specific crop types (Native Tobacco) from other vegetation or weeds.
* **Anomaly & Disease Detection:** Audited the model's success rate in identifying localized infestations, leaf diseases, and the presence of foreign objects.
* **Data Annotation Quality Control:** Ensured that the training data used for model refinement met strict precision standards for bounding box placement and labeling.

---

## 🧪 Testing Methodology
Validating an AI model requires a different approach than traditional software testing. I utilized the following strategies:

1. **Visual Consistency Analysis:** Used high-resolution grid views to ensure the AI maintained detection consistency across large-scale plantation maps.
2. **Edge Case Documentation:** Flagged "difficult" images (e.g., crops with heavy shadows, overlapping leaves, or glare) where the AI struggled to make an accurate inference.
3. **Ground Truth Comparison:** Compared AI "predictions" against verified field reports to calculate the model's real-world reliability.
4. **UI/UX Performance Testing:** Tested the annotation tool’s responsiveness, ensuring the manual "Submit for Review" and "AI Inference" workflows were seamless for large datasets.

---

## 📂 Documentation Standards
Because AI training data is highly proprietary, all documentation followed strict redaction protocols. 

* **Model Performance Logs:** High-level reports on detection accuracy and common misclassification trends.
* **Annotation Style Guides:** Documentation created to standardize how diseases and objects should be labeled for future training sets.
* **Verification Reports:** Summary of "Passed" vs. "Flagged" images during the audit phase.

---
**QA Specialist:** John Ivan P. Ello  
*Specializing in AI Data Validation, Computer Vision QA, and AgriTech Systems.*
