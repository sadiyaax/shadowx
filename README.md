# ShadowX
A project for enhancing low-light images of Lunar Permanently Shadowed Regions (PSRs)

## Overview
ShadowX is a lunar image enhancement project focused on improving the feeble light reflected from the Permanently Shadowed Regions (PSRs) of the Moon. These images are captured by the Optical High-Resolution Camera (OHRC) aboard Chandrayaan-2.

The goal is to enhance the Signal-to-Noise Ratio (SNR), reduce noise, and generate clearer, high-quality image maps of the lunar poles. These enhanced outputs support landing site selection, geomorphological analysis, and scientific exploration of shadowed lunar craters.

---

## Project Structure
```
ShadowX/
├── env/                 # Virtual environment (optional)
├── src/                 # Source code directory
│   ├── gui/             # GUI-related code
│   ├── processing/      # Image processing algorithms
│   └── main.py          # Main entry point for the application
├── tests/               # Testing scripts
├── docs/                # Documentation and guides
├── requirements.txt     # List of dependencies
└── README.md            # Project description
```

### Directory Details

- **env/**  
  Contains the virtual environment for isolation of dependencies.

- **src/**  
  Main source code for ShadowX.

  - **gui/**  
    Code for the graphical user interface.

  - **processing/**  
    Image enhancement and noise reduction algorithms.

  - **main.py**  
    Entry point to run the application.

- **tests/**  
  Scripts used to test features, algorithms, and overall functionality.

- **docs/**  
  Project documentation such as user manuals and technical details.

- **requirements.txt**  
  Python dependencies required for the project.

- **README.md**  
  This documentation file.

---

## Features

- **Low-Light Image Enhancement**  
  Enhances visibility in lunar PSR images.

- **Noise Reduction**  
  Removes noise from extremely low-light OHRC images.

- **Graphical User Interface (GUI)**  
  User-friendly interface to interact with processing tools.

- **Testing Suite**  
  Ensures algorithm reliability and consistent performance.

---

## Use Cases

- **Landing Site Selection**  
  Helps identify suitable landing zones by enhancing hidden PSR terrain.

- **Geomorphological Studies**  
  Enables scientists to analyze terrain features in regions with no direct sunlight.

---

## Roles and Responsibilities

This project is being developed by a team of 6 members:

### **Lead Developer (Member 1)**
- Set up the development environment and repository  
- Lead the implementation and integration of core features  
- Oversee overall project development

### **Image Processing Specialist (Member 2)**
- Research and implement enhancement algorithms  
- Improve SNR and low-light image clarity  
- Support integration with the application backend

### **Data Handling & Integration Specialist (Member 3)**
- Implement image loading, saving, and exporting  
- Ensure smooth data flow across modules

### **GUI Designer/Developer (Member 4)**
- Design and develop GUI using PyQt5/Tkinter  
- Ensure responsiveness and ease of use  
- Integrate backend with GUI

### **Testing & QA (Member 5)**
- Develop and execute test cases  
- Identify issues and ensure application stability

### **Documentation Specialist (Member 6)**
- Maintain user guides and technical documentation  
- Update README and other relevant project files

---

## 1. Clone the Repository
```bash
git clone https://github.com/sadiyaax/ShadowX.git
cd ShadowX
```

## 2. Set Up the Virtual Environment (Optional but Recommended)
```bash
python3 -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
```

## 3. Install Dependencies
```bash
pip install -r requirements.txt
```

## 4. Run the Application
```bash
python src/main.py
```

## Contact
- **Lead Developer:** Shreya Ghodake (shreyaghodake174@gmail.com)  
- **Image Processing Specialist:** Member 2 (samarthscoe@gmail.com)  
- **Data Handling Specialist:** Member 3 (kongarijanhavi@gmail.com)  
- **GUI Developer:** Member 4 (sadiyagavandi@gmail.com)  
- **Testing & QA:** Member 5 (kshitigambhir@gmail.com)  
- **Documentation Specialist:** Member 6 (sanketmalegaonkar@gmail.com)  
