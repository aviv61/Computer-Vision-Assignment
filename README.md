# Computer-Vision-Assignment

Installation guide:
Google  Colab Environment
run these lines:
!pip install pyyaml==5.1
!pip install torch==1.8.0+cu101 torchvision==0.9.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html
!pip install detectron2 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.8/index.html

uncomment the first cell in Preparing CoCO Dataset.

The submission contains two parts:

The first part is the complete task, using two models I preform crop to the Dataset and make a skyless images

The second part is inference to show with the visualization the progress after each part.

In both parts I am giving attention to the possability of the original image being skyless or sky full.

To complete this task I used:

Detectron2 tutorial.

For the Sky Segmentation https://www.gopichandrakesan.com/day-80-coco-panoptic-segmentation-detectron2-computer-vision-by-facebook-ai-research-fair/
