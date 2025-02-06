---
layout: project
permalink: /spotthatplaneblog/
category: projects

project:
  title: "Spot that Plane"
  type: "Personal Project"
  logo: "/assets/images/projects/spotthatplane/thumb.png"

images:
  - image:
    url: "/assets/images/projects/spotthatplan/thumb.png"
    alt: ""
  - image:
    url: "/assets/images/projects/spotthatplane/spotthatplane.gif"
    alt: ""

---
<p style="margin-bottom: 20px;">Your personal plane-spotting assistant.</p>

<p style="margin-bottom: 5px;">Live website: 
  <a href="https://hi1van.github.io/spotthatplane" target="_blank">https://hi1van.github.io/spotthatplane</a>
</p>

<p style="margin-bottom: 5px;">GitHub repo: 
  <a href="https://github.com/hi1van/spotthatplane" target="_blank">https://github.com/hi1van/spotthatplane</a>
</p>

<p style="margin-bottom: 5px;">Gradio app hosted on Hugging Face: 
  <a href="https://huggingface.co/spaces/ivanczhuang/SpotThatPlane" target="_blank">https://huggingface.co/spaces/ivanczhuang/SpotThatPlane</a>
</p>
<p style="margin-bottom: 5px;">Kaggle Jupyter Notebook on model training: 
  <a href="https://www.kaggle.com/code/ivanczhuang/spotthatplane" target="_blank">https://www.kaggle.com/code/ivanczhuang/spotthatplane</a>
</p>
<p style="margin-bottom: 20px;">GitHub repo for the Gradio app powered the model: 
  <a href="https://github.com/hi1van/SpotThatPlaneGradio" target="_blank">https://github.com/hi1van/SpotThatPlaneGradio</a>
</p>


<p style="margin-bottom: 10px;">Project Background</p>

<p style="margin-bottom: 10px;">Combining two interests of mine, deep learning models and plane-spotting, Spot that Plane is 
an assistant of sorts, helping you classify a model of aircraft you may be unsure about out of a given selection.</p>

<p style="margin-bottom: 10px;">Harnessing PyTorch and fast.ai, a deep learning model was trained on a data set of almost 3000 
images of aircraft in the selection. After training, an error-rate of ~11% was achieved, accurate
enough for the purposes of this website and my experiment.</p>

<p style="margin-bottom: 20px;">You can view the process of training the model and some insights in the Kaggle link.</p>

<p style="margin-bottom: 10px;">Tools</p>

<p style="margin-bottom: 60px;">
- Frontend: React, Bulma<br>
- Backend: Gradio app hosted on Hugging Face<br>
- Hosting: GitHub Pages (for frontend), Hugging Face Spaces (for backend)<br>
- Modeling Training: PyTorch, fast.ai<br>
- UI/UX Design: Figma<br>
- Other: Hugging Face @gradio/client for API calls, Kaggle for model training and insights<br>
</p>