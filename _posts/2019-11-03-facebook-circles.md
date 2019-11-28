---
layout: post
title: "Facebook circles"
page: facebook-communities
date:   2019-11-03 11:30:41 -0300
description: "This dataset consists of 'circles' (or 'friends lists') from Facebook. Facebook data was collected from survey participants using this Facebook app. The dataset includes node features (profiles), circles, and ego networks.
Facebook data has been anonymized by replacing the Facebook-internal ids for each user with a new value. Also, while feature vectors from this dataset have been provided, the interpretation of those features has been obscured. For instance, where the original dataset may have contained a feature "political=Democratic Party", the new data would simply contain "political=anonymized feature 1". Thus, using the anonymized data it is possible to determine whether two users have the same political affiliations, but not what their individual political affiliations represent."
data-name: file
link: http://hypergraph-repository.github.io/_datasets/0.circles.hgf
categories: social-network
cat2: ground-truth network
by: 'https://it.wikipedia.org/wiki/Facebook'
icon: 'credit-card'
size: 0.5
vertex-type: user
edge-type: circle
vertex-meta: nd
edge-meta: nd
v: 32
e: 10
max-e-size: 4
max-degree: 4
degree-distribution: 2:10,3:30,4:5,5:40
edges-distribution: 2:15,5:20
modularity: 0.40
two-lcc: 10
two-e: 40
two-density: 0.4
two-triangle: 20
two-min-degree: 3
two-max-degree: 10
two-avg-degree: 4
two-power-law-exp: 2
two-diameter: 4
two-cc: 0.6
two-modularity: 0.6
two-degree-distribution: 2:15,5:20
---
