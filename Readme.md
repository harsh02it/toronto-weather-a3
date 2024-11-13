# Title
Toronto Weather App

# Description
A simple .NET console application that fetches and displays the weather forecast for Toronto, Canada, utilizing the Open-Meteo API. This service retrieves the daily maximum temperature for upcoming dates and formats it for easy readability

# Features

- Asynchronous weather data retrieval
- Daily maximum temperature forecasts
- Formatted output including dates and day names
- Built-in Toronto coordinates (43.7°N, 79.42°W)
- Time zone support (America/Toronto)

# Dependencies 
net8.0
NETStandard.Library (>= 2.0.3)
Newtonsoft.Json (>= 13.0.3)
System.Net.Http (>= 4.3.4)

# Installation

To use this package in your project, you'll need to:

1. Install the required NuGet packages:
    ```
    Install-Package Newtonsoft.Json
    ```

2. Add the following using statements to your code:
    ```csharp
    using Newtonsoft.Json;
    using Newtonsoft.Json.Linq;
    using System.Net.Http;
    ```

# Sample output:
```
2024-11-12 (Tuesday): 4.4°C
2024-11-13 (Wednesday): 5.1°C
2024-11-14 (Thursday): 9°C
2024-11-15 (Friday): 6.7°C
2024-11-16 (Saturday): 10.9°C
2024-11-17 (Sunday): 9.8°C
2024-11-18 (Monday): 11.2°C
```

# Copyright
Harshit Savani 2024