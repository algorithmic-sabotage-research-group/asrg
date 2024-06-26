---
title: Police Officers Faces (POF)
title_h1: Police Officers Faces (POF)
description: A large-scale face recognition dataset containing of approximately 90,000 headshot photos of thousands of police officers. This dataset is intended as a tool to empower community members engaged in copwatch and other counter-surveillance practices.
bookToc: false
url: /police_officers-faces-pof
date: 2024-06-17
modified: 2024-06-28
Tags: ['Counter Surveillance', 'Scrapism', 'Copwatch', 'Social Engineering', 'OSINT', 'Artivism']
images:
- images/output-787.png
---

{{< titling >}}

{{< columns >}} 

<div class="caption"><img src="images/output-274.gif">One hundred sample images from the “POF” face recognition dataset. <span style="color:grey">Faces have been redacted to protect privacy.</span></div>

<--->

<div class="caption"><img src="images/output-367.gif">One hundred sample images from the “POF” face recognition dataset. <span style="color:grey">Faces have been redacted to protect privacy.</span></div>

<--->

<div class="caption"><img src="images/output-536.gif">One hundred sample images from the “POF” face recognition dataset. <span style="color:grey">Faces have been redacted to protect privacy.</span></div>

{{< /columns >}}

{{< columns >}} 

<div class="caption"><img src="images/output-719.gif">One hundred sample images from the “POF” face recognition dataset. <span style="color:grey">Faces have been redacted to protect privacy.</span></div>

<--->

<div class="caption"><img src="images/output-827.gif">One hundred sample images from the “POF” face recognition dataset. <span style="color:grey">Faces have been redacted to protect privacy.</span></div>

<--->

<div class="caption"><img src="images/output-897.gif">One hundred sample images from the “POF” face recognition dataset. <span style="color:grey">Faces have been redacted to protect privacy.</span></div>

{{< /columns >}}

## Context

_“We live in the age of digital data, and in that age mathematics has become the parliament of politics. The social law has become interwoven with models, theorems and algorithms. With digital data, mathematics has become the dominant means in which human beings coordinate with technology … Mathematics is a human activity after all. Like any other human activity, it carries the possibilities of both emancipation and oppression.” — Politically Mathematics Manifesto, 2019[^1]._

In Europe and around the world, AI systems are developed and deployed for harmful and discriminatory forms of state surveillance. From the use of biometrics for identification, recognition and categorization, to predictive systems in various decision-making and resource allocation capacities, AI in law enforcement disproportionately targets already marginalized communities, undermines legal and procedural rights, and enables mass surveillance. When AI systems are deployed in contexts of law enforcement, security and migration control (including the policing of social security), the power imbalance between the authorities and the surveilled is even more profound. This means that there is an even greater risk of harm, and violations of fundamental rights and the rule of law.

AI not only undermines due process but produces thoughtlessness, in the sense that political philosopher Hannah Arendt meant when interpreting the actions of Nazi war criminal Adolf Eichmann; the inability to critique instructions, the lack of reflection on consequences, a commitment to the belief that a correct ordering is being carried out. For AI’s impacts on the ground, the operative concerns are discrimination and segregation. AI is a racist technology, in the sense that AI operates so as to segregate, and racism itself can be understood as a technology of segregation[^2]. 

This is easy to see when it comes to facial recognition, one of the most egregious applications that AI has so far gifted to society. It is not just that facial recognition seems to perform less well on people of colour, it is that it carries out what Simone Browne calls _“digital epidemermalisation: the exercise of power cast by the disembodied gaze of certain surveillance technologies ... that can be employed to do the work of alienating the subject by producing a truth about the racial body and one's identity (or identities) despite the subject's claims”[^3]_.

Facial recognition is a particularly invasive, violent and biased technology that reinforces power imbalances, discrimination, racism, inequality and authoritarian societal control. Within the European Union, for instance, AI-based facial recognition technologies are used in public spaces to capture bystanders’ facial proportions and classify them into racial and ethnic categories such as Roma and Sinti, implying that non-white people are automatically suspect and unwanted[^4].

Reclaiming political agency from the engines of classification means taking solidarity as the starting point for our becoming, through a culture of invention, design, and planning that cares for communities and the grassroots collectives, and never entirely relinquishes agency and intelligence to automation ... The Police Officers Faces (POF) dataset, is a bold investigative counter-surveillance artistic project, focusing on facial recognition technology, particularly its use by the police. It is a large-scale dataset consisting of 88,783 facial images of thousands of police officers. The images are retrieved from the internet and used for facial recognition. In this project, the paradigm of the powerful watching and the powerless being watched is reversed.

To confront the dehumanising effects of the expansion of automated discrimination and segregation, the exacerbation of harm and the overarching correlation, the project promotes a different technical mentality, a collective “counter-intelligence,” that aims to highlight the power of citizens and grassroots realities in exposing facts, focusing on the impact of collective actions to reveal wrongdoing, and the collaborative production of social justice. Through a combination of targeted data collection and compilation, social engineering and analysis, the Police Officers Faces (POF) dataset establishes a comprehensive, structural alternative framework for the emancipatory empowerment of community members involved in copwatch and other counter-surveillance practices.

### Dataset Description

