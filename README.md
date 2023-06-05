# Commercial Classification
## Introduction
The business problem is to classify whether a video segment is a commercial or part of the
scheduled TV news channel. This is a small, sub-problem of Broadcast Monitoring, which
aims to identify content being broadcasted. Unlike TV news segments, commercials tend to
have high energy and fast transitions with the aim to grab the consumers attention. These
characteristics are quantified in our dataset with complex industry-specific features such
as spectral flux, or ZCR. Using this dataset, the learned model can detect if a video segment
is a commercial. This model will provide business value by enforcing ad-coverage laws. If a
company claims it airs 15% less commercials than a competitor, it would be possible to
verify this claim using the machine learning model. Also, this model would enable
organizations to generate statistics about the airing time of advertisements. This can help
organizations to adjust their advertisement strategy to maximize results. The goal for this
project is to use a relatively simple ML model to provide highly accurate classifications
through data processing and hyperparameter optimization.

## DataSet
Link to dataset:
https://archive.ics.uci.edu/ml/datasets/TV+News+Channel+Commercial+Detection+Datas
et
A TV News Channel Commercial dataset is being used for this project. It was found by
filtering the datasets on UCI by number of instances, and then looking for a dataset with a
moderate amount of features, minimal missing values, and having interesting relevant data.
This dataset has 129,685 rows and 4125 columns of data. These features are all numerical
values that represent metadata from audio and video sources. Approximately 63% of the
dataset are commercials, with a positive class label and there are no NaN values within the
dataset. The features or columns of this dataset all contain metadata and metadata
summaries of the actual audio and video of the TV stream.

