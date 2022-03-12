# <center>对话场景说话人分离与理解关键技术研究</center>

<center>招梓枫<sup>1</sup>, 朱利丰<sup>1, 2</sup></center> 

<center> 1 机器人传感与控制研究所, 东南大学, 南京 </center>

<center> 2 生物电子学国家重点实验室, 东南大学, 南京 </center>

## 介绍
Singing voice conversion (SVC) is one promising technique which can enrich the way of human-computer interaction by endowing a computer the ability to produce high-fidelity and expressive singing voice.
In this paper, we propose DiffSVC, an SVC system based on denoising diffusion probabilistic model. DiffSVC uses phonetic posteriorgrams (PPGs) as content features. A denoising module is trained in DiffSVC, which takes destroyed mel spectrogram produced by the diffusion/forward process and its corresponding step information as input to predict the added Gaussian noise. We use PPGs, fundamental frequency features and loudness features as auxiliary input to assist the denoising process. Experiments show that DiffSVC can achieve superior conversion performance in terms of naturalness and voice similarity to current state-of-the-art SVC approaches.

## 效果演示

| <center>分离Hillary Cliton</center> | <center>分离Donald Trump</center> | <center>原始视频 </center>|
| :--- | :--- | :--- |
|<video id="video" controls preload poster="封面"><source id="mp4" src="https://github.com/ZhaZhaFon/demo-speakerseparation/blob/gh-pages/mp4/mix1.mp4" type="video/mp4"></videos>｜|<video id="video" controls="" preload="none" poster="封面"><source id="mp4" src="mp4/mix_s2.mp4" type="video/mp4"></videos>｜|<video id="video" controls="" preload="none" poster="封面"><source id="mp4" src="mp4/mix_s2.mp4" type="video/mp4"></videos>｜

https://github.com/ZhaZhaFon/demo-speakerseparation/blob/gh-pages/mp4/mix1.mp4

## Model Overview
<img src="imgs/model.png" alt="Overall Architecture" />

## Demo
### Samples from the target female singer.

| 1 | 2 | 3 | 4 | 
| :--- | :--- | :--- | :--- |
| <audio src="wavs/ref/1.wav" controls preload></audio> | <audio src="wavs/ref/2.wav" controls preload></audio> | <audio src="wavs/ref/3.wav" controls preload></audio> | <audio src="wavs/ref/4.wav" controls preload></audio> |
| --- | --- | --- | --- |

| Source | Converted (FastSVC) | Converted (DiffSVC) |
| :--- | :--- | :--- |
| <audio src="wavs/source/0.wav" controls preload></audio> | <audio src="wavs/fastsvc/0.wav" controls preload></audio> | <audio src="wavs/diffsvc/0.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/1.wav" controls preload></audio> | <audio src="wavs/fastsvc/1.wav" controls preload></audio> | <audio src="wavs/diffsvc/1.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/2.wav" controls preload></audio> | <audio src="wavs/fastsvc/2.wav" controls preload></audio> | <audio src="wavs/diffsvc/2.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/3.wav" controls preload></audio> | <audio src="wavs/fastsvc/3.wav" controls preload></audio> | <audio src="wavs/diffsvc/3.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/4.wav" controls preload></audio> | <audio src="wavs/fastsvc/4.wav" controls preload></audio> | <audio src="wavs/diffsvc/4.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/5.wav" controls preload></audio> | <audio src="wavs/fastsvc/5.wav" controls preload></audio> | <audio src="wavs/diffsvc/5.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/6.wav" controls preload></audio> | <audio src="wavs/fastsvc/6.wav" controls preload></audio> | <audio src="wavs/diffsvc/6.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/7.wav" controls preload></audio> | <audio src="wavs/fastsvc/7.wav" controls preload></audio> | <audio src="wavs/diffsvc/7.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/8.wav" controls preload></audio> | <audio src="wavs/fastsvc/8.wav" controls preload></audio> | <audio src="wavs/diffsvc/8.wav" controls preload></audio> | 
| --- | --- | --- |
| <audio src="wavs/source/9.wav" controls preload></audio> | <audio src="wavs/fastsvc/9.wav" controls preload></audio> | <audio src="wavs/diffsvc/9.wav" controls preload></audio> | 
| --- | --- | --- |

## 链接

[[机器人传感与控制研究所](https://ins.seu.edu.cn/26900/list2.htm)] [[生物电子学国家重点实验室](https://sklb.seu.edu.cn/18466/list.htm)]

## 参考资料

