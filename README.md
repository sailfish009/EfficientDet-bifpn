this repo is based on mmdetection.

train efficientdet with the same number of iterations as tensorflow-efficientdet,  results are 2~4 mAP lower  
efficientdet-d2  40.4mAP batchsize=64 epoch=154  
efficientdet-d3  43.6mAP batchsize=32 epoch=115  
efficientdet-d5  47.4mAP batchsize=16 epoch=38  


i did not release code about EMA, which has little improvement for this repo(but ema can give a very good result for early epoch)

Please let me know any possible improvement
