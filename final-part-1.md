## Summary

In today’s world, food access has never been easier. With grocery and food delivery services like instacart, uber eats, and the like, we have access to any type of food at our fingertips. Moreover, grocery stores have been on the rise in Pittsburgh. This may sound like it should have a positive effect on food insecurity, however, it does not. Grocery store delivery services, although convenient, are often too pricey for many people to afford. The new grocery stores in the city are extremely concentrated and are usually located in areas where the median income is higher.

## Project Structure
- High-level overview
    - Mention the increased ease of food access
- Number of Grocery Stores in the United States
    - Present graph of the number of stores in the US changing over time (Sketch 1)
    - Present graph of food delivery services in the US changing over the same time frame
- Grocery Store Locations
    - How does Allegheny county stack up against other counties in PA?
        - Show bar chart of where Allegheny lies in Grocery Stores per Capita (Sketch 2)
    - Show a map of where the grocery stores are in the city (Map 1)
    - Group the grocery stores by neighborhood to emphasize that only select neighborhoods have access to grocery stores
- Introduce High Priority Food Areas
    - What are they?
    - Map showing the HFPAs in Pittsburgh (Map 2)
- Ongoing Efforts
    - Urban Farms
        - Grow Pittsburgh has increased the number of community gardens and urban farms from 80 in 2017 to 162 in 2022 (Sketch 3)
    - Graph of how many HFPA’s there are per year (Sketch 4)
- Call to Action
    - Support grow pittsburgh, 412 food rescue, etc.

---

# Initial Sketches
### Sketch 1: Grocery Stores in the United States

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7c94b8f6-bdbb-4468-b69c-3037294f0235/Untitled.png)

### Sketch 2: Grocery Stores per Capita in Allegheny County

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4fc4dfc6-1545-43e6-9761-4c0d9cda8326/Untitled.png)

### Sketch 3: Number of Community Gardens and Urban Farms in Pittsburgh

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/df22e7ad-2478-4fc1-905f-ce21195c2229/Untitled.png)

### Sketch 4: Number of Healthy Food Priority Areas in Pittsburgh

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ed1419a1-7649-4a73-b074-427bc9dcd1eb/Untitled.png)

### Map 1: Where the Grocery Stores are in Pittsburgh

[https://gcp-us-east1.app.carto.com/map/cb9a3315-2067-472d-8657-3fa7aa32fab0](https://gcp-us-east1.app.carto.com/map/cb9a3315-2067-472d-8657-3fa7aa32fab0)

### Map 2: Healthy Food Priority Areas and Grocery Stores in Pittsburgh

[https://gcp-us-east1.app.carto.com/map/6b4c392b-9615-4ba7-8e7b-9b17df9b96fe](https://gcp-us-east1.app.carto.com/map/6b4c392b-9615-4ba7-8e7b-9b17df9b96fe)

# The Data
### Allegheny County Supermarkets

This dataset comes from the Western Pennsylvania Regional Data Center (WPRDC). It contains geospatial data about all supermarkets in the county. I will be using this to illustrate how few markets there are in areas of need in the city.

### Pittsburgh Neighborhoods

This dataset comes from the Western Pennsylvania Regional Data Center (WPRDC). It comes in the form of a GeoJSON file and contains boundaries for all of the neighborhoods in the City of Pittsburgh. I plan on doing a spatial join to count the number of grocery stores in each neighborhood.

### Grow Pittsburgh Food Gardens

There are two datasets that contain information on Grow Pittsburgh food gardens. One is from the WPRDC, which has data from 2017. The other is from the Grow Pittsburgh website, which has data from 2022. I plan on using both of these to present a simple slope graph of the increase in urban gardens in the city as a way to combat food insecurity.

### Healthy Food Priority Areas

The Healthy Food Priority Areas (HFPA) dataset will be from the City of Pittsburgh. It contains census tracts and their associated HFPA score.

### USDA Food Environment Atlas

[https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/)

This dataset contains the number of grocery stores per capita broken down by county. I plan to use this to display a graph of similarly sized counties, and how Allegheny county stacks up.