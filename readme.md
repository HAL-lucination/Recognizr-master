{\rtf1\ansi\ansicpg1252\cocoartf1504\cocoasubrtf760
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;\f1\fnil\fcharset0 Consolas;}
{\colortbl;\red255\green255\blue255;\red38\green38\blue38;\red245\green245\blue245;}
{\*\expandedcolortbl;;\cssrgb\c20000\c20000\c20000;\cssrgb\c96863\c96863\c96863;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs32 \cf2 \expnd0\expndtw0\kerning0
Recognizr\
\
Simple implementation of VGG-Metal on iOS 10 with swift 3\
\
parameters.data can be downloaded from https://mega.nz/%23!fcFyGJBJ!5Zy47jS3xhHP-0CjEVg5CRzx1wF1itnf9AHVdeRBHYk , or be converted by yourself via convert_vggnet.py, and then put under the path ~/Recognizr-master/VGGnet/\
\
Example: \
\pard\pardeftab720\partightenfactor0

\f1\fs27\fsmilli13600 \cf2 \cb3 python3 convert_vggnet.py deploy.prototxt your.caffemodel ./output\
\pard\pardeftab720\partightenfactor0

\f0\fs32 \cf2 \cb1 \
Please note that only a VGG trained network can be successfully converted otherwise dimensions will not agree with each other. Also, DO NOT compile on iOS simulator.}