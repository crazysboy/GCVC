This repository is an official implementation of the IEEE TMMM 2024 paper "Graph Convolution Vector Distribution Calibration for Fish Group Activity Recognition".
---

    Z. Zhao, X. Yang, J. Liu, C. Zhou and C. Zhao, "GCVC: Graph Convolution Vector Distribution Calibration for Fish Group Activity Recognition," in IEEE Transactions on Multimedia, vol. 26, pp. 1776-1789, 2024, doi: 10.1109/TMM.2023.3287339. 


# Dataset Description

Every 10th frame in all video sequences was annotated with image location of fish, activity label, and action direction, action label
Frame number, activity label, X, Y, WIDTH, HEIGHT,action label1, X, Y, WIDTH, HEIGHT,action label2，X, Y, WIDTH, HEIGHT,action label3，……

ex. 000001.jpg None 317 774 535 95 swiming 399 75 511 411 swiming 1164 312 323 436 swiming 840 92 352 160 swiming 378 501 204 362 swiming 907 261 110 484 swiming 770 337 126 453 swiming 1100 434 185 439 swiming 435 310 346 289 swiming 567 221 301 196 swiming 1141 430 346 349 swiming 983 324 167 353 swiming 

000002.jpg None 320 773 533 97 swiming 408 78 502 414 swiming 1169 316 321 436 swiming 842 93 352 160 swiming 377 500 206 361 swiming 906 263 110 485 swiming 767 340 127 450 swiming 1092 444 193 431 swiming 433 310 343 289 swiming 566 221 303 197 swiming 1140 425 344 348 swiming 982 325 169 353 swiming 


**activity label**

1.'None',2.'stronge',3.'Medium',4.'Weak'

**action label**

1.'swiming',2.'static',3.'acceleration',4.'deceleration',5.'feeding'


# Citation

If you use Group DETR in your research or wish to refer to the baseline results published here, please use the following BibTeX entry.

    @ARTICLE{10155192,
    author={Zhao, Zhenxi and Yang, Xinting and Liu, Jintao and Zhou, Chao and Zhao, Chunjiang},
    journal={IEEE Transactions on Multimedia}, 
    title={GCVC: Graph Convolution Vector Distribution Calibration for Fish Group Activity Recognition}, 
    year={2024},
    volume={26},
    number={},
    pages={1776-1789},
    keywords={Fish;Feature extraction;Activity recognition;Calibration;Adhesives;Training;Convolution;Graph convolution vector calibration;fish group activity;activity feature 
    vector calibration;fish activity dataset},
    doi={10.1109/TMM.2023.3287339}}

