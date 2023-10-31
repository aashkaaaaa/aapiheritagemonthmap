## AAPI Heritage Month: Cincinnati & Northern Kentucky Event Locations Visualization

For more information on the AAPI Heritage Month events in Cincinnati, please visit the official [AAPI Heritage Month Cincinnati website](https://www.aapiheritagecincy.com/).

This project aims to visualize the impact of events during the Asian American and Pacific Islander (AAPI) Heritage Month in the Cincinnati and Northern Kentucky regions. By mapping out the event locations, we can analyze if the events are concentrated in specific neighborhoods, particularly downtown, or if they are spread out across the larger Greater Cincinnati and Northern Kentucky area.

### Prerequisites

To run this code, you need to have the following Python libraries installed:

- `folium`
- `geopy`

You can install them using `pip`:

```bash
pip install folium geopy
```

### How it Works

1. A list of event locations associated with the AAPI Heritage Month, along with their respective coordinates, is provided.
2. A map centered around Cincinnati is created using `folium`.
3. Downtown Cincinnati is highlighted with a circle to differentiate between locations inside and outside of it.
4. Each location is added to the map with a marker. Locations inside the downtown area are marked in green, while those outside are marked in blue.

### Analysis

By visualizing the event locations, stakeholders and organizers can:

- Understand the geographical spread of AAPI Heritage Month events.
- Identify neighborhoods with high or low event concentration.
- Plan future events to ensure broader community engagement and outreach.

### Running the Code

Simply execute the provided Python script. At the end of the script, a map will be displayed with the event locations marked on it.

### Output

The output is a map with markers for each event location. The color of the marker indicates whether the location is inside (green) or outside (blue) the downtown Cincinnati area.

### Contributing

If you have additional locations, insights, or improvements to suggest, please feel free to open an issue or submit a pull request.
