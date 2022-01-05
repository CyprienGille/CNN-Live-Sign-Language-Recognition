# Sign Language Recognition using a CNN

> Note: This project was developed on and is meant to be used through the [Google Colab](https://colab.research.google.com/) platform.
> The code can be adapted with minimal changes, but will _not_ work directly on a local computer in its curent state
> (mainly because we make use of the computer's webcam with a javascript code snippet, and because we mount our drive folder to store and access the dataset).

## Files

- `Task6.ipynb` : This file contains the whole dataset creation pipeline (which was built through tasks 1 to 6, that's why we only include task 6 here). Face detection to get the correct color histogram to then perform camshift on the hand, and capture the letters.

- `Task78_Training_Testing.ipynb` : This notebook contains tasks 7 and 8: the training process (using the dataset captured in task 6) and the testing process.

- `haarcascade_frontalface_default.xml` : This face is the [Haar cascade](https://en.wikipedia.org/wiki/Viola%E2%80%93Jones_object_detection_framework) that we use to track the face initially.
