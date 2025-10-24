# Haldane Model Simulation 🧠
This repository contains a Python implementation of the **Haldane model** — a tight-binding model on a honeycomb lattice that exhibits a **quantum anomalous Hall effect (QAHE)** without an external magnetic field. The project allows you to explore topological properties of the system, such as the **energy band structure** and **Chern number**, by adjusting model parameters like on-site potential, hopping amplitudes, and phase factors.  
This code was created based on the theory presented [here](link_do_publikacji_lub_materiału_teoretycznego).

---

## 🧠 Features
- Compute and visualize **energy bands** of the Haldane model.  
- Calculate the **Chern number** using Berry curvature integration.  
- Adjustable parameters:
  - nearest- and next-nearest-neighbor hopping (`taa`, `tbb`, tab)
  - on-site potential difference (`M`)
- Option to display **edge states** for finite ribbons.  

---

## ⚙️ Installation
Clone this repository and move into the project directory:
```bash
git clone https://github.com/yourusername/haldane-model.git
cd haldane-model
```

Install all dependencies automatically:
```bash
pip install -r requirements.txt
```

If you prefer using a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate     # on Linux/macOS
venv\Scripts\activate        # on Windows
pip install -r requirements.txt
```

---

### 🧪 Alternative installation with conda
If you encounter issues installing **kwant** with `pip`, you can use **conda** instead:
```bash
conda create -n haldane python=3.11 numpy scipy matplotlib ipywidgets ipython notebook tinyarray kwant -c conda-forge
conda activate haldane
```
This will automatically install all dependencies, including precompiled binaries of `kwant`.

---

## 🚀 Usage
Run the main script:
```bash
python haldane_model.py
```

Or open the Jupyter notebook:
```bash
jupyter notebook Haldane_graphene.ipynb
```

You can modify parameters directly in the notebook or script to explore different regimes of the model.

---

## 📊 Example Results
*(Example images — replace with your own plots)*  
![Band structure example](images/band_structure.png)  
![Berry curvature example](images/berry_curvature.png)

---

## 📘 Theory
The **Haldane model** describes electrons on a honeycomb lattice with complex next-nearest-neighbor hopping that breaks time-reversal symmetry, leading to a non-trivial **Chern insulating phase** — a realization of the **quantum anomalous Hall effect** without an external magnetic field.  
For theoretical background, see:
- F. D. M. Haldane, *Phys. Rev. Lett.* **61**, 2015 (1988)  
- N. P. Armitage *et al.*, *Rev. Mod. Phys.* **90**, 015001 (2018)

---

## 🧩 Dependencies
All required Python packages are listed in [`requirements.txt`](requirements.txt). You can install them using:
```bash
pip install -r requirements.txt
```

---

## 🧭 Roadmap
- [ ] Add ribbon geometry and edge state visualization  
- [ ] Implement interactive sliders (via ipywidgets)  
- [ ] Extend to spinful model with spin–orbit coupling  

---

## 🧪 Citation
If you use this code in your research, please cite:
> This research was funded by the National Science Centre Poland (NCN) according to decision **2021/42/E/ST3/00128**.

---

## 📜 License
Licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

