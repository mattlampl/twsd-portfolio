## Summary

In today’s world, food access has never been easier. With grocery and food delivery services like instacart, uber eats, and the like, we have access to any type of food at our fingertips. Moreover, grocery stores have been on the rise in Pittsburgh. This may sound like it should have a positive effect on food insecurity, however, it does not. Grocery store delivery services, although convenient, are often too pricey for many people to afford. The new grocery stores in the city are extremely concentrated and are usually located in areas where the median income is higher.

## Project Structure

### Story Arc

![https://user-images.githubusercontent.com/13319538/192105834-d7aaabf3-d5c5-41f3-806a-ed8cad0aa9e4.png](https://user-images.githubusercontent.com/13319538/192105834-d7aaabf3-d5c5-41f3-806a-ed8cad0aa9e4.png)

### Graph and Map Placement in Story

![https://user-images.githubusercontent.com/13319538/192105840-b220eff9-a478-4187-8f9b-14aa4e2f1299.png](https://user-images.githubusercontent.com/13319538/192105840-b220eff9-a478-4187-8f9b-14aa4e2f1299.png)

Using the story arc above, the story can be distilled down to the following elements:

**Setup:** Grocery stores and grocery delivery services have been on the rise in recent years.

**Conflict:** Even though there are a lot of grocery stores in Pittsburgh, it is extremely hard for people who live in historically disadvantaged neighborhoods to get access to good food.

**Resolution:** Volunteer or donate to community organizations like Grow Pittsburgh and 412 Food Rescue.

# Outline

- High-level overview
    - Mention the increased ease of food access
- Number of Grocery Stores in the United States
    - Present graph of the number of stores in the US changing over time (***Sketch 1***)
    
    ### Sketch 1: Grocery Stores in the United States
    
    ![https://user-images.githubusercontent.com/13319538/192105816-5289feb2-51c0-4d95-8096-2409228e8ad0.png](https://user-images.githubusercontent.com/13319538/192105816-5289feb2-51c0-4d95-8096-2409228e8ad0.png)
    
    - Present graph of food delivery services in the US changing over the same time frame
- Grocery Store Locations
    - How does Allegheny county stack up against other counties in PA?
        - Show bar chart of where Allegheny lies in Grocery Stores per Capita (***Sketch 2***)
        
        ### Sketch 2: Grocery Stores per Capita in Allegheny County
        
        ![https://user-images.githubusercontent.com/13319538/192105824-c81ccbaf-8d2a-4d34-abd3-9f536c321979.png](https://user-images.githubusercontent.com/13319538/192105824-c81ccbaf-8d2a-4d34-abd3-9f536c321979.png)
        
    - Show a map of where the grocery stores are in the city (***Map 1***)
        
        ### Map 1: Where the Grocery Stores are in Pittsburgh
        
        <iframe width="640px" height="360px" src="[https://gcp-us-east1.app.carto.com/map/cb9a3315-2067-472d-8657-3fa7aa32fab0](https://gcp-us-east1.app.carto.com/map/cb9a3315-2067-472d-8657-3fa7aa32fab0)"></iframe>
        
    - Group the grocery stores by neighborhood to emphasize that only select neighborhoods have access to grocery stores
- Introduce High Priority Food Areas
    - What are they?
        - Healthy Food Priority Areas (HFPAs) are areas in the city that are deemed to be an anomalous priority based on several census measures like:
            - Poverty Levels
            - Walkability to grocery stores
            - Obesity rates
    - Map showing the HFPAs in Pittsburgh (***Map 2***)
        
        ### Map 2: Healthy Food Priority Areas and Grocery Stores in Pittsburgh
        
        <iframe width="640px" height="360px" src="[https://gcp-us-east1.app.carto.com/map/6b4c392b-9615-4ba7-8e7b-9b17df9b96fe](https://gcp-us-east1.app.carto.com/map/6b4c392b-9615-4ba7-8e7b-9b17df9b96fe)"></iframe>
        
- Ongoing Efforts
    - Urban Farms
        - Grow Pittsburgh has increased the number of community gardens and urban farms from 80 in 2017 to 162 in 2022 (***Sketch 3***)
        
        ### Sketch 3: Number of Community Gardens and Urban Farms in Pittsburgh
        
        ![https://user-images.githubusercontent.com/13319538/192105829-89ccd1e3-2b86-4808-9606-05dc16c7fde7.png](https://user-images.githubusercontent.com/13319538/192105829-89ccd1e3-2b86-4808-9606-05dc16c7fde7.png)
        
    - Graph of how many HFPA’s there are per year (***Sketch 4***)
    
    ### Sketch 4: Number of Healthy Food Priority Areas in Pittsburgh
    
    ![https://user-images.githubusercontent.com/13319538/192105831-9001899d-c619-441e-86e8-e3ec88a735a9.png](https://user-images.githubusercontent.com/13319538/192105831-9001899d-c619-441e-86e8-e3ec88a735a9.png)
    
- Call to Action
    - Volunteer or donate to Grow Pittsburgh, 412 Food Rescue, or the Greater Pittsburgh Community Food Bank!

---

# The Data

### [Allegheny County Supermarkets](https://data.wprdc.org/dataset/allegheny-county-supermarkets-convenience-stores)

This dataset comes from the Western Pennsylvania Regional Data Center (WPRDC). It contains geospatial data about all supermarkets in the county. I will be using this to illustrate how few markets there are in areas of need in the city.

### [Pittsburgh Neighborhoods](https://data.wprdc.org/dataset/neighborhoods2)

This dataset comes from the Western Pennsylvania Regional Data Center (WPRDC). It comes in the form of a GeoJSON file and contains boundaries for all of the neighborhoods in the City of Pittsburgh. I plan on doing a spatial join to count the number of grocery stores in each neighborhood.

### [Grow Pittsburgh Food Gardens](https://www.growpittsburgh.org/garden-and-farm-resources/growers-map/)

There are two datasets that contain information on Grow Pittsburgh food gardens. One is from the WPRDC, which has data from 2017. The other is from the Grow Pittsburgh website, which has data from 2022. I plan on using both of these to present a simple slope graph of the increase in urban gardens in the city as a way to combat food insecurity.

### [Healthy Food Priority Areas](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/)

The Healthy Food Priority Areas (HFPA) dataset will be from the City of Pittsburgh. It contains census tracts and their associated HFPA score.

### [USDA Food Environment Atlas](https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/)

This dataset contains the number of grocery stores per capita broken down by county. I plan to use this to display a graph of similarly sized counties, and how Allegheny county stacks up.

# Feedback Session Notes

After hearing some feedback about my initial visualizations, I will have to amend and add a few visualizations. Firstly, I got feedback that there is a disconnect between community gardens and food access. To help bridge this gap, I will be adding in a map of where the community gardens are after displaying where the priority areas are in the city. This will show that community gardens are placed in/around areas of high need. Second, I will be changing the color scheme of the first map to grey out the neighborhoods with no grocery stores instead of making those areas black. Finally, I will be adding some more information to the axes of the chart comparing Allegheny county with other counties.
