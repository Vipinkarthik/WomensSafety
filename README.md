WomensSafety:

The Women's Safety System is an advanced application designed to enhance public safety for women through video surveillance and harassment detection. The system utilizes machine learning and AI models to analyze video files and detect instances of harassment. Built with Python, the project features a user-friendly interface powered by Tkinter, allowing users to upload video files for analysis. The backend employs deep learning models (harrassment_detection_model.h5 and non_harassment_model.h5), trained on a custom dataset, to classify video frames as harassment or non-harassment using TensorFlow/Keras. OpenCV is used for video preprocessing, extracting frames for analysis.

The application workflow begins with the user uploading a video via the Tkinter GUI, where it undergoes frame-by-frame analysis. Results are displayed in real-time, indicating whether harassment activity is detected. The project supports scalability, enabling future integrations with CCTV feeds for real-time monitoring and alert systems, such as SMS or email notifications. The system’s modular design allows for optional features like exporting reports for documentation or integrating advanced analytics for event-specific details.

The repository includes all necessary files, such as the trained AI models, video processing scripts, and GUI components. Users can clone the repository, install dependencies, and run the application with minimal setup. Additionally, the project emphasizes future enhancements, such as mobile app development, real-time CCTV integration, and advanced reporting capabilities. With its robust architecture and user-friendly design, the Women's Safety System represents a significant step toward leveraging technology for societal safety.







