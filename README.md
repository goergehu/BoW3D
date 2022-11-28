# BoW3D
BoW3D is developed for the real-time loop closing in 3D LiDAR SLAM. It builds the bag of words for the **LinK3D Feature** **[PDF](https://arxiv.org/pdf/2206.05927.pdf)**, which is an efficient and robust 3D LiDAR point cloud feature. BoW3D is able to detect loops and correct the full 6-DoF loop relative pose for the subsequent pose graph optimization in real time. It also can be used to relocalization the 3D LiDAR in real time. We provide an example to run BoW3D on the [KITTI dataset](https://www.cvlibs.net/datasets/kitti/eval_odometry.php). For more details about BoW3D, please refer to our paper "BoW3D: Bag of Words for Real-Time Loop Closing in 3D LiDAR SLAM" in IEEE Robotics and Automation Letters (RA-L) **[PDF](https://arxiv.org/pdf/2208.07473.pdf)**.

## 1. Publication
If you use the code in an academic work, please cite:
<pre><code class="language-css">
@ARTICLE{9944848,
  author={Cui, Yunge and Chen, Xieyuanli and Zhang, Yinlong and Dong, Jiahua and Wu, Qingxiao and Zhu, Feng},
  journal={IEEE Robotics and Automation Letters}, 
  title={BoW3D: Bag of Words for Real-Time Loop Closing in 3D LiDAR SLAM}, 
  year={2022},
  volume={},
  number={},
  pages={1-8},
  doi={10.1109/LRA.2022.3221336}}
</code></pre>

## 2. Prerequisites
We have tested the library in Ubuntu 16.04, but it should be easy to compile in other platforms. A computer with an Intel Core i7 will ensure the real-time performance and provide stable and accurate results.

### C++11 and catkin_make Compiler
We use the catkin_make compiler of ROS to compile the BoW3D package.


