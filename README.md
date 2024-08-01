# driver-drowsiness-detection


A system that alarms the driver as soon as it detects that the driver is becoming drowsy to prevent any accidents.

## Quick Start 🚀

### Clone this Repository

```sh
git clone https://github.com/adityajai25/driver-drowsiness-detection.git
Dataset
We used a dataset downloaded from Kaggle. The dataset is included in the repository, and you can also download it from this Kaggle link.

Creating a Virtual Environment
Windows
Open Command Prompt:

Press Win + R, type cmd, and press Enter.
Navigate to Your Project Directory:

sh
Copy code
cd path\to\your\project
Create a Virtual Environment:

sh
Copy code
python -m venv env
Activate the Virtual Environment:

sh
Copy code
env\Scripts\activate
macOS
Open Terminal:

Press Cmd + Space, type Terminal, and press Enter.
Navigate to Your Project Directory:

sh
Copy code
cd /path/to/your/project
Create a Virtual Environment:

sh
Copy code
python3 -m venv env
Activate the Virtual Environment:

sh
Copy code
source env/bin/activate
Installing Required Packages
Once the virtual environment is activated, install the required packages using the following commands:

Install Pygame:

sh
Copy code
pip install pygame==2.4.0
Install OpenCV-Python:

sh
Copy code
pip install opencv-python==4.6.0.66
Install NumPy:

sh
Copy code
pip install numpy==1.23.0
Install Keras:

sh
Copy code
pip install keras==2.12.0
Install TensorFlow:

sh
Copy code
pip install tensorflow==2.13.0
Execution
To start the project, navigate to the directory where the main file main.py is located, and run the script with the following command:

sh
Copy code
python main.py


It may take a few seconds to open the webcam and start detection.

