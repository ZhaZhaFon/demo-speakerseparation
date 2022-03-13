# <center>对话场景说话人分离与理解关键技术研究</center>

<center>招梓枫<sup>1</sup>, 朱利丰<sup>1, 2</sup></center> 

<center> 1 机器人传感与控制研究所, 东南大学, 南京 </center>

<center> 2 生物电子学国家重点实验室, 东南大学, 南京 </center>

## 介绍
Singing voice conversion (SVC) is one promising technique which can enrich the way of human-computer interaction by endowing a computer the ability to produce high-fidelity and expressive singing voice.
In this paper, we propose DiffSVC, an SVC system based on denoising diffusion probabilistic model. DiffSVC uses phonetic posteriorgrams (PPGs) as content features. A denoising module is trained in DiffSVC, which takes destroyed mel spectrogram produced by the diffusion/forward process and its corresponding step information as input to predict the added Gaussian noise. We use PPGs, fundamental frequency features and loudness features as auxiliary input to assist the denoising process. Experiments show that DiffSVC can achieve superior conversion performance in terms of naturalness and voice similarity to current state-of-the-art SVC approaches.

## 效果演示

#### 2说话人语音分离

| <center>分离Hillary Clinton</center> | <center>分离Donal Trump</center> | <center>原始视频</center> |
| :--- | :--- | :--- |
|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050310-b2ac9e8d-af49-4f49-952d-daf7e26a9874.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050310-b2ac9e8d-af49-4f49-952d-daf7e26a9874.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050314-614f801e-ca74-4b17-8ce4-ea1b79f81908.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050586-695be9e2-425e-40bf-95eb-bc56ed87818e.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050590-961c1b8c-31f4-4eb0-b5df-ca310fc9408f.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050584-3546465b-dee5-4723-b305-0700743f27f1.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050627-70f05787-0d4e-4bd7-b385-f6a95f975813.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050631-9704acbd-d84a-4079-b6df-60e0c751d870.mp4" type="video/mp4"></videos>|<video id="video" controls preload poster=""><source id="mp4" src="https://user-images.githubusercontent.com/87401944/158050624-37ab323d-f657-41e5-8086-07e944a73b57.mp4" type="video/mp4"></videos>|

<!---
https://user-images.githubusercontent.com/87401944/158050264-d92fb19b-fd1a-48ba-842a-cb50e7a6e5a7.mp4
https://user-images.githubusercontent.com/87401944/158050310-b2ac9e8d-af49-4f49-952d-daf7e26a9874.mp4
https://user-images.githubusercontent.com/87401944/158050314-614f801e-ca74-4b17-8ce4-ea1b79f81908.mp4

https://user-images.githubusercontent.com/87401944/158050586-695be9e2-425e-40bf-95eb-bc56ed87818e.mp4
https://user-images.githubusercontent.com/87401944/158050590-961c1b8c-31f4-4eb0-b5df-ca310fc9408f.mp4
https://user-images.githubusercontent.com/87401944/158050584-3546465b-dee5-4723-b305-0700743f27f1.mp4

https://user-images.githubusercontent.com/87401944/158050627-70f05787-0d4e-4bd7-b385-f6a95f975813.mp4
https://user-images.githubusercontent.com/87401944/158050631-9704acbd-d84a-4079-b6df-60e0c751d870.mp4
https://user-images.githubusercontent.com/87401944/158050624-37ab323d-f657-41e5-8086-07e944a73b57.mp4
-->

* 分离Hillary Clinton  

https://user-images.githubusercontent.com/87401944/158022952-ce15ce3f-3867-4e5f-897f-544be3a96028.mp4 

* 分离Donal Trump  

https://user-images.githubusercontent.com/87401944/158022954-6ccc6c05-3d8b-4a2b-9560-05d8e8f022b2.mp4

* 原始视频  

https://user-images.githubusercontent.com/87401944/158022959-446d2e86-1aba-4ace-a6fa-f4f105f973b1.mp4

## 链接

[[机器人传感与控制研究所](https://ins.seu.edu.cn/26900/list2.htm)] [[生物电子学国家重点实验室](https://sklb.seu.edu.cn/18466/list.htm)]

## 参考资料

