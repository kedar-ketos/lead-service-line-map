![Image title](https://raw.githubusercontent.com/kedar-ketos/lead-service-line-map/main/docs/images/logo.png)

<p align="center">
    <em>Lead Service Line Map is a fast, automated way of generating lead service line maps for utilities. Users can build their own lead service line maps in three easy steps.</em>
</p>

## Structure
---

**Demo application**: <a href="https://app.powerbi.com/view?r=eyJrIjoiN2VkNzY0MTktMDU4Zi00MzkzLTk2Y2YtOTJmY2E3N2MyYTk1IiwidCI6IjNhMzM0YmY0LThlNjEtNDNhOS04ZmY1LWFiYTQ0YzcxY2VhOCIsImMiOjZ9&pageName=ReportSection56a47a80c507793ad45d" target="_blank">Open</a>

**Documentation**: <a href="https://kedar-ketos.github.io/lead-service-line-map" target="_blank">https://kedar-ketos.github.io/lead-service-line-map</a>

**Source Code**: <a href="https://github.com/kedar-ketos/lead-service-line-map" target="_blank">https://github.com/kedar-ketos/lead-service-line-map</a>

**Tutorial**: <a href="https://kedar-ketos.github.io/lead-service-line-map/tutorial/prerequisites/" target="_blank">https://kedar-ketos.github.io/lead-service-line-map/tutorial/prerequisites/</a>

---

These are the only three actions that utilities need to take to generate their own lead service line map using our approach:

1. Get your datasets
2. Format data
3. Refresh dashboard


## The need

It was developed by [KETOS](https://ketos.co) as a submission entry to the Water Data Prize 2021.

The first step in building an accurate lead service line inventory is consolidating the existing data and visualizing it on a map. Mapping allows decision-makers to understand the intensity of the challenge posed by lead service lines, prioritize efforts and plan execution. Maps also help keep residents updated about the replacement efforts and adopt healthy drinking water practices.

Unfortunately, most utilities do not have the resources to develop a service line mapping solution. Although several reasonable mapping solutions exist ([DC Water](https://geo.dcwater.com/Lead/), [Pittsburgh's PWSA](https://lead.pgh2o.com/your-water-service-line/planned-water-service-line-replacement-map/), [Flint service line map](https://flintpipemap.org/)), they are often custom-built for specific utilities. In addition, some of them assume specialized geographic information system (GIS) skills and, once adopted, do not allow the user organization flexibility to alter their underlying infrastructure. Finally, some maps bombard the viewers with considerable information taking away focus from the most critical messages.

We have addressed these challenges in our solution by combining a model for data storage with a publicly available mapping tool. At the same time, the two parts of our solution are not dependent on one another. This decoupling of the data storage and visualization gives users the flexibility to switch the mapping tool as they see fit. We have made our maps interactive, fun, and enjoyable to read. We achieved this by combining some excellent visual concepts from exising solutions with some new visual suggestions.


## Challenges with existing mapping solutions

### 1. Generalizability
   
Inability to generalize maps across different utilities is probably the biggest challenge that the existing mapping solutions face today. At best, these maps are typically designed and built for large utilities. Some use excellent mapping concepts, but they inadvertently limit their rapid, widespread adoption by not allowing all utilities to replicate these maps for their own geographies.

### 2. Rigid data infrastructure
   
The most widely used dynamic mapping solutions expect the users to convert their data into a format that their tools support. As a result, a significant amount of effort goes into preparing data. Furthermore, to ensure that the maps dynamically update, the user organizations may need to rethink their existing 'data storage and transformation' infrastructure.

### 3. Difficult to read
   
We also observed that viewers are sometimes overwhelmed by the volume of content they see when they visit lead service line maps. We think users deserve to view all available data about lead lines, but a viewer???s engagement is higher if they are presented that data gradually.

Some lead service line maps also tend to be verbose and text-heavy, discouraging viewer engagement. Besides, they also lack proper guidelines about what a user should do next. Although we know that viewers tend to engage more when a data visualization is conversational, we saw that the existing maps are not very engaging.


## Features of our solution

We combined the best practices used in the existing mapping solutions with newer proposals to improve communication. Specifically, we tried to address the three challenges outlined above - generalizability, rigidity in infrastructure, and difficulty in reading. Here are the significant features of our solution. We discuss each of these in greater depth in the subsequent sections.

1. Universal data model
2. Decoupled data storage and visualization layers
3. Share information in stages
4. User-friendly design and workflow
5. Greater engagement with data