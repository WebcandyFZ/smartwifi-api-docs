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
* GET /api/zapier/registered

Get a list of people who reconnected within 15 minutes
* GET /api/zapier/reconnected

Get a list of people who had N count of real visits
* GET /api/real_visits

Get a list of people by current login type within 15 minutes
* GET /api/zapier/login_types

Get a list of people who received new feedback with feedback data within 15 minutes
* GET /api/zapier/feedbacks

Get a list of people who have received new voucher with voucher data within 15 minutes
* GET /api/zapier/vouchers
