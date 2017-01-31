Recognizr

Simple implementation of VGG-Metal on iOS 10 with swift 3

parameters.data can be downloaded from https://mega.nz/%23!fcFyGJBJ!5Zy47jS3xhHP-0CjEVg5CRzx1wF1itnf9AHVdeRBHYk , or be converted by yourself via convert_vggnet.py, and then put under the path ~/Recognizr-master/VGGnet/

Example: 
python3 convert_vggnet.py deploy.prototxt your.caffemodel ./output

Please note that only a VGG trained network can be successfully converted otherwise dimensions will not agree with each other. Also, DO NOT compile on iOS simulator.
