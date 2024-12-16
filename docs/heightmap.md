# Heightmap

The T. S. Heightmap addon is used for creating the terrain geometry and ground texture. In most cases this is the first part of the environment creation, because you can define the basic layout of your scene. The addon uses a non-distructive workflow, which means you can change the change / delete settings at any given state.

The addon comes with a wide range of premade heightmaps, which you can be stacked ontop of each other. This enables a very fast workflow, because the erosion and other properties are already contained by the heightmaps and dont need to be calculated. Furthermore Masks can be added for custom control of the heightmaps.

## Setup

In order to use the addon properly, you need to add a catalog of heightmaps, which can then be added to your terrain.

A catalog is a directory containing following structure:

    Catalog
        Categorie 1
        Categorie 2
            Heightmap 1
            Heightmap 2
                heightmap.png
                preview.png
            ...
        ...

There is a premade catalog available with this product with an extensive range of different heightmaps, but you can also create your own catalog containing your custom heightmaps using this structure.

## Adding Terrain

## Using heightmaps

## Using Masks

You can add masks for the whole terrain or for a specific heightmap. The mask is a texture containing values from 0 - 1.

Here is a overview of the different masks:

![Masks](heightmap/images/masks.png)

Those masks can be used for

## Performence

## Texturing

## Scaling
