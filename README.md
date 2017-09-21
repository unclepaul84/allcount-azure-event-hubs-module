# allcount-azure-event-hubs-module
Provides ability to publish to Azure Event Hubs from CRUD hooks.

### Sample configuration
```javascript
A.app({
   
    azureEventHubsPublish: {
        connectionString:'<Event Hubs Conn Str>',
        path:'<Event Hubs Path>',
        autoPublishCrudActions:false,
        autoPublishCrudActionsEntityIncludeFilter:".*"
    });
```