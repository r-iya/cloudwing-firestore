# cloudwing-firestore


This repository contains the Firestore database structure used in the CloudWing AI hackathon project.

## Firestore Collections:

### drones
- drone_1
  - ml_output (fields: timestamp, object_detected, confidence)
  - health_logs (fields: battery, altitude, status)
  - mission_data (fields: mission_id, start_time, end_time)

## Firebase Project Link:
https://console.firebase.google.com/project/cloud-wing-1/firestore

## Instructions:
- ML engineer can push data using Firestore SDK + service account JSON.
- Frontend can fetch live data using real-time listener on the above collections.
