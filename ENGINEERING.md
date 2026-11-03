# Engineering notes

## Keep evidence and interpretation distinct

A product investigation combines several kinds of information: listing identity, supplier observations, advertising references, offer context, and economics assumptions. Each has its own source, date, and limits.

The application preserves those distinctions instead of turning a partial dataset into a single unsupported recommendation.

## Product identity and matching

Supplier matching needs to distinguish a variant, a bundle, a substitute, and the same product. Title similarity alone does not establish equivalence.

Algorithmic matches are proposals. Human review compares concrete attributes such as model, size, capacity, variant, and package contents. Inconclusive cases remain inconclusive rather than being counted as positive matches.

## Evaluation without inflated accuracy

Operational review queues prioritize useful cases; that makes them a biased sample. Measuring only those cases does not establish accuracy across the full catalog.

The private project documents a separate evaluation process using positive predictions, borderline candidates, and difficult rejections. Reviewers inspect evidence before seeing the prediction. Any reported metrics need the sampling scope and uncertain cases alongside them.

This repository publishes no matching-accuracy figure.

## Freshness and missing data

Observed stock has a timestamp. Unknown stock is different from zero stock. A supplier's suggested price is different from a verified market price.

Stored research can remain readable while an update runs or fails, but the date and state must remain visible. Refreshing the screen should not make old evidence appear newly observed.

## Unit economics

Cash-on-delivery analysis depends on declared assumptions, including shipping and other costs. Missing inputs should remain unknown; they should not silently become zero or produce a confident profitability conclusion.

## Discuss in an interview

I can walk through product identity, human review, biased evaluation samples, timestamped evidence, and the difference between a useful decision-support tool and an unsupported prediction.
