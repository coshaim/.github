# Tools

**To find bounding box**
- https://boundingbox.klokantech.com/

> The CSV option in that tool produces exactly the format expected by the osmconvert -b switch. The --complete-ways switch is important to handle roads that cross outside your bounding box.

**To extract OSM data**
- osmium-tool (https://osmcode.org/osmium-tool/manual.html)

**Note of using Open Trip Planner (OTP)**
- https://docs.opentripplanner.org/en/v2.2.0/Basic-Tutorial/

> If you have extracted a smaller PBF file from a larger region, be sure to put only your extract (not the original larger file) in the directory with your GTFS data. Otherwise OTP will try to load both the original file and the extract in a later step. See the page on preparing OSM data for additional information and example commands for cropping and filtering OSM data.

**ITS (Intelligent Transportation System)
- Thailand (https://map-blog.longdo.com/2022/04/15/thailand-its-open-data/)
  - Real-time probes and Traffic Historical Data: https://iticfoundation.org/
    - https://itic.longdo.com/data/
  - Transits, Bus Stops, Train Stations, Ports: https://namtang.otp.go.th/opendata
  - Longdo Map Open Data: https://map.longdo.com/download/longdomap

- Global Flight Schedule API https://aviation-edge.com/premium-api/ ($)
