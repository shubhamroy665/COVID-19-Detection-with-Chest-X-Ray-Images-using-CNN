# COVID-19 Detection with Chest X-Ray Images

The novel Coronavirus (COVID-19), first identified in Wuhan, China in December 2019, has since become a global pandemic. With over 30 million infections and approximately 940,651 deaths worldwide, the urgent need for effective diagnostic tools is evident. The shortage of testing kits and resources in many regions has highlighted the necessity for innovative solutions. This project focuses on leveraging deep learning to assist radiologists and clinicians in diagnosing COVID-19 from chest X-ray images.

![COVID-19 Detection using CNN](https://github.com/aviralchharia/COVID-19/blob/master/Detecting%20COVID-19%20with%20Chest%20X-Ray%20Images%20using%20CNN.jpg?raw=true)

## Model Overview

I employed a Convolutional Neural Network (CNN) model trained on a COVID-19 Radiography dataset containing chest X-rays to detect COVID-19 infections. The model achieved approximately 98% accuracy on the validation set, demonstrating strong alignment with clinical findings from radiologists.

### Results

- **Confusion Matrix**

  ![Confusion Matrix](https://github.com/aviralchharia/COVID-19/blob/master/Results%20Obtained/Confusion%20Matrix.png?raw=true)

- **Training and Validation Accuracy**

  ![Training & Validation Accuracy](https://github.com/aviralchharia/COVID-19/blob/master/Results%20Obtained/Training%20&%20Validation%20Accuracy.png?raw=true)

- **Training and Validation Loss**

  ![Training & Validation Loss](https://github.com/aviralchharia/COVID-19/blob/master/Results%20Obtained/Training%20&%20Validation%20Loss.png?raw=true)

## Future Work

Ongoing efforts include enhancing the model for high-accuracy multi-class classification of X-rays. The aim is to develop a comprehensive computer-aided diagnosis system that can also identify the extent of lung damage caused by COVID-19.

## References

- Dataset: [COVID-19 Radiography Dataset](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)
- Research Paper: [Deep Learning for COVID-19 Detection](https://arxiv.org/abs/2002.09334)

## Installation

To run this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/COVID-19-Detection.git
cd COVID-19-Detection
pip install -r requirements.txt
