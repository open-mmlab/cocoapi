# Open-MMLab cocoapi
In this repo, we merged COCO and LVIS API into one repo.

Since the official cocoapi and lvis-api repos are out of maintainance,
we decided to have our own fork, which fixes bugs and compatability issues
with newer version of numpy.
Also we unify the api of COCO and LVIS, since they share similar functions.

Notes:
* We add snack case aliases for functions of [COCO](pycocotools/coco.py).

# Reference
* [cocoapi](https://github.com/cocodataset/cocoapi) of [COCO dataset](http://cocodataset.org/).
* [lvis-api](https://github.com/lvis-dataset/lvis-api) of [LVIS dataset](http://lvisdataset.org).
