---
layout: page
title: Metrics, Analytics & User Research
permalink: /analytics/
---

## 01. Metrics

**16 Startup Metrics.**

[Article](https://a16z.com/2015/08/21/16-metrics/)

**16 More Startup Metrics.**

[Article](https://a16z.com/2015/09/23/16-more-metrics/)

## 02. Marketing Experimentation

**Google: Estimating Ad Effectiveness using Geo Experiments in a Time-Based Regression Framework.**

[Article](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45950.pdf)

> Two previously published papers (Vaver and Koehler, 2011, 2012) describe a model for analyzing geo experiments. This model was designed to measure advertising effectiveness using the rigor of a randomized experiment with replication across geographic units providing confidence interval estimates. While effective, this geo-based regression (GBR) approach is less applicable, or not applicable at all, for situations in which few geographic units are available for testing (e.g. smaller countries, or subregions of larger countries) These situations also include the so-called matched market tests, which may compare the behavior of users in a single control region with the behavior of users in a single test region. To fill this gap, we have developed an analogous time-based regression (TBR) approach for analyzing geo experiments. This methodology predicts the time series of the counterfactual market response, allowing for direct estimation of the cumulative causal effect at the end of the experiment.

**Google: A Time-Based Regression Matched Markets Approach for Designing Geo Experiments.**

[Article](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/b1976d70ccf7119f2193ece2d3d378d5dd0dd7be.pdf)

**Google: R package GeoexperimentsResearch.**

[GitHub](https://github.com/google/GeoexperimentsResearch)

> This R package ('GeoexperimentsResearch') is an open-source implementation of the geo experiment analysis methodology developed at Google. This package provides object classes and methods and functions for handling, verifying, and analyzing data from geo experiments.

**Google: A Revolution in Measuring Ad Effectiveness: Knowing Who Would Have Been Exposed.**

[Article](https://www.thinkwithgoogle.com/intl/en-gb/marketing-resources/data-measurement/a-revolution-in-measuring-ad-effectiveness/)

**Netflix: Incrementality Bidding & Attribution.**

[Article](https://poseidon01.ssrn.com/delivery.php?ID=847004104083014073004109005080126126055092036006058054127082104102096123010086118011039049035031006028001089087025026100089121018007025078012084098083096103100084112018040048025124124126122127116022007071023028064090120079096074067102077090083028106064&EXT=pdf)

> The causal effect of showing an ad to a potential customer versus not, commonly referred to as “incrementality,” is the fundamental question of advertising effectiveness. In digital advertising three major puzzle pieces are central to rigorously quantifying advertising incrementality: ad buying/bidding/pricing, attribution, and experimentation. Building on the foundations of machine learning and causal econometrics, we propose a methodology that unifies these three concepts into a computationally viable model of both bidding and attribution which spans the randomization, training, cross validation, scoring, and conversion attribution of advertising’s causal effects. Implementation of this approach is likely to secure a significant improvement in the return on investment of advertising.

**Google: Impact Of Ranking Of Organic Search Results On The Incrementality Of Search Ads.**

[Article](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/37731.pdf)

**Ebay: Consumer Heterogeneity and Paid Search Effectiveness: A Large Scale Field Experiment.**

[Article](http://conference.nber.org/confer/2013/EoDs13/Tadelis.pdf)

**Airbnb: Experimentation & Measurement for Search Engine Optimization.**

[Article](https://medium.com/airbnb-engineering/experimentation-measurement-for-search-engine-optimization-b64136629760)

**Pinterest: Demystifying SEO with Experiments.**

[Article](https://medium.com/pinterest-engineering/demystifying-seo-with-experiments-a183b325cf4c)

**How to Build a SEO Experiment Framework.**

[Article](https://www.growthengblog.com/blog/2018/4/15/scaling-new-growth-opportunities-series-seo-basics)

## 03. Marketing Attribution

**Attribution Model Evaluation.**

[Article](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/de1c3ab14fd52301fb193237fdffd45352159d5c.pdf)

> Many advertisers rely on attribution to make a variety of tactical and strategic marketing decisions, and there is no shortage of attribution models for advertisers to consider. In the end, most advertisers choose an attribution model based on their preconceived notions about how attribution credit should be allocated. A mis- guided selection can lead an advertiser to use erroneous information in making marketing decisions. In this paper, we address this issue by identifying a well-defined objective for attribution modeling and proposing a systematic approach for evaluating and comparing attribution model performance using simulation. Following this process also leads to a better understanding of the conditions under which attribution models are able to provide useful and reliable informa- tion for advertisers.

**A Causal Framework for Digital Attribution.**

[Article](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/00ac9e279331692b816c7ad5bc10bc88cb555f25.pdf)

> In this paper we tackle the marketing problem of assigning credit for a successful outcome to events that occur prior to the success, otherwise known as the attribution problem. In the world of digital advertising, attribution is widely used to formulate and evaluate marketing but often without a clear specification of the measurement objective and the decision-making needs. We formalize the problem of attribution under a causal framework, note its shortcomings, and suggest an attribution algorithm that is evaluated via simulation.

**If you’re using a single tool for measurement, think again.**

[Article](https://www.thinkwithgoogle.com/marketing-resources/data-measurement/media-measurement-tools/)

**Why conversion modeling will be crucial in a world without cookies.**

[Article](https://www.thinkwithgoogle.com/marketing-resources/data-measurement/conversion-measurement-in-a-cookieless-world/)

**Media Exposure through the Funnel: A Model of Multi-Stage Attribution.**

[Article](https://poseidon01.ssrn.com/delivery.php?ID=623110115067019004064023028108122092051040069008061028095107008090009067077122030071123059021013106005121064005096068097083024105043041005072083103011121003022114096056082040091084090072092103000123101080010026066112028072029025027121079027020117001087&EXT=pdf)

## 04. Product Experimentation

**A/B Testing with Fat Tails.**

[Article](https://eduardomazevedo.github.io/papers/azevedo-et-al-ab.pdf)

> Large and statistically powerful A/B tests are increasingly popular to screen new business and policy ideas. We study how to use scarce experimental resources to screen multiple potential innovations by proposing a new framework for optimal experimentation, that we term the A/B testing problem. The main departure from the literature is that the model allows for fat tails. The key insight is that the optimal experimentation strategy depends on whether most gains accrue from typical innovations or from rare and unpredictable large successes that can be detected using tests with small samples. We show that, if the tails of the unobserved distribution of innovation quality are not too fat, the standard approach of using a few high-powered “big” experiments is optimal. However, when this distribution is very fat tailed, a “lean” experimentation strategy consisting of trying more ideas, each with possibly smaller sample sizes, is preferred.

**Airbnb: Selection Bias in Online Experimentation.**

[Article](https://medium.com/airbnb-engineering/selection-bias-in-online-experimentation-c3d67795cceb)

**Booking.com: Increasing the Sensitivity of Experiments with Rank Transformation.**

[Article](https://booking.ai/increasing-sensitivity-of-experiments-with-the-rank-transformation-draft-c01aff70b255)

## 05. Survey-Based Consumer/Customer Research

**A Practitioner’s Guide to Net Promoter Score.**

[Article](https://andrewchen.co/a-practitioners-guide-to-net-promoter-score/)

**The definitive guide to text analysis.**

[Article](https://www.qualtrics.com/experience-management/research/text-analysis/)

**Qualitative Text Analysis: A Systematic Approach.**

[Book chapter](https://link.springer.com/chapter/10.1007/978-3-030-15636-7_8)

## 06. Qualitative User Research

**GV’s Guide to UX Research for Startups.**

[Article](https://library.gv.com/gv-guide-to-uxresearch-for-startups-b6d0c8ac81b3)

**User Research, Quick and Dirty.**

[Video](https://library.gv.com/user-research-quick-and-dirty-1fcfa54c91c4), [Slide deck](https://www.dropbox.com/s/6kef5x79ap8f9v7/User-Research-Workshop_Google-Ventures_Feb2013.pdf?dl=0)

**How To Do a User Interview.**

[Video](https://youtu.be/Qq3OiHQ-HCU)