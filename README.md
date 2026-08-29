# mask-rcnn-taobao-object-detection

`my_test.py` in the root directory is used for model training, while `demo.py` is used for inference.

The dataset is included in the `Live_dataset` directory, which contains both the training and test sets. Note that the test set used in this project is a subset of the training set.

**Training with `my_test.py`:**

```bash
python my_test.py train --dataset=D:\python\Mask_RCNN\Mask_RCNN\Live_dataset\image --weights=coco
````

The `--dataset=` argument should be modified to the local path of the training images, specifically the `Live_dataset\image` directory in this repository.

**Inference with `demo.py`:**

```bash
python demo.py
```

**Example results:**

![](https://github.com/739982423/mask-rcnn-taobao-object-detection/blob/master/Live_dataset/example.png)

![](https://github.com/739982423/mask-rcnn-taobao-object-detection/blob/master/Live_dataset/example1.png)
