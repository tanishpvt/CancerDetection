# CancerDetection

https://user-images.githubusercontent.com/66123919/164886408-ee0464af-9ed0-4e9c-a56d-30187face51c.mp4


Problem statement:<br>
Normal people cannot determine whether the MRI scan has a tumor in it, even the doctors seem to miss it some times. Brain tumor is a dangerous condition, it must be resolved as immediate as possible, but due to human error and negligence the situation may escalate.

Solution and Aim:<br>
We have put up a AI algorithm which determines whether there is a indication of tumor in the MRI scans. 
We have integrated it into mobile app so that every one can use it, to confirm their suspicion, if any

1) it is extracting features from our image,
let sat we have image of brain ... so we have different filters to take extract different features of a brain area like its tumors will be dark area (whose are important) once this is done then we are doing max-pooling across.

we then flattened the output of convolution layer to create a single long feature vector and...it is connected to final classification model which is called fully connected layer

2) on preprocessing we did:
we did coutouring, cropping and resizing and normalizationon processing image segmentation and our cnn algorithm is applied later
