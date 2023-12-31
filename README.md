# Implementing and Evaluating Adaptive News Recommenders in graphworks.ai

This is the exposé of my master thesis. This document serves as a comprehensive guide to understand the structure, content, and purpose of my thesis project.

## Abstract

This master thesis aims to address the challenge of information overload experienced by users of graphworks.ai, a web application providing business insights through AI-analyzed news articles. The application is utilized by professional clients to identify sales chances as well as supply chain risks. However, the sheer volume of news articles in combination with the lack of a recommendation system makes it difficult for users to find content to the user's specific needs, thereby diminishing the overall effectiveness of the tool.

The central objective of this thesis is to enhance the user experience on graphworks.ai by integrating an adaptive news recommender system. This system aims to

- enable users to discover content that aligns more closely with their interests,
- incorporate features for users to provide both explicit and implicit feedback on the news articles suggested by the system,
- and utilize this feedback dynamically to refine and personalize future recommendations, making the system adaptive and more user-centric.

The thesis will undertake the following structured approach to achieve its objectives:

1. **Literature Review and Empirical Analysis.** A review of current literature on adaptive recommender systems will be conducted, complemented by an empirical analysis of various news platforms. This phase will identify the most effective user interfaces for capturing feedback on suggested articles, such as like/dislike buttons.
2. **System implementation.** Based on the findings from the literature review, state-of-the-art adaptive news recommender systems will be identified. The two most suitable systems, aligning with the established user feedback mechanism, will be implemented in graphworks.ai.
3. **User Study and System Evaluation.** A user study employing a between-subjects design will be conducted to evaluate the effectiveness of the implemented recommender system using a questionnaire. Based on the results of this study, the best-performing recommender system will be selected for permanent implementation in graphworks.ai's productive environment, thereby improving the overall user experience and mitigating the overload issues.

In conclusion, this thesis aims to enhance the utility of graphworks.ai by making it more responsive to individual user needs, thereby addressing the pressing issue of information overload.

## Table of contents

1. Introduction

- Problem statement
- Objectives
- Thesis structure

2. State of the art

- Major challenges in news recommender systems and conventional solutions
- Adaptive (news) recommender systems
- Empirical analysis on feedback interfaces
- Evaluating the quality of recommendations

3. Architecture

- graphwork.ai's current software architecture
- Planned architecture to integrate recommender systems

4. Implementation

- Implementation of <algorithm 1>
- Implementation of <algorithm 2>

5. Evaluation

- Evaluation strategy
- Evaluation results

6. Conclusion

## Important Literature

- Marie Al-Ghossein, Talel Abdessalem, and Anthony BARRÉ. 2021. A Survey on Stream-Based Recommender Systems. ACM Comput. Surv. 54, 5, Article 104 (June 2022), 36 pages. https://doi.org/10.1145/3453443
- Chuhan Wu, Fangzhao Wu, Yongfeng Huang, and Xing Xie. 2023. Personalized News Recommendation: Methods and Challenges. ACM Trans. Inf. Syst. 41, 1, Article 24 (January 2023), 50 pages. https://doi.org/10.1145/3530257
- Raza, S., Ding, C. News recommender system: a review of recent progress, challenges, and opportunities. Artif Intell Rev 55, 749–800 (2022). https://doi.org/10.1007/s10462-021-10043-x

## Timetable

- 20 weeks
- start: 04.12.2023
- end: 22.04.2024

| When?                   | Duration | What?                                      | Description |
| :---------------------- | -------: | :----------------------------------------- | :---------- |
| 04.12.2023              |        - | 🚀 Enrollment                              | -           |
| 04.12.2023 - 10.12.2023 |       1w | ✅ Research User Feedback Interface        | -           |
| 11.12.2023 - 24.12.2023 |       2w | 🧠 Research Adaptive News Recommenders     | -           |
| 25.12.2023 - 04.02.2024 |       6w | 🧑🏽‍💻 Implementation of two News Recommenders | -           |
| 05.02.2024 - 11.02.2024 |       1w | 📦 Deployment                              | -           |
| 12.02.2024 - 18.02.2024 |       1w | ⏳ _Buffer_                                | -           |
| 19.02.2024 - 25.02.2024 |       1w | 👥 User Study                              | -           |
| 26.02.2024 - 03.03.2024 |       1w | 📏 Evaluation of the User Study            | -           |
| 04.03.2024 - 07.04.2024 |       5w | 📝 Writing                                 | -           |
| 08.04.2024 - 21.04.2024 |       2w | 📖 Proofreading                            | -           |
| 22.04.2024              |        - | 🏁 Submission                              | -           |

## Other

- _Reinforcement Learning and Ensemble Learning (e.g. Adaboost) should be considered_
