# Project: OCR (Optical Character Recognition) 

![image](figs/intro.png)

### [Full Project Description](doc/project4_desc.md)

Term: Spring 2019

+ Team # 1
+ Team members
	+ team member 1: Shu, Jason jls2319
	+ team member 2: Xu, Haiqing hx2259
	+ team member 3: Yang, Xi xy2378
	+ team member 4: Zhang, Yue yz3383
	+ team member 5: Zhang, Yun yz3384

+ Project summary: In this project, we created an OCR post-processing procedure to enhance Tesseract OCR output. We discusssed and researched the assigned paper D2 and C4, for the detection algorithm and correction algorithm separately. For error detection, we utilized letter n-gram algorithm，comparing all possible bigrams of all words in Tesseract with positional binary matrix constructed from Ground Truth. For error correction part, we focused on probability scoring with contextual constraints, using Baysian probability to find the correction type with highest prior probability multiplied by probability of it being a typo given the correction. Different methods of estimations such as GT, MLE, and ELE are performed. Performance evaluation is to compare the correction accuracy of different methods of estimations by calculating the proportion of errors before and after correction.
	
**Contribution statement**: All team members approve our work presented in this GitHub repository including this contributions statement. The contribution for each team member is following:

+ Shu, Jason: Studied performance measurement.
+ Xu, Haiqing: Read papers and listed outlines for error correction algorithm. Implemented error correction algorithm. Helped debugging and improved coding. 
+ Yang, Xi:  Read papers and listed out lines for error detection algorithm. Implemented error detection algorithm and wrote wrap-up function in error correction. Helped debugging and improved coding. Prepared slides and presentation to the class.
+ Zhang, Yue: Read papers and listed outlines for error correction algorithm. Implemented performance measurement. Helped debugging and improved coding.
+ Zhang, Yun: Read papers and listed outlines for error correction algorithm. Helped debugging and improved coding. Edited github homepage.


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
