# 📊 Biosignal-Based Stress Detection System Using Machine Learning

## 🔍 Overview
This project is an advanced stress detection system leveraging **machine learning** techniques and biosignals such as **ECG (Electrocardiogram)**, **EMG (Electromyogram)**, **Respiration**, and **GSR (Galvanic Skin Response)**. It aims to detect stress in real-time, with a primary focus on ECG data, which is easily accessible and enables efficient feature extraction. Using **Support Vector Machine (SVM)** models, we have achieved **98.6% accuracy** with a **Gaussian Kernel** function.

## 🔑 Key Features
- **Real-Time Stress Detection**: Utilizes ECG data and derived features like RR Interval, QT Interval, and ECG Derived Respiration (EDR) to classify stress levels.
- **Machine Learning**: Employed **Support Vector Machines (SVM)** with various kernels for stress classification.
- **Data**: The Physionet **Stress Recognition in Automobile Drivers** dataset was used to train and test the model.
- **High Accuracy**: Achieved 98.6% accuracy with the **Gaussian Kernel**.

## 📁 Data
The data used for this project comes from the **Physionet “drivedb”** database, which includes ECG records of individuals driving in stressful and non-stressful conditions.

### 📊 Key ECG Features:
| **Feature**       | **Description**                          |
|-------------------|------------------------------------------|
| **RR Interval**   | Time between successive R peaks in ECG.  |
| **QT Interval**   | Time from Q wave onset to T wave end.    |
| **EDR**           | ECG Derived Respiration - Respiratory rate derived from ECG signals. |

## 🧠 Model & Methodology
- **Algorithm**: Support Vector Machine (**SVM**)
- **Training Dataset**: Physionet "drivedb"
- **Features**: RR Interval, QT Interval, EDR
- **Validation**: Tested with different kernels (Linear, Quadratic, Cubic, Gaussian).

### Model Performance:
| **Model**        | **Accuracy**  |
|------------------|---------------|
| **Linear SVM**   | 52.6%         |
| **Quadratic SVM**| 88.6%         |
| **Cubic SVM**    | 97.2%         |
| **Gaussian SVM** | **98.6%**     |

## 📂 Documentation
- [📄 Base Paper](./path/to/basepaper.docx)  
  The base paper provides a detailed explanation of the methods, models, and results, including relevant research on biosignal-based stress detection.

## 🛠️ Tools & Technologies
- **Programming Languages**: MATLAB
- **Libraries**: Statistics and Machine Learning Toolbox
- **Database**: Physionet “drivedb” dataset
- **Algorithms**: Support Vector Machine (SVM)

## 📈 Results
The results indicate that the **Gaussian Kernel** outperforms other kernels in stress classification:

| **Model**        | **RR Interval** | **QT Interval** | **EDR**       | **Accuracy** |
|------------------|-----------------|-----------------|---------------|--------------|
| **Linear SVM**   | ✅              | ✅              | ✅            | 52.6%        |
| **Quadratic SVM**| ✅              | ✅              | ✅            | 88.6%        |
| **Cubic SVM**    | ✅              | ✅              | ✅            | 97.2%        |
| **Gaussian SVM** | ✅              | ✅              | ✅            | **98.6%**    |

## 🔧 How to Use the Model
1. **Create an Account** on the platform (optional).
2. **Upload ECG Data** in the required format.
3. **Run the Model** and analyze stress levels based on predictions.
4. **Review Results** for detailed information on stress levels detected.

## 👥 Contributors
- **Dr. V. Venkat Rao** - Associate Professor & HOD, Dept. of ECE
- **Dr. Sk. Ebraheem Khaleelullah** - Associate Professor, Dept. of ECE
- **G. Sai Prakash** - Dept. of ECE
- **P. Venkateswarlu** - Dept. of ECE
- **G. Harshitha** - Dept. of ECE
- **D. Abraham** - Dept. of ECE
- **G. Usha Sri** - Dept. of ECE
- **B. Raja Simha** - Dept. of ECE

## 📚 References
Check the base paper for the complete list of references and supporting research.

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](./LICENSE) file for details.
