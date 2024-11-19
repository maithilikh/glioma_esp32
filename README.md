Predictive classification model based on Glioma Grading data deployed on ESP32 board

- Data was preprocessed and analyzed in Python using the Pandas library.
- A binary classification neural network model was designed and trained using TensorFlow.
- The trained model was converted to TensorFlow Lite (TFLite) format and exported as a C header file.
- The C header file was integrated into an Arduino sketch (.ino file) and deployed to the ESP32 board using the EloquentTinyML library via the Arduino IDE.
