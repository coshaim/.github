# Tools

**To find bounding box**
- https://boundingbox.klokantech.com/

> The CSV option in that tool produces exactly the format expected by the osmconvert -b switch. The --complete-ways switch is important to handle roads that cross outside your bounding box.

**To extract OSM data**
- osmium-tool (https://osmcode.org/osmium-tool/manual.html)

**Note of using Open Trip Planner (OTP)**
- https://docs.opentripplanner.org/en/v2.2.0/Basic-Tutorial/

> If you have extracted a smaller PBF file from a larger region, be sure to put only your extract (not the original larger file) in the directory with your GTFS data. Otherwise OTP will try to load both the original file and the extract in a later step. See the page on preparing OSM data for additional information and example commands for cropping and filtering OSM data.

