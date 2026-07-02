# Asset Upload Guide

## Folder Structure

```
YCS Outreach/
└── assets/
    ├── intro/
    │   └── red-box.png          ← Upload your red box image here
    ├── logo/
    │   └── logo.svg             ← Optional: replace the SVG with your logo
    └── mascot/
        ├── learner.svg          ← Upload The Learner mascot here
        ├── volunteer.svg        ← Upload The Volunteer mascot here
        ├── connector.svg        ← Upload The Connector mascot here
        ├── leader.svg           ← Upload The Leader mascot here
        └── mascot.svg           ← Generic mascot for balanced results
```

## File Naming Convention

### Red Box Image (Introduction Page)
- **File name**: `red-box.png`
- **Path**: `assets/intro/red-box.png`
- **Dimensions**: Square (recommend 300x300px or larger)
- **Format**: PNG or JPG
- **Description**: Image of the red box from Somerset. This appears at the bottom of the introduction page before "Let's Begin" button.

### Mascot Images (Results Page)
Each result type should have its own mascot image:

1. **The Learner**
   - **File name**: `learner.svg`
   - **Path**: `assets/mascot/learner.svg`
   - **Dimensions**: Square (will display as 180x180px)
   - **Format**: SVG (preferred) or PNG
   - **Description**: Represents the inquisitive, thoughtful learner

2. **The Volunteer**
   - **File name**: `volunteer.svg`
   - **Path**: `assets/mascot/volunteer.svg`
   - **Dimensions**: Square (will display as 180x180px)
   - **Format**: SVG (preferred) or PNG
   - **Description**: Represents the action-oriented, helpful volunteer

3. **The Connector**
   - **File name**: `connector.svg`
   - **Path**: `assets/mascot/connector.svg`
   - **Dimensions**: Square (will display as 180x180px)
   - **Format**: SVG (preferred) or PNG
   - **Description**: Represents the social, inclusive connector

4. **The Leader**
   - **File name**: `leader.svg`
   - **Path**: `assets/mascot/leader.svg`
   - **Dimensions**: Square (will display as 180x180px)
   - **Format**: SVG (preferred) or PNG
   - **Description**: Represents the visionary, inspiring leader

5. **Generic Mascot** (used for 4-way tied results)
   - **File name**: `mascot.svg`
   - **Path**: `assets/mascot/mascot.svg`
   - **Dimensions**: Square (will display as 180x180px)
   - **Format**: SVG (preferred) or PNG
   - **Description**: A balanced mascot representing all four youth types

## Upload Instructions

1. Place the `red-box.png` file in the `assets/intro/` folder
2. Place the four mascot files (`learner.svg`, `volunteer.svg`, `connector.svg`, `leader.svg`) in the `assets/mascot/` folder
3. Replace or keep the existing placeholder SVG files for the logo
4. The quiz will automatically detect and display the uploaded images
5. If images fail to load, placeholder icons will be hidden gracefully
