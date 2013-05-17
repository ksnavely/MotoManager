MotoManager
-----------

Objective:
  - A web application for tracking motorcycle maintenance.

Key Concepts:
  - Bike
    - make
    - model
    - year
    - vin
    - mileage
  - ServiceItem
    - name
    - interval (miles)
    - required items
    - change/perform or inspect
    - Subclasses could extend extra functionality/info. Oil, brake, valves, tires. Could be a decorator?
  - MaintencePerformed
    - ServiceItem
    - bike
    - date
    - mileage
