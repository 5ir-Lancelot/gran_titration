<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

# 🧪 Gran Titration Procedure for Measuring Alkalinity

## **Purpose**
The **Gran titration** is a precise method to determine the **alkalinity** of an aqueous solution — that is, its capacity to neutralize acid. It is especially useful for natural waters, seawater, and laboratory samples where buffering occurs near the **carbonate system equilibrium**.

---

## **Principle**

When an **acid** (usually HCl) is added to an **alkaline solution** (containing bicarbonate, carbonate, and hydroxide ions), the following reactions occur sequentially:

1. **Neutralization of hydroxide:**
   
   <p align="center">OH⁻ + H⁺ → H₂O</p>


2. **Conversion of carbonate to bicarbonate:**

   
   CO₃²⁻ + H⁺ → HCO₃⁻


3. **Conversion of bicarbonate to carbonic acid:**

   $$
   \mathrm{HCO_3^- + H^+ \rightarrow H_2CO_3 \leftrightharpoons CO_2(aq) + H_2O}
   $$

These reactions consume acid until the equivalence point(s) are reached.

---

## **The Gran Function**

The **Gran plot** transforms pH titration data into a **linear function** that allows accurate extrapolation of the **equivalence volume (Vₑ)** — even before it is reached experimentally.

For a strong acid titrating a bicarbonate/carbonate solution, the **Gran function (G)** is defined as:

$$
G = V_\\mathrm{acid} \times 10^{-\mathrm{pH}}
$$

Plotting \( G \) versus \( V_\mathrm{acid} \) (volume of acid added) produces a straight line near the equivalence point.  
Extrapolating this line to where \( G = 0 \) gives the **equivalence volume (Vₑ)** — the point where all alkalinity has been neutralized.

---

## **Procedure**

1. **Prepare the titration setup:**
   - Sample of unknown alkalinity (typically 50–100 mL)
   - Acid of known concentration (e.g., 0.01 M HCl)
   - pH electrode connected to a pH meter

2. **Titrate the sample:**
   - Gradually add acid while continuously measuring pH.
   - Record **volume added (V)** and **pH** after each increment.
   - Continue the titration until pH ≈ 3.5.

3. **Data analysis:**
   - Calculate \( G = V \times 10^{-\mathrm{pH}} \) for each data point.
   - Plot \( G \) versus \( V \).
   - Fit a straight line to the data points before the equivalence point.
   - Extrapolate the line to \( G = 0 \); this gives \( V_e \).

4. **Calculate alkalinity:**

   $$
   \\text{Alkalinity (eq/L)} = \\frac{C_\mathrm{acid} \times V_e}{V_\mathrm{sample}}
   $$

   where:
   - \( C_\mathrm{acid} \) = concentration of acid (mol/L)  
   - \( V_e \) = equivalence volume (L)  
   - \( V_\mathrm{sample} \) = sample volume (L)

---

## **Advantages of Gran Titration**
