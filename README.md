# MIS-SE

# Search Engine (SE)

The **S**earch **E**ngine **(SE)** is an search module of the **Manufacturer Information Service (MIS)**.

| The Search Engine is still under development. Contributions in form of requirements, issues and pull requests are highly welcome. |
|-----------------------------|

## Search Engine Overview

The **Search Engine** scans the **Supplier Knowledge Base** for suitable manufacturer groups (can consist of several suppliers) that are theoretically suitable for performing a production process together.
The Search Engine thus performs an initial matchmaking process between the manufacturing capabilities offered and required. The Search Engine contains a logic to generate SPARQL queries to navigate through the knowledge graphs and find the required manufacturing capabilities. Additionally, the Search Engine calculates the coverage of the required capabilities based on the found manufacturer sets.

Classification of the Search Engine based on the MIS architecture.

![SE](/../main/docs/src/images/SE.PNG)

The following use cases can be performed with the Search Engine.

###  Use Cases of the Search Engine
UC3 **Requesting manufacturer information**
- Data consumer can use the MIS to query information such as production capabilities for a data provider.

UC4 **Search for potential suppliers/supply chains**
- Identification of potential suppliers/supply chains for a given production process.

### Link to the other MIS components

| Components    | Goals         | URL           |
| ------------- | ------------- | ------------- |
| **Supplier Knowledge Base (SKB)** | Knowledge base for manufacturer/supplier information e.g. capabilities, properties, etc. | [MIS-SKB](https://github.com/FraunhoferIOSB/MIS-SKB)  |
| **Asset Management and Refinement Application (AMARA)**  | Automatically derives manufacturing capabilities from machine specifications with Large Language Models (LLM)  | [MIS-AMARA](https://github.com/FraunhoferIOSB/MIS-AMARA) |
| **Asset Management Service (AMS)**  | Interface to manage asset information like machines, manufacturing capabilities, etc. within the knowledge base |[MIS-AMS](https://github.com/FraunhoferIOSB/MIS-AMS)  |
| **Search Engine (SE)**  | Provision of manufacturer information such as production capabilities for a given process description  | [MIS-SE](https://github.com/FraunhoferIOSB/MIS-SE)  |
| **Multi-Port Connector (MPC)**  | The Multi Port Connector (MPC) is a connector to address the APIs of various Factory Connectors.  | [MIS-MPC](https://github.com/FraunhoferIOSB/MIS-MPC)  |

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions are **greatly appreciated**.
You can find our contribution guidelines [here](CONTRIBUTING.md)

## Contact

info-disc-ecosystem@iosb.fraunhofer.de

## License

Distributed under the Apache 2.0 License. See `LICENSE` for more information.

Copyright (C) 2022 Fraunhofer Institut IOSB, Fraunhoferstr. 1, D 76131 Karlsruhe, Germany.

You should have received a copy of the Apache 2.0 License along with this program. If not, see https://www.apache.org/licenses/LICENSE-2.0.html.
