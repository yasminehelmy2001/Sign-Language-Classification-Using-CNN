# Sign-Language-Classification-Using-CNN

**Problem Statement:** People who suffer from mutism are unable to blend into the community. They use hand signs to communicate, hence normal people face problems trying to understand them. AI technologies can play a crucial role in breaking down these communication barriers, it can contribute significantly to their social inclusion. In the wake of this news, our team has decided to carry this project.

**Motivation:** Communication is one of the basic requirements for survival in society. Our main goal is to make these people feel included, and cared for so that they can blend into the community and show their skills.

**Data Description:** Our data consists of 24 letters of the English sign language pictures. Their pixels were set into CSV files.

**Model 1 Hyper Parameters:**
One Convolution Layer (Filter 3x3)
One Pooling Layer (Filter 2x2)
One Hidden Layer of 512 Neurons
Output Layer of 24 Neurons For 24 Letters

**Model 2 Hyper Parameters:**
Three Convolution Layers (Filter 3x3)
Three Pooling Layers (Filter 2x2)
One Hidden Layer of 512 Neurons
Output Layer of 24 Neurons For 24 Letters

**Model 3 Hyper Parameters:**
Three Convolution Layers (Filter 3x3)
Three Pooling Layers (Filter 2x2)
Two Hidden Layers of 512 Neurons & 256 Neurons
Output Layer of 24 Neurons For 24 Letters

**Comparison:**
MODEL ONE: Although the validation accuracy increased with epochs, it only reached 0.8779.
MODEL TWO:Increasing the number of covolution & pooling layers has affected the validation accuracy that it jumped to 0.9497.
MODEL THREE: Adding more hidden layers i.e More neurons, the validation accuracy has shown greater improvement. It rose to 0.9780.
This has proved that as the number of layers, and filters increase, also as different activation functions are put to trial with different types of data, the accuracy increases.
