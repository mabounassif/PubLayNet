# PubLayNet

PubLayNet is a large dataset of document images, of which the layout is annotated with both bounding boxes and polygonal segmentations. The source of the documents is [PubMed Central Open Access Subset (commercial use collection)](https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/). The annotations are automatically generated by matching the PDF format and the XML format of the articles in the PubMed Central Open Access Subset. More details are available in our paper ["PubLayNet: largest dataset ever for document layout analysis."](https://arxiv.org/abs/1908.07836)

## Getting data

Images and annotations can be downloaded from this [Box folder](https://ibm.box.com/s/ph19ku47eahazje4caijlmnmcwa20v9o)

NOTE: Due to the [Box limitation (10GB) on downloading shared files](https://community.box.com/t5/How-to-Guides-for-Account/Understand-How-Box-Measures-Bandwidth-Usage/ta-p/44), you may not be able to download the training images now. We are trying to work out a solution ASAP. Apologies for any inconvience.

## Annotation format

The annotation files follows the [json format of the Object Detection task of MS COCO](http://cocodataset.org/#format-data)
