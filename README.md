# dataset-correction-tools-and-extensions
This repositorty contains some corrections made to the handgesture dataset described in "http://sun.aei.polsl.pl/~mkawulok/gestures/".
We extendend the HGR2B dataset with its missing keypoints and made corrections to some inaccurately annotated ones.
These extensions and corrections can be found in the folder namend "dataset_correction".
Also some tools to visualise the dataset are included.

We created a new feature for the libhand tool (http://www.libhand.org/).
Pressing "k" will now rotate the camera 180 degrees around the handmodel.
First around the models x-axis and second around its y-axis.
Rendering and saving the handpose every 10-degrees of rotation.
The adjusted source-coude can be found in the "libhand_custom_feature" folder.
