---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: page
---


<div class="id" align="center">
  <font size="+3">Jose Costa Pereira</font>
</div> 

<br>

__Hello, and welcome to my webpage!__


<img src="/assets/jose.jpg" align="right" width="300px"/>
I’m an Assistant Professor at the University of Porto, Portugal. 
You can find me at the [School of Engineering (FEUP)](https://www.up.pt/feup/en/){:target="_blank"}, 
office [D106](https://sigarra.up.pt/feup/en/instal_geral.espaco_view?pv_id=73675){:target="_blank"}.
<br>
If you’ve landed here, chances are you’re interested in my research 
-- below is a brief overview. Feel free to reach out!
<br>
<div class="social-links">     
  {%- include social.html -%}  
</div> 

<br clear="right"/>



[//]: # (FEUP --> https://www.up.pt/feup/	)
[//]: # (CSE  --> https://dei.fe.up.pt/		)

[//]: # (Hello and a warm welcome to my webpage! 			)
[//]: # (I'm an Assistant Professor at University of Porto, Portugal. 	)
[//]: # (based in the School of Engineering, CSE department. 		)
[//]: # (You can find me at the School of Engineering, CSE department. 	)
[//]: # (Presumably, you found yourself in this page because you wanted )
[//]: # (to know more about my research interests. 			)
[//]: # (Below you can find a brief overview; feel free to reach out.	)





<p>&nbsp;</p>

Before joining the University of Porto, I spent six years as a Senior 
Research Scientist at Huawei Technologies in London, UK. 
At the Noah’s Ark Lab, part of Huawei’s R&D division, 
I focused heavily on computational photography, 
particularly _Image-to-Image Restoration_ techniques and 
_No-Reference Image Quality Assessment (NR-IQA)_ from a perceptual standpoint. 
While many solutions have been proposed to tackle these challenges 
-- some with great success -- creating a robust NR-IQA model that 
reliably mimics the human visual system (HVS) remains an open problem, 
especially for images in the wild. 
_Image Quality Assessment (IQA)_ aims to bridge this gap, but we’re still 
far from a perfect solution.

[//]: # (Before joining University of Porto, I worked for six years as a Senior 	)
[//]: # (Research Scientist at Huawei Technologies R&D in London, UK. 			)
[//]: # (At the _Noah’s Ark Lab_ -- a group of the R&D division -- 			)
[//]: # (where the focus was heavily placed on computational photography. 		)
[//]: # (I learned to appreciate image-to-image restoration techniques, 		)
[//]: # (and _no-reference_ image quality metrics from a perceptual standpoint. 	)
[//]: # (Many solutions have been proposed to tackle these problems and, to a certain 	)
[//]: # (extent, with great success.							)
[//]: # (But designing a no-reference image quality metric -- also known as NR-IQA 	)
[//]: # (or B-IQA -- remains a problem which is largely unsolved for images in the wild.)
[//]: # (As one can imagine it is very difficult to come-up with a model that mimics 	)
[//]: # (the human visual system HVS in terms of opinions about image quality. 		)
[//]: # (And this is, ultimately, the goal of _Image Quality Assessment IQA_.		)



[//]: # (Beyond IQA, I’m also interested in Generative AI, particularly Transformer architectures, attention mechanisms, and Stable Diffusion for generating realistic images and videos. More broadly, I enjoy exploring Intelligent Systems—whether it’s AI automating everyday tasks [e.g., copilot-style assistants] or advancing expert-level knowledge [e.g., AI for medical diagnosis]. The rise of AI systems is transforming our daily lives in ways that seemed impossible just a few years ago. )

During my time at INESCTEC, I collaborated with students and researchers on developing 
Computer-Aided Diagnosis/Detection (CADx/e) tools for breast cancer screening. 
The widespread use of digital imaging with annotations in medical diagnosis, 
combined with the success of deep learning in visual recognition, 
has driven the development of many practical medical imaging applications.
Also, recent advancements in large language models (LLMs) have
ushered in a new era of AI -- one where we have yet to define the boundaries of what’s possible.
Generative AI with the ubiquitous 
[_Transformer architecture and its attention mechanisms_](https://papers.nips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html){:target="_blank"}, 
and [_Stable Diffusion_](https://arxiv.org/abs/2112.10752){:target="_blank"}
for generation of realistic images (and videos) are topics that
I also follow closely.
More broadly, I enjoy exploring _'Intelligent Systems'_.
From automation of everyday tasks (_e.g._ copilot-style assistants) 
to _expert-level_ knowledge (_e.g._ AI medical diagnosis); 
the rise of AI systems is transforming our daily lives in ways that seemed 
impossible just a few years ago.


[//]: # (In general, I like all solutions that lead to more )
[//]: # (our everyday life is seeing an explosion of AI systems that help us in ways that we would consider impossible a few years back. )
[//]: # (At INESCTEC, within the VCMI group, I collaborated with students and other 		)
[//]: # (researchers in the development of new CADx/e [Computer Aided Diagnosis/Detection]	)
[//]: # (tools for breast cancer screening. 							)
[//]: # (Given the success of deep learning frameworks in many visual recognition 		)
[//]: # (tasks, these tools are being extensively used in medical imaging applications. 	)
[//]: # (And of course, recent advancements in _language models_ have started			)
[//]: # (a new era in intelligent systems; one where we cannot yet place 			)
[//]: # (a boundary...										)




Before the recent deep learning revolution, extracting meaningful, machine-friendly image representations was a challenging problem. 
Unlike text, which could be handled relatively well with a simple bag-of-words, images lacked a similarly effective descriptor. 
It all changed in 2012 with [Alex Krizhevsky](https://scholar.google.com/citations?user=xegzhJcAAAAJ){:target="_blank"} et al.'s groundbreaking paper 
on [_"ImageNet Classification with Deep Convolutional Neural Networks"_](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html){:target="_blank"}. 
It was a turning point for computer vision. 
Initially, I saw CNNs as powerful feature extractors but felt they lacked the semantic richness of text embeddings. 
Today, however, the search for unified multimodal representations -- for text, images, audio, and video -- is more active than ever. 
Finding accurate, descriptive, and robust representations is crucial for any intelligent system, making this an exciting area of research.

[//]: # (Before this modern-age of [convolutional] neural networks,			)
[//]: # (it was somewhat difficult to come-up with machine-friendly descriptors 	)
[//]: # (that were representative of an image; what is known today as an image 		)
[//]: # (embedding. In clear contradiction with text snippets, where a simple 		)
[//]: # (bag-of-words descriptor [with a decent vocabulary size and some smart 		)
[//]: # (pre-processing] would do the trick.						)
[//]: # (A big breakthrough was achieved with the paper on 				)
[//]: # ([_"ImageNet Classification with Deep Convolutional Neural Networks"_][https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html]  )
[//]: # (by [Krizhevsky][https://scholar.google.com/citations?user=xegzhJcAAAAJ]	)
[//]: # (_et al._ presented at NIPS 2012. 						)
[//]: # (They showed to the community the benefits of using a convolutional 		)
[//]: # (neural network -- trained on a lot of data -- in solving classical 		)
[//]: # (computer vision problems.							)
[//]: # (At that time I was a bit reluctant in adopting neural networks.		)
[//]: # (Surely I saw them as good feature extractors but still lacking 		)
[//]: # (the semantic interpretation intrinsic to text feature vectors.			)
[//]: # (Today, the quest for finding a unified multimodal representation 		)
[//]: # (for texts, images, audios and videos is more active than ever.			)
[//]: # (I find this to be a very interesting topic of research; a _good_ [i.e. descriptive/accurate/robust]	)
[//]: # (representation of modalities is essential for any task performed by an intelligent system.	)


[//]: # (You can have a look at my scholar profile for more details on my publications.		)
[//]: # (And please reach out if you find any of these topics interesting. My email is below.	)

If any of these topics interests you, feel free to check out my Google Scholar profile for more details on my publications. And don’t hesitate to reach out — my email is below!
