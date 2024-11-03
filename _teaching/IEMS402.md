---
title: "Statistical Learning (IEMS-402, Northwestern)"
collection: teaching
type: "Graduate course"
permalink: /teaching/2025-Statistical-Learning
venue: "Northwestern IEMS"
date: 2025-03-01
location: "Evanston, IL"
---


Required graduate course on mathematical foundations of data science. **Syllabus**:[[link]](https://docs.google.com/document/d/1n9GF09jiJ5Nfmd1dlQoMNsgoWvffcpU36zzZ-Bc5iug/edit?usp=sharing)


Objectives:
======
This course provides foundational and advanced concepts in statistical learning theory, essential for analyzing complex data and making informed predictions. Students will delve into both asymptotic and non-asymptotic analyses of machine learning algorithms, addressing critical challenges such as model bias, variance, and robustness in uncertain environments. Toward the end of the course, students will apply these principles to modern machine learning contexts, including the scaling laws of deep learning, generative AI, and language models. (e.g. Neural Tagent Kernel, Mean-Field Limit of Neural Network and In-context Learning)

**ChatGPT Tutor:** The link here provides a Large Language Model agents that is specifically trained for this course.

If you have a question, to get a response from the teaching staff quickly we strongly encourage you to post it to the class Piazza forum. For suggestions to improve Yiping's teaching, you can use the [(anonymous) form](https://forms.gle/Dtw6PRFdnbk8NQWRA). You can also leave a private matter here. If you wish to contact me via email, kindly include the tag "[IEMS402]" in the subject line. This will help ensure that I do not overlook your message.

Syllabus
======
### Text Book
- [[Learning Theory from First Principles]](https://www.di.ens.fr/~fbach/ltfp_book.pdf ) Francis Bach [LTFP]
- [[Asymptotic Statistics]](https://www.cambridge.org/core/books/asymptotic-statistics/A3C7DAD3F7E66A1FA60E9C8FE132EE1D) A. W. van der Vaart [AS]


### Scheldue
- **Lecture 1-2**: <font color=red>Concept</font>
  - Supervised Learning, Empirical Risk Minimization, Risk Decomposition ([LTFP] Section 2)
  - Degree of Freedom.
  - Why the success of Deep Learning is a mystery.
    - Curse of Dimensioanality for approximation
    - Benigning Overfitting
    - Non-convexity of Optimization Landscape
    - Distrbution Mismatch
  - Sugessted Reading:
    - Zhang C, Bengio S, Hardt M, et al. [Understanding deep learning (still) requires rethinking generalization](https://dl.acm.org/doi/10.1145/3446776). Communications of the ACM, 2021, 64(3): 107-115.
    - Kaplan J, McCandlish S, Henighan T, et al. [Scaling laws for neural language models](https://arxiv.org/abs/2001.08361). arXiv preprint arXiv:2001.08361, 2020.
    - Nakkiran P, Kaplun G, Bansal Y, et al. [Deep double descent: Where bigger models and more data hurt](https://arxiv.org/abs/1912.02292). Journal of Statistical Mechanics: Theory and Experiment, 2021, 2021(12): 124003.
    - Curth A, Jeffares A, van der Schaar M. [A U-turn on double descent: Rethinking parameter counting in statistical learning](https://arxiv.org/abs/2310.18988). Advances in Neural Information Processing Systems, 2024, 36.
    - [Rethinking Conventional Wisdom in Machine Learning: From Generalization to Scaling](https://arxiv.org/abs/2409.15156) L Xiao arXiv preprint arXiv:2409.15156
    - <font color=red>(Required)</font> Mallinar N, Simon J, Abedsoltan A, et al. [Benign, tempered, or catastrophic: Toward a refined taxonomy of overfitting](https://proceedings.neurips.cc/paper_files/paper/2022/hash/08342dc6ab69f23167b4123086ad4d38-Abstract-Conference.html). Advances in Neural Information Processing Systems, 2022, 35: 1182-1195.

<font color=red>[Homework 1 DUE]</font>

- **Lecture 3**:
  - Bias-Variance Trade-off of Kernel Smoothing Estimator, Curse of Dimensionality ([LTFP] Section 6)
  - Advanced Reading:
    - Xing Y, Song Q, Cheng G. [Benefit of interpolation in nearest neighbor algorithms](https://arxiv.org/abs/2202.11817). SIAM Journal on Mathematics of Data Science, 2022, 4(2): 935-956.
- **Lecture 4**: <font color=red>Concept</font>
  - Diagram of Learning: Supervised, Unsupervised, Semi-supervised, Self-supervised, Generative AI
  - Deisgn of Loss function: Max Likelihood, Surrogate Loss

<font color=red>[Homework 2 DUE]</font>

- **Lecture 5**:
  - Asymptotic normality, (Implicit) Delta Method
- **Lecture 6**:
  - Influnce function
  - Sugessted Reading:
    - Koh P W, Liang P. [Understanding black-box predictions via influence functions International conference on machine learning](https://proceedings.mlr.press/v70/koh17a/koh17a.pdf) PMLR, 2017: 1885-1894. (ICML 2017 best paper)
    - Basu S, Pope P, Feizi S. [Influence functions in deep learning are fragile](https://arxiv.org/abs/2006.14651).

<font color=red>[Homework 3 DUE]</font>

- **Lecture 7**:
  - Application of Asymptotic Theory
- **Lecture 8**:
  - Concerntration Inequality

<font color=red>[Homework 4 DUE]</font>

- **Lecture 9**:
  - Generalization via Uniform Bound
- **Lecture 10**:
  - Symmetrization
  - Advanced Reading:
    - Kur G, Putterman E, Rakhlin A. [On the variance, admissibility, and stability of empirical risk minimization](https://arxiv.org/abs/2305.18508). Advances in Neural Information Processing Systems, 2024, 36.
    - Kur, Gil, et al. [Minimum Norm Interpolation Meets The Local Theory of Banach Spaces](https://openreview.net/forum?id=G4b32bKnBy). Forty-first International Conference on Machine Learning.

<font color=red>[Homework 5 DUE]</font>
### Homework
- [[Homework 1]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework1.pdf): Review of Probability Statistics and Optimization
- [[Homework 2]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework2.pdf): Bias and Variance Trade-off 1: Kernel Smoothing
- [[Homework 3]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework3.pdf): Bias and Variance Trade-off 2: Overparameterization
- [[Homework 4]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework4.pdf): Asymptotic Theory 1
- [[Homework 5]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework5.pdf): Asymptotic Theory 2 and Concentration Inequality
- [[Homework 6]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework6.pdf): Generalization Error
- [[Homework 7]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework7.pdf): Complexity of Hypothesis Space
- [[Homework 8]](https://2prime.github.io/files/IEMS402/IEMS_402_Homework8.pdf): RKHS and Robust Learning

### Exams
- [[Practice Mid-Term Exam]]()
- [[Practice Final Exam]]()

General Policies
======

In general, we do not grant extensions on assignments/exams. There are several exceptions:

- *Medical Emergencies:* If you are sick and unable to complete an assignment or attend class, please go to University Health Services. For minor illnesses, we expect grace days or our late penalties to provide sufficient accommodation. For medical emergencies (e.g. prolonged hospitalization), students may request an extension afterward by contacting their Student Liaison or Academic Advisor and having them reach out to the instructor on their behalf. Please plan ahead if possible.
- *Family/Personal Emergencies:* If you have a family emergency (e.g. death in the family) or a personal emergency (e.g. mental health crisis), please contact your academic adviser or Counseling and Psychological Services (CaPS). In addition to offering support, they will reach out to the instructors for all your courses on your behalf to request an extension.
- *University-Approved Absences:* If you are attending an out-of-town university-approved event (e.g. multi-day athletic/academic trip organized by the university), you may request an extension for the duration of the trip. You must provide confirmation of your attendance, usually from a faculty or staff organizer of the event.

**Accommodations for Students with Disabilities:** If you have a disability and have an accommodation letter from the Disability Resources office, I encourage you to discuss your accommodations and needs with the Moses Center for Student Accessibility as early as possible in the semester for assistance. (Telephone: 212-998-4980, Website: http://www.nyu.edu/csd) We will work with you to ensure that accommodations are provided as appropriate. If you suspect that you may have a disability and would benefit from accommodations but are not yet registered with the Office of Disability Resources, I encourage you to contact them. Please note that it is your responsibility to schedule exams at the Moses Center, and to ensure that you are receiving all accommodations you are approved for.


**Collaboration among Students:** The purpose of student collaboration is to facilitate learning, not to circumvent it. Studying the material in groups is strongly encouraged. It is also allowed to seek help from other students in understanding the material needed to solve a particular homework problem, provided no written notes (including code) are shared, or are taken at that time, and provided learning is facilitated, not circumvented. The actual solution must be done by each student alone.

The presence or absence of any form of help or collaboration, whether given or received, must be explicitly stated and disclosed in full by all involved. Specifically, each assignment solution must include answering the following questions:

- Did you receive any help whatsoever from anyone in solving this assignment? Yes / No.
If you answered ‘yes’, give full details: ____________
(e.g. “Jane Doe explained to me what is asked in Question 3.4”)
- Did you give any help whatsoever to anyone in solving this assignment? Yes / No.
If you answered ‘yes’, give full details: _____________
(e.g. “I pointed Joe Smith to section 2.3 since he didn’t know how to proceed with Question 2”)