Police Officers Faces (POF) is a database of thousands of facial images of police officers collected from the web. The dataset consists of 88,783 aligned and cropped 200×280 pixel facial images of thousands of police officers (each image is centered on a single face). The majority of the images are annotated with the name of the person in the image. The average number of facial images per person is 12,22. Unlike most other existing facial datasets, these images were taken in completely uncontrolled situations with uncooperative subjects. As a result, there are large variations in pose, resolution, lighting, expression, scene, imaging conditions and parameters, etc. The dataset includes cropped and aligned facial image files in `.JPEG` format, `.JSON` and `.CSV` metadata files containing facial box coordinates and facial biometric landmark data. It also includes each individual’s full real name and attribution data in `.JSON` and `.CSV` files (each facial image in the dataset is automatically annotated with seventy-three different attributes belonging to three distinct recognition tasks: age group, gender and visual attributes, such as hair colour, face shape and the presence of make-up). <span style="color:grey"> * Please note that this page will be updated as more information becomes available.</span>

## License Agreement

`pof-agreement-v2024.3.14`

Any entity using this dataset agrees to the following terms and conditions.

{{< hint danger >}}
- **Non-Commercial Use**: This dataset and its subsets may only be used for non-commercial research purposes only. It is strictly forbidden to reproduce, duplicate, copy, sell, trade, resell or exploit, directly or indirectly, any part of the images and any part of the derived data for direct or indirect commercial purposes.

- **No Warranty**: The dataset is provided “as is” and any express or implied warranties are disclaimed. You are solely responsible for your use of the dataset, and you assume any risks associated with exercising the rights granted by this licence. The administrator of the Police Officers Faces (POF) dataset cannot be held responsible for any damage (physical, financial or otherwise) caused by the use of the database.

- **No Distribution**: You may not allowed to sublicense or distribute the dataset in whole or in part to any third party, in any way or by any means. This includes any redistribution, publication, copying or dissemination to any organisation, company or individual.

- **No Modification**: You may not allowed to modify the dataset in any way.
{{< /hint >}}

## Supplemental Data

### Annotated Sample Images

Below are some random sample images annotated with their corresponding seventy-three attribute labels. [Matplotlib](https://matplotlib.org/) is used to plot the frequency distribution of the labels. Faces have been redacted for privacy reasons.

<div class="caption"><img src="plots/plt-g8ltccwb.png"
       alt=" ">Frequency distribution of the labels on the image with the <code>"image_id": "g8ltccwb"</code> | <a href="data/g8ltccwb.csv">Download data as CSV</a></div>

<tr><td>&nbsp;</td></tr>

<div class="caption"><img src="plots/plt-8g5e6p7g.png"
       alt=" ">Frequency distribution of the labels on the image with the <code>"image_id": "8g5e6p7g"</code> | <a href="data/8g5e6p7g.csv">Download data as CSV</a></div>

<tr><td>&nbsp;</td></tr>

<div class="caption"><img src="plots/plt-lo7zii72.png"
       alt=" ">Frequency distribution of the labels on the image with the <code>"image_id": "lo7zii72"</code> | <a href="data/lo7zii72.csv">Download data as CSV</a></div>

<tr><td>&nbsp;</td></tr>

<div class="caption"><img src="plots/plt-vnqvu49b.png"
       alt=" ">Frequency distribution of the labels on the image with the <code>"image_id": "vnqvu49b"</code> | <a href="data/vnqvu49b.csv">Download data as CSV</a></div>

<tr><td>&nbsp;</td></tr>

<div class="caption"><img src="plots/plt-ek1qpg59.png"
       alt=" ">Frequency distribution of the labels on the image with the <code>"image_id": "ek1qpg59"</code> | <a href="data/ek1qpg59.csv">Download data as CSV</a></div>

<span style="color:grey"> * Please note that this part of the dataset uses a weak and questionable model that categorises faces in a completely discriminative way. The ground truth of the face attribute annotations is automatically estimated and not verified by a human annotator.</span>

### Access

The Police Officers Faces (POF) dataset, version `0.1.0`, is currently unavailable to the public. It is intended to equip investigative journalists, human rights researchers, and digital activists with the means to strengthen justice and advocacy efforts. <span style="color:grey"> * Please note that this page will be updated as more information becomes available.</span>

### Software Credits

Most all of this project was developed using open-source software: the core software application development and data analysis utilizes [Python](https://www.python.org/), [Pandas](https://pandas.pydata.org/), [Markdown](https://daringfireball.net/projects/markdown/), [Matplotlib](https://matplotlib.org/), and many other great open-source software packages that were freely available. Project communication relied on [Signal](https://signal.org/). Face redaction uses the open-source [DFACE.app](https://github.com/vframeio/dface) redaction software.

[^1]: Politically Mathematics collective, “Politically Mathematics Manifesto,” 2019. https://politicallymath.in/manifesto/.
[^2]: Lentin, A. 2018. The Future Is Here – Revealing Algorithmic Racism. Alana Lentin.Net (blog). 22 October 2018. http://www.alanalentin.net/2018/10/22/the-future-is-here-revealing-algorithmic-racism.
[^3]: Browne, S. 2015. Dark Matters: On the Surveillance of Blackness. Durham, NC: Duke University Press Books.
[^4]: Romani rights and biometric mass surveillance. European Digital Rights (EDRi). (2021, August 19). https://edri.org/our-work/roma-rights-and-biometric-mass-surveillance/.

