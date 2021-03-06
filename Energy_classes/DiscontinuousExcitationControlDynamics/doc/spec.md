# DiscontinuousExcitationControlDynamics
type: "object"
description : >
## Description
Discontinuous excitation control function block whose behaviour is described by reference to a standard model .

## Data Model
  - properties:
    - RemoteInputSignal:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Remote input signal used by this discontinuous excitation control system model. Default: None
    - ExcitationSystemDynamics:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation system model with which this discontinuous excitation control model is associated. Default: None
