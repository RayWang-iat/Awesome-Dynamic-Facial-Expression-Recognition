# Awesome Dynamic Facial Expression Recognition

## Datasets 
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
    <th rowspan="2">Venues</th>
    <th colspan="2">DFEW</th>
    <th colspan="2">FERV39k</th>
    <th colspan="2">MAFW</th>
  </tr>
  <tr>
    <th>UAR</th>
    <th>WAR</th>
    <th>UAR</th>
    <th>WAR</th>
    <th>UAR</th>
    <th>WAR</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>C3D</td>
    <td>-</td>
    <td>42.74</td>
    <td>53.54</td>
    <td>22.68</td>
    <td>31.69</td>
    <td>31.17 </td>
    <td>42.25 </td>
  </tr>
  <tr>
    <td>P3D</td>
    <td>-</td>
    <td>43.97</td>
    <td>54.47</td>
    <td>23.20</td>
    <td>33.39</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>I3D-RGB</td>
    <td>-</td>
    <td>43.40</td>
    <td>54.27</td>
    <td>30.17</td>
    <td>38.78</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>3D-ResNet18</td>
    <td>-</td>
    <td>46.52</td>
    <td>58.27</td>
    <td>26.67</td>
    <td>37.57</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>R(2+1)D</td>
    <td>-</td>
    <td>42.79</td>
    <td>53.22</td>
    <td>31.55</td>
    <td>41.28</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>ResNet18-LSTM</td>
    <td>-</td>
    <td>51.32</td>
    <td>63.85</td>
    <td>30.92</td>
    <td>42.95</td>
    <td>28.08</td>
    <td>39.38</td>
  </tr>
  <tr>
    <td>R18-ViT</td>
    <td>-</td>
    <td>55.76</td>
    <td>67.56</td>
    <td>38.35</td>
    <td>48.43</td>
    <td>35.80</td>
    <td>47.72</td>
  </tr>
  <tr>
    <td>EC-STFL<sup>[1]</sup></td>
    <td>MM’20</td>
    <td>45.35</td>
    <td>56.51</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Former-DFER<sup>[2]</sup></td>
    <td>MM’21</td>
    <td>53.69</td>
    <td>65.70</td>
    <td>37.20</td>
    <td>46.85</td>
    <td>31.16 </td>
    <td>43.27</td>
  </tr>
  <tr>
    <td>NR-DFERNet<sup>[3]</sup></td>
    <td>arXiv’22</td>
    <td>54.21</td>
    <td>68.19</td>
    <td>33.99</td>
    <td>45.97</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>DPCNet<sup>[4]</sup></td>
    <td>MM’22</td>
    <td>57.11</td>
    <td>66.32</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>T-ESFL<sup>[5]</sup></td>
    <td>MM’22</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>33.28 </td>
    <td>48.18</td>
  </tr>
  <tr>
    <td>EST<sup>[6]</sup></td>
    <td>PR’23</td>
    <td>53.94</td>
    <td>65.85</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Logo-Form<sup>[7]</sup></td>
    <td>ICASSP’23</td>
    <td>54.21</td>
    <td>66.98</td>
    <td>38.22</td>
    <td>48.13</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>GCA+IAL<sup>[8]</sup></td>
    <td>AAAI’23</td>
    <td>55.71</td>
    <td>69.24</td>
    <td>35.82</td>
    <td>48.54</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>CLIPER<sup>[9]</sup></td>
    <td>arXiv'23</td>
    <td>57.56</td>
    <td>70.84</td>
    <td>41.23</td>
    <td>51.34</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>MSCM<sup>[10]</sup></td>
    <td>PR'23</td>
    <td>58.49</td>
    <td>70.16</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>AEN<sup>[11]</sup></td>
    <td>CVPRW'23</td>
    <td>56.66</td>
    <td>69.37</td>
    <td>38.18</td>
    <td>47.88</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>M3DFEL<sup>[12]</sup></td>
    <td>CVPR'23</td>
    <td>56.10</td>
    <td>69.25</td>
    <td>35.94</td>
    <td>47.67</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>MAE-DFER<sup>[13]</sup></td>
    <td>arXiv'23</td>
    <td>63.41</td>
    <td>74.43</td>
    <td>43.12</td>
    <td>52.07</td>
    <td>41.62</td>
    <td>54.31</td>
  </tr>
