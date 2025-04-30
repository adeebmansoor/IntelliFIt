# IntelliFit: An AI Powered Fitness Companion

## Desciption

Intellifit’s AI-driven performance evaluation and correction system provides professional-grade workout assistance by leveraging deep learning, pose estimation, and motion analysis. Using real-time video input from a camera, it employs frameworks like MediaPipe and OpenCV to detect key skeletal landmarks, analyzing them against an extensive database of ideal exercise forms. This allows Intellifit to identify deviations in posture, joint angles, or balance and deliver instant corrective feedback through visual, auditory, or haptic alerts.

Beyond form correction, Intellifit tracks performance metrics such as range of motion, speed, and consistency, offering personalized recommendations based on fitness levels and goals. By ensuring proper execution, minimizing injury risks, and adapting to user progress, Intellifit transforms workouts into safe, efficient, and results-driven experiences with real-time, AI-powered precision. 

## 📁 Project Structure
ai-pose-reps-tracker/
~ ai pose and reps tracker.ipynb
~ README.md (you are here)

## 🚀 How to Set Up and Run the Project

1. **Clone or Download the Project**
   ```bash
   git clone https://github.com/divyaanshitoria/iNtellifit_Ai_Fitness_companion/
   cd ai-pose-reps-tracker
   ```

2. **Create and Activate a Python Virtual Environment (Recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install mediapipe opencv-python numpy matplotlib
   ```

4. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook "ai pose and reps tracker.ipynb"
   ```

5. **Using the Tracker**
   - Ensure your webcam is active.
   - Run the cells in order.
   - A window will appear showing a live feed with pose landmarks.
   - Press `Q` to quit the window.


## 📦 Dependencies

- `mediapipe`
- `opencv-python`
- `numpy`
- `matplotlib`
- (Optional) `jax`, `protobuf`, `sounddevice`, etc., via MediaPipe

Install them with:
```bash
pip install mediapipe opencv-python numpy matplotlib
```

## 🧠 Features

- Real-time webcam video capture
- Pose detection and landmark drawing
- Foundational structure for:
  - Joint angle analysis
  - Repetition counting logic


## 📸 Screenshots / Demo

You can capture screenshots using your system while the webcam feed is running. A screenshot might look like this:

>
![image](https://github.com/user-attachments/assets/ce3fa154-6c5a-4416-940e-4b051a093f18)


## 🔧 Configuration

No special configuration needed. Just ensure:
- Webcam is connected and accessible
- Python 3.8+ is installed
- All dependencies are installed
