# Covid-protocol-detection

The Covid-19 pandemic has brought the world to a standstill, and governments and healthcare professionals worldwide have been grappling with measures to contain the spread of the virus. One of the most effective ways to control the spread is through social distancing measures. However, it is often challenging to enforce social distancing in public places, especially when large numbers of people gather in a confined space. To tackle this problem, we propose a Covid protocol detection system using YOLO3 and OpenCV.


The system employs a YOLO3 (You Only Look Once) object detection algorithm, which can identify humans in a given image or video feed. By using this algorithm, we can detect the distance between individuals in a public space and determine whether they are following the recommended social distancing guidelines. If two individuals are too close to each other, the system will raise an alert and notify the authorities. The system also creates a database to store the images or videos and the distance metrics for further analysis.


To implement the system, we use OpenCV, an open-source computer vision and machine learning software library. The library provides us with the necessary tools to process images and videos, extract relevant features, and train machine learning models. We use a pre-trained YOLO3 model, which has already been trained on a large dataset of images to recognize different objects. However, we need to fine-tune the model to identify humans and measure the distance between them accurately.


The proposed system can be used in a wide range of scenarios, such as airports, shopping malls, and public transport. It can also be integrated with existing security systems to enhance surveillance measures and detect potential Covid-19 transmission hotspots. The system is designed to be cost-effective, and the technology used is widely available, making it easy to implement in a real-world setting.
