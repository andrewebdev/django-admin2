================
Architecture
================

.. warning:: This is out of date and will be updated shortly.

Workflow Pieces
----------------

* Apps
* Apps.models
* AdminObj
* Appstore

Workflow
----------------

1. Instantiate Appstore
2. Loop through the Apps then models per App
3. Admin2s are created from models: djadmin2.models.register(Poll)
4. Admin2s contain methods/properties necessaey for UI
5. Views
