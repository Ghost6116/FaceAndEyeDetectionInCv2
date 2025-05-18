# FaceAndEyeDetectionInCv2

Python project for face and eye detection in `.mp4` videos using OpenCV.

## Setup

1. **Clone Repo**
   ```bash
   git clone https://github.com/Ghost6116/FaceAndEyeDetectionInCv2.git
   cd FaceAndEyeDetectionInCv2
   ```

2. **Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
   *Note*: Needs `opencv-python`, `numpy`.

4. **Add Test Video**
   - Place your `.mp4` video (e.g., `test.mp4`) in the project directory.

5. **Haar Cascade Files**
   - Ensure `haarcascade_frontalface_default.xml` and `haarcascade_eye.xml` are present ([OpenCV GitHub](https://github.com/opencv/opencv/tree/master/data/haarcascades)).

## Run

Detect faces and eyes:
```bash
python main.py --video test.mp4
```

## Output
- Video with detected faces/eyes saved in `output/` or displayed.

## Requirements
- Python 3.6+
- `opencv-python`, `numpy`

*Note*: Update `main.py` and `test.mp4` with actual names.
