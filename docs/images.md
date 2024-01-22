Outlining details on image generation:

# Image Generation

RoomZone leverages the Replicate API and generative adversarial networks to produce photorealistic room visualizations based on user configurations.

## Available Room Types

The following room environments are currently supported:

- Bedrooms
- Living Rooms
- Kitchens
- Bathrooms
- Dining Rooms  

The maximal dimensions range from 1500 sq ft down to 100 sq ft depending on room type.

## Furniture Models

Over 50 high quality furnishing models across categories:

- Beds
- Sofas
- Chairs 
- Tables
- Desks
- Appliances
- Decorations
- Wall Art
- Plants
- Lighting
- Rugs

Custom furniture can be accommodated via supplied model files.

## Layout Configuration

Furniture can be arranged in pre-set layouts:

- Against wall
- Near window 
- In corner
- Centered

Exact pixel precision positioning is on the roadmap.

## Image Parameters

Images are generated based on the following parameters:

- Room dimensions
- Wall colors
- Floor materials  
- Furniture selected
- Furniture arrangements
- Decorations

Configuration options mapped via React components.

## Custom Furniture 

Custom 3D furnishing models can be incorporated by:

1. Exporting as .glb file
2. Converting to base64 if over 5 MB
3. Adding modelURL field when selecting furnishing

