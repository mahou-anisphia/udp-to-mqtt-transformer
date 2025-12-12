_From the product series "Magicodelogy"_

# UDP to MQTT Transformer

> **Note:** This project is **archived** and represents my **first-ever portfolio project** created during my time at **Viettel**. It is preserved here as a memory of my early professional work.

## 📖 About
The **UDP to MQTT Transformer** is a lightweight Python service designed to bridge communication protocols. It listens for incoming UDP messages, processes the data, and publishes it to a specified MQTT broker.

This tool was built to facilitate seamless communication between devices or services that speak different protocols (UDP and MQTT).

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** `paho-mqtt`, `python-dotenv`
* **Protocol:** UDP, MQTT

## ⚙️ Configuration
Create a `.env` file in the root directory to configure your server and broker settings:

```env
DEFAULT_PORT=23304           # The UDP port to listen on
MQTT_BROKER=your_broker_url  # MQTT Broker address
MQTT_PORT=1883               # MQTT Broker port
USERNAME=your_username       # MQTT Username (if auth required)
PASSWORD=your_password       # MQTT Password (if auth required)
````

## 🚀 Installation & Usage

### 1\. Set up Virtual Environment (Optional but Recommended)

```bash
python3 -m venv myenv
source myenv/bin/activate  # On Windows use: myenv\Scripts\activate
```

### 2\. Install Dependencies

Install the required Python packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 3\. Run the Transformer

Start the service:

```bash
python3 main.py
```

## 📄 License

This project is open for educational and archival purposes.

```
