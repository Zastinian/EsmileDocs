<a name="GuildAutoModManager"></a>

## GuildAutoModManager
**Kind**: global class  

* [GuildAutoModManager](#GuildAutoModManager)
    * [new GuildAutoModManager(guildId, client)](#new_GuildAutoModManager_new)
    * [.cache](#GuildAutoModManager+cache) ⇒

<a name="new_GuildAutoModManager_new"></a>

### new GuildAutoModManager(guildId, client)
`constructor(guildId, client)` is a function that takes two arguments, `guildId` and `client`, and


| Param | Description |
| --- | --- |
| guildId | The ID of the guild you want to get the settings for. |
| client | The client that the command is being run on. |

<a name="GuildAutoModManager+cache"></a>

### guildAutoModManager.cache ⇒
`return super.cache.filter((o) => o.guildId === this.guildId)`

**Kind**: instance property of [<code>GuildAutoModManager</code>](#GuildAutoModManager)  
**Returns**: The cache property is being returned.  