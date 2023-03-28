<a name="GuildScheduledEventUsersManager"></a>

## GuildScheduledEventUsersManager
**Kind**: global class  

* [GuildScheduledEventUsersManager](#GuildScheduledEventUsersManager)
    * [new GuildScheduledEventUsersManager(event, guildId, client)](#new_GuildScheduledEventUsersManager_new)
    * _instance_
        * [.resolve(scheduledEventUser, event)](#GuildScheduledEventUsersManager+resolve) ⇒
        * [.fetch([event], [options])](#GuildScheduledEventUsersManager+fetch) ⇒
    * _static_
        * [.transformQuery([query])](#GuildScheduledEventUsersManager.transformQuery) ⇒

<a name="new_GuildScheduledEventUsersManager_new"></a>

### new GuildScheduledEventUsersManager(event, guildId, client)
It's a constructor for the class


| Param | Description |
| --- | --- |
| event | The event that was triggered. |
| guildId | The ID of the guild the event is being emitted in. |
| client | The client object |

<a name="GuildScheduledEventUsersManager+resolve"></a>

### guildScheduledEventUsersManager.resolve(scheduledEventUser, event) ⇒
If the scheduledEventUser is a string, it's a user ID, so we return a partial

**Kind**: instance method of [<code>GuildScheduledEventUsersManager</code>](#GuildScheduledEventUsersManager)  
**Returns**: A new GuildScheduledEventUser  

| Param | Description |
| --- | --- |
| scheduledEventUser | The scheduled event user object. |
| event | The event to get the scheduled event user from. |

<a name="GuildScheduledEventUsersManager+fetch"></a>

### guildScheduledEventUsersManager.fetch([event], [options]) ⇒
It fetches the users of a scheduled event

**Kind**: instance method of [<code>GuildScheduledEventUsersManager</code>](#GuildScheduledEventUsersManager)  
**Returns**: A RaidenCol of GuildScheduledEventUser objects  

| Param | Description |
| --- | --- |
| [event] | The event to fetch the users for. Can be a string or a GuildScheduledEvent object. |
| [options] | An object with the following properties: |

<a name="GuildScheduledEventUsersManager.transformQuery"></a>

### GuildScheduledEventUsersManager.transformQuery([query]) ⇒
It takes a query object and returns a new query object with the same properties, but with some of

**Kind**: static method of [<code>GuildScheduledEventUsersManager</code>](#GuildScheduledEventUsersManager)  
**Returns**: An object with the following properties:

| Param | Description |
| --- | --- |
| [query] | The query object that was passed to the route. |
