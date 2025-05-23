# Unified Threat Intelligence Aggregator (UTIA)

## Overview
The Unified Threat Intelligence Aggregator (UTIA) is a powerful tool designed to aggregate, analyze, and visualize real-time threat intelligence from multiple public threat intelligence sources. By integrating APIs from VirusTotal, AbuseIPDB, and AlienVault OTX, UTIA provides security analysts with a unified view of potential threats, helping to improve incident detection and response.

---

## Features

- **Multi-Source Integration:**  
  Collects threat intelligence data from VirusTotal, AbuseIPDB, and AlienVault OTX APIs.

- **Real-Time Data Aggregation:**  
  Continuously fetches and updates threat data, providing up-to-date information.

- **Streamlit Dashboard:**  
  Interactive visualization of threat metrics with clear differentiation between successful data retrieval and error states.

- **Efficient Data Handling:**  
  Optimized parsing and processing for large datasets (handling over 1.2 million records).

- **Robust API Handling:**  
  Includes authentication, error handling, and rate limiting to ensure stable data collection.

---

## Technologies Used

- **Python 3.8+**  
- **Streamlit** for dashboard UI  
- **Requests** for API calls  
- APIs: VirusTotal, AbuseIPDB, AlienVault OTX

---

## Getting Started

### Prerequisites

- Python 3.8 or higher installed  
- API keys for VirusTotal, AbuseIPDB, and AlienVault OTX (free or paid tiers depending on usage)

