# Video-Views-Growth-Rate

## Motivation (Credit to https://www.kaggle.com/c/stats101c-lec3-final-competition/data)

YouTube is a large scale video-sharing platform owned by Google since late 2006. The site allows users to upload, view, rate, share, create playlists, comment on videos, and subscribe to other users. Of these interactions, views stand out as particularly important because they are a direct measure of engagement with a video and also help to determine how much revenue the content creator will make. A pressing goal for a content creator is to know how fast a video will grow, especially within the first few hours of its lifetime. A video’s early growth pattern can be a broader indicator of the eventual success of the video as well as the overall health of the channel.

## Data Description (Credit to https://www.kaggle.com/c/stats101c-lec3-final-competition/data)

The training data are in the file training.csv. In the dataset, each row corresponds to a YouTube video and each column to a feature of the video. The dataset includes 7242 videos and 258 predictors, generally falling into one of four categories: thumbnail image features (for example, percent of nonzero pixels), video title features (for example, number of words in title), channel features (for example, number of subscribers to the channel), and other features (for example, video duration). A detailed description of all features can be found in the file 'Feature_Descriptions.xlsx'.

This training data also includes the response variable called 'growth_2_6' which measures the percent change in views between the second and sixth hour since the video was published. For example, if a video has 100 views at the second hour, and 1000 views at the sixth hour, the percent change is 900% so 'growth_2_6' will be 9.0. Note that 'growth_2_6' for the train and test data is bounded between 0 and 10. The id column in this dataset identifies each observation in the training data.

The test data are in file test.csv. The dataset includes 3105 videos and 258 predictors. The test data does not include the 'growth_2_6' column. The challenge is to closely predict the true value of 'growth_2_6' in this dataset. The id column in this dataset identifies each observation in the test data. To avoid confusions, the values in the id column in the test.csv file are different from those in the training.csv file.
