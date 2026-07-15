# Plastic Production Life Cycle Assessment (LCA) using openLCA

## Overview

This project presents a simplified cradle-to-gate Life Cycle Assessment (LCA) of **1 kg of plastic production** using **openLCA 2.6.2**. The model includes the major upstream processes involved in producing plastic and estimates the associated carbon dioxide (CO₂) emissions.

This project was created as part of my learning in Life Cycle Assessment (LCA) and process modeling.

---

## Goal

- Model the plastic production process in openLCA.
- Analyze upstream environmental impacts.
- Estimate CO₂ emissions associated with producing 1 kg of plastic.
- Visualize contribution analysis using Sankey diagrams and process graphs.

---

## Functional Unit

**1 kg Plastic Product**

---

## System Boundary

The model includes the following processes:

- Crude Oil Extraction
- Naptha Production
- Steam Generation
- Diesel Production
- Electricity Generation
- Ethylene Production
- Polymerization
- Plastic Production

---

## Process Flow

```
Crude Oil Extraction
        │
        ▼
 Naptha Production
        │
        ▼
 Ethylene Production
        │
        ▼
 Polymerization
        │
        ▼
 Plastic Production
```

---

## Software Used

- openLCA 2.6.2
- Microsoft Excel

---

## Inventory Inputs

The model includes the following major inputs:

- Crude Oil
- Electricity
- Steam
- Diesel
- Water

---

## Results

### Functional Unit

- **1 kg Plastic Product**

### Total CO₂ Emissions

- **≈ 4.18 kg CO₂ per kg of plastic produced**

### Major Contributors

| Process | Contribution |
|---------|-------------:|
| Crude Oil Extraction | 1.50 kg CO₂ |
| Ethylene Production | 1.125 kg CO₂ |
| Naptha Production | 0.625 kg CO₂ |
| Polymerization | 0.400 kg CO₂ |
| Steam Generation | 0.388 kg CO₂ |
| Plastic Production | 0.100 kg CO₂ |

---

## Repository Structure

```
Plastic-Production-LCA-OpenLCA/
│
├── README.md
├── LICENSE
│
├── database/
│   └── plastic_production.zip
│
├── results/
│   ├── plastic_production_results.xlsx  
│
├── screenshots/
│   ├── model_graph.png
│   ├── sankey_diagram.png
│   ├── contribution_tree.png
│   ├── contribution_chart.png
│   ├── total_requirements.png
│
```

---

## Screenshots

### Process Model

<img width="2182" height="1442" alt="model_graph" src="https://github.com/user-attachments/assets/6112a707-a07e-4051-856d-c5af821052c8" />

---

### Sankey Diagram

<img width="2182" height="1342" alt="sankey_diagram" src="https://github.com/user-attachments/assets/091008cb-8606-42f5-a33d-72407643d1bd" />


---

### Contribution Tree

<img width="797" height="258" alt="contribution_tree" src="https://github.com/user-attachments/assets/73808705-c4e1-43c9-9599-bbb2e1e6a938" />


---

### Contribution Chart

<img width="1064" height="390" alt="contribution_chart" src="https://github.com/user-attachments/assets/12ee1e2e-fc3f-4881-a200-5a0a40ecd42c" />


---

### Total Requirements

<img width="1052" height="250" alt="total_requirements" src="https://github.com/user-attachments/assets/621855c2-356e-41a9-8967-714f169d932b" />


---

## Future Improvements

- Include additional elementary flows.
- Add more detailed background datasets.
- Perform LCIA using ReCiPe 2016 or EF methods.
- Compare results with published LCA literature.
- Extend the model to include end-of-life scenarios.

---

## License

This repository is intended for educational and research purposes.

Please provide appropriate attribution if you use or reference this work.

---

## References

This project demonstrates the modelling of a simplified plastic production system in OpenLCA. Process inventory values are educational estimates based on engineering literature and publicly available industrial information.

Typical references consulted include:

- OpenLCA Documentation
- ecoinvent Database (methodology reference)
- ELCD (European Reference Life Cycle Database)
- PlasticsEurope Eco-profiles
- Engineering literature on naphtha cracking, ethylene production and polymerization

---

## Author

**Mulka Sushanth**

Chemical Engineering Undergraduate  
National Institute of Technology Warangal

Learning Life Cycle Assessment (LCA), Sustainability, and Process Modeling using openLCA.
