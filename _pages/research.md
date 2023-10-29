---
title: "Research"
layout: text_lay
excerpt: "Research"
sitemap: false
permalink: /research/
---

<!-- # Research -->
<!-- alternatives: fa-vial fa-microscope fa-flask fa-atom fa-brain fa-microchip-->
<h1> <i class="fa fa-microchip"></i>&nbsp; Research</h1>
<br>

<div class="justify">
We are interested to solve problems that lie in the intersection of machine learning and image data, specifically medical images. Below we list the main areas of research our group works on. For a full list of publications, please visit the [Publications](../publications) page!
<!-- Recently, an explosion of digitalized data, groundbreaking advances in the life sciences, and the development of cutting-edge algorithms capable of understanding biomedical data, especially from images, have generated terrific excitement around AI and healthcare. Our research revolves around the challenges arising from applying machine learning to medical images.  -->

The research areas in our group include:

<div class="row">
<div class="col-sm-6">
<!-- **Deep learning for breast cancer risk assessment and prediction**   -->
<h3>Deep learning for breast cancer risk assessment</h3>
A crucial application of deep learning methods in medical image analysis is their application in analysis of mammographic images. 
In this regard, we have developed deep learning models capable of predicting breast cancer risk. Introducing a novel mammographic dataset (CSAW-M) containig expert radiologist assessments on _mammographic masking_, we were able to develop models capable of predicting interval breast cancer considerably better than other commonly used methods.
</div>
<div class="col-sm-6">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/mammo_2.png" class="img-responsive" width="90%" style="float: right" />
</div>
</div>


<div class="row">
<div class="col-sm-6">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/transfer_2.png" class="img-responsive" width="90%" style="float: left" />
</div>
<div class="col-sm-6">
<!-- **Transferrable deep learning for medical images**   -->
<h3>Transferrable deep learning for medical image analysis</h3>
Transfer learning is concerned with transferring the knowledge learned in one task to another as to improve the performance. Our group works on better understanding of when transfer learning actually works, especially in the medical domain.
In this regard, our works have shed some light on the role of feature reuse, properties of network architecture and dataset. 
Further, we try to develop models that can use transfer learning effectively to solve better medical image problems.
</div>
</div>


<!-- <br> -->
<div class="row">
<div class="col-sm-6">
<!-- - **Domain adaptation and privacy-preserving machine learning for medical images**   -->
<h3>Privacy-preserving machine learning for MRI images</h3>
Privacy concerns are paramount importance when dealing with medical data, as this type of data typically contains sensitive information about the subjects. If trained carelessly, machine learning models can also leak informaiton about the subjects of the dataset they were trained on. 
The works from our group led to a technique that can reliably de-identify brain MRI images.
<!-- In this regard, we developed a technique that can reliably de-identify brain MRI images. -->
<!-- Therefore, machine learning methdos need to be developed reliablly to ensure the privacy of the subjects in medical datasets.  -->
<!-- faces from brain MRI images without affecting the brain content itself. -->
</div>
<div class="col-sm-6">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/deidentified_face.png" class="img-responsive" width="90%" style="float: right" />
</div>
</div>

<br>
<div class="row">
<div class="col-sm-6">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/ovarian.png" class="img-responsive" style="float: left" />
</div>
<div class="col-sm-6">
<!-- - **Ovarian tumor assessment using deep learning**   -->
<h3>Ovarian cancer assessment using deep learning</h3>
Ovarian cancer is one of the deadliest types of cancer, and hence timely prediction of ovarian tumors can potentially save the lives of quite a few patients by allowing for taking proper measures to optimize their treatment plan.
<!-- by optimizing their treatment plan and taking proper measures.  -->
In this project, we try to develop and improve reliable deep learning models that can accurately predict ovarian tumors based on ultrasound images.
</div>
</div>

<br>
<div class="row">
<div class="col-sm-6">
<!-- - **Generalization of deep learning models**   -->
<h3>Generalization of deep learning models</h3>
An important aspect of of deep learning models is their generalization capabitlites. 
<!-- Here we are interested in how different models have different generalization capabilities and what impact this might have with regards to the data complexity. We empircally studied the relation between different model image classification architectures, their scaling, and the complexity. -->
In this regard, we have proposed an empirical study of how neural networks handle data complexity by investigating several modern architectures with different capacities as the complexity of data increases, exhibithing the log-linear relationship between data complexity and validation accuracy.
</div>
<div class="col-sm-6">
<img src="{{ site.url }}{{ site.baseurl }}/images/research_pic/complexity.png" class="img-responsive" style="float: right" />
</div>
</div>


</div>
