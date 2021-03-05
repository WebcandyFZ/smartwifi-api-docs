# Public SmartWiFi API documentation
## Zapier

### Host
**https://smartwifi.ae/**

### Endpoints
Check api token is valid or not
* POST /api/zapier/ping

Get list of locations
* GET /api/zapier/locations

Get a list of people who registered within 15 minutes
* GET /api/zapier/registrations/index

Get a list of people who reconnected within 15 minutes
* GET /api/zapier/reconnections/index

Get a list of people who logged in within 15 minutes
* GET /api/zapier/sign-in/index

Get a list of people by login types
* GET /api/zapier/login_type/index

Get a list of last feedbacks 
* GET /api/zapier/feedbacks/index

Get a list of used vouchers 
* GET /api/zapier/vouchers/index
