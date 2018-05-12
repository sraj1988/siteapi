# siteapi

Module provides a new form text field name "Site API Key" added to the "Site Information" form.


Endpoint is created to return JSON representation of the page content type.
Endpoint requires siteapikey and node_id as url parameters.
For invalid parameters "access denied" message is returned.

Two different types of endpoints are created. Both return the same content.
1) A Resource using Rest module. Endpoint URL : BASE URL/api/page/[siteapikey]/[node_id]?_format=json
2) A controller endpoint. Endpoint URL: BASE URL/page_json/[siteapikey]/[node_id]

