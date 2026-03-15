---
title: About
layout: page
---
<img
  id="profile-img"
  src="{% if site.external-image %}{{ site.picture_hd }}{% else %}{{ site.url }}/{{ site.picture_hd }}{% endif %}"
  data-hover="{% if site.external-image %}{{ site.picture_hd | replace: 'profile_793', 'profile_793_hover' }}{% else %}{{ site.url }}/{{ site.picture_hd | replace: 'profile_793', 'profile_793_hover' }}{% endif %}"
  data-default="{% if site.external-image %}{{ site.picture_hd }}{% else %}{{ site.url }}/{{ site.picture_hd }}{% endif %}"
  title="'Dr. Hu' in a parallel universe."
  alt="Profile Image"
  onmouseover="this.src=this.dataset.hover"
  onmouseout="this.src=this.dataset.default"
/>

<p>Edward Hu is incubating companies in Woodside, CA with <a href="https://www.drw.com/updates/insights/about-don-wilson">Don R. Wilson</a> and <a href="https://www.linkedin.com/in/suna-said-66985918">Suna Said</a>. He was a researcher at OpenAI, where he worked on o1, and received his Ph.D. in Computer Science under the supervision of <a href="https://yoshuabengio.org/">Yoshua Bengio</a>, a recipient of the 2018 A.M. Turing Award. His Ph.D. thesis in on "Building a Reasoning Machine."</p>

<p>Before graduate school, Edward was a researcher at Microsoft, where he invented <a href="https://github.com/microsoft/LoRA">LoRA</a>, <a href="https://github.com/microsoft/mup">μP (muP)</a>, and <a href="https://www.microsoft.com/en-us/research/blog/%C2%B5transfer-a-technique-for-hyperparameter-tuning-of-enormous-neural-networks/">μTransfer</a>. LoRA is now the industry standard for customizing AI models, and μTransfer is underpinning the largest AI model training runs today.</p>

<h2>Selected Publications</h2>

<ul class="publications">
	LoRA: Low-Rank Adaptation of Large Language Models<br>
	<i>ICLR 2022</i><br>
	[<a href="https://arxiv.org/abs/2106.09685">Paper</a> | <a href="https://www.youtube.com/watch?v=DhRoTONcyZE">Video</a> | <a href="https://github.com/microsoft/LoRA">Code</a> | Mentioned in <a href="https://blogs.microsoft.com/ai-for-business/ai-at-scale-technology/#:~:text=We%20also%20developed,or%20downstream%20task.">"The innovation behind AI at Scale"</a>]<br>
	<br>
	Amortizing Intractable Inference in Large Language Models<br>
	<i>Outstanding Paper Honorable Mention at ICLR 2024</i><br>
	[<a href="https://arxiv.org/abs/2310.04363">Paper</a> | <a href="https://github.com/GFNOrg/gfn-lm-tuning">Code</a>]<br>
	<br>
	μTransfer: Tuning Large Neural Networks via Zero-Shot Hyperparameter Transfer<br>
	<i>NeurIPS 2021</i><br>
	[<a href="https://arxiv.org/abs/2203.03466">Paper</a> | <a href="https://www.microsoft.com/en-us/research/blog/%c2%b5transfer-a-technique-for-hyperparameter-tuning-of-enormous-neural-networks/">Blog</a> | <a href="https://github.com/microsoft/mup">Code</a> | <a href="https://www.youtube.com/watch?v=z8-C42mAwBc">Video</a> | <a href="https://www.theregister.com/2022/03/14/microsoft_openai_mutransfer/">TheRegister</a> | <a href="https://www.techradar.com/news/microsoft-openai-may-have-solved-a-fundamental-ai-bottleneck">TechRadar</a> | <a href="https://analyticsindiamag.com/interview-with-the-team-behind-microsofts-%C2%B5transfer/">AIM</a>]<br>
	<br>
	μP: Feature Learning in Infinite-Width Neural Networks<br>
	<i>ICML 2021</i><br>
	[<a href="https://arxiv.org/abs/2011.14522">Paper</a> | <a href="https://www.microsoft.com/en-us/research/blog/on-infinitely-wide-neural-networks-that-exhibit-feature-learning/">Blog</a> | <a href="https://github.com/edwardjhu/TP4">Code</a>]<br>
	<br>
	Improved Image Wasserstein Attacks and Defenses<br>
	<i>Best Paper at ICLR Trustworthy ML Workshop 2020</i><br>
	[<a href="https://arxiv.org/abs/2004.12478">Paper</a> | <a href="https://github.com/edwardjhu/improved_wasserstein">Code</a>]<br>
</ul>
<br>