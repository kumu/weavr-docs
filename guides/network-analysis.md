# Network Analysis

You’ll recognize Kumu’s powerful relationship mapping technology on the Network Analysis page. 
Network Analysis is accessible to everyone in the community and can help you discover hidden structures in your community. 

To access Network Analysis, click on the menu icon in the top-left corner of your screen, and then choose "Network Analysis". 

## Functionalities 

### View basic Social Network Analysis (SNA) metrics and rank community members accordingly
When arriving on the Network Analysis page you'll automatically see three SNA metrics at the top of your screen:

- **Connections** - Indicates the number of connections in your current view
- **Density** - Density is defined as the number of connections a community member has, divided by the total possible connections a community member could have. For example, if there are 20 community members, each member could potentially connect to 19 other members. In that case, a density of 1 (19/19) is the greatest possible density in the system, where everyone is connected to everyone. A density of 0.05 (1/19) would be the lowest density possible, and indicates that there's much room for improvement in weaving your community!
- **Avg. Degree** - Degree counts the number of connections an element has, so average degree indicates how many connections the average community member has. In general, members with high degree are the local connectors / hubs, but note that they aren't necessarily the best connected to the wider network.

*Note that these metrics are re-calculated for every view. So if you've filtered your network map based on relationships strengths, then your metrics will also update according to the view you're looking at.*

To run more advanced SNA metrics with your community data, we recommend to [export your Weavr data to Kumu](/guides/export-kumu.md), where you can run many more [SNA metrics](https://docs.kumu.io/guides/metrics.html). 

### See your community’s relationships and relationship strengths
Each arrow on your network map indicates a relationships between those two members. The strength of the relationships is reflected by the thickness of the connection. As such, you can quickly see which relationships in your community are stronger vs weaker. 

### Filter based on relationship strengths
Click on the Map Settings icon in the bottom-right corner of your screen to further customize your network map. At the top of the menu that pops up, you'll be able to filter your map by relationship strength. You can check any or all of the checkboxes, depending on the view you'd like to see. 

### Color based on profile fields and add a legend
Click on the Map Settings icon in the bottom-right corner of your screen to further customize your network map. Then, click on the dropdown "Color elements by:" to choose a field to color your map by. Upon choosing the field, a legend will be added in the bottom-left corner of your map. Please note you can only color by one field at a time.

### Include orphans
"Orphans" are community members that aren't connected to anyone in the community, and thus, float around the network map without being part of the community. They are usually placed around the edges of your network map.

Since orphans can distort your SNA metrics, Weavr automatically takes them out of your view. if you prefer to include them, click on the Map Settings icon in the bottom-right cornerr of your screen, and then check the "Include orphans" checkbox at the bottom of the menu that pops up. Don't forget to Save!

### Rank the community
If you click on the menu bar at the bottom of the Network Analysis page where it says "Showing x people(x hidden)", you can rank your community based on some more SNA metrics. The current options are: 

- **Betweenness Centrality** - Betweenness centrality measures how many times a community member lies on the shortest path between two other community members. In general, members with high betweenness have more control over the flow of information and act as key bridges within the network. However, they can also be potential single points of failure.
- **Incoming Connections** - Measures the number of incoming connections for a specific community member (also called "indegree"). That is; many people indicated they have a relationships with them. In general, members with high indegree (incoming connections) can be regarded as leaders in a community, looked to by others as a source of advice, expertise, or information.
- **Outgoing Connection** - Measures the number of outgoing connections for a specific community member (also called "outdegree"). In general, members with high outdegree (outgong connections) have the potential to reach a high number of other elements and spark the flow of information across a network. Nevertheless, they may not be the most efficient at spreading the information, or may report relationships that aren't reciprocated. 
- **Total Connections** - Counts the number of connections a specific community member has (alo called "degree"). In general, members with high degree are the local connectors / hubs, but aren't necessarily the best connected to the wider network.

*Looking to do more extensive network analysis? [Export your Weavr data to Kumu](/guides/export-kumu.md) to use Kumu's more advanced features.*
