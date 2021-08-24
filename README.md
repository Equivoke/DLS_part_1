# DLS_part_1

Alekseev_Nikita_semantic_segmentation_2021 is segmentation project.

ADDI project dataset was used for segmentation of melanomas and birthmarks. SegNet and U-net were implemented "from stratch" with full training cycle. 
BCE-loss, dice-loss, focal-loss, IoU metric were implemented.
Quality of both U-net and SegNet were analyzed.

Detection_project_Alekseev_NA_11_07_2021 is detection project with pure PyTorch and pretrained on MS COCO fasterrcnn_mobilenet_v3_large_fpn as backbone of CNN.
Full training cycle of detection were implemented: 
- dataset selection;
- data preprocessing;
- training model with pure PyTorch without any frameworks;
- testing detection quality on random pictures from Internet;
- IoU, NMS, precision, recall, and F1-score were implemented.
