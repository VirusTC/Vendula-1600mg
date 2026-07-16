# Clinical Mechanisms: Botanical Vector-Repulsion & Post-Exposure Treatment
**Entity:** Single-Ingredient Plant-Derived Volatile Monoterpene/Sesquiterpene Extract (e.g., Linalool)
**Application:** Oral Systemic Pre-Exposure Vector Prophylaxis (PrEP) and Post-Bite Onco-Pathological Intervention

---

## 1. Systemic Dermal Excretion & Transport Kinetics (Pre-Exposure)

The oral botanical compound avoids absolute hepatic first-pass clearing through high affinity binding to lipophilic serum carriers (chylomicrons and high-density lipoproteins). It partitions directly into the capillary networks supplying the eccrine and apocrine sweat glands.

### 1.1 Mathematical Model of Transdermal Volatilization
The continuous, zero-washout field operational profile relies on steady-state physiological delivery. The excretion flux ($J_{sweat}$) of the active volatile compound across the epidermis and onto the skin surface is governed by Fick’s Law of Diffusion modified for active sweat gland advection:

$$J_{sweat} = \left( D_s \cdot \frac{C_{cap} - C_{skin}}{h} \right) + \left( Q_{sweat} \cdot K_{plasma:sweat} \cdot C_{cap} \right)$$

Where:
* $J_{sweat}$: Total transdermal mass flux ($\mu\text{g}/\text{cm}^2/\text{hr}$).
* $D_s$: Diffusion coefficient of the botanical monomer through the lipid stratum corneum matrix ($\text{cm}^2/\text{hr}$).
* $h$: Effective thickness of the epidermal layer ($\text{cm}$).
* $C_{cap}$: Concentration of the active compound in the capillary bed ($\mu\text{g}/\text{mL}$).
* $C_{skin}$: Residual concentration on the epidermis surface ($\mu\text{g}/\text{mL}$).
* $Q_{sweat}$: Local sweat excretion rate ($\text{mL}/\text{cm}^2/\text{hr}$), dictated by user thermoregulation and sympathetic activity.
* $K_{plasma:sweat}$: Partition coefficient specific to the single-ingredient molecule between blood plasma and the aqueous/lipophilic fluid of the sweat coil.

### 1.2 Gas-Phase Boundary Layer Volatilization
Upon reaching the skin surface, the molecule transforms into a local gas-phase barrier via evaporation. The concentration profile within the immediate 0–5 cm micro-environmental boundary layer ($C_{boundary}$) determines insect olfactory receptor neuron (ORN) saturation:

$$C_{boundary}(x) = C_{skin} \cdot \exp\left( -\frac{v_{air} \cdot x}{D_{air}} \right)$$

Where:
* $x$: Distance orthogonal to the surface of the skin ($\text{cm}$).
* $v_{air}$: Ambient wind velocity or thermal convective plume movement ($\text{cm}/\text{s}$).
* $D_{air}$: Mass diffusivity of the volatile molecule in air ($\text{cm}^2/\text{s}$).

Because the molecule is constantly replenished through $J_{sweat}$, surface friction, abrasion, submersion, or heavy sweating accelerates, rather than degrades, the delivery kinetics.

---

## 2. Onco-Pathological Tissue Remodeling Mitigation (Post-Bite)

If a breakthrough vector bite occurs, mosquito salivary proteins (e.g., sialokinins, claudins) induce immediate local mast-cell degranulation and micro-vascular hyperplastic remodeling. Left unchecked, chronic focal inflammation can trigger malignant transformation. 

### 2.1 The Apoptotic Signaling Ratio (Oncology Mechanism)
The botanical compound halts this pathogenic transformation by shifting the intracellular balance of pro-apoptotic and anti-apoptotic proteins in hyperplastic cell lineages. The therapeutic clearance efficiency is determined by the **Caspase-3 to Bcl-2 Activation Index ($\chi_{apoptosis}$)**:

$$\chi_{apoptosis} = \frac{[\text{Cleaved Caspase-3}]}{[\text{Bcl-2}]} = \alpha \cdot \left( \frac{K_d + [Active\_Compound]_{intracellular}}{K_d} \right)$$

