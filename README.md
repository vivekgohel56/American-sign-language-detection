# American-sign-language-detection
Dataset_source:- https://www.kaggle.com/datamunge/sign-language-mnist

The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion),

The training data has 27,455 cases and test data has 7172 cases with a header row of label, pixel1,pixel2….pixel784 which represents a single 28x28 pixel image with grayscale values between 0-255,

A robust visual recognition algorithm could provide not only new benchmarks that challenge modern machine learning methods such as Convolutional Neural Nets but also could pragmatically help the deaf and hard-of-hearing better communicate using computer vision applications,

After training on train data with a simple CNN model it gives 99.99% accuracy on test data and I had also plotted the test image from the test dataset with the title of predicted_value and true_value so that we can see that the image recognized is correct or not.
