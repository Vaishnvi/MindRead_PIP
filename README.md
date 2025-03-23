# MindRead

## Can Reasons Help Improve Pedestrian Intent Estimation? A Cross-Modal Approach

### 2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

[Paper](https://arxiv.org/pdf/2411.13302) / [Talk](https://drive.google.com/file/d/1dUXsWc1RSUt869FA5SxCO9NKh2udiS2D/view) / [Poster](https://docs.google.com/presentation/d/1ji-Ibjx1E9CWN1SRykB16G0943ZITas8mvt6Jeuy7pY/edit#slide=id.g3066c511380_0_2) / [Graphical Abstract](https://docs.google.com/presentation/d/1SnMTcl4fXXl4th5M68IGkscUyqJRLebCcRyZyW5LF0A/edit#slide=id.g3066c511380_0_2)

```
@inproceedings{khindkar2024can,
  title={Can Reasons Help Improve Pedestrian Intent Estimation? A Cross-Modal Approach},
  author={Khindkar, Vaishnavi and Balasubramanian, Vineeth and Arora, Chetan and Subramanian, Anbumani and Jawahar, CV},
  booktitle={2024 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages={11515--11522},
  year={2024},
  organization={IEEE}
}
```

## Abstract

![Intro](https://github.com/Vaishnvi/MindRead_PIP/blob/main/intro.png)

With the increased importance of autonomous navigation systems has come an increasing need to protect the safety of Vulnerable Road Users (VRUs) such as pedestrians. Predicting pedestrian intent is one such challenging task, where prior work predicts the binary cross/no-cross intention with a fusion of visual and motion features. However, there has been no effort so far to hedge such predictions with human-understandable reasons. We address this issue by introducing a novel problem setting of exploring the intuitive reasoning behind a pedestrian’s intent. In particular, we show that predicting the ‘WHY’ can be very useful in understanding the ‘WHAT’. To this end, we propose a novel, reason-enriched PIE++ dataset consisting of multi-label textual explanations/reasons for pedestrian intent. We also introduce a novel multi-task learning framework called MINDREAD, which leverages a cross-modal representation learning framework for predicting pedestrian intent as well as the reason behind the intent. Our comprehensive experiments show significant improvement of 5.6% and 7% in accuracy and F1-score for the task of intent prediction on the PIE++ dataset using MINDREAD. We also achieved a 4.4% improvement in accuracy on a commonly used JAAD dataset. Extensive evaluation using quantitative/qualitative metrics and user studies shows the effectiveness of our approach.

## Dataset

![Intro](https://github.com/Vaishnvi/MindRead_PIP/blob/main/DatasetSamples.png) 

Our PIE++ dataset is the first pedestrian reason+intent prediction dataset. PIE++ consists of human-referenced, multi-label explanation annotations for all the 1842 pedestrians. For pedestrians that: (i) have no crossing intention, there could be reasons such as “Pedestrians are just doing their work” or “Two pedestrians just interacting with each other on the road-side”; and (ii) have crossing intention, reasons could include “Pedestrian acknowledges the ego-car to stop/slow-down with a hand-ack gesture since the pedestrian is intending to cross”. Our list of reasons indicate that it is possible for more than one reason to be relevant for a given pedestrian’s intent in a scene. We hence provide multi-label annotations for every pedestrian for their crossing vs no-crossing intent. 

You can download PIE++ annotation attributes from [here](https://mail.google.com/mail/u/0?ui=2&ik=f09b9f5dff&attid=0.1&permmsgid=msg-a:r-8321158983356550365&th=1874051035066ebb&view=att&disp=safe&realattid=f_lfyxfk9u0&zw).

## 

