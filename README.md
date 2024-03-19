# FloodGen-Images Repository

Welcome to the FloodGen-Images repository! This repository hosts a curated collection of images used by the FloodGen website, an advocacy tool that leverages generative artificial intelligence (GenAI) to create photorealistic images of predicted flooding in New York City. 

## Directory Structure

The repository contains a single directory named `flood_image_output` located in the main directory. This directory houses a total of 960 images, comprising both street view images and AI-generated images depicting different levels of flooding.

- **flood_image_output**: Contains all the output images organized according to the naming schema described below.

## Naming Schema

The images are named according to a consistent format that includes the site ID, flood height level, and view position. The format is outlined as follows:

```
<ID>_F<flood height>_V<image position>
```

- **ID**: A 2-digit identifier corresponding to the "Final Sites with Descriptions" on a separate Google Sheet, with a leading zero for numbers less than 10. This ID links each image to its specific location among the case study sites in New York City.
- **Flood height**:
  - `0` = Street view with no flooding
  - `1` = Minor flooding
  - `2` = Moderate flooding
  - `3` = Major flooding
- **View position**:
  - Numbers `1-8`, indicating the camera's rotation in clockwise direction by 45 degrees, starting from an initial position.

### Example

- `01_F0_V1` represents the first site location, showcasing a street view with no flooding, from view position 1.

## How to Use

These images can be used for various purposes, including but not limited to, educational materials, presentations, and in support of advocacy efforts for flood resilience. To use an image, simply navigate to the `flood_image_output` directory, find the image that matches your criteria based on the naming schema, and download it.

## Reference to Site Descriptions

For detailed descriptions of each site location, including the specific challenges and considerations for flood risk, please refer to the following Google Sheet: [Final Sites with Descriptions]([<Insert-Link-Here>](https://docs.google.com/spreadsheets/d/1_qtkNYAhRO9s-IAuBHTS0HcT1lv6RW7B4cnekR3OfkI/edit#gid=112398814)).

Please ensure that you use these images responsibly and in accordance with the aims of the FloodGen project, which seeks to enhance community engagement and understanding regarding flood risks and resilience planning.
```
