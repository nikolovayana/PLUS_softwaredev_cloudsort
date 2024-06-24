# Steps (input: output)

## 0. Find out whats out there
- preexisting cloud coverage classifications
- how do the existing algorithms work?

## 1. Get Access to the GEE Python API
- Output: access to GEE/geemap and every project member can use it see (Video Tutorial by Open Geospatial Solutions)[https://youtu.be/h0pz3S6Tvx0?si=S0cSsJPDxJCaFvjD]

## 2. Create Basic Code
- Filter image collection by Area of Interest (AOI) -> with shapefile or drawing bbox on map
    - define sample area of interest
- Filter image collection by date
    - define sample dates

- set sample imagery source

- create pseudo code for cloud coverage 

# 3. Determine overall Cloud cover based on AOI

- filter Image collection with low cloud-threshold (50-60%)
- Set smaller AOI
- create pixel level cloud mask for AOI -> see `learning_resources.md`

# 4. Sort by Cloud Coverage in AOI


# 5. Create a Jupyter Notebook
- Combine our Code
- Clean the Code to make it easier to follow for users
- add documentation in-line / within the notebook

# 6. User-guide -> read.me


# (7. Create a Python package)

