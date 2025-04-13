# ShadowX
A project for enhancing low-light images of Lunar PSR regions

## Overview
The ShadowX project aims to enhance the feeble light reflected from the Permanently Shadowed Regions (PSR) of Lunar craters. These regions are captured by the Optical High-Resolution Camera (OHRC) aboard Chandrayaan-2. The goal is to improve the Signal-to-Noise Ratio (SNR) of these low-light images, remove noise, and produce a clear PSR image map of the lunar poles. This enhanced image data will be useful for landing site selection and geomorphological studies.

## Project Structure
The project is organized into the following directories and files:

ShadowX/
├── env/ # Virtual environment
├── src/ # Source code directory
│ ├── gui/ # GUI-related code
│ ├── processing/ # Image processing algorithms
│ ├── main.py # Main entry point for the application
├── tests/ # Testing scripts
├── docs/ # Documentation
├── requirements.txt # Dependencies list
└── README.md # Project description


- **`env/`**: Contains the virtual environment for the project (optional).
- **`src/`**: The source code for the project is stored here.
  - **`gui/`**: Code related to the graphical user interface (GUI).
  - **`processing/`**: Contains the image processing algorithms.
  - **`main.py`**: The main entry point for running the application.
- **`tests/`**: Scripts and files for testing the application.
- **`docs/`**: Project documentation, including user manuals and technical guides.
- **`requirements.txt`**: A list of dependencies required to run the project.
- **`README.md`**: The file you're reading right now, describing the project.

## Features
- **Low-Light Image Enhancement**: Improves the visibility of low-light images captured in the Permanently Shadowed Regions (PSR) of the Moon.
- **Noise Reduction**: Reduces noise in the enhanced images to produce clearer data for analysis.
- **Graphical User Interface (GUI)**: A user-friendly interface to interact with the image processing algorithms.
- **Testing Suite**: A set of tests to ensure the functionality and accuracy of the image enhancement algorithms.

## Use Cases
- **Landing Site Selection**: Helps in selecting suitable landing sites on the Moon by providing enhanced images of the PSR regions.
- **Geomorphological Studies**: Assists scientists in studying the surface features of the Moon in shadowed regions where sunlight does not reach.

## Roles and Responsibilities
The project is being developed by a team of 6 members, with the following roles:

1. **Lead Developer(Member 1)**:
   - Set up the development environment and repository.
   - Lead the development of the main application logic and integrate all features.
   - Oversee the project progress and ensure timely completion.

2. **Image Processing Specialist (Member 2)**:
   - Research and implement image processing techniques (e.g., SNR improvement, noise reduction).
   - Develop and test algorithms to enhance low-light images.
   - Collaborate on integrating the image processing algorithms into the application.

3. **Data Handling & Integration Specialist(Member 3)**

    -Develop and implement file handling features (loading, saving, exporting images).
    -Ensure smooth interaction between the backend and file handling components.

4. **GUI Designer/Developer (Member 4)**:
   - Design and develop the user interface using PyQt5 or Tkinter.
   - Ensure that the interface is user-friendly and responsive.
   - Work with the Lead Developer to integrate the GUI with the backend logic.

5. **Testing & QA (Member 5)**:
   - Develop and execute test cases to ensure the application works as intended.
   - Identify and report any bugs or issues to the development team.
   - Ensure that the final product is stable and meets quality standards.

6. **Documentation Specialist (Member 6)**:
   - Maintain project documentation, including user guides and technical documentation.
   - Update the `README.md` file as the project evolves.
   - Ensure that all project details are well-documented for future reference.

## Setup Instructions
To set up the project on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Shre-05/ShadowX.git
   cd ShadowX

## Set Up the Virtual Environment (Optional but Recommended)

To set up a virtual environment, follow these steps:

```bash
python3 -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`

### **2. Install Dependencies**

This section outlines how to install the necessary dependencies for the project. It assumes that you have a `requirements.txt` file listing the project’s dependencies.

```markdown
## Install Dependencies

After setting up the virtual environment, install the required dependencies by running:

```bash
pip install -r requirements.txt

### **3. Run the Application**

This section explains how to run the application, specifying the entry point script.

```markdown
## Run the Application

To run the application, execute:

```bash
python src/main.py

## Contact

For any questions or feedback, please reach out to the project team:

- **Lead Developer**: shreya Ghodake (shreyaghodake174@gmail.com)
- **Image Processing Specialists**: Member 2(samarthscoe@gmail.com)
- **Data Handling & Integration Specialist(Member 3)**(kongarijanhavi@gmail.com)
- **GUI Designer/Developer**: Member 4(sadiyagavandi@gmail.com)
- **Testing & QA**: Member 5(kshitigambhir@gmail.com)
- **Documentation Specialist**: Member 6(sanketmalegaonkar@gmail.com)

