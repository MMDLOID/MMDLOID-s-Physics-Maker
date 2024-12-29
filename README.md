# MMDLOID's Physics Maker

**MMDLOID's Physics Maker** is a powerful and easy-to-use tool designed to simplify the process of setting up physics for MMD (MikuMikuDance) models.

---

## Features

- **Standalone Software**: This tool is not a PMX-Editor plugin but works alongside it to enhance the workflow.
- **Effortless Physics Setup**: Automates the process of configuring physics values for joints and rigid bodies in MMD models.
- **Physics Calculator**: Automatically extend and adjust CSV files to match your model’s specific needs.
- **Template Creation**: Save custom physics setups as reusable templates for other models.
- **CSV Row Checker**: Verify the total number of rows in a template for accuracy.

---

## Getting Started

### Prerequisites
- **Windows OS**: Required to run the `.exe` file.
- **PMX-Editor**: Used for exporting and importing CSV files.
- An MMD model file to work on.

### Installation
1. Download the latest version of **MMDLOID's Physics Maker** from the [Releases](#) page.
2. Extract the downloaded `.zip` file to your desired location.
3. Double-click the `MMDLOIDs_Physics_Maker.exe` file to start the software.

---

## Usage

### Step 1: Prepare Files in PMX-Editor
1. Open your model in PMX-Editor.
2. Navigate to the "Body" and "Joint" tabs.
3. While holding **Shift**, select the bodies and joints you want to edit. Ensure they are ordered correctly (from top to bottom).
4. Right-click and select **Save CSV**.
5. Save the file in the appropriate folder based on its type (e.g., **Body CSV** or **Joint CSV**).
6. Note the total number of rows in your exported file (e.g., 20).

### Step 2: Use the Physics Calculator
1. Launch the Physics Calculator in the **Homu UI**.
2. Load your exported CSV file into the "Extend" section.
3. Enter the total number of rows required (e.g., 20).
4. The calculator will automatically generate an extended CSV file.

### Step 3: Apply the Template
1. In the **Homu UI**, click on **Edit CSV**.
2. For each file type (Body or Joint):
   - Click **Edit Body CSV** (or the respective option for Joints).
   - Select the extended template file.
   - Select the original CSV file exported from PMX-Editor.
   - Save the output file.

### Step 4: Import the CSV Files into PMX-Editor
1. Open PMX-Editor and navigate to the appropriate tab (Body or Joint).
2. Select any item, right-click, and choose **Import CSV**.
3. Load the final edited CSV file.
4. Repeat for both file types.

---

## Extra Features

### Create Your Own Templates
1. Export the Body and Joint CSV files from PMX-Editor.
2. In the **Homu UI**, click on **Create Template**.
3. Select the correct type (Body or Joint) and save the template with an appropriate name.

### CSV Row Checker
- Use the **CSV Row Checker** in the **Homu UI** to verify the total number of rows in a template. This ensures compatibility and accuracy.

### Row Input Cycle
- The software may prompt you for the desired number of rows during certain operations:
  - For single-line physics setups, enter **1**.
  - For multi-line setups (e.g., skirt physics), enter the total number of vertical rows required.

---

## Downloads

Get the latest version from the [Releases](#) page.

---

## License

This software is licensed under a **custom license**. Please refer to the [LICENSE](LICENSE.txt) file for detailed terms and conditions.

