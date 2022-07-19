---
layout: page
title: "COCO Dataset Visualizations"
permalink: /coco/
---
Predictions from classifier trained on captions with nouns, verbs, adjectives, and adverbs substituted with placeholder words:
- [Complex predictions, nouns masked](complex-predictions-classifier-trained-on-full-set-nouns-masked.html)
- [Noncomplex predictions, nouns masked](noncomplex-predictions-classifier-trained-on-full-set-nouns-masked.html)
- [Complex predictions, nouns and verbs masked](predictions-complex-classifier-trained-on-full-set-mask-noun-verb.html)
- [Noncomplex predictions](predictions-noncomplex-classifier-trained-on-full-set-mask-noun-verb.html)
- [Complex predictions, nouns, verbs, and adjectives masked](predictions-complex-classifier-trained-on-full-set-mask-noun-verb-adj.html)
- [Noncomplex predictions](predictions-noncomplex-classifier-trained-on-full-set-mask-noun-verb-adj.html)
- [Complex predictions, nouns, verbs, adjectives, and adverbs masked](predicted-complex-classifier-trained-on-full-set-mask-all.html)
- [Noncomplex predictions](predicted-noncomplex-classifier-trained-on-full-set-mask-all.html)

MS-COCO 2017: Grayscale images excluded
- All complex/noncomplex [val set images](color-coco-val2017.html) using meanshift segmented number of distinct regions as groundtruth
- All complex/noncomplex [val set images containing instances of 'bicycle'](coco-bicycle-val2017.html)
- All complex/noncomplex [val set images containing instances of 'person'](coco-person-val2017.html)

BERT predicted complex/complex images:
- Predictions from best model trained on all 10,000 images in complexity dataset:
	- [Top 50 images](predicted-complex-full-set.html) predicted to be complex with highest probability
	- [Top 50 images](predicted-noncomplex-full-set.html) predicted to be noncomplex with highest probability
- Predictions from best model trained on color image subset of full complexity dataset:
	- [Complex](predicted-complex-full-color-set.html)
	- [Noncomplex](predicted-noncomplex-full-color-set.html)
- Predictions from best model trained on color images with instances of category "accessory":
	- [Complex](predicted-complex-accessory-rgb.html)
	- [Noncomplex](predicted-noncomplex-accessory-rgb.html)
- Predictions from best model trained on color images with instances of category "animal":
	- [Complex](predicted-complex-animal-rgb.html)
	- [Noncomplex](predicted-noncomplex-animal-rgb.html)
- Predictions from best model trained on color images with instances of category "car":
	- [Complex](predicted-complex-car-rgb.html)
	- [Noncomplex](predicted-noncomplex-car-rgb.html)
- Predictions from best model trained on color images with instances of category "food":
	- [Complex](predicted-complex-food-rgb.html)
	- [Noncomplex](predicted-noncomplex-food-rgb.html)
- Predictions from best model trained on color images with instances of category "outdoor":
	- [Complex](predicted-complex-outdoor-rgb.html)
	- [Noncomplex](predicted-noncomplex-outdoor-rgb.html)
- Predictions from best model trained on color images with instances of category "person":
	- [Complex](predicted-complex-person-rgb.html)
	- [Noncomplex](predicted-noncomplex-person-rgb.html)
- Predictions from best model trained on color images with instances of category "vehicle":
	- [Complex](predicted-complex-vehicle-rgb.html)
	- [Noncomplex](predicted-noncomplex-vehicle-rgb.html)

Click on the links below to view ~5,000 images from the MS-COCO 2017 validation set, ranked by automated visual complexity scores.
- Images ranked by # of distinct mean-shift segmented regions
	- [Top 500 most complex images](complex-coco-eval.html)
	- [Bottom 500 least complex images](noncomplex-coco-eval.html)

Click on the links below to view ~5,000 images from the MS-COCO 2017 train set, ranked by automated visual complexity scores.
- Images ranked by # of distinct mean-shift segmented regions
	- Top 11,828 most complex images (top 10% of train set)
		- [Page 1/10](complex-coco-train1.html)
		- [Page 2/10](complex-coco-train2.html)
		- [Page 3/10](complex-coco-train3.html)
		- [Page 4/10](complex-coco-train4.html)
		- [Page 5/10](complex-coco-train5.html)
		- [Page 6/10](complex-coco-train6.html)
		- [Page 7/10](complex-coco-train7.html)
		- [Page 8/10](complex-coco-train8.html)
		- [Page 9/10](complex-coco-train9.html)
		- [Page 10/10](complex-coco-train10.html)
	- Bottom 11,828 least complex images (bottom 10% of train set)
		- [Page 1/10](noncomplex-coco-train1.html)
		- [Page 2/10](noncomplex-coco-train2.html)
		- [Page 3/10](noncomplex-coco-train3.html)
		- [Page 4/10](noncomplex-coco-train4.html)
		- [Page 5/10](noncomplex-coco-train5.html)
		- [Page 6/10](noncomplex-coco-train6.html)
		- [Page 7/10](noncomplex-coco-train7.html)
		- [Page 8/10](noncomplex-coco-train8.html)
		- [Page 9/10](noncomplex-coco-train9.html)
		- [Page 10/10](noncomplex-coco-train10.html)

Click on the links below to view ~5,000 images from the MS-COCO 2014 validation set, ranked by human and automated visual complexity scores. The scoring was conducted
by vislang.

- [Human-scored Images](coco-human.html)
- [Automatically scored Images](coco-auto.html)
- Images ranked by mean-shift segmented # of regions
	- [Page 1/4](coco-regions-1.html)
	- [Page 2/4](coco-regions-2.html)
	- [Page 3/4](coco-regions-3.html)
	- [Page 4/4](coco-regions-4.html)
- Images ranked by feature congestion
	- [Page 1/4](coco-fc-1.html)
	- [Page 2/4](coco-fc-2.html)
	- [Page 3/4](coco-fc-3.html)
	- [Page 4/4](coco-fc-4.html)

**Citation:** Lin, T.-Y., Maire, M., Belongie, S., Hays, J., Perona, P., Ramanan, D., Dollár, P., & Zitnick, C. L. (2014). Microsoft COCO: Common Objects in Context. 
In D. Fleet, T. Pajdla, B. Schiele, & T. Tuytelaars (Eds.), Computer Vision – ECCV 2014 (Vol. 8693, pp. 740–755). Springer International Publishing. 
https://doi.org/10.1007/978-3-319-10602-1_48
