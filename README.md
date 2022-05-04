# Instagram_analysis for Aritzia

This project aims to help Aritzia increase engagement on their Instagram page, by analyzing what type of images they should post more and less. The main steps are as follows:

- It will start by scraping the latest 500 images and related captions and the number of comments per post from Aritzia's Instagram page. 
- Topic modeling (LDA) will be performed on the image labels from Google Vision.
- Sort the data from high to low engagement (measured by the number of comments), and take the highest and the lowest quartiles.
- Find out the main differences in the average topic weights of images across the two quartiles.
- Analyze what types of image will gain more engagement and make suggestions. 


#### See [Instagram Analysis](https://github.com/574567254/Instagram_analysis/blob/2a0e8bb0776e54ee0a67e16112338b4099b0fdfe/Instagram_analysis.ipynb) Jupyter Notebook for detailed analysis
#### All the external data used and outputs of the project are in the [data_used&output](https://github.com/574567254/Instagram_analysis/blob/2a0e8bb0776e54ee0a67e16112338b4099b0fdfe/data_used&Output) folder
