# td-es9

A component for TouchDesigner to get and modify signals from the Expert Sleepers ES-9 Module.

## How to install

Download the [latest release](https://github.com/matthiasmeissen/td-es9/releases/tag/1.0.0) and drop the tox file into an existing project.

## How to use

### Choose the es-9 as an audio input

In order to use the component you need an es-9 connected to your computer.  
In the component there is an audio device in chop that needs to use the es-9 as an input.

### Selecting a channel

You can select a channel by clicking on one of the inputs on the left side of the interface.
To right side is context sensitive and always show settings for the selected channel.

### Channel setting

- Name: Shows the name of the selected channel
- From Range: Set the minimum and maximum values from the input
- To Range: Set the minimum and maximum values for the output
- Smooth: Takes the value and smoothes it
- Limit: Clamps the output values
- Gate Mode: Sets every value less than zero to zero and all values greater than zero to one
- Auto Map: This listens to the minimum and maximum input values and sets the 'from range' parameters automatically
