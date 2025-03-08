# JDE05_Interim_Project
Banana Analysis

**I. Introduction:**

Sustainability is becoming more important in the food industry, and food waste is a growing problem, especially in Singapore. Our client, a food start-up that specializes in baked goods without added sugar, has noticed that banana-based products like banana chips and banana bread are among their best sellers.

However, many bananas are thrown away because they don't meet the perfect look or ripeness for sale in stores. These "imperfect" bananas could still be great for making food products, but they often go to waste.

Using data from our research, we've identified key banana varieties and regions that offer valuable insights for sourcing bananas in a more sustainable way.

**II. Objective:**

Our goal is to find the best varieties of bananas that can be used while also helping to reduce food waste.
By focusing on bananas that are still good but not perfect for retail, we can help the company support sustainability efforts, create healthier products, and reduce food waste—all while still delivering delicious banana products.

**III. ETL Pipeline:**

<img width="572" alt="ETL Pipeline" src="https://github.com/user-attachments/assets/586c853d-6dd0-4d49-b205-9b243abb0ddd" />

**IIIa. ETL Extract:**

<img width="572" alt="ETL_Extact" src="https://github.com/user-attachments/assets/3860ceb2-ceb5-4969-9c6b-185bf83f1f79" />

**IIIb. ETL Transformation:**

<img width="575" alt="ETL_Trans_1" src="https://github.com/user-attachments/assets/48feea10-376a-4264-bda2-d29aac414ce4" />

<img width="575" alt="ETL_Trans_2" src="https://github.com/user-attachments/assets/c59544da-69d3-4d57-a1f4-da9ec5905934" />

<img width="569" alt="ETL_Trans_3" src="https://github.com/user-attachments/assets/21b39749-3634-4d5b-a188-3fe6e3a7d9fa" />

**IIIc. ETL Load:**

<img width="572" alt="ETL_Load" src="https://github.com/user-attachments/assets/9f483327-c731-4a0f-b853-614871e544f7" />

**IV. Analysis:**

**Analysis 1:**

  Banana Varieties with the Lowest Sugar Content

  Query Overview: Focus on varieties with sugar content below 16 °Bx for healthier options.

  3 Banana Varieties with the Lowest Sugar Content:
    Blue Java (Ecuador) - 15.00 °Bx
    Manzano (Brazil) - 15.00 °Bx
    Burro (Colombia) - 15.01 °Bx

  Relevance:
    These varieties could be healthier options for consumers with dietary restrictions (e.g., diabetics or those avoiding sugar).

**Analysis 2:**

  Banana Varieties with the Highest Length (Value)

  Query Overview: Longest average banana length per variety.

  3 Longest Banana Varieties:
    Manzano – 20.90 cm
    Blue Java – 20.75 cm
    Burro – 20.41 cm

  Relevance:
    Longer bananas provide more raw material for banana chips and baked goods, contributing to better cost-effectiveness and value.

**Analysis 3:**

  Banana Varieties with the Highest Weight (Value)

  Query Overview: Focus on the heaviest bananas for more yield per banana.

  3 Heaviest Banana Varieties:
    Fehi (Costa Rica) - 249.89 g
    Lady Finger (Colombia) - 249.79 g
    Red Dacca (Brazil) - 249.60 g

  Relevance:
    Heavier bananas mean more banana product per banana, improving the efficiency of the start-up’s production process and supporting food waste reduction by maximizing      product yield.

**Analysis 4:**

  Average Size and Weight of Bananas in the Processing Quality Category

  Query Overview: Focus on bananas in the "processing" quality category to assess average size and weight.

  Top 3 Bananas in Processing Quality:
    Fehi (Costa Rica) - Avg. Length: 19.86 cm, Avg. Weight: 249.89 g
    Lady Finger (Colombia) - Avg. Length: 19.63 cm, Avg. Weight: 249.79 g
    Red Dacca (Brazil) - Avg. Length: 15.74 cm, Avg. Weight: 249.60 g

  Relevance:
    Processing-quality bananas are perfect for the start-up’s needs, providing a good balance of size and weight while aligning with sustainability goals. Obtaining          their averages allow for a lasting recommendation for future uses

**Analysis 5:**

  Harvest Month of Processing Quality Category

  Query Overview: Focus on the harvest dates of bananas in the "processing" quality 

  Months when Processing Quality Bananas are Harvested:

  September & October 

  ![image](https://github.com/user-attachments/assets/a114f44f-3a40-46f4-b8eb-1b35b5fbe472)

  Relevance:
    Reflects the period when the bananas were harvested, an indication of what to expect.

**V. Conclusion and Actionable Insights:**

**Key Takeaways:**

* Bananas in the processing category (such Fehi, Lady Fingers) are the ideal considerations for banana-based products, like chips and baked goods.

* These varieties can help the start-up reduce food waste by utilizing bananas that may otherwise be discarded.

* Lower sugar varieties (Blue Java, Manzano) may be attractive to health-conscious customers.

* Larger, heavier varieties (Burro, Cavendish) provide more yield for each banana, optimizing the production process.



