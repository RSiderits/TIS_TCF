Tumor Cell Proportion Calculator – README

PURPOSE This calculator is designed to estimate tumor cellularity in
tissue samples using two complementary approaches: 1. Direct observation
of tumor and stromal cell counts 2. Derived estimation using stromal
composition, cellularity, and necrosis

It provides a standardized, inspection-defensible method for determining
whether a specimen meets a minimum tumor threshold (>20%).

FEATURES

1.  Dual Calculation Methods

-   OPTION 1: Observed cell count method Uses estimated tumor cells and
    stromal cells
-   OPTION 2: Derived tumor field method Uses % stroma, stromal
    cellularity, and % necrosis

2.  Automatic PASS / FAIL Determination

-   PASS if tumor proportion > 20%
-   FAIL if ≤ 20%
-   Independent evaluation for both methods

3.  Real-Time Calculations

-   Immediate computation after input
-   No external dependencies

4.  Input Validation

-   Enforces valid ranges: • Stroma: 0–100% • Cellularity: 1–99% •
    Necrosis: 0–100%

5.  Transparent Formula Display

-   Shows how derived values are calculated
-   Supports auditability and reproducibility

6.  Visual Alignment

-   Side-by-side comparison of both methods
-   PASS/FAIL panels aligned for direct interpretation

HOW TO USE

OPTION 1 – Observed Cell Count Method 1. Enter estimated number of tumor
cells 2. Enter estimated number of stromal cells 3. Click “Calculate” 4.
Review: - Total cells - Tumor proportion (%) - PASS/FAIL result

OPTION 2 – Derived Tumor Field Method 1. Enter percent tumor-induced
stroma 2. Enter percent stromal cellularity 3. Enter percent necrosis in
tumor fields 4. Click “Calculate” 5. Review: - Derived stromal
component - Derived viable tumor component - Derived tumor field (%) -
PASS/FAIL result

INTERPRETATION

-   PASS indicates sufficient tumor content for downstream analysis
-   FAIL indicates insufficient tumor cellularity
-   Both methods can be used together for cross-validation

NOTES

-   The derived method accounts for necrosis and stromal dilution
    effects
-   The observed method reflects direct microscopic estimation
-   Results should be interpreted in the context of pathologist
    assessment
