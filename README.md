Dataset
To collect dataset, we captured a scrolling screenshots from wide range of website categories in portrait mode. All screenshots were pre-processed to standardize the screenshot sizes.
 Data Collection
We collected 1000 portrait-oriented scrolling screenshots. We took care to gather a varied dataset that encompassed a variety of website categories, such as corporate, government, e-commerce, membership, and online forums. We collected our data and saved it as 922 x 744 pixel JPG images using the GoFullPage tool .The screenshots collection process resulted in 1678 image, gathered from 963 websites. To create the final dataset, we meticulously picked 1000 screenshots from this enormous collection. We applied particular criteria to eliminate the screenshots in order to guarantee a unique and varied aesthetics while also ensuring the dataset's relevance and focus. 

Dataset Annotation
QUESTIM based annotation: For the objective evaluation, we utilized the QUESTIM tool  to assess six aesthetic metrics. These metrics, chosen for their relevance in capturing various aspects of visual aesthetics of screenshot image (𝑰), were evaluated on a scale from 0 to 1. Specifically, when interpreting data metrics where 0 indicates low and 1 indicates high, it is important to note that this is standard for all metrics except compression complexity. For compression complexity, the scale is inverted. The aesthetics metricsevaluated by QUSETIM are:
1. Saliency Balance (SB): Measures the balance of visual saliency across the webpage.
2. Border Balance (BB): Assesses the distribution of borders within the layout.
3. Border Density (𝑩𝑫): Quantifies the density of borders in the design.
4. Color Density (CD): Evaluates the distribution and concentration of colors.
5. Colorfulness (𝑪𝑭): Measures the overall colorfulness of the design.
6. Compression Complexity (CC): Assesses the complexity of the visual design in terms of compression.
These metrics can be formally represented as a vector for each website screenshot :

Human expert based annotation: In addition to automated evaluation, we incorporated human judgments into our assessment process. A panel of human experts evaluated each design based on three additional aesthetic metrics, rated on a scale from 1 to 5. Theaesthetics metrics evaluated by Human expert are:
1. Rate Consistency (𝑹𝑪𝑺): Evaluates the consistency of the visual design.
2. Rate Text Clarity (RCT): Assesses the clarity and readability within website design.
3. Rate Satisfaction (RS): Measures the overall satisfaction with the design.
These human evaluations can be represented as another vector for each website screenshot

[Download  the dataset](https://drive.google.com/drive/folders/1gI9WlMelxzZNow4jT5YStgb9ynW1wbe0?usp=sharing)

note:Data set will be available after paper published