[Oral Botanical Compound]\
│\
┌───────────┴───────────┐\
▼ ▼\
[Bcl-2 Downregulation] [Caspase-3 Cleavage]\
│ │\
└───────────┬───────────┘\
▼\
High χ_apoptosis Index Value\
│\
▼\
[Targeted Hyperplastic Clearance]

Where $\alpha$ is the baseline physiological apoptotic rate and $K_d$ is the dissociation constant of the botanical molecule to its cytosolic target receptor. High values of $\chi_{apoptosis}$ dictate clean, non-inflammatory programmed cell death of pre-malignant cells at the puncture zone, preventing tissue hyperplasia.

### 2.2 Antioxidant Response Element (ARE) Equation
To protect surrounding healthy tissue from oxidative stress-induced DNA mutations driven by reactive oxygen species (ROS) in mosquito saliva, the compound activates the **Nrf2** transcriptive pathway:

$$\frac{d[\text{HO-1}]}{dt} = \beta \cdot \left( \frac{[\text{Nrf2}\cdot\text{ARE}]}{K_m + [\text{Nrf2}\cdot\text{ARE}]} \right) - \gamma \cdot [\text{HO-1}]$$

This kinetics loop drives the rapid synthesis of cytoprotective Heme Oxygenase-1 ($\text{HO-1}$) and downstream intracellular glutathione, neutralizing ROS free radicals at a rate outstripping the localized inflammatory curve.

---

## 3. Kinetic & Molecular Baseline Matrixes

The following multi-variable matrices provide the data baselines required for IRB protocol submission endpoints, tracking validation thresholds across the pre-exposure and post-bite phases.

### Matrix 3.1: Pre-Exposure Volatilization & Olfactory Saturation Baselines

| Parameter Code | Physiochemical Property | Target Operational Baseline | Validation Assay Methodology | Sourcing Regulatory Standard |
| :--- | :--- | :--- | :--- | :--- |
| **MW-01** | Molecular Weight | $< 160.0 \text{ g/mol}$ | High-Performance Liquid Chromatography (HPLC) | USP-NF Monograph |
| **LogP-02** | Octanol-Water Partition | $2.5 \text{ to } 3.8$ | Shake-Flask Extraction Matrix | EPA Product Properties Test |
| **VP-03** | Vapor Pressure ($25^\circ\text{C}$) | $15 \text{ to } 25 \text{ Pa}$ | Static Headspace Gas Chromatography | ASTM E1194 |
| **K-PS-04** | Plasma-to-Sweat Ratio | $0.15 \text{ to } 0.35$ | Cannulated Sudorific Fluid Analysis | FDA GFI #236 Standards |
| **SAT-05** | Mosquito OBP Inhibition | $> 92.4\%$ Efficiency | Caged Insectary Olfactometer Assays | DoD MIL-SPEC Repellent Assay |

### Matrix 3.2: Post-Bite Pathological Biomarker Validation Thresholds

| Tissue Compartment | Intended Therapeutic Action | Molecular Biomarker | Target Threshold Criteria | Clinical Assay Endpoint |
| :--- | :--- | :--- | :--- | :--- |
| **Epidermal Biopsy** | Inflammation Arrest | $\text{NF}-\kappa\text{B}$ Translocation | $> 75\%$ Nuclear Exclusion | Immunohistochemistry (IHC) |
| **Dermal Fluid** | Cytokine Suppression | $\text{IL}-1\beta, \text{IL}-6, \text{TNF}-\alpha$ | $\ge 4.5\text{-fold decrease vs Placebo}$ | Multiplex Electrochemiluminescence |
| **Local Vasculature** | Angiogenesis Blockade | $\text{VEGF} \text{ / Vimentin Expression}$ | Downregulation by $\ge 60\%$ | Quantitative Real-Time PCR (qRT-PCR) |
| **Bite Micro-Zone** | Hyperplasia Clearance | $\text{Cleaved Caspase-3}$ | $\ge 3.2\text{-fold increase at 48h}$ | TUNEL Chromogenic Staining |
| **Systemic Serum** | Vector Pathogen Load | Target DNA/RNA Copies | Undetectable at Day 7 | High-Sensitivity Reverse-Transcription PCR |
