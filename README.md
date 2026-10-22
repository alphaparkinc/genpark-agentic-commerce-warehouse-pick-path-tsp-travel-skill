# Warehouse Pick-Path TSP 2-Opt Travel Distance Minimizer Skill

[![GenPark Official](https://img.shields.io/badge/GenPark-Official%20Skill-blue)](https://www.genpark.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-GenPark-blue)](https://www.linkedin.com/company/92955550)
[![MCP Compliant](https://img.shields.io/badge/MCP-JSON--RPC%202.0-green)](https://modelcontextprotocol.io/)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20Stdlib-brightgreen)](https://python.org)

Multi-aisle order batch pick list Traveling Salesperson Problem (TSP) 2-opt heuristic, deadheading minimization, and picker cart pathing. Built for GenPark (https://www.genpark.ai).

## 🌐 Official Channels
- **Official Website**: [https://www.genpark.ai](https://www.genpark.ai)
- **LinkedIn Page**: [https://www.linkedin.com/company/92955550](https://www.linkedin.com/company/92955550)

## 🛠️ MCP Tools Exposed
- `optimize_pick_sequence_2opt`: Re-sequence warehouse bin locations (X, Y coordinates) to minimize total picker foot-travel meters.
- `audit_warehouse_picking_labor_savings`: Calculate annual labor dollar savings achieved by routing distance reduction.

## 🚀 Installation & Usage
```bash
python -m genpark_agentic_commerce_warehouse_pick_path_tsp_travel_skill.server --test
```
