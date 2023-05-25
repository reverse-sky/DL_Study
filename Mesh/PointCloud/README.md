
# Classification
[Point_net_classification.ipynb](./Point_net_classification.ipynb)  
> ploly를 사용하여 classification을 진행하였다. 핵심은 mesh data를 point cloud로 바꾸는 point sampler가 핵심 
> data type은 off 

# segmentation
[Point_seg.ipynb](./Point_seg.ipynb)
> point net을 바탕으로 segmentation을 진행한다. 
> 데이터 타입은 .pts(point cloud) , .seg(label)로 되어있다. 
> 한개의 class(e.g. Airplane)에 대한 segmentataion은 이해가 되지만, multi class의 경우는 따로 전처리가 필요 할 것 같음 
