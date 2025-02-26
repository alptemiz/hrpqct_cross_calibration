# HR-pQCT Cross-Calibration

## Overview

We previously used an older device, **XCT 1**, for measurements during the **1st, 2nd, and 3rd visits**. However, XCT 1 has now been retired, and measurements for the **4th and 5th visits** are being conducted with a new device, **XCT 2**.

The challenge is that XCT 1 and XCT 2 use different technologies, leading to systematic differences in their measurements of the same parameters.

Fortunately, we conducted a **direct comparison study** in which **50 patients were scanned consecutively on both XCT 1 and XCT 2 on the same day**. This allowed us to establish **transformation formulas** that account for the measurement differences between the two devices. Specifically, we derived **79 distinct equations**—each corresponding to a specific measurement type (e.g., total area, cortical thickness) and anatomical site (e.g., MCP, tibia, radius). These formulas convert XCT 2 measurements into their equivalent values as if they had been obtained with XCT 1. Most of these equations demonstrate a **strong explanatory power**, with **R² values exceeding 0.95**.

---

## Next Steps

For future longitudinal analyses, we will apply these transformation formulas to the **XCT 2 measurements from visits 4 and 5**. This will allow us to generate **XCT 1-equivalent values**, ensuring that data from **all visits (1–5)** remain comparable.

---

### Questions:

#### Does transforming XCT 2 values into XCT 1 equivalents affect resolution, accuracy, or certainty?

Transforming XCT 2 values into XCT 1 equivalents introduces minor noise from mathematical calculations, not from voxel resolution differences. Since we are only comparing numerical equivalents, the measurement accuracy at the voxel level remains unchanged. The high R² values (>0.95) ensure strong agreement and reliable comparisons.

#### Do derived values from XCT 1 create inconsistencies with directly measured equivalents in XCT 2?

No, there is no meaningful inconsistency. Whether derived from XCT 1 or directly measured from XCT 2, we always have two values to compare. Special translation formulas, each with different slopes, intercepts, and R² values, ensure compatibility between new and old device outputs while maintaining reliable comparisons.

---
#### About derived values from XCT-1

In XCT1 analysis, some values are directly measured from the scan (e.g., Bone Mineral Density (BMD), Trabecular Number (Tb.N)), while others are derived using formulas that combine multiple parameters.

Here are some common derived values in XCT1-based bone analysis and how they relate to measured values:

##### 1. Trabecular Thickness (Tb.Th)
Derived from: BMD and Trabecular Number (Tb.N)

Formula:

$$\text{Tb.Th} = \frac{BMD}{\rho_{\text{bone}} \times \text{Tb.N}}$$

##### 2. Trabecular Separation (Tb.Sp)
Derived from: Trabecular Number (Tb.N) and Trabecular Thickness (Tb.Th)

Formula:

$$\text{Tb.Sp} = \frac{1}{\text{Tb.N}} - \text{Tb.Th}$$
 
##### 3. Bone Volume Fraction (BV/TV)
Derived from: BMD and reference full-density bone (𝜌 bone)

Formula:

$$BV/TV = \frac{BMD}{\rho_{\text{bone}}}$$

##### 4. Trabecular Bone Pattern Factor (TBPf)
Derived from: Bone surface area (BS) and Bone Volume (BV)

Formula:

$$TBPf = \frac{BS}{BV}$$

Indicates trabecular connectivity: Higher values suggest more disconnected trabeculae.

##### 5. Structure Model Index (SMI)
Derived from: Bone surface area and volume

Formula:

$$SMI = 6 \times \left( \frac{BV}{BS} \right)$$
