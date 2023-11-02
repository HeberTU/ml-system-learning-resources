ML System Learning Resources
==============================

- [Send Email](mailto:heber.trj.urt@gmail.com)
- [Connect with me on LinkedIn](https://www.linkedin.com/in/heber-trujillo/)
- Date of last update: 02.11.2023

This is a curated list of resources about Machine Learning Systems. Please feel free to contribute any items that should be included.

# Content
- [Machine Learning handbook links](#Machine-Learning-handbook-links)
  - [Problem Definition](#Problem-Definition)
  - [Offline Model Evaluation](#Offline-Model-Evaluation)
  - [Monitoring](#Monitoring)
    - [Data Distribution shifts](#Data-Distribution-shifts)
- [Machine Learning Systems Design](#Machine-Learning-Systems-Design)
- [Machine Learning System Use Cases](#Machine-Learning-System-Use-Cases)
- [Causal Inference](#Causal-Inference)
- [Machine Learning in Organizations](#Machine-Learning-in-Organizations)


# Machine Learning handbook links

## Problem Definition 

During the Modeling phase, the primary objective is to create a Machine Learning model tailored to a specific business case. This process entails deriving a well-defined modeling strategy. While specific parameters like where the inference pipeline comes into play are usually given, critical elements like defining the target variables and observation space require meticulous design.

### Observational Space & Target Definition
- **Research Papers**
  - [Sample Selection Bias as a Specification Error](https://www.jstor.org/stable/1912352?origin=crossref&typeAccessWorkflow=login) by James J. Heckman et al. This paper discusses the bias that results from using nonrandomly selected samples to estimate behavioral relationships as an ordinary specification error or "omitted variables" bias.
  - [Addressing Delayed Feedback for Continuous Training with Neural Networks in CTR prediction](https://arxiv.org/abs/1907.06558) by Sofia Ira Ktena et al. This paper combats challenges of data freshness and delayed labels through continuous training and benchmarks loss functions and models to optimize CTR predictions, achieving significant gains in offline and online settings.
  - [Semi-Supervised Learning with Graphs](https://pages.cs.wisc.edu/~jerryzhu/pub/thesis.pdf) by Xiaojin Zhu. This paper shows how Semi-supervised learning leverages labeled and unlabeled data for improved classifiers by introducing graph-based methods addressing various challenges, from label propagation to scalability. 
  - [Snorkel: Rapid Training Data Creation with Weak Supervision](https://arxiv.org/abs/1711.10160) by Alexander Ratner et al. This paper shows how Snorkel empowers users to train high-quality ML models without hand-labeled data, using labeling functions to express heuristics, significantly speeding up model development and closely matching the performance of hand-curated training sets.
  - [Combining Labeled and Unlabeled Data with Co-Training](https://www.cs.cmu.edu/~avrim/Papers/cotrain.pdf) by Avrim Blum et al. This paper, leveraging dual views of web pages, explores using unlabeled data to enhance learning from a small labeled dataset, providing a PAC-style analysis and demonstrating empirical improvements in web page classification.
  - [The Class Imbalance Problem: A Systematic Study](https://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=96F26971E9360C5D02F4E2C8D858357E?doi=10.1.1.711.8214&rep=rep1&type=pdf) by Nathalie Japkowiz et al. The paper systematically examines the impact of class imbalances on machine learning classifiers
  - [The Class Imbalance Problem: Significance and Strategies](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.35.1693&rep=rep1&type=pdf) by Nathalie Japkowicz et al. The paper evaluates how class imbalances affect the performance of connectionist systems and compares different methods previously suggested to address this challenge.
  - [kNN Approach to Unbalanced Data Distributions: A Case Study involving Information Extraction](https://www.site.uottawa.ca/~nat/Workshop2003/jzhang.pdf) by Jianping Zhang et al. This paper describes an application of simple KNN approach to a novel classification problem with an unbalanced class distribution.
  - [Addressing the Curse of Imbalanced Training Sets: One-Sided Selection](https://sci2s.ugr.es/keel/pdf/algorithm/congreso/kubat97addressing.pdf) by Miroslav Kubat et al. This paper introduces the idea of One-side selection: an undersampling technique, which means it works by reducing the number of instances from the majority class.
- **Online Resources**
  - [AI's Proof-of-Concept to Production Gap](https://www.youtube.com/watch?v=tsPuVAMaADY) by Andrew Ng. Talk about key challenges facing AI deployments and possible solutions, ranging from techniques for working with small data to improving algorithms' robustness and generalizability to systematically planning out the full cycle of machine learning projects.

### Offline Model Evaluation
- **Research Papers**
  - [The Relationship Between Precision-Recall and ROC Curves](https://www.biostat.wisc.edu/~page/rocpr.pdf)  by Jesse Davis et al. The paper delves into the relationship between ROC and PR curves in machine learning, highlighting their deep connection, differences, and the implications for algorithm design, while introducing an efficient method to compute the achievable PR curve.


### Monitoring

#### Data Distribution shifts
- **Books**
  - [Machine Learning in Non-Stationary Environments: Introduction to Covariate Shift Adaptation](https://direct.mit.edu/books/book/3774/Machine-Learning-in-Non-Stationary) by Masashi Sugiyama et al. This book focuses on a specific non-stationary environment known as covariate shift, in which the distributions of inputs (queries) change but the conditional distribution of outputs (answers) is unchanged, and presents machine learning theory, algorithms, and applications to overcome this variety of non-stationarity.
- **Research Papers**
  - [An introduction to domain adaptation and transfer learning](https://arxiv.org/abs/1812.11806) by Wouter M. Kouw et al. In this paper, the significance of unbiased training samples in machine learning for accurate predictions is emphasized. The challenges arising from differences in training and test data distributions are highlighted, and the concepts of domain adaptation and transfer learning as solutions are introduced. The paper explores the conditions under which classifiers can effectively generalize across different domains, discusses risk minimization, examines types of data set shifts, and presents various strategies to handle complex domain shifts.
  - [Covariate Shift by Kernel Mean Matching](https://www.gatsby.ucl.ac.uk/~gretton/papers/covariateShiftChapter.pdf) by Arthur Gretton et al. In this paper, they introduce a method to adjust training data so its distribution aligns more closely with test data by matching covariate distributions in a high-dimensional feature space.  This technique bypasses the need for distribution estimation, utilizing a straightforward quadratic programming process to determine sample weights.
  - [Rethinking Importance Weighting for Deep Learning under Distribution Shift](https://arxiv.org/abs/2006.04662) by Tongtong Fang et al. In this paper, the authors address the challenges of using importance weighting (IW) under distribution shift in complex data, particularly its incompatibility with deep learning. The circular dependency between weight estimation (WE) and weighted classification (WC) is highlighted. To resolve these challenges, the paper introduces "dynamic IW," an end-to-end solution that iteratively combines WE and WC. 
  - [Learning under Concept Drift: an Overview](https://arxiv.org/abs/1010.4784) by Indrė Žliobaitė. This paper provides a comprehensive survey of the concept drift area. The paper not only offers a taxonomy of concept drift types but also discusses methods to handle them.


# Machine Learning Systems Design
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



# Machine Learning System Use Cases
- **Research Papers**
  - [The Netflix Recommender System: Algorithms, Business Value, and Innovation](https://dl.acm.org/doi/10.1145/2843948) by Carlos A. Gomez-Uribe et al. This article discusses the various algorithms that make up the Netflix recommender system, and describes its business purpose. 
- **Online Resources**
  - [Artwork Personalization at Netflix](https://netflixtechblog.com/artwork-personalization-c589f074ad76) by Ashok Chandrashekar. Netflix leverages machine learning and contextual bandits to personalize artwork for titles, enhancing user engagement and offering a tailored viewing experience by understanding individual preferences and viewing histories.
  - [Pareto-Based Multiobjective Machine Learning: An Overview and Case Studies](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.157.2352&rep=rep1&type=pdf) by Yaochu Jin et al. Research paper on applying Pareto optimization for ML, in which the authors claimed that “machine learning is inherently a multiobjective task”.
  - [On Learning Invariant Representations for Domain Adaptation](https://proceedings.mlr.press/v97/zhao19a.html) by Han Zhao et al. In this paper, the authors challenge the prevailing belief in unsupervised domain adaptation that using deep neural nets to learn domain-invariant features ensures successful adaptation. Through a counterexample, they highlight issues related to conditional shift in class-conditional distributions. They introduce a generalization upper bound that accounts for this shift and provide an information-theoretic lower bound related to learning invariant representations. The findings highlight a key tradeoff in domain adaptation when label distributions vary between source and target domains.


# Causal Inference
- **Books**
  - [Causal Inference in Python](https://learning.oreilly.com/api/v1/continue/9781098140243/) by Matheus Facure. This book explains the largely untapped potential of causal inference for estimating impacts and effects.
- **Research Papers**
  - [Democratizing online controlled experiments at Booking.com](https://arxiv.org/pdf/1710.08217.pdf) by Raphael Lopez Kaufman et al. In this paper they how building a central repository of successes
and failures to allow for knowledge sharing, having a generic and extensible code library which enforces a loose coupling between experimentation and business logic.
  - [A Randomized Assessment of Online Learning](https://www.proquest.com/openview/df502791278ac05f879e354c5dae7645/1.pdf?pq-origsite=gscholar&cbl=42182) by y William T. Alpert. In this paper they present a comprehensive randomized study on the effectiveness of online learning compared to traditional classroom instruction. Utilizing robust statistical methodologies, the authors assess student outcomes, engagement levels, and retention rates between the two modes of instruction. Key findings suggest that while online platforms offer greater flexibility and can achieve similar academic results, certain nuances, like student-teacher interaction and peer collaboration, differ significantly from in-person settings. The research delves deep into the data, using advanced analytical techniques to control for confounding variables and biases, ensuring the results are both reliable and generalizable. This study provides valuable insights not just for educators, but also for data scientists interested in the complexities of educational data and the challenges of conducting randomized trials in real-world settings.
  - [A/B Testing Intuition Busters: Common Misunderstandings in Online Controlled Experiments](https://drive.google.com/file/d/1oK2HpKKXeQLX6gQeQpfEaCGZtNr2kR76/view) by Ron Kohavi et al. This paper highlights the misleading concepts often promoted in the industry regarding A/B testing, debunks these misconceptions with statistical reasoning, and offers suggestions to platform designers to prevent such intuitive errors.
  - [Making Sense of Sensitivity: Extending Omitted Variable Bias](https://academic.oup.com/jrsssb/article/82/1/39/7056023) by Carlos Cinelli et al. In this paper, the autors extend the omitted variable bias framework with a suite of tools for sensitivity analysis in regression models that: (i) does not require assumptions on the functional form of the treatment assignment mechanism nor on the distribution of the unobserved confounders; (ii) naturally handles multiple confounders, possibly acting non-linearly; (iii) exploits expert knowledge to bound sensitivity parameters; and, (iv) can be easily computed using only standard regression results.
  - [A Crash Course in Good and Bad Controls](https://ftp.cs.ucla.edu/pub/stat_ser/r493.pdf) by Carlos Cinelli et al. In this paper, the authors address the recurrent issue encountered by students and professionals in statistics, econometrics, and empirical social sciences concerning "bad controls" in regression models. Bad controls refer to variables that, when added to a regression equation, might create unintended discrepancies between the regression coefficient and its anticipated effect. Historically, mainstream literature has lacked comprehensive guidance on distinguishing between "good controls" (or confounders) – variables that reduce biases when included – and "bad controls", potentially exacerbating biases. Although some resources touch upon this topic, they often address only specific facets, leaving a gap in holistic understanding. In contrast to the prevailing belief that more controls invariably enhance regression models, this paper aims to elucidate recent advancements in graphical models that help discern between good and bad controls. By utilizing illustrative examples, the paper offers a concise and visual guide for practitioners to navigate the challenges surrounding the inclusion of controls in regression models, ultimately aiming to aid in the causal interpretation of these models.
  - [Difference-in-Differences with Variation in Treatment Timing](https://www.nber.org/system/files/working_papers/w25018/w25018.pdf) by Andrew Goodman-Bacon. In this paper, the author investigates the intricacies of the two-way fixed effects difference-in-differences (TWFEDD) estimator, often used when treatment timings vary across units. The paper reveals that TWFEDD is a weighted average of all two-period/two-group difference-in-differences estimators, where weights are influenced by the timing group sizes and treatment variance. The analysis highlights that TWFEDD can yield a variance-weighted average of treatment effects if these effects are consistent over time; however, varying effects result in "negative weights" and could lead to misleading estimates. The author introduces a new perspective on the common trends assumption, tailored for TWFEDD, and provides tools for dissecting and understanding changes in estimates across different specifications. The methods are applied to a case study on unilateral divorce laws' impact on female suicide rates, indicating potential biases in TWFEDD estimates due to treatment effect evolution over time. The findings emphasize caution in using TWFEDD with varied treatment timings and point towards more flexible estimators that can better handle such variations.
- **Online Resources**
  - [Causal Inference for The Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)by Matheus Facure. This is a free e-book format of [Causal Inference in Python](https://learning.oreilly.com/api/v1/continue/9781098140243/)

# Machine Learning in Organizations
- **Books**
  - [Reliable Machine Learning](https://learning.oreilly.com/library/view/reliable-machine-learning/9781098106218/) by Cathy Chen et al. This practical book shows data scientists, software and site reliability engineers, product managers, and business owners how to run and establish ML reliably, effectively, and accountably within your organization.
- **Online Resources**
  - [The Value of Keeping the Right Customers](https://hbr.org/2014/10/the-value-of-keeping-the-right-customers) by Amy Gallo. This post gives the rationale behind why retaining existing customers is substantially cheaper than acquiring new ones.
  - [Startup Killer: the Cost of Customer Acquisition](https://www.forentrepreneurs.com/startup-killer/) by David Skok. The post emphasizes the criticality of balancing the cost of acquiring customers (CAC) with the lifetime value of a customer (LTV) for startup success. While product/market fit is essential, a viable business model is equally important, focusing on ensuring CAC is significantly lower than LTV.
  - [How Data Scientists Are Also Susceptible to the Layoffs Amid Crisis](https://analyticsindiamag.com/how-data-scientists-are-also-susceptible-to-the-layoffs-amid-crisis/) by Sejuti Das. The post shows that despite data science's high demand, companies are cutting costs, often at the expense of analytics roles. Upskilling and adapting to newer technologies are crucial for data professionals to maintain relevance in this evolving landscape.
  - [Machine learning isn't Kaggle competitions](https://jvns.ca/blog/2014/06/19/machine-learning-isnt-kaggle-competitions/) by Julia Evans. This post shows that while Kaggle competitions focus on machine learning algorithm challenges, real-world ML jobs encompass understanding business problems, data cleanup, model deployment, and performance measurement, making them distinct from the Kaggle experience.
  - [AI competitions don’t produce useful models](https://laurenoakdenrayner.com/2019/09/19/ai-competitions-dont-produce-useful-models/) by Lauren Oakden-Rayner. This post shows that AI competitions, while fostering community and publicity, often fall short in producing reliable models due to issues like multiple hypothesis testing and dataset limitations, emphasizing that winning models aren't necessarily the most useful in real-world applications.
  -[Amazon’s One Hour of Downtime on Prime Day May Have Cost It up to $100 Million in Lost Sales](https://www.businessinsider.com/amazon-prime-day-website-issues-cost-it-millions-in-lost-sales-2018-7) by Sean Wolfe.    

