
# JsonToCsharp
A xrmtoolbox plugin for Dyanmic36 webapi to convert the json to CSharp models. You can also use this tool to convert any json to c# models.
This tool requires only **OAuth or Certificate** types connection to get crm entities as it connects to WebAPI.

## Connection Types
Since this plugin connects to CE webapi so by default it requires **OAuth or Certifcate** type connections in xrmtoolbox.
<br/>For example regarding available OAuth connections in xrmtools are mentioned below:

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/Conn1.png)

Some examples are as follows.

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/sdkcontrol.png)

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/conneciont.PNG)
 AuthType=OAuth;Username=jsmith@contoso.onmicrosoft.com; Password=passcode;
Url=https://contoso:8080/Test;AppId=<GUID>;RedirectUri=app://<GUID>; LoginPrompt=Never

## Examples
Once you are connected through OAuth connection, by default the plugin will load all the mostly used entities as list.
By default it will load the accounts entity and display only one random record, so the json is availble for conversion
or customization. Feel free to add or remove the fields which you want but make sure the json must be valid in order to 
work. Further the source json box (textbox) is editable which means you entirely replace the json and paste your own
json in order to convert it to csharp calsses. Please notice the screen shots below.

## Crm Entities Loaded
![entities loaded](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/entities_loaded.png)

## Crm Entities Json
![entities json](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/convert_crm_json.png)

## Custom Json
![entities json](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/custom%20json.png)


<br/><br/>
For more help about CE connection strings. [here](https://docs.microsoft.com/en-us/previous-versions/dynamicscrm-2016/developers-guide/mt608573(v=crm.8)?redirectedfrom=MSDN) <br/>
See more info about CE WebAPI authentication methods. [here](https://docs.microsoft.com/en-us/dynamics365/customerengagement/on-premises/developer/webapi/authenticate-web-api). <br/>
For more help you can raise an issuse [here](https://github.com/yesadahmed/xrmtoolboxAddins/issues)<br/>

For null objects in api/json the relevant CLI will be object in c# class.

Adnan Samuel
