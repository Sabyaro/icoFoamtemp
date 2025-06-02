# icoFoamTemp

**icoFoamTemp** is a customized version of the `icoFoam` solver from OpenFOAM, extended to solve the temperature (energy) equation in addition to the incompressible laminar Navier–Stokes equations. This solver is ideal for basic conjugate heat transfer simulations involving laminar flow and thermal transport.

---

## 🔧 Installation

To use this solver, **OpenFOAM v2312** must be installed on your system.

### Steps:
1. **Download** or clone the `icoFoamTemp` folder.
2. **Copy** the folder into your OpenFOAM user directory:
   ```bash
   $WM_PROJECT_USER_DIR
3. **Run** the command in the terminal:
   ```bash
   wmake

## 🚀 Running a Case 

To run a sample case, ensure you have the following folders: **0**, **constant**, and **system**.

### Execution Steps: 

1. Navigate to your case directory and generate the mesh:
   ```bash
   blockMesh
2. Run the solver:
   ```bash
   icoFoamTemp

## ⚠️ Notes 

> This solver is designed for laminar, incompressible flow with heat transport
> When refining the mesh, ensure numerical stability by adjusting **deltaT** parameter in the **controlDict** file.
> Suitable for academic use, method validation, and fundamental heat transder studies.

## 📫 Contributions 

Contributions are welcome! Feel free to fork the repository, raise issues, or open pull requests to suggest improvements.

