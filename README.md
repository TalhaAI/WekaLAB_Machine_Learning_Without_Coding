# WekaLAB Design Project

## How to AI if you can’t code and don’t have GPU

### Advisors
- **Advisor:** Dr. Wajahat Hussain
- **Co-Advisor:** Dr. Abid Rafique

### Author
- **Talha Anwar (307793)_EE-12D**

### Institution
- **Bachelors of Electrical Engineering**
- **School of Electrical Engineering and Computer Sciences (SEECS)**
- **National University of Sciences and Technology (NUST)**

---

## Abstract
In today's technological world, machine learning (ML) is crucial in almost every field. However, it is challenging for non-technical individuals to apply ML due to the required coding skills and computational resources. This project presents WekaLab, an innovative graphical user interface platform that simplifies the creation and evaluation of ML models. WekaLab leverages Google Colab's processing power, making ML accessible without advanced computational resources or programming expertise. WekaLab includes three modules: CNN Module, RNN Module, and Pre-Trained Module. Comparative analysis with tools like WEKA and Google AutoML demonstrates WekaLab's efficiency and scalability in ML tasks, making it a powerful tool for democratizing ML usage.

## Introduction
Machine Learning (ML) often requires coding skills and computational resources, posing a barrier for non-technical individuals. Existing tools like WEKA and Google AutoML offer solutions but come with limitations. WEKA, an open-source tool developed by the University of Waikato, provides a GUI for ML but relies on personal computers' processing power, making it inefficient for large datasets. Google AutoML, although accessible and powerful, is a paid tool, which may not be affordable for everyone. WekaLab aims to bridge this gap by offering a free, easy-to-use ML platform leveraging Google Colab's computational resources.

## Methodology
WekaLab is developed on Google Colab and consists of three main modules:
1. **CNN Module**
   - Mounts Google Drive for dataset access.
   - Converts images to CSV files.
   - Splits dataset into train/test sets.
   - Allows addition of layers and adjustment of hyperparameters.
   - Trains and evaluates CNN models.

2. **Pre-Trained Module**
   - Loads image datasets from Google Drive.
   - Converts images to CSV files.
   - Provides a selection of pre-trained models (e.g., VGG19, ResNet50).
   - Trains models with adjustable epochs and batch sizes.

3. **RNN Module**
   - Loads sequential datasets.
   - Allows addition of layers.
   - Trains and evaluates RNN models.

## Project Description

### CNN Module
1. Run the CNN Module code.
2. Mount Google Drive and enter the image dataset folder name.
3. Convert images to CSV files.
4. Adjust test size and input shape.
5. Load dataset, split into train/test, resize images, and apply label encoding.
6. Add and configure layers (Convolution, Subsampling, Dense, Activation, Dropout, Batch Normalization, Flatten).
7. Adjust epochs and batch size.
8. Select optimizer and loss function.
9. Train the model.

### Pre-Trained Module
1. Enter image dataset folder name from Google Drive.
2. Convert images to CSV files.
3. Select pre-trained models from the dropdown menu.
4. Adjust epochs and batch sizes.
5. Train the model.

### RNN Module
1. Select dataset from the dropdown menu.
2. Load the dataset.
3. Add layers and configure them.
4. Train the model.
5. Show model summary.

## Results
### CNN Module
The CNN module successfully solved a cancer classification problem with a model consisting of four layers: Convolution, Subsampling, Flatten, and Dense. The model trained within seconds, demonstrating WekaLab's time efficiency compared to WEKA, which takes significantly longer.

### Pre-Trained Module
The pre-trained module significantly reduces loading time for models like VGG19 compared to WEKA. WekaLab's pre-trained module offers time efficiency and accuracy, making it advantageous over both WEKA and Google AutoML.

### RNN Module
The RNN module, although limited, effectively handles sequential datasets. Future development can expand its capabilities.

## Future Recommendations
- Combine all modules into a single web or application interface.
- Develop a preprocessing module to handle necessary preprocessing steps.
- Expand the CNN module to include image segmentation and detection.
- Enhance the RNN module to handle more complex tasks.

## Conclusion
WekaLab addresses the computational and financial constraints of existing ML tools, making machine learning accessible to a broader audience. By leveraging Google Colab's processing power, WekaLab offers an efficient and cost-effective solution for non-technical users to implement machine learning.

## References
- [WEKA](https://waikato.github.io/weka-site/index.html)
- [Google AutoML](https://cloud.google.com/automl)
- [Google Cloud](https://cloud.google.com/)

## Project Files
- [WekaLAB Design Project Report](./docs/WekaLAB%20Design%20Project%20Report.pdf)
