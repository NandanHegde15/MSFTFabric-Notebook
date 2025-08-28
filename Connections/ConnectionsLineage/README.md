
**Description** :
This Fabric notebook is designed to analyze and visualize data connection dependencies across Microsoft Fabric workspaces.
It automatically:

Retrieves all workspaces and their items (like Semantic Models and Dataflows).

Extracts the connections each item depends on (such as linked data sources).

Builds a dependency graph (DAG) using networkx to show how items and connections are related.

Provides an interactive, visual representation of data lineage, helping users trace how data flows through Fabric.

**Benefits** :
Transparency: Makes it easier to see which dataflows, models, and workspaces depend on specific connections.

Impact Analysis: Helps identify what might break if a connection changes or fails.

Governance & Compliance: Supports data governance by documenting data lineage and dependencies.

Optimization: Enables teams to simplify or optimize connection usage by spotting redundancies.

Collaboration: Provides a clear visualization for both technical and non-technical stakeholders to understand dependencies.
