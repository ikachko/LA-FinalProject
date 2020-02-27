# LA-FinalProject


## Assumptions
* We know the exact number of original signals
* The number of records is no less than the number of original signals, which is a requirement of ICA. In our future work, when applying Deep Learning to this problem, we aim to remove this assumption.

## References
1. https://en.wikipedia.org/wiki/Signal_separation
2. https://scikit-learn.org/stable/auto_examples/decomposition/plot_ica_blind_source_separation.html

## Tools
1. `numpy` and `scipy.signal` to work with signals
2. `librosa` for working with Audio
3. `sklearn.decomposition` for ICA
