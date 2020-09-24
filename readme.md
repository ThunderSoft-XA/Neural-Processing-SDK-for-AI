## Neural Processing SDK for AI

#brief introduction
#Show the ability of training modle

#Environment configuration
#usage method
1、Installing the ADB tool
2、install Neural Processing SDK for AI
3、insatll caffe and TensorFlow
4、Run:python ./models/alexnet/scripts/setup_alexnet.py -a ./temp-assets-cache -d or python ./models/inception_v3/scripts/setup_inceptionv3.py -a ./temp-assets-cache -d
5、 python $SNPE_ROOT/models/alexnet/scripts/show_alexnet_classifications.py -i data/cropped/raw_list.txt \
                                                                         -o output/ \
                                                                         -l data/ilsvrc_2012_labels.txt

python $SNPE_ROOT/models/inception_v3/scripts/show_inceptionv3_classifications.py -i data/cropped/raw_list.txt \
                                                                                  -o output/ \
                                                                                  -l data/imagenet_slim_labels.txt

6、Then,you will see the result.
