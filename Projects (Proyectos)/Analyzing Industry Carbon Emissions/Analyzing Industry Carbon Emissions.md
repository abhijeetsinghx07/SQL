
___

### Food, clothing, footwear, and appliances all contribute to more than 75% of the world's carbon emissions.
___

![image](https://user-images.githubusercontent.com/108348003/211213928-ab581c1d-fe7d-453f-8c37-e00ce1f05f28.png)


**Product carbon footprints (PCFs) for various businesses are contained in the data, which is publically accessible online. The PCFs are the CO2 emissions from a certain product that may be attributed to greenhouse gas emissions (carbon dioxide equivalent).**

**PCFs, or product carbon footprints, are becoming more important in helping businesses and consumers make sustainability-related decisions.**

***Read more about carbon footprints here(https://www.nature.com/articles/s41597-022-01178-9#Tab1).***

### 1. Coca-Cola's emissions

First, let's look at a small subset of the data: emissions reported by Coca-Cola. Coca-Cola is actually made up of multiple companies around the globe, so we'll make sure our query returns data for any company name that starts with "Coca-Cola".

```sql
SELECT * 
FROM product_emissions
WHERE company LIKE 'Coca-Cola%';
```
