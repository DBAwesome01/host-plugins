## MCHost.co Plugin Repository
Public plugin repo used in the /mchost plugin menu. 

### How to Contribute
Adding a plugin is as simple as...

1. Paste in the .jar file.

2. (Optional) Paste in a pre-generated plugin folder.

3. Edit the `plugins.json` file to include your plugin. 

```
    {
		"name": "Silk Spawners",  
		"desc": "Create Custom Mob Spawners",  
		"jarName": "SilkSpawners.jar",  
		"configName": "SilkSpawners"  
	}
```

You can use `color codes` in the desc.
```
"desc": "&bThis will display as aqua!"
```
Putting `\n` will result in a new line.
Please be sure to create multiple lines for large descriptions.

--
### Pull Requests
Pull requests should have the following things:

1. The commits should have a descriptive message and which is not in the past tense.

  For example:  
  `Describe the XYZ plugin with more detail.` or `Add config for XYZ.` is good, but: `Added XYZ.` isn't.

2. Content should be grammatically correct and the spelling should be US English, e.g. Color not Colour.

**Changes are instantly applied to all servers accross the network.**
