
## Note: In case of reload error you can copy paste the *.ipynb notebook link that you want to view in "https://nbviewer.jupyter.org/"
(sometimes github fails to render the ipynb notebooks, I believe that is some temporary (and recurring) issue with their backend)

# Truth-about-cars
Brands Analysis

Step1 : To retrieve 5000 posts from 
You can find the scrapper here in Web Scrapper.ipynb and all the posts after scrapping are stored in 'posts.csv'

Step2 : Mapping the models with their respective brand names using the 'car-list.csv' mapping file. 
Replacing the characteristics mentioned in the posts with matching 5 hand-picked attributes (practicality, performance, features and look, durability, desire)
for easy analysis. ('attributesmapping.csv' mapping file )

Step 3 : Calculating the lift ratios for associations between brands and analysing the MDS plot to understand the similarity of the 
existing brands.

Step 4 : Calculating the lift ratios between brands and attributes to understand strongly associated attributes with the respective brands 
Note: Assuming that the sentiment is positive.

Step 5 : Providing insights for the product, marketing and advertising teams based on the relative observations from the MDS plot, lift ratios and brand associations 
with our hand-picked attributes.

