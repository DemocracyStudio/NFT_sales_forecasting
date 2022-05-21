# NFT sales forecasting: a hybrid approach with Computer Vision and Time Series. 
This repository gathers all the information, code and data about the NFT sales forecasting started as a group project at Machine Learning degree of [opencampus.sh](https://opencampus.sh). Team mates are: Malte Bartels, Khanh Ho, Julien Carbonnell.

### Project Description:
NFT sales increased fastly and there’s a lot of speculation around. It is nascent market of $50B capitalization, highly volatile and hardly predictable. Because it is becoming a key element of ownership in the digital world, forecasting NFT value is important for individual financial security and investment making. Since the value of NFTs depend on weak signals scattered on different digital platform of various nature, AI can help making a sense out of the NFT market to identify good investments and build a trustworthy NFT recommendation system.

In the determination of critical factors making NFT valuable or not, visual features are mainly undiscovered. Our approach will be to hybrid computer vision and time series on sales to predict NFT values forecasting. A CNN model will be used to extract visual features, which will be combined with historical market data, to perform a cross-sourced regression analysis looking for market changes and their timing.

A pitch deck is available [here](https://docs.google.com/presentation/d/1jHd8AsHRDuHgiaFrP9hq1H6JN3bmCKH4gCR4JS-Z7NQ/edit?usp=sharing). 

### Datasets:
There are more NFTs on NFT marketplaces today than there were websites in 2010. Covering the whole available NFTs' data would have been impossible. Furthermore our model ambitions to take a mainly undiscovered approach to NFT sales forecasting by using feature extraction on images, which induces heavier data manipulation and higher computational costs. We first trained our model on existing datasets publicly shared on Kaggle before deploying it on OpenSea API. The training datasets are the followings:

Historical sales data
- [NFT sales](https://www.kaggle.com/datasets/hemil26/nft-collections-dataset) collected on [cryptoslam.io](https://cryptoslam.io/) on April 30, 2022.
- [NFT Top Collections](https://www.kaggle.com/datasets/nenamalikah/nft-collections-by-sales-volume) collected on [coinmarketcap.com](https://coinmarketcap.com/nft/collections/) on January 16, 2022.
- [NFT collections, NFT Daily Volume and NFT Chainlevel](https://www.kaggle.com/datasets/sudalairajkumar/nft-dataset-from-defillama) collected on [defillama.com](https://defillama.com/nfts) on January 6, 2022.
- [OpenSea Collections](https://www.kaggle.com/datasets/mathurinache/opensea-collections) collected on [opensea.com](https://opensea.com) on November 27, 2021.
- [NFT History Sales](https://www.kaggle.com/datasets/mathurinache/nft-history-sales) collected on [nonfungible.com](https://nonfungible.com/) on November 12, 2021.
- [Ethereum NFTs](https://www.kaggle.com/datasets/simiotic/ethereum-nfts) collected on [moonstream.to](https://moonstream.to) on September 25, 2021.
- [Spacebudz metadata](https://www.kaggle.com/datasets/kabure/spacebudz-cardano-nft-complete) provided by [spacebudz.io](https://spacebudz.io/) on July 8, 2021.
- [Solana NFT Collections](https://www.kaggle.com/datasets/eyenpi/solana-nft-collections?select=Solana+NFT+Collections) collected on [magiceden.io](https://magiceden.io) on April 18, 2021.
- [Opensea Sales](https://www.kaggle.com/datasets/francescofalleni/nft-historical-sales?select=nft_sales.csv) collected on [opensea.com](https://opensea.com) on February 28, 2021.
- [Niftys](https://www.kaggle.com/datasets/cianoner/nifty-gateway-nfts) collected on [niftys.com](https://niftys.com) on February 8, 2021.

Images data
- [Witches](https://www.kaggle.com/datasets/harrywang/crypto-coven) collected on opensea.com on April 22, 2022.
- [CryptoPunks](https://www.kaggle.com/datasets/tunguz/cryptopunks) collected on [larvalabs.com](https://larvalabs.com/cryptopunks) on October 8, 2021.
- [Bored Apes](https://www.kaggle.com/datasets/stanleyjzheng/bored-apes-yacht-club) collected on opensea.com (https://opensea.com) on July 14, 2021.
- [NFT art collection](https://www.kaggle.com/datasets/vepnar/nft-art-dataset) collected on [nftshowroom.com](https://nftshowroom.com/) on March 29, 2021.

Additionnaly, reddit.com and twitter.com datasets are available. 

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
