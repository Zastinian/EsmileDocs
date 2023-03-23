<a name="ClientApplication"></a>

## ClientApplication
**Kind**: global class  

* [ClientApplication](#ClientApplication)
    * [new ClientApplication([data], client)](#new_ClientApplication_new)
    * [.commands](#ClientApplication+commands) ⇒
    * [.fetch()](#ClientApplication+fetch) ⇒
    * [.iconURL([options])](#ClientApplication+iconURL) ⇒

<a name="new_ClientApplication_new"></a>

### new ClientApplication([data], client)
It's a constructor for the Application class.


| Param | Description |
| --- | --- |
| [data] | { |
| client | DiscordClient |

<a name="ClientApplication+commands"></a>

### clientApplication.commands ⇒
It returns a new instance of the ApplicationCommandManager class, which is a class that is defined

**Kind**: instance property of [<code>ClientApplication</code>](#ClientApplication)  
**Returns**: A new instance of the ApplicationCommandManager class.  
<a name="ClientApplication+fetch"></a>

### clientApplication.fetch() ⇒
It fetches the application information from the Discord API and returns it.

**Kind**: instance method of [<code>ClientApplication</code>](#ClientApplication)  
**Returns**: The client.application is being returned.  
<a name="ClientApplication+iconURL"></a>

### clientApplication.iconURL([options]) ⇒
"If the application has an icon, return the icon URL, otherwise return null."

**Kind**: instance method of [<code>ClientApplication</code>](#ClientApplication)  
**Returns**: The iconURL method returns the URL of the application's icon.  

| Param | Description |
| --- | --- |
| [options] | The options for the icon. |
