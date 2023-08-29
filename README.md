# Awesome Dynamic Facial Expression Recognition

## Benchmarks 
  - [DFEW [ACM MM 2020]](https://dfew-dataset.github.io/)
  - [FERV39k [CVPR 2022]](https://wangyanckxx.github.io/Proj_CVPR2022_FERV39k.html)
  - [MAFW [ACM MM 2022]](https://mafw-database.github.io/MAFW/)
  - [CAER [ICCV 2021]](https://caer-dataset.github.io/)
  - [AFEW [IEEE Multimedia 2012]](https://cs.anu.edu.au/few/AFEW.html)

## Comparison of State-of-the-Art
<table>
<thead>
  <tr>
    <th style="text-align: center" rowspan="2">Methods</th>
    <th style="text-align: center" rowspan="2">Venues</th>
    <th style="text-align: center" rowspan="2">Years</th>
    <th style="text-align: center" colspan="2">DFEW</th>
    <th style="text-align: center" colspan="2">FERV39k</th>
    <th style="text-align: center" colspan="2">MAFW</th>
  </tr>
  <tr>
    <th style="text-align: center">UAR</th>
    <th style="text-align: center">WAR</th>
    <th style="text-align: center">UAR</th>
    <th style="text-align: center">WAR</th>
    <th style="text-align: center">UAR</th>
    <th style="text-align: center">WAR</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="text-align: center">C3D</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">42.74</td>
    <td style="text-align: center">53.54</td>
    <td style="text-align: center">22.68</td>
    <td style="text-align: center">31.69</td>
    <td style="text-align: center">31.17 </td>
    <td style="text-align: center">42.25 </td>
  </tr>
  <tr>
    <td style="text-align: center">P3D</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">43.97</td>
    <td style="text-align: center">54.47</td>
    <td style="text-align: center">23.20</td>
    <td style="text-align: center">33.39</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">I3D-RGB</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">43.40</td>
    <td style="text-align: center">54.27</td>
    <td style="text-align: center">30.17</td>
    <td style="text-align: center">38.78</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">3D-ResNet18</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">46.52</td>
    <td style="text-align: center">58.27</td>
    <td style="text-align: center">26.67</td>
    <td style="text-align: center">37.57</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">R(2+1)D</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">42.79</td>
    <td style="text-align: center">53.22</td>
    <td style="text-align: center">31.55</td>
    <td style="text-align: center">41.28</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">ResNet18-LSTM</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">51.32</td>
    <td style="text-align: center">63.85</td>
    <td style="text-align: center">30.92</td>
    <td style="text-align: center">42.95</td>
    <td style="text-align: center">28.08</td>
    <td style="text-align: center">39.38</td>
  </tr>
  <tr>
    <td style="text-align: center">R18-ViT</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">55.76</td>
    <td style="text-align: center">67.56</td>
    <td style="text-align: center">38.35</td>
    <td style="text-align: center">48.43</td>
    <td style="text-align: center">35.80</td>
    <td style="text-align: center">47.72</td>
  </tr>
  <tr>
    <td style="text-align: center">EC-STFL<sup>[1]</sup></td>
    <td style="text-align: center">ACM MM</td>
    <td style="text-align: center">2020</td>
    <td style="text-align: center">45.35</td>
    <td style="text-align: center">56.51</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">Former-DFER<sup>[2]</sup></td>
    <td style="text-align: center">ACM MM</td>
    <td style="text-align: center">2021</td>
    <td style="text-align: center">53.69</td>
    <td style="text-align: center">65.70</td>
    <td style="text-align: center">37.20</td>
    <td style="text-align: center">46.85</td>
    <td style="text-align: center">31.16 </td>
    <td style="text-align: center">43.27</td>
  </tr>
  <tr>
    <td style="text-align: center">NR-DFERNet<sup>[3]</sup></td>
    <td style="text-align: center">arXiv</td>
    <td style="text-align: center">2022</td>
    <td style="text-align: center">54.21</td>
    <td style="text-align: center">68.19</td>
    <td style="text-align: center">33.99</td>
    <td style="text-align: center">45.97</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">DPCNet<sup>[4]</sup></td>
    <td style="text-align: center">ACM MM</td>
    <td style="text-align: center">2022</td>
    <td style="text-align: center">57.11</td>
    <td style="text-align: center">66.32</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">T-ESFL<sup>[5]</sup></td>
    <td style="text-align: center">ACM MM</td>
    <td style="text-align: center">2022</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">33.28 </td>
    <td style="text-align: center">48.18</td>
  </tr>
  <tr>
    <td style="text-align: center">EST<sup>[6]</sup></td>
    <td style="text-align: center">PR</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">53.94</td>
    <td style="text-align: center">65.85</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">Logo-Form<sup>[7]</sup></td>
    <td style="text-align: center">ICASSP</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">54.21</td>
    <td style="text-align: center">66.98</td>
    <td style="text-align: center">38.22</td>
    <td style="text-align: center">48.13</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">GCA+IAL<sup>[8]</sup></td>
    <td style="text-align: center">AAAI</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">55.71</td>
    <td style="text-align: center">69.24</td>
    <td style="text-align: center">35.82</td>
    <td style="text-align: center">48.54</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">CLIPER<sup>[9]</sup></td>
    <td style="text-align: center">arXiv</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">57.56</td>
    <td style="text-align: center">70.84</td>
    <td style="text-align: center">41.23</td>
    <td style="text-align: center">51.34</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">MSCM<sup>[10]</sup></td>
    <td style="text-align: center">PR</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">58.49</td>
    <td style="text-align: center">70.16</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">AEN<sup>[11]</sup></td>
    <td style="text-align: center">CVPRW</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">56.66</td>
    <td style="text-align: center">69.37</td>
    <td style="text-align: center">38.18</td>
    <td style="text-align: center">47.88</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">M3DFEL<sup>[12]</sup></td>
    <td style="text-align: center">CVPR</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">56.10</td>
    <td style="text-align: center">69.25</td>
    <td style="text-align: center">35.94</td>
    <td style="text-align: center">47.67</td>
    <td style="text-align: center">-</td>
    <td style="text-align: center">-</td>
  </tr>
  <tr>
    <td style="text-align: center">MAE-DFER<sup>[13]</sup></td>
    <td style="text-align: center">ACM MM</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">63.41</td>
    <td style="text-align: center">74.43</td>
    <td style="text-align: center">43.12</td>
    <td style="text-align: center">52.07</td>
    <td style="text-align: center">41.62</td>
    <td style="text-align: center">54.31</td>
  </tr>
  <tr>
    <td style="text-align: center">DFER-CLIP<sup>[14]</sup></td>
    <td style="text-align: center">BMVC</td>
    <td style="text-align: center">2023</td>
    <td style="text-align: center">59.61</td>
    <td style="text-align: center">71.25</td>
    <td style="text-align: center">41.27</td>
    <td style="text-align: center">51.65</td>
    <td style="text-align: center">39.89</td>
    <td style="text-align: center">52.55</td>
  </tr> 
<!-- copy this to add new methods
  <tr>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
    <td style="text-align: center"></td>
  </tr> 
-->
</tbody>
</table>

## References
<!-- Using Vancouver Format -->
### 2020
1. Jiang X, Zong Y, Zheng W, Tang C, Xia W, Lu C, Liu J. DFEW: A Large-scale Database for Recognizing Dynamic Facial Expressions in the Wild. *ACM MM*, 2020. [[Paper](https://doi.org/10.1145/3394171.3413620)]
### 2021
2. Zhao Z, Liu Q. Former-DFER: Dynamic Facial Expression Recognition Transformer. *ACM MM*, 2021. [[Paper](https://doi.org/10.1145/3474085.3475292)] [[Code](https://github.com/zengqunzhao/Former-DFER)]
### 2022
3. Li H, Sui M, Zhu Z. NR-DFERNet: Noise-Robust Network for Dynamic Facial Expression Recognition. arXiv, 2022.[[Paper](https://arxiv.org/abs/2206.04975)]
4. Wang Y, Sun Y, Song W, Gao S, Huang Y, Chen Z, Ge W, Zhang W. DPCNet: Dual Path Multi-Excitation Collaborative Network for Facial Expression Representation Learning in Videos. *ACM MM*, 2022. [[Paper](https://doi.org/10.1145/3503161.3547865)]
5. Liu Y, Dai W, Feng C, Wang W, Yin G, Zeng J, Shan S. MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild. *ACM MM*, 2022. [[Paper](https://mafw-database.github.io/MAFW/)]
### 2023
6. Liu Y, Wang W, Feng C, Zhang H, Chen Z, Zhan Y. Expression snippet transformer for robust video-based facial expression recognition. Pattern Recognition. *Pattern Recognition*, 2023. [[Paper](https://doi.org/10.1016/j.patcog.2023.109368)]
7. Ma F, Sun B, Li S. Logo-Former: Local-Global Spatio-Temporal Transformer for Dynamic Facial Expression Recognition. *ICASSP*, 2023. [[Paper](https://ieeexplore.ieee.org/abstract/document/10095448)]
8. Li H, Niu H, Zhu Z, Zhao F. Intensity-Aware Loss for Dynamic Facial Expression Recognition in the Wild. *AAAI*, 2023. [[Paper](https://arxiv.org/abs/2208.10335)] [[Code](https://github.com/muse1998/IAL-for-Facial-Expression-Recognition)] 
9. Li H, Niu H, Zhu Z, Zhao F. CLIPER: A Unified Vision-Language Framework for In-the-Wild Facial Expression Recognition. *arXiv*, 2023. [[Paper](https://arxiv.org/abs/2303.00193)] 
10. Li T, Chan KL, Tjahjadi T. Multi-Scale Correlation Module for Video-based Facial Expression Recognition in the Wild. *Pattern Recognition*, 2023. [[Paper](https://doi.org/10.1016/j.patcog.2023.109691)]
11. Lee B, Shin H, Ku B, Ko H. Frame Level Emotion Guided Dynamic Facial Expression Recognition With Emotion Grouping. *CVPRW*, 2023. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Rethinking_the_Learning_Paradigm_for_Dynamic_Facial_Expression_Recognition_CVPR_2023_paper.html)] 
12. Wang H, Li B, Wu S, Shen S, Liu F, Ding S, Zhou A. Rethinking the Learning Paradigm for Dynamic Facial Expression Recognition. *CVPR*, 2023. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Rethinking_the_Learning_Paradigm_for_Dynamic_Facial_Expression_Recognition_CVPR_2023_paper.html)] [[Code](https://github.com/faceeyes/M3DFEL)]
13. Sun L, Lian Z, Liu B, Tao J. MAE-DFER: Efficient Masked Autoencoder for Self-supervised Dynamic Facial Expression Recognition. *ACM MM*, 2023. [[Paper](https://arxiv.org/abs/2307.02227)] [[Code](https://github.com/sunlicai/MAE-DFER)]
14. Zhao Z, Patras I. Prompting Visual-Language Models for Dynamic Facial Expression Recognition. *BMVC*, 2023. [[Paper](https://arxiv.org/abs/2308.13382)] [[Code](https://github.com/zengqunzhao/DFER-CLIP)]
