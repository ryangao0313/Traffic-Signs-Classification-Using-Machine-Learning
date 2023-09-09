
# Traffic Sign Recognition using Convolutional Neural Networks

This Python script implements a Convolutional Neural Network (CNN) to recognize traffic signs. It uses the German Traffic Sign Recognition Benchmark dataset.

## Requirements

- Python 3
- TensorFlow
- NumPy
- OpenCV
- Matplotlib
- Pillow (PIL)

You can install the required libraries using `pip`:

```bash
pip install tensorflow numpy opencv-python-headless matplotlib pillow
```

## Usage

1. Clone this repository to your local machine.

2. Download the [German Traffic Sign Recognition Benchmark dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) and extract it to a folder (e.g., `archive`).

3. Open the script (`traffic_sign_recognition.py`) and make sure to set the correct path to your dataset:

```python
# Set the path to your dataset folder
dataset_path = '/path/to/your/dataset'
```

4. Run the script using a Python interpreter:

```bash
python traffic_sign_recognition.py
```

5. The script will preprocess the data, build and train a CNN model, display training performance graphs, and evaluate the model's accuracy on the test dataset.

6. The trained model will be saved as `traffic_classifier.keras` for future use.

## Customization

You can customize the script by changing the model architecture, hyperparameters, or preprocessing steps as needed for your specific use case.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project demonstrates the use of Convolutional Neural Networks (CNNs) for traffic sign recognition.
- Thanks to the authors of the German Traffic Sign Recognition Benchmark dataset for providing the data for this project.
```

Feel free to modify and expand this README file as needed, especially if you want to provide more details about the project, the dataset, or any additional instructions for users.
