# HashReID - Dynamic Network with Binary Codes for Efficient Person Re-identification

Code located at -> https://git.unl.edu/ece-unl-images-lab/hash-reid

Biometric applications, such as person re-identification
(ReID), are often deployed on energy constrained devices.
While recent ReID methods prioritize high retrieval performance, they often come with large computational costs
and high search time, rendering them less practical in realworld settings. In this work, we propose an input-adaptive
network with multiple exit blocks, that can terminate computation early if the retrieval is straightforward or noisy,
saving a lot of computation. To assess the complexity of
the input, we introduce a temporal-based classifier driven
by a new training strategy. Furthermore, we adopt a binary hash code generation approach instead of relying on
continuous-valued features, which significantly improves
the search process by a factor of 20. To ensure similarity preservation, we utilize a new ranking regularizer that
bridges the gap between continuous and binary features.
Extensive analysis of our proposed method is conducted on
three datasets: Market1501, MSMT17 (Multi-Scene MultiTime), and the BGC1 (BRIAR Government Collection). Using our approach, more than 70% of the samples with compact hash codes exit early on the Market1501 dataset, saving 80% of the networks computational cost and improving over other hash-based methods by 60%. These results
demonstrate a significant improvement over dynamic networks and showcase comparable accuracy performance to
conventional ReID methods.

# Citation
```
@inproceedings{nikhal2024hashreid,
  title={HashReID: Dynamic network with binary codes for efficient person re-identification},
  author={Nikhal, Kshitij and Ma, Yujunrong and Bhattacharyya, Shuvra S and Riggan, Benjamin S},
  booktitle={Proceedings of the IEEE/CVF winter conference on applications of computer vision},
  pages={6046--6055},
  year={2024}
}
```
