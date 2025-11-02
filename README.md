### face-gate
A Python project that primarily uses OpenCV and the face-recognition library to detect faces, and Tkinter for the GUI.
To use, create a folder titled "faces" containing multiple images of your face taken under various lighting conditions. Then, run register.py to generate a pickle file containing your facial data.
### calibration.py
This script allows the user to view facial recognition confidence levels in real time. It can be used to test or calibrate the program.
### program.py
This script uses facial recognition to grant the user access to a "hub," where encrypted notes can be created using Fernet encryption keys. Currently, the key is stored in the file, but it can easily be moved to an environment variable for better security.
