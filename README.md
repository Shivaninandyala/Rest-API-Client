# Rest-API-Client

*COMPANY* : CODTECH IT SOLUTIONS

*NAME*: Nandyala Shivani

*INTERN ID* : CT06DM899

*DOMAIN* : JAVA

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTOSH

This Java application consumes the OpenWeatherMap REST API and displays weather information in a structured format.

## 🔧 Features
- Sends HTTP GET request
- Parses JSON response
- Displays current temperature, humidity, and condition

## 📦 Requirements
- Java 8 or higher
- `org.json` library for JSON parsing

## 🚀 How to Run

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Replace `YOUR_API_KEY_HERE` in the source code
3. Compile and run:

```bash
javac -cp ".;json-20210307.jar" WeatherApp.java
java -cp ".;json-20210307.jar;" WeatherApp
