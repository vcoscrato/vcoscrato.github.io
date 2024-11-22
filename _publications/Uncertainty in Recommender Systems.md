---
title: "Uncertainty in Recommender Systems"
collection: publications
category: dissertations
permalink: /publication/PHD
excerpt: 'My Ph.D Thesis.'
date: 2024
venue: 'University College Cork'
paperurl: 'https://cora.ucc.ie/bitstreams/7a718b2e-45f6-4468-8a90-caee0911ada6/download'
citation: 'Coscrato, Victor. (2024). "Uncertainty in Recommender Systems." <i>University College Cork</i>.'
---

Recommender Systems have emerged as a powerful tool in the information era.
Due to the overwhelming number of items (products and services) currently offered on digital platforms, it is often necessary to use a system capable of ranking
the items and offering those that are most relevant to each user. These systems
typically use historical user-item interaction data to build models that can predict
the relevance of each item to the user.

There has long been a focus on increasing recommendation accuracy through the
development of new prediction models. However, this is just one of the ways
to improve these systems. It is also possible to equip them with new tools that
extend their functionality in different ways. The tools that we focus on in this
dissertation are uncertainty estimators.

The problem of uncertainty is relevant to Recommender Systems in at least two
ways: prediction uncertainty and label uncertainty. Prediction uncertainty is
the expected imprecision of the predictions given by the system’s model. Label
uncertainty is the chance that interactions used to learn the prediction model are
mislabeled. This dissertation reports by far the most extensive study of these
two types of uncertainty, offering a varied set of methods for their estimation,
ranging from heuristic data metrics to novel uncertainty prediction models.

In overview, this dissertation is the largest compilation of methods for estimating
prediction uncertainty and label uncertainty in Recommender Systems to date.
This collection includes already-existing methods – that we survey, rewrite in a
common notation, implement, make available under an open license, and compare
in-depth – and many original methods, some that derive directly from existing
work, but others that involve complex modeling. We divide our work into three
branches: prediction uncertainty in explicit feedback-based systems, prediction
uncertainty in implicit feedback-based systems, and label uncertainty in implicit
feedback systems.

While this dissertation proposes new uncertainty estimation methods, the novel
work in this dissertation is not restricted to new estimation methods. We also
propose new techniques for evaluating prediction uncertainty estimators. Furthermore, we present and validate novel ways of using uncertainty estimators to
improve the operation of a Recommender System.

At the core of our research program, and for each of the three branches cited
above, we have rigorous validation of our prediction and label uncertainty estimation methods through large-scale, reproducible empirical studies on publicly
available recommendation datasets that unveil important insights into the performance and usefulness of the proposed methods. These studies include both the
novel and surveyed uncertainty estimation methods, and make use of the novel
uncertainty evaluation techniques that we propose.

This work can be an important mechanism for promoting new research on this
topic that is still largely unexplored in the world of Recommender Systems. Thus,
this dissertation is a contribution to the field of Recommender Systems, not just
in terms of an all-encompassing compendium of uncertainty estimation methods
for practitioners, but also in guiding future work. Given that the landscape
of Recommender Systems continues to evolve, our work is poised to shape the
discourse about uncertainty in the field.
