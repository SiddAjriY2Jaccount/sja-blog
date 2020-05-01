---
title: FaceBook OpenEDS Challenge
description: Semantic Segmentation track
#date: "2019-05-02T19:49:05+02:00"
date: "2019"
projectUrl: "TBD"
publishDate: "2019-11-22T19:49:05+02:00"
---

{{< figure src="/research/images/fb-openeds.jpg">}}

<!--more-->
<!--
```YAML
---
title: 
description: 
date: "2019-05-02T19:47:09+02:00"
jobDate: 201
work: []
techs: []
designs: []
thumbnail: 
projectUrl: 
testimonial:
  name: 
  role: 
  image: 
  text: 
---
```
-->
<!--
Here are some explanations about the portfolio FrontMatter:
- `jobDate` is the year displayed on the list and show of your project
- `work` is displayed on the list of projects. It is an array of type of job that you did on the project.
- `techs` and `designs` are displayed on the show page of your project. It is an array of tools you used on the project
- `thumbnail` is a image file displayed both for the list and show of the project
- `projectUrl` is the URL to the project.
- The `testimonial` params define the person giving your a testimonial as well as the text of the testimonial.

NB: if `techs`, `designs` or `projectUrl` is not defined, it will not be displayed at all.
-->

Using open sourced Eye Dataset provided by FaceBook, Semantic Segmentation was performed to identify four classes in an eye image: sclera, iris, pupil and the background. We were able to develop a model using an Encoder-Decoder network with Skip Connections approach to reduce model complexity that was able to beat the baseline model provided by FaceBook.

Find my research profile [here](https://drive.google.com/file/d/1xrek9nFKP0BwowGDtie0HO1WMxH0aRPh/view?usp=sharing).
