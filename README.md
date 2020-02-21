# Mask RCNN



## > balloon.py

balloon  dataset:   <https://github.com/matterport/Mask_RCNN/releases>  



### Training

```
$ python balloon.py train --dataset='<add>/balloon' --weights=coco --logs='<add>/weights'
```



### Testing

```
$ python balloon.py splash --weights='<add>/mask_rcnn_balloon_0030.h5' --image='<add>/balloon/val/410488422_5f8991f26e_b.jpg'
```



**![balloon_result](Mask_RCNN/Mask_RCNN/ballon_result2.JPG)**







