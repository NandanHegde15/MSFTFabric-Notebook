
📘 Notebook Description

The notebook is designed to extract, enrich, and visualize semantic model metadata and measure-level dependencies within Microsoft Fabric. It connects to a specified semantic model, retrieves tables, columns, measures, and relationships, and enhances measures with AI-generated business descriptions. The notebook then derives measure-to-measure dependencies from DAX expressions, builds a Directed Acyclic Graph (DAG), and presents both tabular lineage outputs and graph-based visualizations. This enables a deep understanding of how calculations are structured and interrelated within the semantic model.

🌟 Benefits

Measure Lineage Transparency:
Provides clear visibility into how measures are built on top of one another, improving model understanding and governance.

AI-Powered Documentation:
Automatically generates business-friendly descriptions for DAX measures, reducing manual documentation effort.

Impact Analysis:
Identifies upstream and downstream dependencies between measures, helping assess the impact of logic changes.


<img width="2585" height="632" alt="image" src="https://github.com/user-attachments/assets/9e930814-017e-4939-8581-4aae638537c7" />


Measure Description :
<img width="2565" height="1042" alt="image" src="https://github.com/user-attachments/assets/a7d36f53-b619-4cfc-8652-b53c44dcd099" />

Measure Dependency DAG :
<img width="2285" height="1305" alt="image" src="https://github.com/user-attachments/assets/924a5fd1-e263-4179-994c-b6840d4edef9" />


