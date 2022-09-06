## TweetInfo
This GitHub repository corresponds dataset used for TweetInfo. TweetInfo provides a customised user interface using the filter button on the right-hand side. Participants can choose the filter option to customise the content on their timeline. Users must check the box parameter and click on search to filter the tweets. By default, all radio buttons are set as no. Until now, hate speech and misinformation are mutually exclusive (users can not use both options simultaneously). On the timeline, each tweet contains an icon to provide the metainformation in the pop-up window. The metainformation provides the details of tweets from the content analysis.

## Dataset
The dataset is shared by following the Twitter data sharing policy. The description of the columns are given below
* **tweet_id** - unique ID of a Tweet
* **tweet_class** - class of the tweet defined by us.
* **lang** - Language of the tweet
* **Country** - Country of Author
* **hate speech** - This column identifies it as hate speech; zero means Hate Speech while one means not
* **sentiment** - Gives the class of sentiment score
* **category_text** - Category of a tweet
* **verified** - If the account is verified
* **Misinformation** - If a tweet is misinformation, it has four classes as per https://tinyurl.com/3humkacp
* **misinformation_source_url** - Link to the fact-checked article as background truth.

#### How do I cite this work?

Please cite the [OSNEM paper](https://doi.org/10.1016/j.osnem.2020.100104):

```
@article{shahi2021exploratory,
  title={An exploratory study of covid-19 misinformation on twitter},
  author={Shahi, Gautam Kishore and Dirkson, Anne and Majchrzak, Tim A},
  journal={Online Social Networks and Media},
  volume={22},
  pages={100104},
  year={2021},
  publisher={Elsevier}
}
```
