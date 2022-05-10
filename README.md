# CRPD (Chinese Road Plate Dataset)

Download links:

- CRPD-all (Google Drive, [Baidu Netdisk](https://pan.baidu.com/s/1P_7AFhfrIBqPHr2SQfMkbw?qq-pf-to=pcqq.c2c#list/path=%2F), Code:1234) (This file contents all the following three files.)

  - CRPD-single (Google Drive, [Baidu Netdisk](https://pan.baidu.com/s/119ddewBs21yo4UpWWlYIeA?qq-pf-to=pcqq.c2c), Code:1234)
  - CRPD-double ([Google Drive](https://drive.google.com/file/d/14zZ8FG0dnjzAO84Rl4v76GuhYN22bY4C/view?usp=sharing), [Baidu Netdisk](https://pan.baidu.com/s/1O2TVQcUBEe8l-kze5iegNQ?qq-pf-to=pcqq.c2c), Code:1234)
  - CRPD-multi ([Google Drive](https://drive.google.com/file/d/1Ud1QB-y9kXCWf1J9pegpMUnW5wkPgvis/view?usp=sharing), [Baidu Netdisk](https://pan.baidu.com/s/1zbms6sLC0_rw45M1mmXIQg?qq-pf-to=pcqq.c2c), Code:1234)

## Examples

![]()

## Annotations

The annotations are included in txt files in the labels/ folder, whose file names are the same as the names of the corresponding images. In the txt file, each line denotes a LP in the images. The format of the annotation of one LP is:

x1, y1, x2, y2, x3, y3, x4, y4, type, content

The first eight numbers represent the coordinates of the bounding quadrilateral corners. The "type" annotation represents the type of the LP, 0 for blue plates, 1 for yellow and single-line plates, 2 for yellow and double-lines plates, 3 for white plates. The "content" annotation represents the LP content.

## Citation
    @misc{gong2022unified,
          title={Unified Chinese License Plate Detection and Recognition with High Efficiency}, 
          author={Yanxiang Gong and Linjie Deng and Shuai Tao and Xinchen Lu and Peicheng Wu and Zhiwei Xie and Zheng Ma and Mei Xie},
          year={2022},
          eprint={2205.03582},
          archivePrefix={arXiv},
          primaryClass={cs.CV}
    }


The code will be avaliable after the corresponding paper is published.
