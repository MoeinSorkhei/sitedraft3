---
title: "Research"
layout: text_lay
excerpt: "Research"
sitemap: false
permalink: /research/
---

# Research
<div class="justify">
We are interested to solve problems that lie in the intersection of machine learning and image data, mostly medical images. Recently, an explosion of digitalized data, groundbreaking advances in the life sciences, and the development of cutting-edge algorithms capable of understanding biomedical data, especially from images, have generated terrific excitement around AI and healthcare. Our research revolves around the challenges arising from applying machine learning to medical images. 

The research areas in our group include the following:

<div class="row">
<div class="col-sm-8">
- **deep learning for breast cancer risk assessment and prediction**  
    A crucial application of deep learning models in medical image analysis is their use in analysis of mammographic images. In our group, We utilize these models to solve problems such as breast cancer risk prediction and its relation to actual breast cancer. In this line of research, we trained models that could differentiate between _inherent (long-term)_ and _short-term_ risk of breast cancer. Moreover, we intorduced the concept of _mammographic masking_ and utulized it to develop models that can indicate different types of breast cancers more accurately than other commonly used measure.
</div>
<div class="col-sm-4">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/mammo.png" class="img-responsive" width="100%" style="float: right" />
</div>
</div>

<div class="row">
<div class="col-sm-8">
- **Transferrable deep learning for medical images**  
    Transfer learning of deep neural networks is an exciting field in deep learning with the goal of reusing the knowledge learned by a network in one domain in another domain. This has numerous applications in medical image analysis, especially due to lack of data and the cost of acquiring annotations from medical experts. In this regard, we try to investigate and develop models that can effectively benefit from this technique to solve medical image analysis problems more successfully, considering different aspects such as pre-training setup, architecture type, properties of the target dataset etc.
</div>
<div class="col-sm-4">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/transfer.png" class="img-responsive" width="100%" style="float: right" />
</div>
</div>


<div class="row">
<div class="col-sm-8">
- **Domain adaptation and privacy-preserving machine learning for medical images**
    Privacy concerns are of very important when dealing with medical data, since they can potentially leak information about the subjects in a dataset. Moreover, if trained carelessly, machine learning methods can also leak informaiton about the subjects of the dataset they were trained on. 
    Therefore, machine learning methdos need to be developed reliablly to ensure the privacy of the subjects in medical datasets. We developed a technique that can reliably de-identify faces from brain MRI images without affecting the brain content itself.
</div>
<div class="col-sm-4">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/deidentified_face.png" class="img-responsive" width="100%" style="float: right" />
</div>
</div>


<div class="row">
<div class="col-sm-8">
- **Generalization of deep learning models**
    An important aspect of of deep learning models is their generalization capabitlites. Here we are interested in how different models have different generalization capabilities and what impact this might have with regards to the data complexity. We empircally studied the relation between different model image classification architectures, their scaling, and the data complexity.
</div>
<div class="col-sm-4">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/complexity.png" class="img-responsive" style="float: right" />
</div>
</div>


<div class="row">
<div class="col-sm-8">
- **Assessing malignancy of ovarian tumors using deep learning models**
    Ovarian cancer is one of the deadliest types of cancer, and hence correctly classifying ovarian tumors can potentially save the lives of a lot of patients by optimizing the treatment plan and taking timely measures. In this project, we try to develop and improve reliable deep learning models that can accurately predict malignant ovariant tumors by processing and analysing ultrasound images.
</div>
<div class="col-sm-4">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/ovarian.png" class="img-responsive" style="float: right" />
</div>
</div>
    

<div class="row">
<div class="col-sm-12">
- **Diverse and controllable generative models for domain generalization**
An interesting line of research in the area of generative modeling is the ability to interpret and control the latent space modeled by deep networks. This, in theory, enables us to control data generation according to our desired properties of data points. In this project, the goal is to manipulate and control different parts of the latent space learned by the Glow model through proper conditioning in order to be able to model different properties of the generated image (e.g. a digit class, its rotation degree etc.) in different parts of the latent space.
</div>
</div>


<div class="row">
<div class="col-sm-12">
- **Application of small small transformer models for microscopic cell image analysis**
Since the first successful application of Transformer models in computer vision, the community has been utilizing them in a vairty of applications while improving the efficiency and performance. In this project, we are interested in applying efficient, lightweight transformer models for microscopic image analysis. These models should be able to make reliable predictions based only a subset of tokens related to the most important regions of the image.

</div>
</div>


</div>
