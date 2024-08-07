# MIS-SE

# Search Engine (SE)

The **S**earch **E**ngine **(SE)** is an search module of the **Manufacturer Information Service (MIS)**.

| The Search Engine is still under development. Contributions in form of requirements, issues and pull requests are highly welcome. |
|-----------------------------|

## Search Engine Overview

The **Search Engine** scans the **Supplier Knowledge Base** for suitable manufacturer groups (can consist of several suppliers) that are theoretically suitable for performing a production process together.
The Search Engine thus performs an initial matchmaking process between the manufacturing capabilities offered and required. The Search Engine contains a logic to generate SPARQL queries to navigate through the knowledge graphs and find the required manufacturing capabilities. Additionally, the Search Engine calculates the coverage of the required capabilities based on the found manufacturer sets.

Classification of the Search Engine based on the MIS architecture.

<img width="605" alt="SE" src="https://github.com/user-attachments/assets/d12cada7-2d9b-4231-8550-59c645a54dbf">

The following use cases can be performed with the Search Engine.

###  Use Cases of the Search Engine
4. UC4 **Search for potential suppliers/supply chains**
- Identification of potential suppliers/supply chains for a given production process.

### Link to the other MIS components

| Components    | Goals         | URL           |
| ------------- | ------------- | ------------- |
| **Supplier Knowledge Base (SKB)** | Knowledge base for manufacturer/supplier information including capabilities, properties, etc. | [MIS](https://github.com/FraunhoferIOSB/MIS)  |
| **Asset Management and Refinement Application (AMARA)**  | Automatically derives manufacturing capabilities from machine specifications with Large Language Models (LLM)  | tbd  |
| **Asset Management Service (AMS)**  | Interface to manage asset information like enterprise, factories, manufacturing capabilities, etc. within the knowledge base |[MIS-AMS](https://github.com/FraunhoferIOSB/MIS-AMS)  |
| **Search Engine (SE)**  | Provision of manufacturer information such as production capabilities for a given process description  | [MIS-SE](https://github.com/FraunhoferIOSB/MIS-SE)  |