<!-- copy this to add new methods
  <tr>
    <td></td>  
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr> 
-->
</tbody>
</table>

## References
<!-- Using Vancouver Format -->
### 2020
1. Jiang X, Zong Y, Zheng W, Tang C, Xia W, Lu C, Liu J. DFEW: A Large-scale Database for Recognizing Dynamic Facial Expressions in the Wild. *MM*, 2020. [[Paper](https://doi.org/10.1145/3394171.3413620)]
### 2021
2. Zhao Z, Liu Q. Former-DFER: Dynamic Facial Expression Recognition Transformer. *MM*, 2021. [[Paper](https://doi.org/10.1145/3474085.3475292)] [[Code](https://github.com/zengqunzhao/Former-DFER)]
### 2022
3. Li H, Sui M, Zhu Z. NR-DFERNet: Noise-Robust Network for Dynamic Facial Expression Recognition. arXiv, 2022.[[Paper](https://arxiv.org/abs/2206.04975)]
4. Wang Y, Sun Y, Song W, Gao S, Huang Y, Chen Z, Ge W, Zhang W. DPCNet: Dual Path Multi-Excitation Collaborative Network for Facial Expression Representation Learning in Videos. *MM*, 2022. [[Paper](https://doi.org/10.1145/3503161.3547865)]
5. Liu Y, Dai W, Feng C, Wang W, Yin G, Zeng J, Shan S. MAFW: A Large-scale, Multi-modal, Compound Affective Database for Dynamic Facial Expression Recognition in the Wild. *MM*, 2022. [[Paper](https://mafw-database.github.io/MAFW/)]
### 2023
6. Liu Y, Wang W, Feng C, Zhang H, Chen Z, Zhan Y. Expression snippet transformer for robust video-based facial expression recognition. Pattern Recognition. *Pattern Recognition*, 2023. [[Paper](https://doi.org/10.1016/j.patcog.2023.109368)]
7. Ma F, Sun B, Li S. Logo-Former: Local-Global Spatio-Temporal Transformer for Dynamic Facial Expression Recognition. *ICASSP*, 2023. [[Paper](https://ieeexplore.ieee.org/abstract/document/10095448)]
8. Li H, Niu H, Zhu Z, Zhao F. Intensity-Aware Loss for Dynamic Facial Expression Recognition in the Wild. *AAAI*, 2023. [[Paper](https://arxiv.org/abs/2208.10335)] [[Code](https://github.com/muse1998/IAL-for-Facial-Expression-Recognition)] 
9. Li H, Niu H, Zhu Z, Zhao F. CLIPER: A Unified Vision-Language Framework for In-the-Wild Facial Expression Recognition. *arXiv*, 2023. [[Paper](https://arxiv.org/abs/2303.00193)] 
10. Li T, Chan KL, Tjahjadi T. Multi-Scale Correlation Module for Video-based Facial Expression Recognition in the Wild. *Pattern Recognition*, 2023. [[Paper](https://doi.org/10.1016/j.patcog.2023.109691)]
11. Lee B, Shin H, Ku B, Ko H. Frame Level Emotion Guided Dynamic Facial Expression Recognition With Emotion Grouping. *CVPRW*, 2023. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Rethinking_the_Learning_Paradigm_for_Dynamic_Facial_Expression_Recognition_CVPR_2023_paper.html)] 
12. Wang H, Li B, Wu S, Shen S, Liu F, Ding S, Zhou A. Rethinking the Learning Paradigm for Dynamic Facial Expression Recognition. *CVPR*, 2023. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Rethinking_the_Learning_Paradigm_for_Dynamic_Facial_Expression_Recognition_CVPR_2023_paper.html)] [[Code](https://github.com/faceeyes/M3DFEL)]
13. Sun L, Lian Z, Liu B, Tao J. MAE-DFER: Efficient Masked Autoencoder for Self-supervised Dynamic Facial Expression Recognition. *arXiv*, 2023. [[Paper](https://arxiv.org/abs/2307.02227)] [[Code](https://github.com/sunlicai/MAE-DFER)] 
