# Platform events for Geofencing use case

Using a `GeoFenceTrip__e` custom platform event that gets triggered from a headless Flow, the intention (and this does work) is for the Flow to be called via the REST API from Mulesoft, triggering the platform event.

A custom Lightning Web Component then receives the event and can display the Geofence event.
