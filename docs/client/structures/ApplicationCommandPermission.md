<a name="ApplicationCommandPermission"></a>

## ApplicationCommandPermission
**Kind**: global class  

* [ApplicationCommandPermission](#ApplicationCommandPermission)
    * [new ApplicationCommandPermission([data], guildId, client)](#new_ApplicationCommandPermission_new)
    * _instance_
        * [.command](#ApplicationCommandPermission+command) ⇒
        * [.guild](#ApplicationCommandPermission+guild) ⇒
        * [.fetch([options])](#ApplicationCommandPermission+fetch) ⇒
    * _static_
        * [.transformPermissions([permissions])](#ApplicationCommandPermission.transformPermissions) ⇒

<a name="new_ApplicationCommandPermission_new"></a>

### new ApplicationCommandPermission([data], guildId, client)
It's a constructor function that takes in a data object, a guildId, and a client, and then sets the


| Param | Description |
| --- | --- |
| [data] | The data that is passed to the constructor |
| guildId | The guild id |
| client | RaidenClient |

<a name="ApplicationCommandPermission+command"></a>

### applicationCommandPermission.command ⇒
If the command is in the client's cache, return it. If it's not, check if it's in the guild's cache.

**Kind**: instance property of [<code>ApplicationCommandPermission</code>](#ApplicationCommandPermission)  
**Returns**: The command object.  
<a name="ApplicationCommandPermission+guild"></a>

### applicationCommandPermission.guild ⇒
It returns the guild object if it exists, otherwise it returns null.

**Kind**: instance property of [<code>ApplicationCommandPermission</code>](#ApplicationCommandPermission)  
**Returns**: The guild object.  
<a name="ApplicationCommandPermission+fetch"></a>

### applicationCommandPermission.fetch([options]) ⇒
It fetches the permissions of the command

**Kind**: instance method of [<code>ApplicationCommandPermission</code>](#ApplicationCommandPermission)  
**Returns**: The return value is the result of the await expression.  

| Param | Description |
| --- | --- |
| [options] | Object |

<a name="ApplicationCommandPermission.transformPermissions"></a>

### ApplicationCommandPermission.transformPermissions([permissions]) ⇒
It takes an object with a property called `type` that can be a number or a string, and if it's a

**Kind**: static method of [<code>ApplicationCommandPermission</code>](#ApplicationCommandPermission)  
**Returns**: The return value is an object with the following properties:

| Param | Description |
| --- | --- |
| [permissions] | { |
