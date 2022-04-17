See `monero_fee_analysis.ipynb`

PLEASE feel free to use / modify / contribute to this repo.

The top half of the notebook can be used to model different fee protocol limitations (such as 1 significant figure, or multiples of some particular basis). You can play around with the functions to try out different ideas and model applying the filters to past fee data.

The bottom part with HDBSCAN clustering is a half-baked prototype, if you play around with tuning the clusterer object, you might be able to get much better performance.