---
title: "Towards a standard experimental protocol"
excerpt: "for open source additive manufacturing"
img-path: /assets/img/projects/Standard-Protocol/
header:
  overlay_image: /assets/img/projects/Standard-Protocol/Teaser.jpg
  overlay_filter: 0.3
  teaser: /assets/img/projects/Standard-Protocol/Teaser.jpg

classes: wide

categories:
  - Research  
  
tags: 
  - Benchmarking
  - 3D Printing
  - Open Source

sidebar:
  - title: "Role"
    image: http://placehold.it/350x250
    image_alt: "logo"
    text: "Designer, Front-End Developer"
  - title: "Responsibilities"
    text: "Reuters try PR stupid commenters should isn't a business model"

gallery:
  - url: /assets/img/projects/Standard-Protocol/Benchmarking/Childs1994.jpg
    image_path: /assets/img/projects/Standard-Protocol/Benchmarking/Childs1994.jpg    
    alt: "Childs1994"
  - url: /assets/img/projects/Standard-Protocol/Benchmarking/Ippolito1995.jpg
    image_path: /assets/img/projects/Standard-Protocol/Benchmarking/Ippolito1995.jpg
    alt: "Ippolito1995"    
  - url: /assets/img/projects/Standard-Protocol/Benchmarking/Johnson2011.jpg
    image_path: /assets/img/projects/Standard-Protocol/Benchmarking/Johnson2011.jpg
    alt: "Johnson2011"    
  - url: /assets/img/projects/Standard-Protocol/Benchmarking/Mahesh2006.jpg
    image_path: /assets/img/projects/Standard-Protocol/Benchmarking/Mahesh2006.jpg
    alt: "Mahesh2006"    
  - url: /assets/img/projects/Standard-Protocol/Benchmarking/Reilly1994.jpg
    image_path: /assets/img/projects/Standard-Protocol/Benchmarking/Reilly1994.jpg
    alt: "placeholder image 2"
  - url: /assets/img/projects/Standard-Protocol/Benchmarking/Scaravetti2007.jpg
    image_path: /assets/img/projects/Standard-Protocol/Benchmarking/Scaravetti2007.jpg
    alt: "placeholder image 3"


feature_row2:
  - image_path: /assets/images/pic04.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---


## Goal of the article:


To propose an experimental protocol in order to characterise the dimensional accuracy of a representative open-source 3D printer, based on Design of Experiments (DoE) and integrating different families of geometrical features. 


## Why is it important?
- Exponential growth of the open-source (OS) 3D Printers.
- Characteristics such as its OS nature, its customisation and self-replication capability, open up the possibility for exponential growth for innovation in both products and 3D printer systems.


<figure class="half">
  <img src="{{ site.baseurl | append: page.img-path | append: '3DP-Growth.jpg' }}" alt="OS-3D Printers growth">
  <img src="{{ site.baseurl | append: page.img-path | append: 'RepRap-Tree.jpg' }}" alt="OS-3D Printers growth">

  <figcaption class="figure-caption">
    <p>Exponential groowth of the OS 3D printers. <a href="https://wohlersassociates.com/2016report.htm" type="text/html"> Source </a></p>  
  </figcaption>
</figure>



## Research Problem

Diferent benchmarking **Methodologies + Geometrical Models** have been proposed in the literature of commercial Additive Manufacturing with the purpose of:

- Comparing AM processes.
- Finding optimal parameters.
- Establishing minimal performance standards.


      
{% include gallery caption="This is a sample gallery to go along with this case study." %}


**Nevertheless** <span style="color:red">for open-source case</span>:

- Little benchmarking methodologies have been proposed.
- Performance between Open-Source and commercial AM was not clarified.

## What is our proposition about?

We propose an experimental **methodology**

1. Dimensional performance of an open-source 3D printer:
  * **XZ**---Plane
  * **Z**---Axis 
  * **D**---Circular features
  * **T**---Thing walls
2. Establishment of optimal manufacturing parameters.



<figure> 
<img src="{{ site.baseurl | append: page.img-path | append: "Methodology.svg" }}" class="align-center" alt="Methodology" style="max-width: 80%">
  <figcaption class="figure-caption">          
    Proposed Methodology for test an open source 3D printer.
  </figcaption>
</figure>




## Our Case Study: The FoldaRap

![image-center]({{ site.baseurl | append: page.img-path | append: 'Foldarap.jpg' }}){: .align-center} 

A derivative machine from the RepRap project called  <a href="http://reprap.org/wiki/FoldaRap" type="text/html"> The FoldaRap </a>  was selected for this investigation. This machine is a representative 3D printer among the set of open source machines developed by the RepRap community.


### A. Geometric Benchmarking Model

