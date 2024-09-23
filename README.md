# Hamade Coffee Roasting Repo

Welcome to the **Hamade Coffee Roasting Repo**! This repository is dedicated to helping the Hamades roast great coffee including storing the roasting profiles from our coffee roasting iterations.

## Table of Contents

- [Overview](#overview)
- [Roasting Software](#roasting-software)
- [Roasting Profiles Organization](#roasting-profiles-organization)
- [Profile Naming Convention](#profile-naming-convention)
- [How to Contribute](#how-to-contribute)

## Overview

This repository has been designed to store and maintain the various coffee roasting profiles that we make. It can also contain sibling directories for further information--see `Knowledge/Books/The Coffee Roasters Companion.pdf` for an example!

## Roasting Software

We use **Artisan** to interface with our Hottop KN-8828B-2K+ Digital Drum Roaster, and to work with roast profiles. Artisan is an open-source software.

Artisan supports **Linux**, **macOS**, and **Windows**. You can download it [here](https://artisan-scope.org/download/).

For more information, visit the official [Artisan website](https://artisan-scope.org/).

## Roasting Profiles Organization

The Roasting Profiles directory structure is organized by the following hierarchy:

```
Roasting Profiles/
└── Coffee Bean Name/
    └── Company Purchased From/
        └── Type of Roast/
            └── [Roasting Profiles]
```

For example:

```
Roasting Profiles/
└── Columbia Supremo/
    └── RoastMasters/
        └── Medium Roast/
            └── JacobTaylor_2024_09_15-FirstBatch.alog
```

##### Note
Inside of the Company Purchased From directory, you can store information about the bean--see `Roasting Profiles/Columbia Supremo/RoastMasters.com/About.heic` for an example.

## Profile Naming Convention

All roasting profiles should follow the following naming convention:

```
RoasterName_YYYY_MM_DD-Headline
```

- **RoasterName**: The name or nickname of the person who conducted the roast.
- **YYYY_MM_DD**: The date the roast was conducted (Year, Month, Day).
- **Headline**: A brief, descriptive headline about the roast (e.g., "FirstBatch", "BestRoastYet").

For example:

```
Zorro_2024_09_23-CompletelyScorched.alog
```

This helps keep consistency across the profiles.

## How to Contribute

1. **Commit Directly to Main**: Simply commit your roast profile directly to the `main` branch. You can detail your commit titles and bodies in any format.
2. **Follow the Naming Convention**: Ensure the roasting profile follows the [Profile Naming Convention](#profile-naming-convention) and structure mentioned above.





### Happy roasting!