# TECF Simulation: Geodesic Deflection in Quantum Codes

Computational exploration of path lengthening in entanglement landscapes.

## 📄 Paper

**Computational Study of Geodesic Deflection in Topological Quantum Error-Correcting Codes**  
chez prefect with assistance from Claude (Anthropic)  
arXiv: [pending]  
Status: Exploratory research, October 2025

## 🎯 Summary

This project explores whether graph-theoretic geodesics in mutual information (MI) fields exhibit deflection around regions of suppressed entanglement. Using toric code lattices as a test case, we observe path lengthening effects and discuss their interpretation.

### Key Findings

- **Path lengthening:** Geodesics deflect by 2.54 ± 0.23× relative to Euclidean paths
- **Baseline effect:** 2.28× from global MI gradient structure
- **Defect contribution:** Additional 0-0.5× from localized defects (configuration-dependent)
- **Curvature proxy:** 12-66× enhancement in discrete scalar curvature at defects

### Limitations

This is a **toy model** using:
- Phenomenological MI fields (not exact stabilizer calculations)
- Classical simulation (no quantum hardware validation)
- Discrete lattice (no demonstrated continuum limit)
- Graph geodesics (not rigorous metric construction)

**This work does NOT claim to prove spacetime emergence.** It demonstrates graph-theoretic effects that are *suggestive* of geometric behavior and may inform future rigorous approaches.

## 🚀 Quick Start

### Run in Google Colab

1. Click `tecf_simulation.ipynb` above
2. Open in Colab
3. Runtime → Run all

### Run Locally
```bash
git clone https://github.com/YOUR-USERNAME/tecf-simulation.git
cd tecf-simulation
pip install numpy matplotlib
jupyter notebook tecf_simulation.ipynb
