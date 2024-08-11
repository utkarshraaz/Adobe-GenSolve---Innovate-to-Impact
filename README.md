**Team Name:** Pi-Thons  
**College Name:** IIT Roorkee  
**Team Members:** Utkarsh Raj, Md Atif Husain  

---

### Project Title: Curvetopia - A Journey into the World of Curves

**Problem Statement:**  
This project aims to identify, regularize, and beautify various types of curves in 2D Euclidean space. The focus is on closed curves, particularly in symmetry and curve completion techniques. The project is divided into the following key tasks:

1. **Regularize Curves:**
   - **Straight Lines**: Detect and regularize straight lines.
   - **Circles and Ellipses**: Identify curves that represent circles or ellipses based on the properties of equidistance from a centre or having two focal points.
   - **Rectangles and Rounded Rectangles**: Distinguish between rectangles and those with curved edges.
   - **Regular Polygons**: Identify polygons with equal sides and angles.
   - **Star Shapes**: Identify star shapes by looking for central points with multiple radial arms.

2. **Exploring Symmetry in Curves:**
   - Identify reflection symmetries in closed shapes, detecting lines of symmetry where the shape can be divided into mirrored halves.

3. **Completing Incomplete Curves:**
   - Address curves that have been "planarized," leading to gaps or partial holes, and complete these curves naturally and aesthetically pleasingly.

**Approach and Methodology:**

1. **Corner Detection Using Curvature:**
   - The first step in our process was to detect the corners of shapes using curvature analysis. This allowed us to accurately identify key points in the shape where changes in direction occur.

2. **Fitting Regression Lines:**
   - For the detected corners, we applied a best-fit regression line to create straight lines wherever possible. This helped in simplifying the shapes and ensuring that they align with geometric primitives.

3. **Merging Points to Create Closed Shapes:**
   - Based on the proximity of the points, we merged them to form closed shapes. This step was crucial in defining distinct boundaries and ensuring that all shapes are properly closed.

4. **Shape Identification and Regularization:**
   - Once the closed shapes were formed, we identified each shape as a circle, square, rectangle, star, etc. Regularization was then applied to make each shape conform to its ideal geometric form.

5. **Symmetry Detection:**
   - We explored reflection symmetry within the identified shapes, ensuring that the shapes are mirrored correctly across their axes of symmetry.

6. **Curve Completion:**
   - For any shapes that had gaps or were incomplete, we applied curve completion techniques to fill in the missing sections, resulting in smooth and continuous shapes.

**Usage Instructions:**

1. **Input Format:**
   - The input consists of CSV files containing polylines that represent various shapes.

2. **Running the Code:**
   - Load the input CSV file using the provided reading functions.
   - Apply the regularization and symmetry detection algorithms to the loaded shapes.
   - If applicable, run the curve completion algorithm to fill in any gaps.

3. **Output:**
   - The output will be a set of regularized and completed curves, which can be visualized or saved as image or CSV files for further use.


Here is a glimpse at our solution:


![image](https://github.com/user-attachments/assets/f983e8e5-9a2a-4d03-9ddd-c07710d7f5f1)
![image](https://github.com/user-attachments/assets/dd072137-053b-44c4-b316-a2a2ee54930f)
![image](https://github.com/user-attachments/assets/2696e05a-b1be-4f45-aecb-c8b2e8443aa7)


### Demo Video
Check out the Project Demo Video [Link](https://drive.google.com/file/d/1mqFf9THEJBDAXzeijk4nDfnyTXPX-pID/view?usp=drive_link)

