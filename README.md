# mask-r-cnn-pytorch-sagemaker
Object instance segmentation is to detect objects in an image while simultaneously generate segmentation mask for each object detected. Customers use object instance detection in many use cases, such as defects detection in manufacturing, people detection, object tracking, and surveillance. We hear from our customers that they would like to bring object instance segmentation algorithms to SageMaker. In many cases, customer would like to customize their algorithm and bring it to SageMaker. 

In this blog, we use Mask R-CNN as an example, to demonstrate how to build your own Mask R-CNN container to train and serve on SageMaker. 

