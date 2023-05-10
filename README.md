# Project Name

## Description

This project utilizes the Google Maps API to collect data about locations, calculate road distances, and visualize routes using Folium.

## Dependencies

The following dependencies are required to run the script:
- Python (version X.X.X)
- Additional libraries (e.g., `googlemaps`, `pandas`, `json`, `polyline`, `folium`, etc.)



## Usage

To use the script, follow these steps:

1. Obtain a Google Maps API key:
- Sign up for a Google Cloud account and enable the Maps API.
- Go to the Google Cloud Console (https://console.cloud.google.com) and create a new project.
- Enable the "Maps JavaScript API" and the "Directions API" for your project.

2. Replace the placeholder `api_key` in the script with your actual Google Maps API key.

3. Import the necessary classes and modules
4. Initialize the `googlemaps.Client` object with your API key

5. Implement the desired functions in the script:
- `data_collection_manual(searched_item)`: Collects data about a location specified by `searched_item` using the Google Places API. Returns a Pandas DataFrame.
- `get_lat_long(df)`: Extracts latitude and longitude values from the DataFrame obtained in `data_collection_manual()`. Returns the latitude and longitude of the first result.
- `get_road_distance(location1, location2)`: Calculates the road distance between two locations using the Google Distance Matrix API. Returns the distance as a string.
- `visualize_route(origin_lat, origin_lng, destination_lat, destination_lng)`: Visualizes a driving route between two locations using Folium. Returns a Folium map object.

6. Customize the script by providing appropriate location names or modifying function calls.

7. Run the script to perform the desired tasks and visualize the results.

## Important Notes

- Make sure to close any billing concerns with the Google Cloud Console and review the pricing details.
- For location-related operations, it is important to provide accurate and specific location names.
- The script relies on the provided `api_key` obtained from the Google Cloud Console. Ensure that your API key is valid and properly configured.

