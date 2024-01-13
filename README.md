This converter converts PASCAL VOC formated CSV file into JSON file for DETR.

-----------------------Example CSV-------------------------
filename,width,height,class,xmin,ymin,xmax,ymax
imagename,1200,800,LabelId,322,54,821,742

----------------------Converted Json-----------------------
{"images": [{"id": 0, "width": 1200, "height": 800, "file_name": "imagename}], "annotations": [{"id": 0, "image_id": 0, "category_id": 1, "bbox": [322, 54, 499, 688], "area": 343312, "iscrowd": 0}], "categories": [{"id": 1, "name": "LabelId"}]}
