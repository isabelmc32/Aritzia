# Aritzia

Aritzia has mastered being every girl’s trusted brand for any event. However, there are challenges with the e-commerce environment that get between me, your average consumer and you Aritizia. In order for Aritzia to uphold it’s leadership in the fashion industry with e-commerce, we need to empower consumer style. 

To do so, let us introduce you to Amy, an avid aritzia shopper. She has a birthday party tomorrow and needs an outfit. So as every other gen-Z, she goes on tik tok. She sees the melina pants styled on her For You Page. She goes to the Aritzia website and adds the Melina pants to her cart. Then, she runs into some friction in her purchase journey which could lead to cart abandonment.

-> The FIRST Pain point comes from her being in between sizes. 

-> Her SECOND pain point is that she struggles to find the shirt and put together an outfit she's confident about purchasing.


As you might already know, "the cart abandonment rate in fashion e-commerce is 68.3%” According to Ascendia Insights.  That’s a large portion of missed sales.

Therefore, our project has designed a solution to address this issue, and minimize the points of friction during Amy's shopping experience.

SmartStyle is a new feature that allows clients to visualize pieces of clothing put together as a cohesive outfit on a virtual mannequin. Additionally, with Aritzia's fit analytics, we are hoping to use this data to provide size recommendations in order to improve customer satisfaction and increase inventory turnover. This would provide Artizia an innovative edge to drive revenues in the e-commerce plateform and truly highlights their values of everyday luxury in their customer shoppping experience.

[INSERT PICTURES OF SMARTSTYLE HERE]

Aritzia's SmartStyle outfit pairings are based off of data generated from outfit videos on Tiktok, as well as website sales data analytics.

In the following code, the SmartStyle Algorithm is built from scratch using R. A mock dataset was created and imported into R, showing data that might be generated from TikTok videos styling multiple Aritzia pieces together, as well as from website analytics showing which items are commonly purchased together to form an outfit.The knn classifier learns from the mock data we present to it, and shows a 82% accuracy in predicting the correct item to complete the outfit. For example, given the Ganna Jacket, the Melina Pant and The Contour Squareneck Bodysuit, the algorithm will predict that the New Balance 2002R Shoes sold at Aritzia would pair well with this combination of items. The following code runs through the generation of the algorithm, and then tests the algorithm to provide four different outfit suggestions at the bottom of the page.

