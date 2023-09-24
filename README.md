# Face_Recognition_Program
 
This repository contains a face recognition program implemented in C++, Java, and Python using the OpenCV library. The program compares images to perform facial recognition and detects matches between the images. The program is containerized using Docker for easy deployment and portability. 
 
## Installation 
 
1. Clone the repository:
git clone <repository_url>
2. Install Docker: 
 
   - Follow the official Docker installation guide: [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/) 
 
## Usage 
 
### C++ 
 
1. Build the Docker image for the C++ version:
docker build -t face-recognition-cpp -f Dockerfile.cpp .
2. Run the Docker container for the C++ version:
docker run -it face-recognition-cpp
### Java 
 
1. Build the Docker image for the Java version:
docker build -t face-recognition-java -f Dockerfile.java .
2. Run the Docker container for the Java version:
docker run -it face-recognition-java
### Python 
 
1. Build the Docker image for the Python version:
docker build -t face-recognition-python -f Dockerfile.python .
2. Run the Docker container for the Python version:
docker run -it face-recognition-python
