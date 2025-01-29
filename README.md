# BrainApp

This project is a web application built with React that allows users to paste image links, and then uses an AI API to detect faces within those images.  It provides a simple and efficient way to identify and locate faces in photos. This Repo only has API code

## How it works

1. **Login:** Users can log in to access the face detection functionality.

2. **Image Input:**  Users can provide images to the application by:
    * **Paste Link:** Users can paste a direct link to an image hosted online.

3. **Face Detection:** Once an image is provided, the application utilizes an AI API to process the image and identify any faces present.

4. **Results:** The application then displays the original image with bounding boxes drawn around each detected face, visually highlighting the identified faces.

## Features

* **Image Link Support:**  Conveniently process images directly from the web.
* **AI-Powered Face Detection:**  Accurate and efficient face identification.
* **Visual Results:** Clear display of identified faces with bounding boxes.

## Technologies Used

* React
* Clarifai API
* postgres DB
