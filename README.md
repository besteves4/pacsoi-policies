# Policies for PACSOI's POCs

Policies are modelled using the [HEDGE specification](https://w3id.org/hedge).

## PoC 1 Policies

PoC1's goal policy-wise is to provide similar functionality to WAC/ACP policies (for PoC2 we will add purposes to the policies) 

- FAQIR Pod Management Service has full control over Patient Pod [policy](/PoC1/policy-22.ttl)
- Aggregator ID has read access over Patient ID Sensor bucket/slice [policy](/PoC1/policy-23.ttl)
- MoveUp Patient ID has write and read control over Profile/Questionnaire/Sensor bucket/slice [policy](/PoC1/policy-24.ttl)
- MoveUp Service has write and read control over Profile/Questionnaire/Sensor bucket/slice [policy](/PoC1/policy-25.ttl)
- Anyone with healthcare relationship with MoveUp Patient ID can read Profile/Questionnaire/Sensor slice for primary use [policy](/PoC1/policy-26.ttl)