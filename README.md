ML System Learning Resources
==============================

- [Send Email](mailto:heber.trj.urt@gmail.com)
- [Connect with me on LinkedIn](https://www.linkedin.com/in/heber-trujillo/)
- Date of last update: 13.10.2023

This is a curated list of resources about Machine Learning Systems. Please feel free to contribute any items that should be included.

## Contents
- [Machine Learning handbook links](#Machine-Learning-handbook-links)
  - [Problem Definition](#Problem-Definition)
- [Machine Learning Systems Design](#Machine-Learning-Systems-Design)
- [Machine Learning System Use Cases](#Machine-Learning-System-Use-Cases)
- [Causal Inference](#Causal-Inference)
- [Machine Learning in Organizations](#Machine-Learning-in-Organizations)


## Machine Learning handbook links

### Problem Definition 

During the Modeling phase, the primary objective is to create a Machine Learning model tailored to a specific business case. This process entails deriving a well-defined modeling strategy. While specific parameters like where the inference pipeline comes into play are usually given, critical elements like defining the target variables and observation space require meticulous design.

#### Observational Space & Target Definition
- **Research Papers**
  - [Sample Selection Bias as a Specification Error](https://www.jstor.org/stable/1912352?origin=crossref&typeAccessWorkflow=login) by James J. Heckman et al. This paper discusses the bias that results from using nonrandomly selected samples to estimate behavioral relationships as an ordinary specification error or "omitted variables" bias.
  - [Addressing Delayed Feedback for Continuous Training with Neural Networks in CTR prediction](https://arxiv.org/abs/1907.06558) by Sofia Ira Ktena et al. This paper combats challenges of data freshness and delayed labels through continuous training and benchmarks loss functions and models to optimize CTR predictions, achieving significant gains in offline and online settings.
  - [Semi-Supervised Learning with Graphs](https://pages.cs.wisc.edu/~jerryzhu/pub/thesis.pdf) by Xiaojin Zhu. This paper shows how Semi-supervised learning leverages labeled and unlabeled data for improved classifiers by introducing graph-based methods addressing various challenges, from label propagation to scalability. 
  - [Snorkel: Rapid Training Data Creation with Weak Supervision](https://arxiv.org/abs/1711.10160) by Alexander Ratner et al. This paper shows how Snorkel empowers users to train high-quality ML models without hand-labeled data, using labeling functions to express heuristics, significantly speeding up model development and closely matching the performance of hand-curated training sets.
  - [Combining Labeled and Unlabeled Data with Co-Training](https://www.cs.cmu.edu/~avrim/Papers/cotrain.pdf) by Avrim Blum et al. This paper, leveraging dual views of web pages, explores using unlabeled data to enhance learning from a small labeled dataset, providing a PAC-style analysis and demonstrating empirical improvements in web page classification.

## Machine Learning Systems Design
- **Books**
  - [Designing Machine Learning Systems](https://learning.oreilly.com/library/view/designing-machine-learning/9781098107956/) by Chip Huyen This book offers a holistic perspective on constructing ML systems that are both reliable and adaptable, emphasizing their unique nature due to data dependencies.
  - [Building Machine Learning Powered Applications](https://learning.oreilly.com/library/view/building-machine-learning/9781492045106/) by Emmanuel Ameisen: This dives into the process of building and deploying ML applications, covering the lifecycle of an ML product.
  - [Designing Data-Intensive Applications](https://learning.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) by Martin Kleppmann: While not exclusively about ML systems, this book provides a comprehensive overview of modern data systems, some of which underpin ML applications.
- **Research Papers**
  - [Machine Learning: The High-Interest Credit Card of Technical Debt](https://research.google/pubs/pub43146/) by Sculley et al. This paper provides insights into the complexities and challenges of ML systems in production.
  - [150 Successful Machine Learning Models: 6 Lessons Learned at Booking.com](https://blog.kevinhu.me/2021/04/25/25-Paper-Reading-Booking.com-Experiences/bernardi2019.pdf) by Lucas Bernardi et al. This paper contains an analysis on about 150 successful customer facing applications of Machine Learning, developed by dozens of teams in Booking.com, exposed to hundreds of millions of users worldwide and validated through rigorous Randomized Controlled Trials.
- **Online Resources**
  - [Rules of Machine Learning:Best Practices for ML Engineering](https://developers.google.com/machine-learning/guides/rules-of-ml) by Martin Zinkevich. This document is intended to help those with a basic knowledge of machine learning get the benefit of Google's best practices in machine learning. It presents a style for machine learning, similar to the Google C++ Style Guide and other popular guides to practical programming.
  - [Science at Uber: Powering Machine Learning at Uber](https://www.uber.com/en-ES/blog/uber-science-machine-learning-platform/) by Wayne Cunningham. This resource talks about how Uber's machine learning platform, Michelangelo, lets teams across the company train, evaluate, and deploy models that help them forecast a wide range of business metrics.
  - [Architecture of a real-world Machine Learning system](https://medium.com/louis-dorard/architecture-of-a-real-world-machine-learning-system-795254bec646) by Louis Dorard. This post describes a client-server architecture of a “supervised learning” system, where predictions are requested by a client and made on a server. 



## Machine Learning System Use Cases
- **Research Papers**
  - [The Netflix Recommender System: Algorithms, Business Value, and Innovation](https://dl.acm.org/doi/10.1145/2843948) by Carlos A. Gomez-Uribe et al. This article discusses the various algorithms that make up the Netflix recommender system, and describes its business purpose. 
- **Online Resources**
  - [Artwork Personalization at Netflix](https://netflixtechblog.com/artwork-personalization-c589f074ad76) by Ashok Chandrashekar. Netflix leverages machine learning and contextual bandits to personalize artwork for titles, enhancing user engagement and offering a tailored viewing experience by understanding individual preferences and viewing histories.
  - [Pareto-Based Multiobjective Machine Learning: An Overview and Case Studies](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.157.2352&rep=rep1&type=pdf) by Yaochu Jin et al. Research paper on applying Pareto optimization for ML, in which the authors claimed that “machine learning is inherently a multiobjective task”


## Causal Inference
- **Books**
  - [Causal Inference in Python](https://learning.oreilly.com/api/v1/continue/9781098140243/) by Matheus Facure. This book explains the largely untapped potential of causal inference for estimating impacts and effects.
- **Research Papers**
  - [Democratizing online controlled experiments at Booking.com](https://arxiv.org/pdf/1710.08217.pdf) by Raphael Lopez Kaufman et al. In this paper they how building a central repository of successes
and failures to allow for knowledge sharing, having a generic and extensible code library which enforces a loose coupling between experimentation and business logic.
- **Online Resources**
  - [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)by Matheus Facure. This is a free e-book format of [Causal Inference in Python](https://learning.oreilly.com/api/v1/continue/9781098140243/)


## Machine Learning in Organizations
- **Books**
  - [Reliable Machine Learning](https://learning.oreilly.com/library/view/reliable-machine-learning/9781098106218/) by Cathy Chen et al. This practical book shows data scientists, software and site reliability engineers, product managers, and business owners how to run and establish ML reliably, effectively, and accountably within your organization.
- **Online Resources**
  - [The Value of Keeping the Right Customers](https://hbr.org/2014/10/the-value-of-keeping-the-right-customers) by Amy Gallo. This post gives the rationale behind why retaining existing customers is substantially cheaper than acquiring new ones.
  - [Startup Killer: the Cost of Customer Acquisition](https://www.forentrepreneurs.com/startup-killer/) by David Skok. The post emphasizes the criticality of balancing the cost of acquiring customers (CAC) with the lifetime value of a customer (LTV) for startup success. While product/market fit is essential, a viable business model is equally important, focusing on ensuring CAC is significantly lower than LTV.
  - [How Data Scientists Are Also Susceptible to the Layoffs Amid Crisis](https://analyticsindiamag.com/how-data-scientists-are-also-susceptible-to-the-layoffs-amid-crisis/) by Sejuti Das. The post shows that despite data science's high demand, companies are cutting costs, often at the expense of analytics roles. Upskilling and adapting to newer technologies are crucial for data professionals to maintain relevance in this evolving landscape.
  - [Machine learning isn't Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions/) by Julia Evans. This post shows that while Kaggle competitions focus on machine learning algorithm challenges, real-world ML jobs encompass understanding business problems, data cleanup, model deployment, and performance measurement, making them distinct from the Kaggle experience.
  - [AI competitions don’t produce useful models](https://laurenoakdenrayner.com/2019/09/19/ai-competitions-dont-produce-useful-models/) by Lauren Oakden-Rayner. This post shows that AI competitions, while fostering community and publicity, often fall short in producing reliable models due to issues like multiple hypothesis testing and dataset limitations, emphasizing that winning models aren't necessarily the most useful in real-world applications.
  -[Amazon’s One Hour of Downtime on Prime Day May Have Cost It up to $100 Million in Lost Sales](https://www.businessinsider.com/amazon-prime-day-website-issues-cost-it-millions-in-lost-sales-2018-7) by Sean Wolfe.    

