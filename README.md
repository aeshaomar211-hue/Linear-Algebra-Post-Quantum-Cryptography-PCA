# Linear-Algebra-Post-Quantum-Cryptography-PCA
# Linear Algebra Project: Post-Quantum Cryptography & PCA

[!["License: MIT"](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📖 Description

This repository contains the final project report for our BS CIS (24-28) Linear Algebra course, advised by Sir Zaheer Asghar.

Our project had two main objectives:
1.  **To study the mathematical foundations** of Post-Quantum Cryptography (PQC) and understand why linear algebra is central to algorithms like Lattice-based, Code-based, and Multivariate cryptography.
2.  **To apply Principal Component Analysis (PCA)** , a key linear algebra technique, to a real-world dataset. We analyzed performance metrics from 25 standardized PQC algorithms to uncover patterns, trade-offs between speed and memory, and groupings based on security levels.

This work demonstrates how abstract concepts like eigenvectors, eigenvalues, and covariance matrices can be used to solve practical problems in cybersecurity and data science.

## ✨ Key Highlights

*   **Applied Focus:** We used PCA to reduce a 6-dimensional dataset of algorithm performance into 2 principal components.
*   **Key Insight:** The first two principal components captured over **78% of the total variance** in the data, allowing for clear visualization.
*   **Real-World Relevance:** Our analysis revealed distinct clusters for algorithm families (e.g., Kyber, McEliece) and the trade-offs associated with higher security levels.
*   **Educational Value:** The report connects foundational linear algebra concepts directly to their application in a cutting-edge field (PQC).

## 📂 Repository Contents

*   `Report_LA.pdf`: The complete project report, including abstract, methodology, mathematical foundations, results, and graphs [citation:2][citation:3][citation:5].
*   `README.md`: This file, providing an overview of the project.

## 🛠️ Methodology

The core of our analysis involved the following steps, as detailed in the report:

1.  **Data Standardization:** Normalized the features (e.g., keygen time, ciphertext size) to have a mean of 0 and standard deviation of 1.
2.  **Covariance Matrix Computation:** Calculated the `6x6` covariance matrix to understand relationships between different performance metrics.
3.  **Eigen Decomposition:** Computed the eigenvectors and eigenvalues of the covariance matrix to identify the principal components.
4.  **Dimensionality Reduction:** Projected the original 6D data onto the first two principal components to create 2D visualizations.

## 📊 Results

The PCA was highly effective in simplifying the complex dataset. The table below shows the variance explained by each new component:

| Component | Eigenvalue | Variance Explained | Cumulative Variance |
| :-------- | :--------- | :----------------- | :------------------ |
| PC1       | 3.42       | 57.0%              | 57.0%               |
| PC2       | 1.28       | 21.3%              | **78.3%**           |
| PC3       | 0.85       | 14.2%              | 92.5%               |

*The full analysis, including plots that visualize algorithm families (Kyber, McEliece, BIKE) and security levels in the new PCA space, can be found in the full report (`Report_LA.pdf`).*

## 🚀 Getting Started

To view the project, simply download and open the `Report_LA.pdf` file. You can do this directly from the GitHub repository by navigating to the file and clicking "Download" or by cloning the repo.

### Prerequisites
*   A PDF reader (like Adobe Acrobat, Chrome's PDF viewer, etc.)

### Installation & Viewing
1.  Clone the repository:
    ```bash
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
    ```
2.  Navigate to the directory and open the PDF file.

## 🗺️ Roadmap / Future Work

This project lays the groundwork for further exploration. Potential next steps include:
*   Extending the analysis to include more recent PQC algorithms as they are standardized.
*   Performing a similar PCA on a dataset of digital signature algorithms (e.g., ML-DSA, SLH-DSA).
*   Developing an interactive Python notebook (Jupyter) to allow users to explore the PCA results dynamically [citation:1].

## 🤝 Contributing

This project was completed as a course requirement and is not currently seeking contributions. However, feel free to fork the repository or reach out if you have questions.


## 🙏 Acknowledgments

*   **Course Instructor:** Sir Zaheer Asghar
*   **Group Members:** Aameen Fatima, Ayesha Omar, Hadia Sohail, Hafsa Naz, Meshal Gul
*   **Sources:** Palo Alto Networks, NIST, and academic papers cited within the report.

---
*Project completed on December 20, 2025.*
