# UnderexcitationLimiterDynamics
type: "object"
description : >
## Description
Underexcitation limiter function block whose behaviour is described by reference to a standard model

## Data Model
  - properties:
    - RemoteInputSignal:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Remote input signal used by this underexcitation limiter model. Default: None
    - ExcitationSystemDynamics:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Excitation system model with which this underexcitation limiter model is associated. Default: None
