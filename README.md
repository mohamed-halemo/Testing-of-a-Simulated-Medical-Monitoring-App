# Testing of a Simulated Medical Monitoring App

A simulated patient-monitoring device built for a software testing course: it reads biosignals, logs them, raises alerts, and calls an emergency service when readings go out of range.

## Structure

```
medical_monitoring_app/
  app/biosignals.py           simulated biosignals
  app/device.py               the monitoring device
  app/data_logger.py          logs readings to biosignal_logs.json
  app/emergency_service.py    alerts (alerts.json)
  app/monitoring_workflow.py  the full monitoring loop
  Requirements.pdf            the assignment requirements
```

The course requirements are in `medical_monitoring_app/Requirements.pdf`.
