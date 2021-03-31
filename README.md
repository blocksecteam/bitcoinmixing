# Dataset

This repository contains the dataset introduced in the paper: Towards Understanding and Demystifying Bitcoin Mixing Services, accepted on The Web Conference (WWW'21).

[Link to the paper.](http://yajin.org/papers/www21_mixing.pdf)

Repository organization:
* `Mixing Record.md`: mixing records for experiments with mixing services using real Bitcoins, as mentioned in the paper.
* `data`: directory containing mixing transactions data (to be organized).
  * `chipmixer_mixing_transactions.json`: collected mixing transactions from Chipmixer using our proposed algorithm.
  * `shapeshift_full_records.json`: full records of our ShapeShift crawler.
  * `shapeshift_mixing_transactions.json`: mixing transactions using refined matching algorithm based on crawled records.

To cite this paper:

```
@inproceedings{
  title={Towards Understanding and Demystifying Bitcoin Mixing Services},
  author={Wu, Lei and Hu, Yufeng and Zhou, Yajin and Wang, Haoyu and Luo, Xiapu and Wang, Zhi and Zhang, Fan and Ren, Kui},
  booktitle={Proceedings of the World Wide Web Conference},
  year={2021},
  organization={The Web Conference}
}
```