<!-- <figure class="half">
  <img src="{{ site.baseurl | append: page.img-path | append: 'Methodology-1.png' }}" class="img-fluid" alt="Methodology" style="width:20%">  
  <img src="{{ site.baseurl | append: page.img-path | append: 'GBM.jpg' }}" alt="Methodology" style="width:70%">  
  <figcaption class="figure-caption">
    <p>Exponential groowth of the OS 3D printers. <a href="https://wohlersassociates.com/2016report.htm" type="text/html"> Source </a></p>  
  </figcaption>
</figure>

This research uses a modified version of the benchmarking model from the National Institute of Standards and Technology (NIST)  <a href="https://sffsymposium.engr.utexas.edu/Manuscripts/2012/2012-69-Moylan.pdf" type="text/html">(Moylan et al. 2012)</a> -->


<img src="{{ site.baseurl | append: page.img-path | append: 'Methodology-1.png' }}" class="img-fluid align-left" alt="" style="width: 15%">  


<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'GBM.jpg' }}"  class="align-center" style="width: 70%">
  <figcaption class="align-right">
  This research uses a modified version of the benchmarking model from the National Institute of Standards and Technology (NIST)  <a href="https://sffsymposium.engr.utexas.edu/Manuscripts/2012/2012-69-Moylan.pdf" type="text/html">(Moylan et al. 2012)</a>
  </figcaption>
</figure>



### B. Design of Experiments


<img src="{{ site.baseurl | append: page.img-path | append: 'Methodology-2.png' }}" class="img-fluid align-left" alt="" style="width: 15%">  


<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'Taguchi.svg' }}"  class="align-center" style="width: 70%">
  <figcaption class="align-right">
  Design of experiments: Taguchi Approach.
  </figcaption>
</figure>


One of the available DoE approaches in the scientific literature is the Taguchi method. It has been proven to be successful for improvement of product quality and process performance. <br> Using Taguchi’s approach, <b>three control factors </b> have been considered in this investigation. 
A reliable estimation of the effect of factors can be obtained by using an orthogonal array with fewer experiments than classical DoE. The appropriate orthogonal array for this experiment is L <sub>9</sub>(3<sup>4</sup>).



### C. Fabrication

<div class="wrapper">
<img src="{{ site.baseurl | append: page.img-path | append: 'Methodology-3.png' }}" class="img-fluid align-left" alt="" style="width: 20%">  


<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'samples.png' }}"  class="align-center" style="width: 70%">
  <figcaption class="align-right">
  Surface quality of the printed samples.
  </figcaption>
</figure>
</div>

18 samples were fabricated according to the Taguchi's table.
- Detailed measurements on the Geometrical Benchmarking Model was made in order to obtain the **percent deviation measurements (&#916;Y)**
  

### D. Results

<div class="wrapper">

<img src="{{ site.baseurl | append: page.img-path | append: 'Methodology-4.png' }}" class="img-fluid align-left" alt="" style="width: 20%">  

<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'Probability-Function.svg' }}"  class="align-center" style="width: 70%">
  <figcaption class="align-right">
  Determination of probabilities of each type of dimensional accuracy
  </figcaption>
</figure>

</div>

<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'IT-Comparison.svg' }}"  class="align-center" style="width: 70%">
  <figcaption class="align-right">
  Determination of probabilities of each type of dimensional accuracy
  </figcaption>
</figure>

1. Precision of the machine
2. Comparison of commercial AM  Vs. open-source machines
3. To find the best compromise of the manufacturing parameters tested


We use RMSD value as an estimator of accuracy. The lower the RSMD value, the higher the precision.

<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'RMSD-1.svg' }}"  class="align-center" style="width: 100%">
  <figcaption class="align-right">
  
  </figcaption>
</figure>

We calculate the frequency of each manufacturing identified as "Best", "Best-2" and "Best-3" 


<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'RMSD-2.svg' }}"  class="align-center" style="width: 100%">
  <figcaption class="align-right">
  
  </figcaption>
</figure>


<figure> 
  <img src="{{ site.baseurl | append: page.img-path | append: 'RMSD-3.svg' }}"  class="align-center" style="width: 100%">
  <figcaption class="align-right">
  
  </figcaption>
</figure>




A <b>*Global Index*</b> of performance is established with three relative weights <em>w<sub>i</sub></em>  for pondering the significance of each type of frequency, giving more importance to the set of frequencies of the factors qualified as the most accurate ("Best")



## Specifics results for our case study:
{% capture notice-text %}
1. There is a 82.14% of probability that the feature's measurement made by the 3D printer are in the range of (-5%,5%) with respect to the CAD measurement
2. International standard tolerance: (IT14 - IT16)
3. Best trade-off: 
  * Layer thickness: 0.18mm
  * Raster width: 0.71mm
  * Nozzle speed movement: 50mm/s

{% endcapture %}

<div class="notice--success">
  <!-- <h4>Notice Headline:</h4> -->
  {{ notice-text | markdownify }}
</div>


{% include feature_row id="feature_row2" type="left" %}

