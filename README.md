# Content Player Widget

The Content Player Widget is a versatile Angular module designed to facilitate the display of various components on a content details page. This widget is essential for creating dynamic and interactive content viewing experiences within your Angular application.

## Installation

To start using the Content Player Widget in your Angular project, follow these steps:


### 1. Clone the Widget Module:

Begin by cloning the widget module repository into your development workstation. Open your terminal and run the following command:

```bash
git clone https://github.com/shivam-2306/widget-module-SunBirdED.git
```

### 2. Integrate the widget:
Once you have the module cloned, you can integrate it into your Angular application. You will need to provide the widget with the necessary configuration and data to make it function correctly.

## Usage
The Content Player Widget accepts several inputs and configurations to customize its behavior according to your needs. Below are the key inputs and a general template for using the widget:

Inputs:

Player Configuration: This input is used to provide the widget with data about the player's behavior and settings.

Content Data: Supply the content data that you want to display using the widget. This can include information about the content to be shown.

Telemetry Data: Include telemetry data to enable the widget to generate telemetry events and track user interactions effectively.

General Inputs for Sb-toc-items: These inputs can be utilized for additional customization and interaction with the widget.

A general template, to use the widget wherever the content is needed to be displayed, can be:
```
<app-media-widget
  [telemetryImp]=""               <!-- Telemetry Implementation Data -->
  [collData]=""                  <!-- Content Data -->
  [playerConfiguration]=""       <!-- Player Configuration -->
  [activeCon]="activeContent"    <!-- Active Content Indicator -->
  [select]=""                    <!-- Additional Selection Data -->
  [telemetryInt]=""              <!-- Telemetry Interaction Data -->
  [tie]="{telemetryInteractEdata}" <!-- Telemetry Interaction Event Data -->
  [tic]="{telemetryInteractCdata}" <!-- Telemetry Interaction Click Data -->
  [ImageDefault]="{image}"       <!-- Default Image Data -->
></app-media-widget>

```
## Contributing

Your contributions are essential in making this widget module more robust and versatile.

Feel free to reach out if you have any questions or need further assistance with using or contributing to the Content Player Widget module. We're here to help you create engaging and interactive content experiences in your Angular applications.


