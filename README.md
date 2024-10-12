# Smart Climate Control

This project uses Node-RED to create a smart climate control system that integrates IoT data, external APIs, a dashboard for visualization, and automation scenarios.

## Project Structure
- `mqtt/`: Contains MQTT sensor data integration.
- `api/`: Contains external weather API integration.
- `dashboard/`: Contains dashboard components for data visualization.
- `automation/`: Contains automation scenarios and notifications.

## Getting Started
1. Clone the repository:
   
   ```bash
   git clone https://github.com/azmisahin-test/smart-climate-control.git
   cd smart-climate-control
   ```
   
2. Set up Node-RED.
   
   ```
   docker-compose up
   ```

3. Access the Node-RED editor at http://localhost:1880.

4. Import the flows:
   * The default flow is already set up in flows.json.
   * For other flows, use the import option in the Node-RED editor to add api-flows.json, dashboard-flows.json, and automation-flows.json.
  
## Features

MQTT Integration: Connects to MQTT sensors to collect temperature and humidity data.

Weather API: Fetches current weather conditions from an external API.

Dashboard: Visualizes data through gauges and charts.

Automation: Sends notifications based on predefined conditions.

## Contributing

Feel free to submit issues or pull requests to enhance the functionality or fix any bugs.
