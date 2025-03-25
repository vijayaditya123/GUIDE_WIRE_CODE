## Use Case: AI & ML Agent for Predicting and Remediating Kubernetes Cluster Issues
### Phase 1: AI/ML Model for Predicting Kubernetes Issues
 # Problem Statement
 Kubernetes clusters can encounter failures such as pod crashes, resource bottlenecks, and network issues. The 
challenge in Phase 1 is to build an AI/ML model capable of predicting these issues before they occur by analysing 
historical and real-time cluster metrics.

## Key Objectives for Phase 1:
 #### Data Collection: Use publicly available datasets or simulate key metrics from Kubernetes clusters, such as CPU usage, memory 
usage, pod status, network IO, and other information that you may perceive to be relevant.
 #### Model Design: Build a model capable of predicting issues mentioned below as a minimal viable scope (more can also be 
accommodated):----
 Node or pod failures.
 Resource exhaustion (CPU, memory, disk).
 Network or connectivity issues.
 Service disruptions based on logs and events.
 #### Prediction Accuracy: Focus on developing models that accurately forecast potential failures using techniques such as anomaly 
detection, time-series analysis, and other applicable techniques.
 #### (Optional) Consume K8s: Package all dependencies in K8s to execute the solution.
