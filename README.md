# MMWorld: Towards Multi-discipline Multi-faceted World Model Evaluation in Videos

[Xuehai He](https://sheehan1230.github.io/)<sup style="color: #FFB6C1;">†,1</sup>, [Weixi Feng*](https://weixi-feng.github.io/)<sup style="color: #ADD8E6;">2</sup>, [Kaizhi Zheng*](https://kzzheng.github.io/)<sup style="color: #FFB6C1;">1</sup>, [Yujie Lu*](https://yujielu10.github.io/)<sup style="color: #ADD8E6;">2</sup>, [Wanrong Zhu*](https://wanrong-zhu.com/)<sup style="color: #ADD8E6;">2</sup>, [Jiachen Li*](https://sites.google.com/view/jiachenli/)<sup style="color: #ADD8E6;">2</sup>, [Yue Fan*](http://www.yfan.site/)<sup style="color: #FFB6C1;">1</sup>, [Jianfeng Wang](https://scholar.google.com/citations?user=vJWEw_8AAAAJ&hl=en)<sup style="color: #90EE90;">3</sup>, [Linjie Li](https://www.linkedin.com/in/linjie-li/)<sup style="color: #90EE90;">3</sup>, [Zhengyuan Yang](https://zyang-ur.github.io/)<sup style="color: #90EE90;">3</sup>, [Kevin Lin](https://sites.google.com/site/kevinlin311tw/me)<sup style="color: #90EE90;">3</sup>, [William Yang Wang](https://sites.cs.ucsb.edu/~william/)<sup style="color: #ADD8E6;">2</sup>, [Xin Eric Wang](https://eric-xw.github.io/)<sup style="color: #FFB6C1;">†,1</sup>


<sup style="color: #FFB6C1;">1</sup>UCSC, <sup style="color: #FFB6C1;">2</sup>UCSB, <sup style="color: #FFB6C1;">3</sup>Microsoft

<sup style="color: #FFB6C1;">*</sup>Equal contribution

<a href='https://arxiv.org/abs/2406.08407'><img src='https://img.shields.io/badge/Paper-Arxiv-red'></a> <a href='https://mmworld-bench.github.io/'><img src='https://img.shields.io/badge/Project-Page-green'></a> <a href='https://huggingface.co/datasets/Xuehai/MMWorld'><img src='https://img.shields.io/badge/🤗-Dataset-blue'></a> <a href='https://eval.ai/web/challenges/challenge-page/2359'><img src='https://img.shields.io/badge/EvalAI-Challenge-orange'>
</a>

![Teaser figure](figures/overall.png)



## Dataset Structure
The dataset can be downloaded from Hugging Face.
Each entry in the dataset contains the following fields:
- `video_id`: Unique identifier for the video. Same as the relative path of the downloaded video
- `video_url`: URL of the video
- `discipline`: Main discipline of the video content
- `subdiscipline`: Sub-discipline of the video content
- `captions`: List of captions describing the video content
- `questions`: List of questions related to the video content, each with options and correct answer


## Example Entry


## Evaluation
You can do evaluation by running our evaluation code [eval.py](utils/gpt4_eval.py). 
The deployment of the model can refer to [models](models).







## Citation
```
@misc{he2024mmworld,
      title={MMWorld: Towards Multi-discipline Multi-faceted World Model Evaluation in Videos}, 
      author={Xuehai He and Weixi Feng and Kaizhi Zheng and Yujie Lu and Wanrong Zhu and Jiachen Li and Yue Fan and Jianfeng Wang and Linjie Li and Zhengyuan Yang and Kevin Lin and William Yang Wang and Lijuan Wang and Xin Eric Wang},
      year={2024},
      eprint={2406.08407},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
