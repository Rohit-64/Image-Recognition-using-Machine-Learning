<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   

</head>
<body>

  <h1>Real-Time Face Recognition with OpenCV and face_recognition</h1>

  <p>This project uses a webcam to capture real-time video, detect faces, and match them to known individuals using the <code>face_recognition</code> and <code>OpenCV</code> libraries. The recognized faces are labeled with names in the video feed.</p>

   <h2>Features</h2>
    <ul>
        <li>Real-time face detection and recognition.</li>
        <li>Matches faces against a predefined set of known faces.</li>
        <li>Displays bounding boxes and names for recognized faces.</li>
        <li>Easy to extend with more known faces by simply adding images.</li>
    </ul>
    <h2>Requirements</h2>
    <p>To run this project, ensure you have the following dependencies installed:</p>
    <ul>
        <li>Python </li>
        <li>OpenCV</li>
        <li>face_recognition</li>
        <li>NumPy</li>
    </ul>
    <div class="command">
        <strong>Install required packages:</strong>
        <pre><code>pip install opencv-python face-recognition numpy</code></pre>
    </div>

  <h2>How It Works</h2>
    <p>The program performs the following steps:</p>
    <ul>
        <li>Captures video from the default webcam.</li>
        <li>Loads and encodes known face images from the <code>face_images</code> folder.</li>
        <li>Detects faces in each frame and computes the encodings for the detected faces.</li>
        <li>Compares the detected faces against known faces and displays the name of the person (or "Unknown") in the video feed.</li>
    </ul>
    <h2>Usage</h2>
  <p>Add images to the <code>face_images</code> folder with filenames that correspond to the person’s name (e.g., <code>john_doe.jpg</code>).</p>
    <p>Press <strong>q</strong> to quit the video feed.</p>

   <h2>Dependencies</h2>
    <p>This project requires the following libraries:</p>
  <ul>
        <li><code>OpenCV</code> – For capturing and processing video.</li>
        <li><code>face_recognition</code> – For face detection and recognition.</li>
        <li><code>NumPy</code> – For handling array operations.</li>
    </ul>

</body>
</html>
