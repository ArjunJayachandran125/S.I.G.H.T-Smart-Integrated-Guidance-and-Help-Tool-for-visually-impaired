## Features
- **Object Detection**: Detects objects in the surroundings and alerts the user.  
- **Collision Avoidance**: Uses ultrasonic sensors to prevent obstacles in the walking path.  
- **Optical Character Recognition (OCR)**: Reads printed text (books, signs, documents) and converts it into speech.  
- **Emotion Detection**: Identifies human emotions using a trained deep learning model.  
- **Audio Feedback**: All modules give real-time voice guidance to the user.  

## Hardware
- Raspberry Pi 4 (64-bit)  
- Ultrasonic sensors  
- USB/Camera Module  
- Microphone & Speaker  
- Power supply (portable battery pack)  

## Software & Libraries
- Python 3.13  
- TensorFlow / Keras (for emotion & object detection models)  
- OpenCV (computer vision tasks)  
- Tesseract OCR (text recognition)  
- Pyttsx3 / gTTS (text-to-speech)  
- RPi.GPIO (hardware interfacing with sensors & switches)  

## Working
1. The user wears the smart cap.  
2. Based on the physical switch pressed, the corresponding module is activated:  
   - **Object Detection** → Camera detects objects and announces them.  
   - **Collision Avoidance** → Ultrasonic sensors measure distance and alert if too close.  
   - **OCR** → Captures text, extracts it using Tesseract, and speaks it aloud.  
   - **Emotion Detection** → Captures face, predicts emotion, and informs the user.  
3. The Raspberry Pi processes data and provides real-time **audio output**.  

## Future Scope
- Integrating GPS for outdoor navigation.  
- Adding cloud-based support for remote monitoring.  
- Improving deep learning models for higher accuracy.
- Include Language Translation.

## Authors
Developed as a final-year project @ NIT Calicut.  
Team: Arjun Jayachandran & collaborators.  
