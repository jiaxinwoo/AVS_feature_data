# AVS_feature_data
This repository shares the feature and other data of the ad-hoc video search. Currently, it has the data of three datasets: IACC.3, V3C1 and V3C2. For each video clip, we provide the frame-level feature. Please refer to video2frames.txt to find the corresponding frames for a video clip. For example a video clip shot35903_7 in IACC.3 dataset has six frames extracted features and the format looks like this:'shot35903_7': ['shot35903_7_0', 'shot35903_7_75', 'shot35903_7_150', 'shot35903_7_225', 'shot35903_7_300', 'shot35903_7_375']. Each frame corresponds to a npy file (e.g., shot35903_7_0.npy under the npy folder of the feature file). 

## **IACC.3 dataset**

335,944 video clips ([clip ids](https://portland-my.sharepoint.com/:t:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EYDbIU3aV-1KlhV98W7nN2kBwLKa74OzmK1cKq5bQJgH-A?e=VhnFtC))

Query sets: tv16.avs.txt, tv17.avs.txt,tv18.avs.txt  ([query and ground truth files](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EqF8SG8mxbZNpray_YikaE8BbW4Wb7YbPJbgH-o1GaSBZg?e=RAbqJP))

Available features:

[video2frames.txt](https://portland-my.sharepoint.com/:t:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EbuptdSLMIdHjYUVznwpHAABTG_ZHhPbr65FLXZcW1f8kg?e=yAIaBB)

CLIP_ViT-B_32 
([query features](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/Evg-Z-J8boxBirxt_IjUVi4BxWPo3_Nw3t_awWyce3Ldnw?e=aqHqSq), 
[frame-level features](https://portland-my.sharepoint.com/:u:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/ETtDR5I-VyNIrq5APIZ_1HcBRVnxyDKgHPVUGUv4Zb0CSg?e=ymTaDJ))

BLIP-2
([query features](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/Eld8M0OEBy5Gh0cHbBBnb3AB-58cgdmWLcV3AaM4CzrCrg?e=u0quAi), 
[frame-level features](https://portland-my.sharepoint.com/:u:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/Ec-4CM3MJ11NinAForKPgYsBso8beY1nTcdLhQo_8MO3vw?e=4TT2Du))

## **V3C1 dataset**

1,082,649 video clips ([clip ids](https://portland-my.sharepoint.com/:t:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EagcB0P8xFtMrKjTH_UQtlABqsU7fBoPrd3P_K27lGFpFQ?e=5vt65M))

Query sets: tv16.avs.txt, tv17.avs.txt,tv18.avs.txt  ([query and ground truth files](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EqGgR1gx4-VCqm9cqQ7nbAUBnFN4kkrilCCBGouHqUrVPg?e=Fvs6CZ))

Available features:

[video2frames.txt](https://portland-my.sharepoint.com/:t:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EZobKJ96lkNMsxmxQBPeTlgBBs3XSw9fv9H56XnqaqgjxQ?e=XqvjNR)

CLIP_ViT-B_32 
([query features](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/Eu2eT-36Jr9OvlEImM906qEBU98jOKJLyvSBZh62zj1XvA?e=xaC0QS), 
[frame-level features](https://portland-my.sharepoint.com/:u:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EeYTCeTuLGlPlFM83RNlwxMBeA1dJl2LuQbpNICHBE3FaA?e=IJ8fvr))

BLIP-2
([query features](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/Em1079DBfUdIqpBma9OzSCQBwsS5Oe__ZwUO4L2JPC2XUQ?e=GnCjXe), 
[frame-level features](https://portland-my.sharepoint.com/:u:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EbzXeoA3ogBCrbwRRAKuWA4BAvSpzwtB_3MzDw10tEnsKQ?e=IbG8vF))

## **V3C2 dataset**

1,425,451 video clips ([clip ids](https://portland-my.sharepoint.com/:t:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/Ebyks5_rNoVGkYQqZCtGAe0B4HaheXazhDP_kguvW34sJw?e=cOSNdQ))

Query sets: tv16.avs.txt, tv17.avs.txt,tv18.avs.txt  ([query and ground truth files](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EgbLXw3h3-9CiEFi2kAbmPwBjzh2N8KQMtlUYj6yy998ew?e=EJJrkp))

Available features:

[video2frames.txt](https://portland-my.sharepoint.com/:t:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EQZfUFxM3CtAq9O1bzGltcQBSAyNY1ceWPqBuEdPWuwnGg?e=2ergMV)

CLIP_ViT-B_32 
([query features](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EjWMmUnVgjpJpPtUSMHwG7UBSHZq-hBcipS5M90fSpbaHw?e=kOQbh1), 
[frame-level features](https://portland-my.sharepoint.com/:u:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EaV4VUSGEcZJt0rL648qdEsBN1OPwf8d3G88YDWzKpMpdA?e=D3EqOd))

BLIP-2
([query features](https://portland-my.sharepoint.com/:f:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/EksVulHnUFBGtZP73O2rG4UBczlHpiq4qdUlavBgl8fyRg?e=eK1zdo), 
[frame-level features](https://portland-my.sharepoint.com/:u:/g/personal/jiaxinwu9-c_my_cityu_edu_hk/Ecs7FejkKM5CufWDPqkQqhABI5lT1Noo1p__ehfyKAzYkw?e=zEbzQ3))



## Citation
If you found the data useful, please cite our paper as followed:
```
@misc{wu2023VIREO_TRECVidAVS,
      title={VIREO @ TRECVid 2023 Ad-hoc Video Search}, 
      author={Jiaxin Wu and, Zhixin Ma and Sheng-Hua Zhong and Chong-Wah Ngo},
      year={2023},
      booktitle = {TRECVID workshop},
}
```
