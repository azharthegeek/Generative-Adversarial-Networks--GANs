# GAN_s 
## __Generative Adversarial Network__ __Introduction & Outlook__

#                                   Abstract
Generative Adversarial Networks, or GANs for short, are a method to generative modeling using deep learning approach Unsupervised learning, such as convolutional neural networks. Recently, generative adversarial networks (GAN) have become one amongst the foremost popular topics in artificial intelligent field. Its outstanding ability of generating realistic samples. Encourage by two-player zero-sum game, GANs consist of a generator and a discriminator both trained under the adversarial learning approach. The goal of GANs is to judge the distribution of real data samples and generate new samples from scratch from that distribution. Since their initiation, GANs have been widely studied due to their massive perspective for applications, including images and vision computing, speech and languages processing, etc. In this review paper, I try to summarize the GAN and its applications. 

 #                                Introduction
Generative adversarial networks, or (G A Ns), are a very powerful type of neural network used for unsupervised machine learning process. Made up of two rival(competing) models which run in competition with one another, GANs are capable to capture and copy difference within a dataset. They are excellent for image generation and manipulation, but they can also be deployed for tasks like understanding risk of security and recovery in healthcare and pharmacology. Design by Ian Goodfellow with his partners in 2014.Two neural networks fight with each other in a game to win (just like game theory).

#                     How do Generative Adversarial Networks work?
Let’s start with a simple analogy(likeness). You have a painting – say the Mona Lisa – and we have a master forger who want to make a duplicate painting of it. The forger does this by learning how the original painter – Leonardo Da Vinci – designed the painting.

Meanwhile, you have an investigator who trying to capture the forger & second guess the rules 
the forger is learning from real dataset.

The forger is that the generator network used to map this onto the architecture of a GAN, which learns the distribution(allocation) of classes used while the investigator is the discriminator network, which learning the boundaries between those classification – the formal 'shape' of the 
dataset. 

   ##                          Applications of GANs
Generative adversarial networks are used for a different number of multiple purposes some are discuss below.

 ##                           |. Using GANs for Security
The rise of AI has been wonderful for many industries. But there’s a true concern that has shadowed the whole AI revolution – cyber threats. Even deep neural networks are vulnerable to being hacked. A constant concern of industrial applications is that they should be strong to cyber-attacks. There’s a lot of confidential information on the line! GANs are proving to be of vast(massive) help here, directly addressing the concern of “adversarial attacks”. These adversarial attacks use a variety of techniques to fool deep learning architectures. GANs are used to make existing deep learning models more tough to these techniques. How? By creating more such fake examples and training the model to recognize them. Pretty clever stuff. One of the examples is Google brain project.

###                               Google brain project
One of the best examples of GAN is a google brain project back in 2016 – researchers used
it develops a method of encryption.

This process used 3 neural networks – Alice, Bob, and Eve. Alice’s job is to send an encrypted message to Bob. Bob’s job is to decode that message, while Eve’s job is to intercept it.

To start with Alice’s messages were smartly intercepted(catch) by Eve. However, due to Eve’s adversarial work, Alice began to develop its own encryption strategy – it takes 15,000 runs for
Alice to successfully encrypt a message that could be decode by Bob that Eve couldn’t intercept.

  ##                           ||. GANs In Medical
GANs are also being used in fields such as drug Structure research providing awesome results day by day. The neural networks can be trained on the existing drugs Structures and suggest new synthetic chemical structures that improve on drugs that exist already.

  ##                          |||. GANs for Image editing
Most image editing software these days don’t give us much freedom to make creative changes in pictures. For example, let’s say you want to change the appearance of a 90-year-individual by changing his / her hairstyle. This can’t be done by the current image editing Software’s out there. But guess what? using generative network, we can recreate images and attempt to change the appearance easily and drastically with many features.

   ##                      IV.GANs for 3D Object Generation
It won’t surprise you understanding GANs are quite popular within the gaming industry rise drastically. Game designers work countless hours recreating 3D avatars and backgrounds 
to give them a realistic feel. And let me assure you, it certainly takes a lot of effort to form 3D models by imagination. Does this sound unrealistic?. You might believe the incredible power of GANs, wherein they can be used to automate the entire process easily!
we suggest you watch this video >https://raw.githubusercontent.com/maxorange/pix2vox/master/img/sample.gif

 ##                           In the end Remember
As we have notice, GANs offer some really outstanding exciting opportunities in AI.
There are two key benefits you need to remember about it: GANs solve the complication of generating data when you don’t have enough data to begin with & second, they require no human supervision (Unsupervised learning).

 ##                              Conclusion
In this paper, we seen the state of the art of GANs. Since the proposal of GAN in 2014 by lan Goodfellow have become a research focus of AI. The core idea of GANs is taken from two-player zero-sum game in game theory. A GAN usually comprises on a generator and a 
discriminator. The ability to generate “infinite” new samples from distribution has excellent application value in numerous fields such as image and vision computing, language processing
and speech, and information security. GANs are comparatively new and still require
some research to reach their new potential. Researchers should struggle to develop better theoretical understanding and improve training algorithms for this framework. Success of GANs on this front would improve many other applications. GANs are crucial and have the potential to produce many other applications in the future.

# Hand on Experience

## IBM GAN demonstration
link
>https://gan-paint-demo.mybluemix.net/?cm_mc_uid=18442949964915524319331&cm_mc_sid_50200000=60398911561414360866&cm_mc_sid_52640000=69930581561414360872


# 3D sketch-modeling demonstration

link

> https://sketch-modeling.com/

# Concept clearing resources 

## Neural Network

> https://youtu.be/bfmFfD2RIcg

## Convolutional neural networks(pixels filtering numbers set of values) (used in face recognition)

> https://youtu.be/jwpSMg6Ebp0

## Convolution operation

> https://youtu.be/Be15A_GJrL4?list=PLxlkzujLkmQ8YYNaQx_iRGjuQkvuz2H9w

## Game theory

> https://youtu.be/WOe0pBO25_o

## Minmax algorithm or game

> https://youtu.be/bOxdGdu1suk

## 3D GAN resources zoo

> https://tmoriya.com/

# References

GAN’s: Introduction and Outlook by Kunfeng Wang, Member, IEEE, Chao Gou, Yanjie Duan, Yilun Lin, Xinhu Zheng,
and Fei-Yue Wang.

>https://www.researchgate.net/publication/320827528_Generative_Adversarial_Networks_Introduction_and_Outlook  (Research paper link)

Invertible Conditional Generative adversarial networks for image editing by Joost van de Weijer, Bogdan Raducanu, Jose M. Álvarez, Guim Perarnau.

> https://arxiv.org/pdf/1611.06355.pdf (Research paper link)

Image-to-Image Translation with Conditional Adversarial Networks by Jun-Yan Zhu,Tinghui Zhou, Alexei A. Efros, Phillip Isola

> https://arxiv.org/pdf/1611.07004v3.pdf (Research paper link)

other helpful sites

> https://hub.packtpub.com/

> https://www.youtube.com/	

> https://www.analyticsvidhya.com/

# Papers List Published on GAN’s  150+:

> https://github.com/zhangqianhui/AdversarialNetsPapers

## Built with ❤︎

> If you Think This File Need Improvement Pull a request or share suggestion at azharthegeek@gmail.com

More Material on GAN's is Available on second Branch of this Respositery.(More data update soon) 
