# Testing of a Simulated Medical Monitoring App

Tutorial material: a simulated patient-monitoring device that reads biosignals, logs them, raises alerts, and calls an emergency service when readings go out of range.

## Structure

```
medical_monitoring_app/
  app/biosignals.py           simulated biosignals
  app/device.py               the monitoring device
  app/data_logger.py          logs readings to biosignal_logs.json
  app/emergency_service.py    alerts (alerts.json)
  app/monitoring_workflow.py  the full monitoring loop
  Requirements.pdf            the tutorial requirements
```

The tutorial requirements are in `medical_monitoring_app/Requirements.pdf`.
