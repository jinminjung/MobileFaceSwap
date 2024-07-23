# MobileFaceSwap

### [MobileFaceSwap: A Lightweight Framework for Video Face Swapping (AAAI 2022)](https://arxiv.org/abs/2201.03808)
--- 

**Dependencies**
- paddlepaddle==2.6.1
- insightface==0.2.1
- opencv-python
- numpy

```
python image_test.py --target_img_path data/xxx.png --source_img_path data/xxx.png --output_dir results --use_gpu True

python video_test.py --target_video_path data/xxx.mp4 --source_img_path data/xxx.png --output_dir results --use_gpu True
```

**Citation**
```
@inproceedings{xu2022MobileFaceSwap,
  title={MobileFaceSwap: A Lightweight Framework for Video Face Swapping},
  author={Xu, Zhiliang and Hong, Zhibin and Ding, Changxing and Zhu, Zhen and Han, Junyu and Liu, Jingtuo and Ding, Errui},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  year={2022}
}
```
