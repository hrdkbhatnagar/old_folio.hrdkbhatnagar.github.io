---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
order: 2
---

##### **Linking saliency with modulations along the visual processing hierarchy**
*Oct 2022 - Present* 

*University of Tübingen, Germany*

As a research assisstant under Prof. Andreas Bartels, my focus is on analyzing a large fMRI dataset (the NSD dataset) to create "brain-derived" deep learning models for activity prediction. I am currently designing saliency metrics for stimuli and identifying correlations with retinotopic activity in visual, parietal, and prefrontal regions of the brain. As part of the project, I am also conducting a comparative analysis of high versus low-level model predictions for spatial modulations in the cortex, with a specific focus on model complexities. 

---
##### **Inferring neuronal computation from partial observations**
*Feb - Aug 2022* 

*Allen Institute of Brain Sciences, Seattle*

Under [Prof. Kaspar Podgorski](https://alleninstitute.org/what-we-do/brain-science/about/team/staff-profiles/kaspar-podgorski/), I investigated methods for inferring a neuron's computations from incomplete observations of its inputs and outputs. Using PyTorch, I simulated neurons as hierarchical linear-nonlinear models under various conditions, and utilized gradient descent methods to infer the parameters of the simulated neuron. This was part of my work for my master's thesis

---
##### **Investigating the physiology of aging across genetically diverse mouse population**
*Aug 2021 - Jan 2022* 

*EPFL, Switzerland*


Working under [Prof. Johan Auwerx](https://people.epfl.ch/johan.auwerx?lang=en), I analyzed biological time-series data with machine learning and computational modeling. I developed a health index to summarize aging properties across genetically diverse mouse populations, and explored methods for analyzing time-series data across these populations.

---
##### **Cloud Infrastructure Automation for Health Checks and Maintenance**
**
*May - July 2021* 

*ServiceNow, Hyderabad, India*

As a software development intern in the cloud computing and development operations (DevOps) team, I worked on a proprietary cloud infrastructure platform for monitoring the health of cloud instances and load balancing. I developed tools for automating cloud instance health checks and maintenance.

---
##### **Formal Language Modeling of Biological Networks**
*Aug - Dec 2020* 

*Department of Computer Science, BITS Pilani*

Working under [Prof. Rajesh Kumar](https://www.bits-pilani.ac.in/pilani/rajeshk/profile), I analyzed biological networks such as gene regulatory networks (GRNs) using formal language and automata theory. I focused on fault analysis of GRNs to understand the effects of induced drugs, and modeled stochasticity in GRNs using probabilistic boolean networks.

---

##### **Machine Learning for Coronary Heart Disease Prediction**
*Aug - Dec 2020* 

*Department of Biological Sciences, BITS Pilani*

Working under [Prof. Syamantak Majumder](https://www.bits-pilani.ac.in/pilani/syamantakmajumder/profile), I used machine learning and deep learning models to understand the biological parameters influencing heart diseases. I compared various models for their performance in predicting coronary heart disease using data from hospital patients.

---

##### **Analysis of the neural patterns betweeen face and shape recognition**
*Neuromatch Academy*

*July 2020* 

The [Neuromatch Academy](https://www.neuromatchacademy.org/) was a summer school where we were trained on learning computational tools and apply them to real-life neuroscience research problems. Some of the topics which interested me the most were dynanimcal networks, bayesian statistics, and optimal control. As part of the group project, we worked on the [Human Connectome Project (HCP)](https://www.humanconnectome.org/study/hcp-young-adult/data-releases) dataset, where we analysed the neural patterns between face and shape recognition in the brain.

---

##### **Protein engineering with deep learning**
*RWTH Aachen University, Germany*

*May - July 2020*

I worked as a research intern at the [Institute of Biotechnology](https://www.biotec.rwth-aachen.de/cms/~imne/BIOTEC/lidx/1/) under Prof. Mehdi D. Davari. I worked on the prediction of biophysical properties of enzymes created through directed evoultion, a process mimicking natural selection. I experimented with various machine learning and deep learning models for choosing the best performing model for the required task, and analyzed high throughput data for protein mutation samples. 

---

##### **Machine learning for cancer prognosis using biomedical image data**
*Department of Biological Sciences, BITS Pilani*

*May - July 2020*

I worked under [Prof. Meghana Tare](https://www.bits-pilani.ac.in/pilani/meghanatare/profile) to analyze biomedical image samples with machine learning and deep learning models. I performed biomedical image segmentation with the help of convolutional neural networks, and classified the MR images using the 3-D voxel data.

---

##### **Custom JupyterHub AWS instance with automated load balancing using Kubernetes**
*UST Global, Trivandrum, India*

*May - July 2019*

I worked as a software development intern at the research center of the company, Infinity Labs. I worked on developing a proof of concept AWS JupyterHub cluster using Kubernetes for internal company resources to explore and prototype machine learning models without local installation and dependices. I also worked on automating the load management for each user's instance, along with a custom login protocol based on an internal authentication method of the organization.

<!--
<div class="projects grid">

  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title text-lowercase">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
          <div class="row ml-1 mr-1 p-0">
            {% if project.github %}
            <div class="github-icon">
              <div class="icon" data-toggle="tooltip" title="Code Repository">
                <a href="{{ project.github }}" target="_blank"><i class="fab fa-github gh-icon"></i></a>
              </div>
              {% if project.github_stars %}
              <span class="stars" data-toggle="tooltip" title="GitHub Stars">
                <i class="fas fa-star"></i>
                <span id="{{ project.github_stars }}-stars"></span>
              </span>
              {% endif %}
            </div>
            {% endif %}
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div>
-->


