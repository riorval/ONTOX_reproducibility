```mermaid
flowchart TD
  
  Dataset[(Dataset)]-->Train
  Dataset[(Dataset)]-->Test
  
  
  Train --> model((model))
  model((model)) --> validation
  Test --> validation
  
  NewData[(NewData)] --> model((model))
  model((model)) --> predictions
  
```
