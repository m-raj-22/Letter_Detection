
# Letter Detection using Tkinter

This project is a simple letter/digit detection application built using Python, Tkinter, and Keras. The application allows users to draw digits on a canvas, and it predicts the digit using a pre-trained model on the MNIST dataset.

## Features

- **Draw on Canvas**: Users can draw digits on a 300x300 pixel canvas.
- **Real-time Prediction**: The application predicts the drawn digit with the confidence level displayed.
- **Clear Canvas**: Users can clear the canvas to draw a new digit.


## Usage

Run the application using the following command:

```bash
python app.py
```

### Drawing and Predicting

1. Use your mouse to draw a digit on the canvas.
2. Click the "Recognise" button to see the prediction and confidence level.
3. Use the "Clear" button to clear the canvas and draw another digit.

## Project Structure

- **app.py**: The main application file that contains the Tkinter interface and prediction logic.
- **mnist.h5**: The pre-trained model file (not included in the repository).

## Requirements

- Python 3.x
- Keras
- Tkinter
- NumPy
- Pillow
- win32gui (for capturing the canvas)

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

Created by Raj Mehta
