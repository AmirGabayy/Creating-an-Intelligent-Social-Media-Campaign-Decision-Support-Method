**This is a repository for the paper "Creating an Intelligent Social Media Campaign Decision-Support Method" presented at UMAP 2024 conference**

## Citation

_When data is used please cite our paper._

```bibtex
@inproceedings{gabay2024creating,
  title={Creating an Intelligent Social Media Campaign Decision-Support Method},
  author={Gabay, Amir and Solomon, Adir and Guy, Ido and Shapira, Bracha},
  booktitle={Proceedings of the 32nd ACM Conference on User Modeling, Adaptation and Personalization},
  pages={149--158},
  year={2024}
}
```

## Data

In the "data" directory you can find data collected by the authors from 10 different ecommerce stores.

Each data row represents metrics collected for an ad on a specific date.

The features in the dataset are as follows:

1. **Store ID:** A unique id of a store.
1. **Campaign ID:** A unique id of a social media campaign.
1. **Adset ID:** A unique id of an ad set.
1. **Ad ID:** A unique id of an ad.
1. **Date start:** Starting date of the data in the row.
1. **Date end:** Ending date of the data in the row.
1. **Spend:** Ad spend in USD.
1. **Impressions:** Number of impressions.
1. **Reach:** Number of unique users reached.
1. **Purchase:** Number of purchases.
1. **Initiated checkout:** Number of checkouts initiated.
1. **Add to cart:** Number of add to cart events initiated.
1. **Link click:** Number of link clicks.
1. **Landing page view:** Number of landing page views.
1. **View content:** Number of content views (e.g., number of products viewed).
1. **Lead:** Number of leads generated.
1. **Search:** Number of search events in a store.
1. **CTR:** Click through rate.
1. **CPC:** Cost per click.
1. **CPM:** Cost per mille (cost per 1,000 impressions).
1. **Frequency:** The ratio between impressions and reach.
1. **Cost per landing page view:** Cost in USD per landing page view.
1. **Cost per link click:** Cost in USD per link click.
1. **Cost per post engagement:** Cost in USD per post engagement (i.e. post like, comment etc.)
1. **Cost per page engagement:** Cost in USD per page engagement (i.e. page like etc.)
1. **Cost per add to cart:** Cost in USD per add to cart event.
1. **Cost per initiated checkout:** Cost in USD per checkout initiated.
1. **Cost per lead:** Cost in USD per lead generated.
1. **Cost per purchase:** Cost in USD per purchase generated.
1. **Cost per search:** Cost in USD per search event.
1. **Cost per view content:** Cost in USD per content view (e.g., number of products viewed).
1. **Add to cart value:** Sum of price in USD of products added to cart.
1. **Initiated checkout value:** Sum of price in USD of products in cart while checkout is initiated.
1. **View content value:** Sum of product prices in USD of products viewed.
1. **Add payment info value:** Sum of price in USD of products in cart while payment info was entered.
1. **Purchase value:** Sum of product prices in USD of products purchased.
1. **Post engagement:** Amount of post engagements (i.e. post likes, comments etc.)
1. **Page engagement:** Amount of page engagements (i.e. page likes etc.)
1. **Comment:** Amount of comments on post.
1. **Post save:** Amount of times the post was saved.
1. **Photo view:** Amount of times a photo on the post was viewed.
1. **Post shares:** Amount of times the post was shared.
1. **Video view:** Amount of times a video on the post was viewed.
1. **ROAS (ROI):** Reutrn on ad spend / return on investment.

_Amir Gabay (gabayam@post.bgu.ac.il), Adir Solomon, Ido Guy, Bracha Shapira_
