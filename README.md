[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/health-data-science-OR/healthcare-logistics/HEAD)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4333675.svg)](https://doi.org/10.5281/zenodo.4333675)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/release/python-3100+/)

---

# 🗺️ Healthcare Logistics & Optimization

Practical materials for modeling and optimizing healthcare logistics, part of the **HPDM097: Making a Difference with Health Data** module.

## 📖 Overview

This repository provides hands-on training in geospatial analysis and optimization for healthcare logistics. Through practical exercises, you'll learn to apply location science, routing algorithms, and geographic analysis to real-world health service delivery problems, from facility placement to ambulance routing.[1]

### What You'll Learn

- Geospatial data analysis and visualization for healthcare
- Facility location optimization and accessibility modeling
- Healthcare routing and scheduling problems
- Vehicle Routing Problem (VRP) fundamentals
- Geographic equity and access analysis
- Real-world case studies in sexual health services

## 🚀 Quick Start

### Prerequisites

- **Python**: 3.10 or higher
- **Core Skills**: Python programming, pandas, NumPy

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/health-data-science-OR/healthcare-logistics.git
   cd healthcare-logistics
   ```

2. **Create the conda environment**
   ```bash
   conda env create -f binder/environment.yml
   conda activate hds_logistics
   ```

3. **Launch Jupyter**
   ```bash
   jupyter lab
   ```

### 🚨 Important Notes

- **Notebooks 2, 3, and 4** require a local `metapy` package and **will not run in Google Colab**
- All notebooks are fully compatible with **Binder** for cloud-based execution
- For local execution, ensure all dependencies are installed via the provided environment file

## 📚 Course Structure

### Exercise 1: Mapping and Geospatial Analysis

**Topics**: Geographic data handling, coordinate systems, spatial visualization, catchment areas

**Materials**:
- Exercise: Introduction to geospatial analysis for healthcare
- Solutions: Complete implementation with visualizations

**Key Skills**:
- Loading and manipulating geographic data (shapefiles, GeoJSON)
- Creating interactive maps with healthcare facilities
- Calculating distances and travel times
- Catchment area analysis
- Population accessibility metrics
- Spatial joins and overlays

**Applications**: 
- Mapping hospital locations and patient populations
- Service coverage analysis
- Health equity assessment by geography

**Technologies**: GeoPandas, Folium, Shapely

***

### Exercise 2: Facility Location - Sexual Health Case Study

**Topics**: Location-allocation modeling, p-median problem, maximum coverage, accessibility optimization

**Materials**:
- Exercise: Real-world sexual health service location problem
- Solutions: Complete optimization workflow

**Key Skills**:
- Formulating facility location problems
- Implementing location-allocation algorithms
- Evaluating service accessibility and coverage
- Trade-offs between equity and efficiency
- Scenario analysis and sensitivity testing
- Constraint handling (capacity, budget, political)

**Applications**:
- Sexual health clinic placement
- Hospital consolidation planning
- Urgent care center network design
- Mobile health unit deployment

**Case Study Context**: 
Optimizing the location of sexual health clinics to maximize population access while considering travel barriers, demographic needs, and resource constraints.[1]

**Technologies**: PuLP/Pyomo for optimization, GeoPandas, custom metapy package

***

### Exercise 3: Introduction to Routing and Scheduling

**Topics**: Traveling Salesman Problem (TSP), route optimization, scheduling constraints, healthcare-specific routing

**Materials**:
- Exercise: Healthcare routing scenarios
- Solutions: Complete implementation examples

**Key Skills**:
- Formulating routing problems
- Implementing TSP and tour construction heuristics
- Incorporating time windows and priorities
- Route evaluation metrics (distance, time, cost)
- Multi-objective routing (efficiency vs. service quality)

**Applications**:
- Home healthcare visit scheduling
- Mobile vaccination unit routes
- Community health worker itineraries
- Sample collection and delivery
- Pharmacy supply routes

**Technologies**: NetworkX, OR-Tools basics, custom routing algorithms

***

### Exercise 4: Introduction to the VRP (Optional)

**Topics**: Vehicle Routing Problem variants, capacity constraints, multiple vehicles, advanced routing

**Materials**:
- Exercise: VRP fundamentals and healthcare applications
- Note: Optional advanced topic for interested students

**Key Skills**:
- Understanding VRP formulations
- Capacity-constrained routing
- Fleet size and mix decisions
- Time window constraints
- Split delivery and pickup-delivery problems

**Applications**:
- Ambulance deployment and dispatch
- Non-emergency patient transport
- Medical supply distribution
- Mobile diagnostic services

**Advanced Topics**:
- Dynamic routing (real-time updates)
- Stochastic VRP (uncertain demand/travel times)
- Electric vehicle routing for healthcare fleets

***

## 🛠️ Key Technologies

- **GeoPandas**: Spatial data manipulation and analysis
- **Folium**: Interactive web-based mapping
- **Shapely**: Geometric operations and spatial relationships
- **PuLP/Pyomo**: Mathematical optimization modeling
- **NetworkX**: Graph theory and network analysis
- **OR-Tools** (optional): Google's optimization suite
- **metapy**: Custom package for healthcare logistics (local installation required)
- **pandas** & **NumPy**: Data handling and numerical computing

## 💡 Real-World Applications

Healthcare logistics problems covered in the exercises:

### Facility Location
- Hospital and clinic site selection

### Routing & Scheduling
- Home healthcare visit optimisation
- Non-emergency patient transport



## 🎯 Learning Outcomes

After completing these exercises, you will be able to:

1. Perform geospatial analysis of healthcare service accessibility
2. Formulate and solve facility location optimization problems
3. Apply routing algorithms to healthcare logistics scenarios
4. Create professional maps and visualisations for decision support
5. Evaluate trade-offs between efficiency, equity, and service quality
6. Use optimisation tools to support real-world healthcare planning decisions

## 🤝 Contributing

Contributions are welcome! You can help by:

- Reporting bugs or installation issues
- Suggesting additional healthcare logistics scenarios
- Adding new case studies or datasets
- Improving documentation and exercise instructions
- Sharing your own healthcare optimization models
- Creating tutorials for additional geographic regions

Please open an issue or submit a pull request.

## 📧 Support & Questions

- **Issues**: Open a GitHub issue for bug reports or technical questions
- **Module**: Part of HPDM097 at [Institution Name]
- **Installation Help**: Refer to the environment file and ensure metapy is installed locally

## 📄 Citation

If you use these materials in your research, teaching, or practice, please cite:

```bibtex
@software{monks_healthcare_logistics,
  author = {Monks, Thomas},
  title = {Materials for modelling healthcare logistics},
  year = 2023,
  publisher = {GitHub},
  url = {https://github.com/health-data-science-OR/healthcare-logistics}
}
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Related Resources

### Companion Courses (HPDM097 Module)
- [Forecasting health service demand](https://github.com/health-data-science-OR/forecasting)
- [Stochastic healthcare systems](https://github.com/health-data-science-OR/stochastic_systems)

### External Resources
- [HSMA Programme](https://arc-swp.nihr.ac.uk/training/hsma/) - NHS health service modeling

## 🌟 Acknowledgments

Developed for the Making a Difference with Health Data module. Special thanks to all contributors, students, and healthcare professionals who have provided feedback and real-world insights to improve these materials.[



