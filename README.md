Description 

## Project: Lotr Face Recognition 

This project demonstrates real-time face recognition in a video while identifying and handling unknown faces. It utilizes Python libraries like OpenCV, face_recognition, and cvzone for efficient processing and visualization.

**Key Features:**

- Identifies known faces from a pre-built encoding database.
- Labels unknown faces as "Unknown" based on a distance threshold.
- Plays audio announcements using pyttsx3 (optional).
- Offers speed optimizations like frame skipping and resizing.

**Requirements:**

- Python 3.x
- OpenCV
- face_recognition
- cvzone
- pyttsx3 (optional)

**Setup:**

1. Install required libraries using `pip install opencv-python face_recognition cvzone pyttsx3`.
2. Prepare your dataset with images of known faces, each in a separate folder.
3. Generate encodings from your dataset using the provided script `encode_faces.py`.
4. Place the "EncodeFile1.p" file containing encodings in the project directory.
5. Replace the video path `"Kara Kapılar.mp4"` in the main script with your desired video.

**Running the Project:**

1. Run the main script `main.py` from the terminal.
2. The script will read the video, detect faces, match them to known encodings, and display names or "Unknown" labels.
3. Press `q` to quit the program.

**Read Me Content:**

**Getting Started:**

- Provide installation instructions with library versions.
- Explain dataset preparation and encoding generation process.
- Guide users on replacing the video path.

**Features:**

- Describe known face recognition functionality.
- Explain unknown face detection and labeling.
- Mention optional audio announcement feature.

**Usage:**

- Provide detailed instructions on running the script and interacting with the program.

**Customization:**

- Explain adjusting the unknown face detection threshold (`facedis < 0.70` in code).
- Mention other potential customizations like audio configuration.

**Additional Notes:**

- Briefly discuss performance optimizations used (frame skipping, resizing).
- Acknowledge potential limitations based on dataset quality and threshold selection.
- Include contribution guidelines if open to code contributions.

**GitHub Repository:**

- Structure the repository with clear folder organization.
- Include all necessary files (scripts, encodings, README).
- Add a license file like MIT or Apache 2.0.

**Remember:**

- Replace placeholders like `"C:/Users/KAAN/Desktop/Lotr Data"` with your specific paths.
- Consider providing a Dockerfile for easy setup in different environments.
- Regularly update the README with project changes and improvements.

I hope this comprehensive response helps you create a well-structured and informative README for your GitHub project!

![,output 4](https://github.com/ARAGORN1453/Lord-of-The-Rings-Face-Recognition-/assets/119515258/64b79fd7-84a0-4d05-b9a7-368fd956b2cf)

![output 3](https://github.com/ARAGORN1453/Lord-of-The-Rings-Face-Recognition-/assets/119515258/e73e1494-3792-44ee-80a6-e2dbc5c2e551)

![Output2](https://github.com/ARAGORN1453/Lord-of-The-Rings-Face-Recognition-/assets/119515258/8ab387c0-9fcf-4274-a4a4-56c1ef3e9f63)





