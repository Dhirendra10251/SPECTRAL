# SPECTRAL
First semester computational chemistry project

⚛️ **Spectral:** Hydrogen Atom Simulator

Spectral is an interactive web-based simulation that visualizes the quantum mechanics of the Hydrogen atom. It calculates the emission spectra of hydrogen-like ions using the Rydberg Formula and animates electron transitions in real-time using the Bohr Model.

🚀**Live Demo:**

[Insert your GitHub Pages link here once deployed, e.g., https://www.google.com/search?q=https://yourusername.github.io/spectral]

🧪 **The Science:**

This project visualizes the Bohr Model of the atom. When an electron "jumps" from a high energy orbit ($n_i$) to a lower energy orbit ($n_f$), it loses energy. This energy is released as a photon of light.

The app uses the Rydberg Formula to calculate the exact wavelength ($\lambda$) and color of that light:

$$\frac{1}{\lambda} = R \cdot Z^2 \left( \frac{1}{n_f^2} - \frac{1}{n_i^2} \right)$$

Where:

$R$: Rydberg Constant ($1.097 \times 10^7 m^{-1}$)

$Z$: Atomic Number (Proton count)

$n$: Principal Quantum Numbers (Orbits)

✨ **Key Features**

Interactive Simulation: Drag sliders to change electron orbits and watch the atom react.

Multi-Element Support: Supports Hydrogen ($H$), Helium Ion ($He^+$), Lithium Ion ($Li^{2+}$), and Beryllium Ion ($Be^{3+}$).

Real-Time Math: Instantly calculates Wavelength ($nm$), Frequency ($Hz$), and Energy ($J$).

Dynamic Visuals: * Orbits and Nucleus resize based on the element ($Z$).

Photons are emitted with the correct calculated color (or UV/IR representation).

Spectral Series Detection: Automatically identifies Lyman, Balmer, Paschen, Brackett, and Pfund series.

Experiment History: detailed log of all transitions performed during the session.

🛠️ **How to Run Locally**

Clone the repository:

git clone [https://github.com/Dhirendra10251/spectral-app.git](https://github.com/Dhirendra10251/spectral-app.git)


**Open the file:**
Simply double-click index.html to open it in any modern web browser (Chrome, Edge, Firefox, Safari). No server installation required!

👥 **Project Team**

This project was designed and built by:

**Dhirendra Kumar Thakur [25bai10251]**

**Mahi Vijay [25bai10333]**

**Ayesha Raza [25bai10998]**

📜 **License**
This project is open source and available for educational use.
