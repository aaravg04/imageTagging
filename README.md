# imageTagging
given a library of images and sentences describing them, first reduce the sentence descriptions to keywords and then train an algorithm to perform multi-classification on those images

note: the majority of my progress so far is being done on a private notebook on Kaggle as it's a lot of data processing (soon to be machine learning/cv algorithms which my poor laptop cannot handle) and when I have a working piece of the project I'll push it to this repository (i.e. the keyword isolation from the captions)

# Todo/Project Status
* [x] isolate keywords from provided 5 captions per image in flickr30k dataset
* [ ] LATER -> fine tune keywords to provide more useful ones (i.e. for an image of men at a garden, the keyword "green" might not be as useful as "man", "bushes", "garden")
* [ ] multiclassification computer vision network (given a set of images, each with several keywords, assign keywords to a new image) -> combination of object detection for items (table, laptop, handbag, dog, cat, etc.) and something else to pull information from the background? looking into papers on image tagging algorithms/pipelines for guidance
* [ ] desktop application for folder to be selected, automatically tagged efficiently (probably dictionary/hashmap based for fast retrieval), and searching -> likely trivial, just pyqt5 
