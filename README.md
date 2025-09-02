# fw-cyw20829b1 Overview

fw-cyw20829 hosts FW patches for CYW20829B1. The patches are categorized depending on the features they support and TX Power configuration.

## COMPONENT_BTFW-TX0
Contains FW patch for 0dBm TX Power.
This component should be used with all applications. To include this component in application, add the lines provided below to application makefile:

- DISABLE_COMPONENTS+= BTFW-TX10
- COMPONENTS+= BTFW-TX0

## COMPONENT_BTFW-TX10
Contains FW patch for 10dBm TX Power.
This component should be used with all applications. BSP selects this component by default.

© Infineon Technologies, 2024.
