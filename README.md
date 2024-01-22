## The Chongqing University Bituminous Pavement Disease Detection Dataset (CQU-BPDD)

**The CQU-BPDD** consists of 60,056 bituminous pavement images, which were automatically captured by the in-vehicle cameras of the professional pavement inspection vehicle at different times from different areas in southern China . Each pavement image is corresponding to a 2 × 3 meters pavement patch of highways and its resolution is 1200×900. The CQU-BPDD involves seven different distresses, namely **transverse crack, massive crack, alligator crack, crack pouring, longitudinal crack, ravelling, repair, and the normal ones.** 

For more details of this task, see [Pavement Distress Classification](https://github.com/DearCaat/Pavement-Distress-Classification).

### The Preview of CQU-BPDD
CQU-BPDD has the following characteristics:
* Illumination  is  uneven,  which  is  manifested  as  weaklight  in  some  areas  (called  dark  parts)  and  sufficientlight in some areas (called bright parts).
* The proportion of diseased areas is relatively small, andsome diseased areas are in the dark, which is difficultto identify.
* There are a variety of background interferences in realenvironments, such as zebra crossings, foreign bodies,ruts, etc.

![Image](https://github.com/DearCaat/CQU-BPDD/blob/gh-pages/images/dataset.png?raw=true)

### The data distribution of CQU-BPDD
We randomly select 5,137 diseased pavement images involving all diseases and 5,000 normal pavement images to produce the training set, while the rest of dataset is used as the testing set. In the testing set, there are 11,589 diseased pavement images and 38,330 normal images.

||Transverse Crack|Massive Crack|Alligator Crack|Crack Pouring|Longitudinal Crack|Ravelling|Repair|Normal|All|
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Train Set|518|1200|424|1000|1000|477|518|5000|10137|
|Test Set|520|5007|426|3199|1382|479|576|38330|49919|

### Download CQU-BPDD
[Downloading the dataset](https://pan.baidu.com/share/init?surl=nEwGiKZpmwyIq97YV8qdqQ&pwd=mq0a). _Please note: CQU-BPDD can be only used in the uncommercial case._
