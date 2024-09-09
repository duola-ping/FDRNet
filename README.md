# FDRNet
Code for TCSVT 2024 paper "Edge Perception Camouflaged Object Detection under Frequency Domain Reconstruction"
> Camouflaged object detection has been considered a challenging task due to its inherent similarity and interference from background noise. It requires accurate identification of targets that blend seamlessly with the environment at the pixel level. Although existing methods have achieved considerable success, they still face two key problems. The first one is the difficulty in removing texture noise interference and thus obtaining accurate edge and frequency domain information, leading to poor performance when dealing with complex camouflage strategies. The latter is that the fusion of multiple information obtained from auxiliary subtasks is often insufficient, leading to the introduction of new noise. In order to solve the first problem, we propose a frequency domain reconstruction module based on contrast learning, through which we can obtain high-confidence frequency domain components, thus enhancing the model's ability to discriminate target objects. In addition, we design a frequency domain representation decoupling module for solving the second problem to align and fuse features from the $RGB$ domain and the reconstructed frequency domain. This allows us to obtain accurate edge information while resisting noise interference. Experimental results show that our method outperforms 12 state-of-the-art methods in three benchmark camouflaged object detection datasets. In addition, our method shows excellent performance in other downstream tasks such as polyp segmentation, surface defect detection, and transparent object detection.

By Zijian Liu

# Code
The code is coming soon
# Visualization results

The results of our method on the CAMO COD10K and NC4K datasets can be found in https://pan.baidu.com/s/122LumUto3DktvsPmei2UWQ     (PVT)

The results of res2net as a backbone network are in https://pan.baidu.com/s/1IjMMMG3hD66b98uPpJz_MA?pwd=p82e 
### Citation
```
  @article{liu2024edge,
  title={Edge Perception Camouflaged Object Detection under Frequency Domain Reconstruction},
  author={Liu, Zijian and Deng, Xiaoheng and Jiang, Ping and Lv, Conghao and Min, Geyong and Wang, Xin},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2024},
  publisher={IEEE}
}
```
### License
Our code is released under MIT License.
