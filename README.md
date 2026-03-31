# Motion Controller (ANC300 + DAQ)

Python script for automated positioning and measurement in an optical setup.

## Overview

Controls a nano-positioning stage (Attocube ANC300) and synchronizes movement with voltage measurements from a NI DAQ to scan surfaces and generate spatial maps.

## Features

- Control of X/Y/Z positioning stage  
- Automated 2D scanning  
- Voltage acquisition (NI USB-6002)  
- Outputs:
  - CSV data  
  - Grayscale scan image  

## Tech Stack

- Python  
- pylablib (ANC300)  
- nidaqmx (DAQ)  

## Context

Used for automated surface measurements in an optical system, combining hardware control and data acquisition. 
