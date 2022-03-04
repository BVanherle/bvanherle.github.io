# Synthetic tool dataset

This dataset contains synthetically generated images of four tools as well as a test set of real images for each tool. The images are annotated with keypoint locations and bounding boxes.

This file sturcture looks like this:
```
SyntheticTools
- Hammer
- Wrench
- CombWrench
- Wrench
  - real
  - synthetic
    annotations.json
    - images
```

The annotaion file has the following layout:
```
{
  "keypoint_names": [
    "Keypoint"
  ],
  "images": [
    {
      "image": "0_img.png",
      "keypoints": {
        "Keypoint": [324.4769287109375, 106.1048583984375]
        },
      "bounding_box": [321, 105, 395, 287]
    }
  ]
}
```
