# Cubic EOS Calculator

Thermodynamics computer project: PVT behaviour, enthalpy, entropy and fugacity of real gases using cubic equations of state.

**Submitted by:** Viraj Chauhan (2025CH11046) and Prakhar Rawat (2025CH11477)

**Live website:** https://viraj-chauhan.github.io/cubic-eos-calculator/

**Project report:** [report.pdf](report.pdf) ([open in browser](https://viraj-chauhan.github.io/cubic-eos-calculator/report.pdf))

## What it does

For a selected gas at a given temperature and pressure, the program calculates the following using the van der Waals, Redlich-Kwong, Soave-Redlich-Kwong and Peng-Robinson equations:

1. **PVT behaviour:** roots of the cubic in Z, phase, Z, molar volume and density
2. **Fugacity:** fugacity coefficient and fugacity of the pure component, plus the saturation pressure from f<sup>L</sup> = f<sup>V</sup>
3. **Enthalpy and entropy:** residual properties H<sup>R</sup> and S<sup>R</sup>, and total H and S relative to an ideal-gas reference state
4. **Saturation properties:** P<sup>sat</sup>, saturated liquid and vapour volumes, and the enthalpy of vaporization

## Files

| File | Description |
|---|---|
| `index.html` | The complete program (HTML, CSS and JavaScript in one file) |
| [`report.pdf`](report.pdf) | Project report (4 pages) |

## How to run

Open the live website link above, or download `index.html` and open it in any web browser. No installation is needed.

## Reference

J.M. Smith, H.C. Van Ness, M.M. Abbott and M.T. Swihart, *Introduction to Chemical Engineering Thermodynamics*, 8th ed., McGraw-Hill (2018).
