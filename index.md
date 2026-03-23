# AI Supply Chain Network

## The Artifact

![Network visualization showing AI supply chain from mining and labor to manufacturing, big tech companies, and data centers](assets/AI%20Map.jpeg)

*Figure 1. AI supply chain network showing flow from resource extraction to AI infrastructure.*

[View the interactive AI supply chain network on Kumu](https://embed.kumu.io/876a9150196a60570cb17fcced850534)


## Network Analysis
The most central node in this network is NVIDIA, based on its high degree and betweenness centrality. It connects to multiple major technology companies, including Google, Microsoft, Amazon, and Tesla, and acts as a key supplier of AI chips. This makes NVIDIA a critical intermediary between manufacturing (e.g., TSMC) and the companies that deploy AI systems.

Several clusters emerged clearly. First, there is a resource extraction cluster on the left, including cobalt and lithium mines, which are connected to workers and traders. This flows into a manufacturing cluster (CATL, Panasonic, TSMC, Foxconn), which then connects to a Big Tech cluster (NVIDIA, Apple, Tesla, Google, Microsoft, Amazon). Finally, there is an infrastructure and energy cluster centered on data centers and the electric grid.

One surprising insight is how small and peripheral the labor and mining nodes appear, despite being essential to the entire system. In contrast, companies like NVIDIA and large data centers dominate visually and structurally.

What is missing from this network is the environmental impact of extraction and energy use, as well as more detailed representation of global inequalities, such as working conditions and regulatory systems.

## Artist Statement
This network reveals that power in AI is highly concentrated in a small number of visible actors, particularly large technology companies and infrastructure providers. Nodes like NVIDIA and data centers are positioned centrally and appear larger, emphasizing their dominance.

In contrast, many essential contributors are structurally and visually marginalized. Workers in mining regions and sites of resource extraction are pushed to the edges of the network, making them less visible despite their importance.

The structure of the network also shapes interpretation. By organizing the system as a linear flow, the visualization emphasizes efficiency but may obscure inequalities and dependencies. A different structure could instead highlight labor, environmental costs, or global inequality.

Overall, this network demonstrates that visualization is not neutral and that design choices influence what becomes visible and what remains hidden.

## Process Notes
I created this network using Kumu to visualize the AI supply chain. I first built a spreadsheet listing connections between entities, including source, target, relationship type, and weight.

After importing the data into Kumu, I structured the network from left to right to show the flow from mining to manufacturing to Big Tech and infrastructure. I limited the number of relationship types to keep the visualization clear.

I also categorized nodes into groups such as mining, manufacturing, Big Tech, infrastructure, and labor, and sized nodes by degree centrality to highlight important actors.

## Reflection
This project showed me that network visualizations are not neutral but constructed interpretations. The decisions I made about structure, inclusion, and layout influenced what appears important.

I observed that central actors like NVIDIA and data centers dominate the network, while labor and resource extraction remain peripheral. This reflects real-world power structures but also shows how visualization can reinforce them.

The network also simplifies reality by excluding environmental and political factors. This made me more aware of how visualization can both reveal and obscure power.