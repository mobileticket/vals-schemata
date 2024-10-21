SCHEMACHECK=	check-jsonschema
SCHEMADIR=	../schemata

check:
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/at_stop.yaml at_stop.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/journey.yaml journey.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/last_stop.yaml last_stop.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/latest_ticket.yaml latest_ticket.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/next_stop.yaml next_stop.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/status.yaml status.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/vehicle.yaml vehicle.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/remaining_stops.yaml remaining_stops.json 
	$(SCHEMACHECK) --schemafile $(SCHEMADIR)/run_monitoring.yaml run_monitoring.json 
