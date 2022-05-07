 <img src="https://pbs.twimg.com/media/FRT011vVUAAE0iF?format=jpg&name=4096x4096" alt="Beeple Art" width="100%"/>

## Table of Contents

1. [Project Summary](#-1-project-summary)
2. [Hypothesis](#-2-hypothesis)
3. [Data Collection & Cleanup](#-3-data-collection--cleanup)
4. [Analysis](#-4-analysis)
5. [Postmortem](#%EF%B8%8F-5-postmortem)
6. [Discussion](#-6-discussion)
7. [Contributors](#7-contributors)

## 🎒 1. Project Summary
* Our project uncovers patterns in NFT trading for three NFT collections.
    * Part One : [*Boyed Ape Yatch Club*](https://boredapeyachtclub.com/)
    * Part Two : [*Azuki*](https://www.azuki.com)
    * Part Three : [*Cryptopunks*](http://larvalabs.com/cryptopunks)
* We'll examine relationships between types of:
    * Art and customers
    * Purchase prices and timestamps
    * Trends in purchases over time
    * Historical Volume 
    * Purchase prices
    * Trends in sales
    * Transaction data ie. transaction fees paid for all collections
    * Other related questions as the data admits

## 🎩 2. Hypothesis
* Should you invest in Azuki, BAYC or Crypto Punks? 
    * What are people paying for NFT in USD value?
    * How much in fees are being paid per transaction?
    * Is the value appreciating or declining?
* How can you tell which collection is performing well?
    * What is the daily transaction volume after Collection is released?

## 🧤 3. Data Collection & Cleanup
* How do we collect NFT data?
    - [x] Covalent APIs
    - [x] Etherscan API
    - [X] CSV data imports
    - [x] Other Dependancies ie. Plotly Express
    ![APIs and Imports](./exports/png/nft_analysis.png)
* Why cleanup data?
    * Prepare data for analysis
    * Isolate the types of data we are interested in from the rest
    * See what the customer data look like
    * Evaluate performance

## 🦺 4. Analysis

* What kind of data we like to work with and the field we're interested in 
    * Market Caps
    * Transaction data
    * NFT art trading sales
    * Gas Prices prices
    * Price volatility
    * Collections
    * Token IDs
    * Contract addresses
    * NFT Owners
    * Global view of NFT Marketplace
    * Wrapped tokens
    * Major Exchanges that process NFT transactions

<!---
 <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flh3.googleusercontent.com%2FOr5DrlLFz9XuY-qAbl-YrkFd0BADhLjwbmWoRDil17X-UAxmSwngrzXiFuJcVb42SDp5eH3dvnflOdsea98jGy1X24dfFgERgcQV&f=1&nofb=1" alt="Beeple Art" width="100%"/>
-->

- [x] Part One: Bored Ape Yatch Club

    ![Daily Volume Bored Apes](./exports/BAYC_daily_volume.png)
    ![Ape Sales](./exports/BAYC_daily_sales.png)

<!---
    ![](./images/azuki_girl44.png)
-->

- [x] Part Two : Azuki

    ![Daily Volume Azukis](./exports/azuki_daily_volume.png)

    ![Azuki Sales](./exports/azuki_1000_sales.png)

    ![Fees Comparison](./exports/fees_paid_comparison.png)

    ![Comparing Collections performance](./exports/Volume_sales_recent_1000.png)

<!--- 
![ Punks](./images/punks_pr0.png)
-->

- [x] Part Three: Cryptopunks

    ![Wrapped Cryptopunks](./images/wraped_punks.png)
    ![Cris Punks](./images/cryptopunks_bokeh_plot.png)
    ![Chris Combined plot](./images/punks_combined_wrapped_analysis.png)
    ![Chris Cryptopunks Sales Ether](./images/cryptopunks_sales_by_ether.png)



## ⛑️ 5. Postmortem
* Did we find everything we expected to find?
    - [x] Difficulties
        * Setting proper scope on NFTs there is a lot of data that is available
        * Concating data from multiple data sources
        * Data cleaning
        * Choosing which data to compare and study
        * Selecting plots to display data
        * Using unfarmiliar libraries
        * Working in git as a group
        * Coordinating schedules with people remote
    - [x] How did we deal with them
        * Googling
        * Stackoverflow
        * Reading official documentation
        * Consulting instructor
        * Asking tutors
    - [x] Additional questions that came up that we would research next if we had more time
        * Global NFT market sales comparison
        * Burned tokens vs Active tokens
        * Correlate NFTs that were around pre 2020 to major crypto pricing trends
        * How can we separate authentic sales from suspicious NFT transactions?
        * Why would I buy an NFT vs just create my own?
    
## 🎤 6. Discussion

* After we've analyzed our data to our satisfaction, we'll put together a presentation to show off our work, explain our process, and discuss our conclusions.
* This presentation will be delivered as a slideshow, and it would give our classmates and instructional staff an overview of our work. 

## Summary
* CryptoPunks, Azuki & BAYC
    - Would not recommend investment at this time unless you were a seasoned NFT collector, looking at long term royalty market in metaverse or were passionate about a particular punk.
    * I would recommend trying to get in on ground for new NFT releases and have a plan why you are getting into market. 
    * Possibly reasons to invest:
        * Passion for NFTs
        * Flip for profit
        * Creator
        * Community love
    * CyrptoPunks activity and pricing stayed pretty level from inception 2017 through mid-2020 then the market exploded in parallel with adoption of Crypto currencies.

**File:** [Analysis](./project_analysis_2.0.ipynb) <br>
**File:** [Project Presentation](./exports/pdf/group_presentation.pdf)

![](./exports/project_analysis_2.0.png)
## 7. Contributors 

- [@mmsaki](https://github.com/mmsaki)
    * Organisation
    * Analysis
    * Powepoint Presentation
    * README.md
    * Azukis
- [@dockingbay24](https://github.com/dockingbay24)
    * Data Collection
    * APIs selections
    * Merge branching
    * Cryptopunks
- [@angel-estrada7](https://github.com/angel-estrada7)
    * Genreal Analysis
    * Assist w/ presentation
    * Bored Ape Yatch Club

