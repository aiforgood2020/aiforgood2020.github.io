---
layout: page
title: Invited Speakers
---

### Joanna Bryson (Hertie School of Governance)

#### What Is Good? Social Impacts and Digital Governance

Bio: Joanna Bryson is Professor of Ethics and Technology at Hertie School of Governance in Berlin recognised for broad expertise on intelligence, its nature, and its consequences. She advises governments, transnational agencies, and NGOs globally, particularly in AI policy. Most recently, she has been selected to represent Germany at the Global Partnership on AI. She holds two degrees each in psychology and AI (BA Chicago, MSc & MPhil Edinburgh, PhD MIT). Her work has appeared in venues ranging from reddit to the journal Science.  From 2002-19 she was Computer Science faculty at the University of Bath; she has also been affiliated with Harvard Psychology, Oxford Anthropology, The Mannheim Centre for Social Science Research, The Konrad Lorenz Institute for Evolution and Cognition Research, and the Princeton Center for Information Technology Policy. During her PhD she first observed the confusion generated by anthropomorphised AI, leading to her first AI ethics publication “Just Another Artifact” in 1998. She has remained active in the field including coauthoring the first national-level AI ethics policy, the UK's (2011) Principles of Robotics. She continues to research both the systems engineering of AI and the cognitive science of intelligence, with present focusses on the impact of technology on human cooperation, and new models of governance for AI and ICT.

### Oisin Mac Aodha (School of Informatics, University of Edinburgh)

#### Human-in-the-Loop Computer Vision for Biodiversity Monitoring

Abstract:
In order to manage the impact of anthropogenic change there is a critical need for robust and accurate tools to scale up biodiversity monitoring. Machine learning powered systems offer the promise of scaling up current manually intensive monitoring by automatically processing large quantities of image and audio data to find events of interest e.g. detecting the presence of a particular species. In this talk I will discuss recent work where we have shown that by explicitly including humans-in-the-loop we can improve the accuracy of these systems. I will touch on recent computer vision benchmarks for fine-grained visual understanding, algorithms for teaching visual knowledge to humans, and models for exploiting spatial and temporal biases in data to improve image classification performance.

Bio:
Oisin Mac Aodha is an Assistant Professor in Machine Learning at the University of Edinburgh. Previous to that, he was a postdoc with Prof. Pietro Perona in the Computational Vision Lab at the Caltech. He obtained his PhD from University College London with Prof. Gabriel Brostow. His current research interests are broadly in the areas of machine learning, computer vision, and human-in-the-loop methods such as active learning and machine teaching. More information can be found on his website (www.oisin.info) and twitter (@oisinmacaodha).

### Vukosi Marivate (Department of Computer Science, University of Pretoria)

#### Data Science at the frontier: What does it really mean to do Data Science for Society?

Abstract:
We talk about Data Science or Artificial Intelligence for Good. What does it really mean to do this? What are the challenges when you have society in the loop of our science? Actually, what does it mean to center society in this science? I go through trying answer these questions and use some of our recent work on COVID-19 in South Africa and African Natural Language processing to better understand what we have learned through his process. 

Bio
Dr Vukosi Marivate is the ABSA UP Chair of Data Science at the University of Pretoria. Vukosi works on developing Machine Learning/Artificial Intelligence methods to extract insights from data. A large part of his work over the last few years has been in the intersection of Machine Learning and Natural Language Processing (due to the abundance of text data and need to extract insights). As part of his vision for the ABSA Data Science chair, Vukosi is interested in Data Science for Social Impact, using local challenges as a springboard for research. In this area Vukosi has worked on projects in science, energy, public safety and utilities. Vukosi is an organiser of the Deep Learning Indaba, the largest Machine Learning/Artificial Intelligence workshop on the African continent, aiming to strengthen African Machine Learning. He is passionate about developing young talent, supervising MSc and PhD students and mentoring budding Data Scientists.

### Ziad Obermeyer (UC Berkeley School of Public Health)

#### Dissecting racial bias in health algorithms

Abstract: The choice of convenient, seemingly effective proxies for ground truth can be an important source of algorithmic bias in many contexts. We illustrate this with an empirical example from health, where commercial prediction algorithms are used to identify and help patients with complex health needs. We show a widely-used algorithm, typical of this industry-wide approach and affecting millions of patients, exhibits significant racial bias: at a given risk score, blacks are considerably sicker than whites, as evidenced by signs of uncontrolled illnesses. Remedying this would increase blacks receiving additional help from 17.7% to 46.5%. The bias arises because the algorithm predicts health care costs rather than illness. But unequal access to care means we spend less caring for blacks than whites. So, despite appearing to be an effective proxy for health by some measures of predictive accuracy, large racial biases arise. 

Bio: Ziad Obermeyer is an Associate Professor at UC Berkeley, where he does research at the intersection of machine learning, medicine, and health policy. He was named an Emerging Leader by the National Academy of Medicine, and has received numerous awards including the Early Independence Award -- the National Institutes of Health’s most prestigious award for exceptional junior scientists -- and the Young Investigator Award from the Society for Academic Emergency Medicine. Previously, he was an Assistant Professor at Harvard Medical School. He continues to practice emergency medicine in underserved communities.

### Danielle Wood (MIT Media Lab)

#### Sustainability in Space and on Earth: Research Initiatives of the Space Enabled Research Group

Abstract: The presentation will present the work of the Space Enabled Research Group at the MIT Media Lab. The mission of the Space Enabled Research Group is to advance justice in Earth's complex systems using designs enabled by space. Our message is that six types of space technology are supporting societal needs, as defined by the United Nations Sustainable Development Goals. These six technologies include satellite earth observation, satellite communication, satellite positioning, microgravity research, technology transfer, and the infrastructure related to space research and education. While much good work has been done, barriers remain that limit the application of space technology as a tool for sustainable development. The Space Enabled Research Group works to increase the opportunities to apply space technology in support of the Sustainable Development Goals and to support space sustainability. Our research applies six methods, including design thinking, art, social science, complex systems, satellite engineering and data science. The presentation will give examples of research projects that harness tools from artificial intelligence, satellite data analysis and machine learning. The projects build relationships with leaders from communities in Brazil, Benin, Ghana and India; in each location, the team learns from local leaders what priorities they set for increasing the use of artificial intelligence to support informed decision making while working toward a just society.

Bio: Professor Danielle Wood serves as an Assistant Professor in Media Arts & Sciences and holds a joint appointment in the Department of Aeronautics & Astronautics at the Massachusetts Institute of Technology. Within the MIT Media Lab, Prof. Wood leads the Space Enabled Research Group. Prof. Wood is a scholar of societal development with a background that includes satellite design, earth science applications, systems engineering, and technology policy. In her research, Prof. Wood applies these skills to design innovative systems that harness space technology to address development challenges around the world and contribute to the long-term sustainability of outer space. Prior to serving as faculty at MIT, Professor Wood held positions at NASA Headquarters, NASA Goddard Space Flight Center, Aerospace Corporation, Johns Hopkins University, and the United Nations Office of Outer Space Affairs. Prof. Wood studied at the Massachusetts Institute of Technology, where she earned a PhD in engineering systems, SM in aeronautics and astronautics, SM in technology policy, and SB in aerospace engineering.

<div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>


