# Mechanics of Materials (ME-333) — Laboratory Reports

[![Institution: IIT Gandhinagar](https://img.shields.io/badge/Institution-IIT%20Gandhinagar-orange.svg)](https://www.iitgn.ac.in/)
[![Course: ME-333](https://img.shields.io/badge/Course-ME--333%20Mechanics%20of%20Materials-blue.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status: Completed](https://img.shields.io/badge/Status-Completed-brightgreen.svg)](#)

This repository contains the comprehensive experimental laboratory reports for **ME-333: Mechanics of Materials**, conducted in the Department of Mechanical Engineering at the **Indian Institute of Technology Gandhinagar (IITGN)**.

The reports investigate fundamental mechanics of materials principles, constitutive stress-strain behaviors, dynamic impact toughness, torsional shear response, and transverse flexural bending under varying boundary conditions.

---

## 👨‍🎓 Author & Course Information

- **Author:** Rishabh Shah
- **Roll Number:** 24110327
- **Department:** Mechanical Engineering
- **Institution:** Indian Institute of Technology Gandhinagar (IITGN)
- **Course:** ME-333: Mechanics of Materials
- **Academic Term:** Autumn 2026

---

## 📂 Repository Structure

```plaintext
MOM_reports/
├── LICENSE                 # MIT License
├── README.md               # Repository documentation and comprehensive lab summaries
├── MOM_lab1.pdf            # Lab 1: Uniaxial Tension and Compression Testing
├── MOM_lab2.pdf            # Lab 2: Material Response Under Impact and Torsional Loading
└── MOM_lab3.pdf            # Lab 3: Deformations Induced Due to Bending in Beams
```

---

## 📑 Overview of Laboratory Reports

| # | Report Title | Tested Materials | Primary Setup & Standards | Key Findings & Extracted Properties | Report Link |
|---|---|---|---|---|:---:|
| **1** | **Uniaxial Tension and Compression Testing of Aluminium, Mild Steel, and Cast Iron** | Aluminium, Mild Steel, Cast Iron | Universal Testing Machine (UTM), Load Cell, Extensometer, ASTM Dog-bone & Cylindrical samples | Evaluated $\sigma_y$, UTS, and $E$ in tension and compression; characterized ductile necking vs. brittle cleavage and barreling effect. | [📄 PDF](MOM_lab1.pdf) |
| **2** | **Material Response Under Impact and Torsional Loading** | Aluminium (Al) | Charpy Pendulum Impact Tester (150 J), Torsion Testing Machine ($T$-$\theta$ sensors) | Average impact energy $KV = 16.35\text{ J}$; shear modulus $G = 15.67\text{ GPa}$, $\tau_y = 148.5\text{ MPa}$, $\tau_{\max} = 204.2\text{ MPa}$; analyzed strain-rate sensitivity. | [📄 PDF](MOM_lab2.pdf) |
| **3** | **Deformations Induced Due to Bending in Beams with Different End Conditions** | Aluminium (Al), Mild Steel (MS) | Dead-weight bending frame (100–400 g), plunger dial gauge (0.01 mm), cantilever & simply supported fixtures | Verified Euler–Bernoulli beam theory; measured Al-to-MS slope ratio of 2.84 (within 2.2% of theoretical ratio $E_{\text{MS}}/E_{\text{Al}} \approx 2.90$); quantified clamp compliance. | [📄 PDF](MOM_lab3.pdf) |

---

## 🔬 Detailed Summaries of Laboratory Reports

### 1. Lab Report 1: Uniaxial Tension and Compression Testing

* **File:** [`MOM_lab1.pdf`](MOM_lab1.pdf)
* **Title:** *Uniaxial Tension and Compression Testing of Aluminium, Mild Steel, and Cast Iron*
* **Lab Group:** Group 22

#### Objectives & Theoretical Scope
- Investigate material constitutive responses under monotonic uniaxial tensile and compressive loading.
- Familiarize with Universal Testing Machine (UTM) operation, instrumentation (strain-gauge load cells, LVDTs, extensometers), and data acquisition.
- Understand standard ASTM specimen geometries:
  - **Tension (Dog-bone):** Enlarged ends prevent stress concentrations at grips; reduced gauge section enforces uniform uniaxial stress distribution and controlled localized failure.
  - **Compression (Cylindrical):** Precise $L/D$ aspect ratio prevents geometric buckling instability ($L/D$ too high) and minimizes end-platen frictional constraint artifacts ($L/D$ too low).
- Construct engineering stress-strain ($\sigma$-$\epsilon$) curves and extract constitutive parameters:
  - **Engineering Stress:** $\sigma = \dfrac{P}{A_0}$
  - **Engineering Strain:** $\epsilon = \dfrac{\Delta L}{L_0}$
  - **Young's Modulus (Elastic Slope):** $E = \dfrac{\Delta\sigma}{\Delta\epsilon}$
  - **Yield Strength ($\sigma_y$):** Determined via standard 0.2% (0.002) strain offset method for ductile materials.

#### Specimen Dimensions
- **Tension (Dog-bone):**
  - Aluminium: $L_0 = 34.1\text{ mm}$, Grip Length $= 71.7\text{ mm}$, Thickness $= 3.0\text{ mm}$, Width $= 6.0\text{ mm}$ ($A_0 = 18.0\text{ mm}^2$)
  - Mild Steel: $L_0 = 35.3\text{ mm}$, Grip Length $= 70.0\text{ mm}$, Thickness $= 3.0\text{ mm}$, Width $= 6.0\text{ mm}$ ($A_0 = 18.0\text{ mm}^2$)
  - Cast Iron: $L_0 = 35.1\text{ mm}$, Grip Length $= 70.8\text{ mm}$, Thickness $= 3.0\text{ mm}$, Width $= 6.0\text{ mm}$ ($A_0 = 18.0\text{ mm}^2$)
- **Compression (Cylindrical):**
  - All specimens: Height $L_0 = 15.0\text{ mm}$, Diameter $d_0 = 10.0\text{ mm}$ ($A_0 = 78.54\text{ mm}^2$)

#### Experimental Results & Extracted Mechanical Properties
| Loading Mode | Material | Young's Modulus $E$ (GPa) | Yield Strength $\sigma_y$ (MPa) | Failure / Deformation Mode |
|---|---|:---:|:---:|---|
| **Tension** | Aluminium | $3.5$ | $50$ | Ductile yielding, localized necking, shear cup-and-cone fracture |
| **Tension** | Mild Steel | $18.4$ | $234$ | Distinct yield point, Lüders bands, extensive plastic deformation, ductile cup-and-cone fracture |
| **Tension** | Cast Iron | $13.3$ | — *(Brittle)* | Linear elastic up to sudden brittle tensile cleavage fracture (near-zero plastic strain) |
| **Compression** | Aluminium | $8.6$ | $341$ | High ductility, plastic flattening, visible barreling |
| **Compression** | Mild Steel | $9.9$ | $468$ | High ductility, extensive plastic flow, barreling |
| **Compression** | Cast Iron | $8.5$ | — *(Brittle)* | High compressive strength; brittle failure along $\sim 45^\circ$ maximum shear planes |

#### Key Observations & Error Diagnostics
1. **Ductility vs. Brittleness:** Aluminium and Mild Steel demonstrated classical ductile behavior in tension and high malleability in compression. Cast Iron displayed pronounced asymmetry: weak in tension due to graphite flake stress risers, but substantially stronger in compression.
2. **Grip Slippage:** Small initial drops and flat segments in raw tension curves occurred due to specimen seating inside the wedge grips before full mechanical bite was established.
3. **Machine Compliance Effect:** Apparent modulus values calculated from crosshead displacement were significantly lower than textbook values ($E_{\text{Al}} \approx 69\text{ GPa}$, $E_{\text{MS}} \approx 200\text{ GPa}$), reflecting load frame compliance and grip elasticity that were superposed on the specimen deformation.
4. **Barreling Effect in Compression:** Friction at specimen-platen contact interfaces constrained lateral radial expansion at the top and bottom faces, producing the characteristic barrel profile in ductile specimens.

---

### 2. Lab Report 2: Material Response Under Impact and Torsional Loading

* **File:** [`MOM_lab2.pdf`](MOM_lab2.pdf)
* **Title:** *Material Response Under Impact and Torsional Loading*
* **Course:** ME-333: Mechanics of Materials

#### Objectives & Theoretical Scope
- Investigate how loading rate and stress state govern material failure modes.
- **Charpy V-Notch Test:** Evaluate notch sensitivity and dynamic fracture energy absorption ($KV$) under high strain-rate impact loading using a swinging pendulum impact machine.
- **Torsion Test Formulations:** Determine shear constitutive behavior and fundamental shear elastic-plastic parameters under pure twisting moment:

  - Polar Moment of Area:
    $$J = \frac{\pi d^4}{32}$$
  - Maximum Shear Stress at Outer Radius:
    $$\tau = \frac{T \cdot r}{J}$$
  - Surface Shear Strain:
    $$\gamma = \frac{\theta_{\text{rad}} \cdot r}{L}$$
  - Shear Modulus (Hooke's Law in shear):
    $$G = \frac{\Delta\tau}{\Delta\gamma}$$
  - Yield Shear Strength (0.2% offset):
    $$\tau_{\text{offset}} = G(\gamma - 0.002)$$
  - Ultimate Shear Strength:
    $$\tau_{\max} = \frac{T_{\max} \cdot r}{J}$$

- **Elastic Constant Cross-Validation:** Correlate Shear Modulus ($G$) with tensile Young's Modulus ($E$) to compute Poisson's ratio:

$$
\nu = \frac{E}{2G} - 1
$$

#### Experimental Setup & Specimen Specifications
- **Charpy Impact Setup:** Standard pendulum machine with initial potential energy $E_0 = 150\text{ J}$. Specimens were standard Aluminium V-notched bars ($55\text{ mm} \times 10\text{ mm} \times 10\text{ mm}$) placed as simply supported beams with the notch facing away from the striker. Four independent trials were recorded.
- **Torsion Setup:** Pure torsion testing apparatus equipped with dynamic torque and angular rotary sensors. Solid cylindrical Aluminium specimen: diameter $d = 6.91\text{ mm}$, gauge length $L = 70.0\text{ mm}$ ($J = 2.238 \times 10^{-10}\text{ m}^4$).

#### Experimental Results & Extracted Parameters
##### A. Charpy V-Notch Impact Data (Aluminium)
| Sample ID | Striking Angle ($^\circ$) | Absorbed Energy $KV$ (J) | Impact Strength ($\text{kJ/m}^2$) | Fracture Appearance |
|:---:|:---:|:---:|:---:|---|
| **Sample 1** | $-149.1$ | $19.71$ | $246.35$ | Flat, granular brittle snap at notch root |
| **Sample 2** | $-150.0$ | $12.68$ | $158.44$ | Rapid crack initiation, minimal plastic stretch |
| **Sample 3** | $-150.0$ | $22.14$ | $276.74$ | Transverse brittle cleavage across section |
| **Sample 4** | $-149.1$ | $10.86$ | $135.75$ | Low energy absorption, clean break |
| **Average** | **—** | **$16.35\text{ J}$** | **$204.32\text{ kJ/m}^2$** | **Predominantly brittle dynamic response** |

##### B. Quasi-Static Torsion Properties (Aluminium)
| Mechanical Property | Symbol | Experimental Value | Units |
|---|:---:|:---:|:---:|
| Polar Moment of Area | $J$ | $2.238 \times 10^{-10}$ | $\text{m}^4$ |
| Shear Modulus | $G$ | $15.67$ | $\text{GPa}$ |
| Yield Shear Strength ($0.2\%$ offset) | $\tau_y$ | $148.5$ | $\text{MPa}$ |
| Maximum Twisting Moment | $T_{\max}$ | $13.23$ | $\text{N}\cdot\text{m}$ |
| Maximum Angle of Twist | $\theta_{\max}$ | $589.27^\circ\ (10.285\text{ rad})$ | — |
| Ultimate Shear Strength | $\tau_{\max}$ | $204.2$ | $\text{MPa}$ |
| Maximum Shear Strain at Fracture | $\gamma_f$ | $0.51$ | $\text{rad}$ |

#### Key Insights & Anomaly Analysis
1. **Strain-Rate Sensitivity:** While Aluminium displayed vast plastic deformation during slow twisting ($\theta_{\max} \approx 589^\circ$, plastic shear strain $\gamma_f \approx 0.51$), it failed in a flat, brittle cleavage mode under sudden high-speed impact ($KV_{\text{avg}} = 16.35\text{ J}$). This contrast proves that triaxial notch stress concentration and high loading rates inhibit dislocation mobility.
2. **Negative Poisson's Ratio Diagnostic ($\nu = -0.89$):**
   Substituting experimental Young's Modulus $E = 3.5\text{ GPa}$ (from Lab 1) and Shear Modulus $G = 15.67\text{ GPa}$ into the isotropic linear elastic relation:

$$
\nu = \frac{E}{2G} - 1 = \frac{3.5}{2(15.67)} - 1 = 0.111 - 1 = -0.889 \approx -0.89
$$

   For standard isotropic metals, volume conservation dictates $0.25 \le \nu \le 0.35$ (for Aluminium, $\nu_{\text{theor}} \approx 0.33$). A negative value is physically impossible for monolithic aluminium. This diagnostic directly proved that while the torsional measurement ($G = 15.67\text{ GPa}$) was physically reasonable, the tensile modulus ($E = 3.5\text{ GPa}$) was severely corrupted by machine compliance and grip slippage.

---

### 3. Lab Report 3: Deformations Induced Due to Bending in Beams

* **File:** [`MOM_lab3.pdf`](MOM_lab3.pdf)
* **Title:** *Deformations Induced Due to Bending in Beams with Different End Conditions*
* **Course:** ME-333: Mechanics of Materials

#### Objectives & Theoretical Scope
- Measure and analyze transverse elastic deflections of slender rectangular beams under two classical boundary conditions:
  1. **Cantilever Beam:** Point load applied at distance $a = 200\text{ mm}$ from fixed support, deflection recorded at $x = a$.
  2. **Simply Supported Beam:** Symmetric knife-edge supports separated by active span $L = 400\text{ mm}$, central load applied at $a = L/2 = 200\text{ mm}$, deflection recorded at mid-span $x = L/2$.
- Investigate spatial deflection profiles $\delta(x)$, cubic span scaling ($\delta \propto L^3$), and boundary condition non-idealities.

#### Governing Beam Deflection Equations

Transverse elastic deflections $\delta(x)$ of slender beams are governed by the Euler–Bernoulli differential equation:

$$
EI \frac{d^2 \delta}{dx^2} = M(x)
$$

Integrating for the respective boundary conditions yields:

- **Simply Supported Mid-Span Deflection** ($L = 400\text{ mm}$, central load at $x = a = L/2 = 200\text{ mm}$):

$$
\delta_{\text{SS}}\left(\frac{L}{2}\right) = -\frac{P L^3}{48 EI} = -\frac{P a^3}{6 EI}
$$

- **Cantilever Load-Point Deflection** ($L = 400\text{ mm}$, load and dial gauge at $x = a = 200\text{ mm}$):

$$
\delta_{\text{Cant}}(a) = -\frac{P a^3}{3 EI}
$$

- **Theoretical Kinematic Deflection Ratio** (identical geometry, material, and load $P$ at $x = a = L/2$):

$$
\frac{|\delta_{\text{Cant}}(a)|}{\left|\delta_{\text{SS}}\left(\frac{L}{2}\right)\right|} = 2.00
$$

- **Theoretical Material Deflection Ratio** (Aluminium vs. Mild Steel):

$$
\frac{\delta_{\text{Al}}}{\delta_{\text{MS}}} = \frac{E_{\text{MS}}}{E_{\text{Al}}} = \frac{200\text{ GPa}}{69\text{ GPa}} \approx 2.90
$$

#### Specimen Geometry & Section Properties
- Measured rectangular cross-section: width $b = 19.0\text{ mm}$, thickness $h = 3.2\text{ mm}$, active length $L = 400\text{ mm}$.
- Aspect / Slenderness Ratio: $L/h = 125 \gg 15$ (Euler–Bernoulli assumptions hold; transverse shear deformation is negligible).
- **Area Moment of Inertia ($I$):**

$$
I = \frac{b h^3}{12} = \frac{19.0 \times 3.2^3}{12} = 51.88\text{ mm}^4
$$

- Theoretical Flexural Rigidities:
  - $(EI)_{\text{Al}} = (69 \times 10^3\text{ N/mm}^2) \times 51.88\text{ mm}^4 = 3.58 \times 10^6\text{ N}\cdot\text{mm}^2$
  - $(EI)_{\text{MS}} = (200 \times 10^3\text{ N/mm}^2) \times 51.88\text{ mm}^4 = 1.04 \times 10^7\text{ N}\cdot\text{mm}^2$

#### Experimental Deflection Data
Dead-weights were applied incrementally from $100\text{ g}$ to $400\text{ g}$ ($P = 0.981\text{ N}$ to $3.924\text{ N}$):

##### Table 1: Cantilever Beam Deflections ($x = a = 200\text{ mm}$)
| Mass $m$ (g) | Load $P$ (N) | $\delta_{\text{Al}}$ (mm) | $\delta_{\text{MS}}$ (mm) | Deflection Ratio (Al / MS) |
|:---:|:---:|:---:|:---:|:---:|
| $100$ | $0.981$ | $-0.96$ | $-0.44$ | $2.182$ |
| $200$ | $1.962$ | $-1.79$ | $-0.80$ | $2.238$ |
| $300$ | $2.943$ | $-2.62$ | $-1.17$ | $2.239$ |
| $400$ | $3.924$ | $-2.99$ | $-1.56$ | $1.917$ |

##### Table 2: Simply Supported Beam Deflections ($x = L/2 = 200\text{ mm}$)
| Mass $m$ (g) | Load $P$ (N) | $\delta_{\text{Al}}$ (mm) | $\delta_{\text{MS}}$ (mm) | Deflection Ratio (Al / MS) |
|:---:|:---:|:---:|:---:|:---:|
| $100$ | $0.981$ | $-0.19$ | $-0.31$ | $0.613$ *(seating offset)* |
| $200$ | $1.962$ | $-0.43$ | $-0.40$ | $1.075$ |
| $300$ | $2.943$ | $-0.61$ | $-0.44$ | $1.386$ |
| $400$ | $3.924$ | $-0.82$ | $-0.54$ | $1.519$ |

#### Slope-Based Young's Modulus & Theoretical Comparison
To eliminate constant zero-offsets and seating artifacts, analysis was conducted using the incremental load-deflection slopes ($\Delta\delta/\Delta P$):

| Configuration | Specimen | Experimental Slope (mm/100 g) | Experimental Compliance (mm/N) | Derived Modulus $E_{\text{exp}}$ (GPa) | Nominal $E$ (GPa) | Deviation vs. Nominal |
|---|---|:---:|:---:|:---:|:---:|:---:|
| **Cantilever** | Aluminium | $0.830$ | $0.846$ | $60.7$ | $69.0$ | $-12.0\%$ |
| **Cantilever** | Mild Steel | $0.365$ | $0.372$ | $138.0$ | $200.0$ | $-31.0\%$ |
| **Simply Supported** | Aluminium | $0.207$ | $0.211$ | $122.0$ | $69.0$ | $+76.5\%$ |
| **Simply Supported** | Mild Steel | $0.073$ | $0.0744$ | $345.0$ | $200.0$ | $+72.7\%$ |

#### Key Analytical Highlights & Verification

1. **Ratio of Young's Moduli Verification:**
   The least-squares slope ratio in the simply supported configuration was:

$$
\frac{\left(\dfrac{\Delta\delta}{\Delta m}\right)_{\text{SS, Al}}}{\left(\dfrac{\Delta\delta}{\Delta m}\right)_{\text{SS, MS}}} = \frac{0.207\text{ mm / 100 g}}{0.073\text{ mm / 100 g}} = 2.84
$$

   Comparing this against the theoretical inverse modulus ratio:

$$
\frac{E_{\text{MS}}}{E_{\text{Al}}} = \frac{200\text{ GPa}}{69\text{ GPa}} \approx 2.90
$$

   the experimental slope ratio matches Euler–Bernoulli predictions within **2.2%** (the end-point slope ratio $2.74$ is within **5.5%**). This confirms that evaluating the incremental slope ($\Delta\delta / \Delta m$) effectively eliminates constant zero-point offsets and initial seating clearance artifacts.

2. **Initial Seating Anomaly in Mild Steel:** At $m = 100\text{ g}$, the Mild Steel beam registered a larger initial deflection ($-0.31\text{ mm}$) than Aluminium ($-0.19\text{ mm}$), creating an apparent ratio $< 1$. This was identified as initial clearance / bow at knife-edge contact surfaces that seated under load.
3. **Cantilever Clamp Rotational Compliance:** Measured cantilever deflections exceeded theory (yielding apparent $E < E_{\text{nominal}}$). A bench vice cannot enforce an infinitely rigid rotational clamp; load-induced parasitic rotation $\theta_0 \approx (0.7\text{--}0.85) \times 10^{-3}\text{ rad/N}$ contributed an additional rigid-body displacement $a\theta_0$.
4. **Effective Knife-Edge Span:** In the simply supported configuration, both materials deflected less than predicted by a consistent factor of $\approx 1.75$ (compliances were $\sim 57\%$ of theoretical). Because $\delta \propto L^3$, this stiffness increase corresponds directly to an effective support span of $L_{\text{eff}} \approx 332\text{ mm}$ (instead of nominal $400\text{ mm}$) or friction-induced axial restraint at the knife edges.
5. **Dial Gauge Travel Limitation:** At $400\text{ g}$ on cantilever Aluminium, the deflection increment dropped significantly (from $0.83\text{ mm}$ down to $0.37\text{ mm}$) due to plunger travel limits ($\approx 3\text{ mm}$) or the hanger contacting the base plate.

---

## 📊 Cross-Report Synthesis & Comparative Insights

| Loading Condition | Primary Stress State | Characteristic Material Metric | Aluminium Response | Mild Steel Response | Cast Iron Response |
|---|---|---|---|---|---|
| **Uniaxial Tension** | Pure normal tensile stress ($\sigma_{xx} > 0$) | Yield strength $\sigma_y$, UTS, Ductility | Ductile, extensive necking, shear cup-and-cone | Ductile, yield point phenomenon, Lüders bands | Brittle cleavage, zero necking, low tensile strength |
| **Uniaxial Compression** | Pure normal compressive stress ($\sigma_{xx} < 0$) | Compressive yield strength, Malleability | High ductility, plastic barreling | High ductility, plastic barreling | High strength, brittle crush along $45^\circ$ shear planes |
| **Dynamic Impact** | Triaxial tensile stress at notch, high strain rate ($\dot{\epsilon} \gg 1$) | Absorbed impact energy ($KV$), Notch toughness | Brittle dynamic fracture ($KV_{\text{avg}} = 16.35\text{ J}$) | — | — |
| **Quasi-Static Torsion** | Pure shear stress ($\tau_{xy}$), zero normal stress | Shear modulus $G$, Yield shear strength $\tau_y$ | Extreme ductility ($\theta_{\max} = 589^\circ$, $\gamma_f = 0.51$) | — | — |
| **Transverse Flexural Bending** | Non-homogeneous normal & shear stresses ($\sigma(y) = -My/I$) | Flexural rigidity ($EI$), Elastic deflection $\delta$ | High compliance, $\delta \propto P L^3 / EI$ | High stiffness ($E_{\text{MS}} / E_{\text{Al}} \approx 2.90$) | — |

---

## 🛠️ Viewing the Reports

To view the complete laboratory reports with high-resolution vector plots, full data tables, and schematics:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RishabhShahIITGN/MOM_reports.git
   cd MOM_reports
   ```
2. **Open with any standard PDF reader:**
   - Linux: `evince MOM_lab1.pdf`, `okular MOM_lab2.pdf`
   - macOS: `open MOM_lab1.pdf`
   - Windows: Double-click or open with Acrobat / Edge / Chrome

You can also view the reports directly in your browser on GitHub by clicking the links in the table above.

---

## 📚 References

1. **R. C. Hibbeler**, *Mechanics of Materials*, 10th ed., Pearson, Hoboken, NJ, USA, 2016.
2. **F. P. Beer, E. R. Johnston, J. T. DeWolf, and D. F. Mazurek**, *Mechanics of Materials*, 7th ed., McGraw-Hill Education, New York, NY, USA, 2015.
3. **J. M. Gere and B. J. Goodno**, *Mechanics of Materials*, 8th ed., Cengage Learning, Stamford, CT, USA, 2013.
4. **W. D. Callister Jr. and D. G. Rethwisch**, *Materials Science and Engineering: An Introduction*, 10th ed., John Wiley & Sons, Hoboken, NJ, USA, 2018.
5. **R. S. Figliola and D. E. Beasley**, *Theory and Design for Mechanical Measurements*, 6th ed., John Wiley & Sons, Hoboken, NJ, USA, 2014.

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
