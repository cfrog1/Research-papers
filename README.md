# Research-papers

1. Genre Classification for Movies

The paper implemented and analysed the use
of decision tree and logistic regression models
on a dataset of textual ‘tags’ and audio-visual
features from each movie’s trailer.

Decision tree models performed poorly even
after restricting the depth of the tree, and it is
put forth that this is primarily due to the large
number of features, limiting the effectiveness
of the model’s greedy algorithm. Feature
reduction techniques may prove useful for
future work.

The logistic regression model outperformed
the baseline, though the unbalanced nature of
the dataset caused significant over-prediction
in high-frequency classes. Weighting the
classes during training did not improve overall
accuracy. More instances of the low-frequency
classes may have made a greater difference. It
was also noted that a significant portion of
movies share two genres, and that some genres
may be a subset of others and therefore a
multi-label output may allow the classifier to
match reality more closely.

