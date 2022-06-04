# NFT sales forecasting: a hybrid approach with Computer Vision and Time Series. 
This repository gathers all the information, code and data about the NFT sales forecasting started as a group project at Machine Learning degree of [opencampus.sh](https://opencampus.sh). Team mates are: Malte Bartels, Khanh Ho, Julien Carbonnell.

### Project Description:
NFT sales increased fastly and there’s a lot of speculation around. It is nascent market of $50B capitalization, highly volatile and hardly predictable. Because it is becoming a key element of ownership in the digital world, forecasting NFT value is important for individual financial security and investment making. Since the value of NFTs depend on weak signals scattered on different digital platform of various nature, AI can help making a sense out of the NFT market to identify good investments and build a trustworthy NFT recommendation system.

In the determination of critical factors making NFT valuable or not, visual features are mainly undiscovered. Our approach will be to hybrid computer vision and time series on sales to predict NFT values forecasting. A CNN model will be used to extract visual features, which will be combined with historical market data, to perform a cross-sourced regression analysis looking for market changes and their timing.

A pitch deck is available [here](https://docs.google.com/presentation/d/1jHd8AsHRDuHgiaFrP9hq1H6JN3bmCKH4gCR4JS-Z7NQ/edit?usp=sharing). 

### Project Management:
A notion board is available [here](https://www.notion.so/4a4a3421bc1c490190a07de4529345c8?v=bfcefed471a24d66a681ab0f50db22eb)


### Datasets:
There are more NFTs on NFT marketplaces today than there were websites in 2010. Covering the whole available NFTs' data would have been impossible. Our model ambitions to experiment an undiscovered approach to NFT sales forecasting by using feature extraction on images, which induces some computational costs due to a high data size. 

To collect full datasets including images + last sale prices, we combined existing datasets Kaggle, with OpenSea API requests, and data scraping with selenium. The resulting datasets are the followings:
- [Crypto Coven Witches](https://www.kaggle.com/datasets/harrywang/crypto-coven) collected on opensea.com on April 22, 2022.
- [CryptoPunks](https://www.kaggle.com/datasets/tunguz/cryptopunks) collected on [larvalabs.com](https://larvalabs.com/cryptopunks) on October 8, 2021.
- [Bored Apes](https://www.kaggle.com/datasets/stanleyjzheng/bored-apes-yacht-club) images collected on opensea.com (https://opensea.com) on July 14, 2021 (images) and historical sales on May 22, 2022.
- [Solana NFT Collections](https://www.kaggle.com/datasets/eyenpi/solana-nft-collections?select=Solana+NFT+Collections) sales collected on [magiceden.io](https://magiceden.io) on April 18, 2021 and images collected on June 1, 2022.

### Literature:
2022
- [Predicting the Bubble of Non-Fungible Tokens (NFTs): An Empirical Investigation](https://paperswithcode.com/paper/predicting-the-bubble-of-non-fungible-tokens)
- [NFT Appraisal Prediction: Utilizing Search Trends, Public Market Data, Linear Regression and Recurrent Neural Networks](https://paperswithcode.com/paper/nft-appraisal-prediction-utilizing-search)
- [Constructing a NFT Price Index and Applications](https://paperswithcode.com/paper/constructing-a-nft-price-index-and)
- [An Analysis of the Features Considerable for NFT Recommendations](https://paperswithcode.com/paper/an-analysis-of-the-features-considerable-for)

2021 
- [Mapping the NFT revolution: market trends, trade networks and visual features](https://paperswithcode.com/paper/mapping-the-nft-revolution-market-trends)
- [Networks of Ethereum Non-Fungible Tokens: A graph-based analysis of the ERC-721 ecosystem](https://cs.paperswithcode.com/paper/networks-of-ethereum-non-fungible-tokens-a)

A literature review is available [here](https://docs.google.com/presentation/d/13lzX5JJ7U8a3sf9UAFjuZBYbBgpauxM9nzDNnZ2Tc4c/edit#slide=id.g128c0eb9983_0_0).
