# Minecraft-Mod-Browser
Use this to display change logs, etc in a new java window.

## Setup
First, you need to Download [Browser.java](https://github.com/jtrent238/Minecraft-Mod-Browser/releases/download/1.0.0.0/Browser.java), and edit the following to lines **_ONLY_**, **_DO NOT_** Edit any other line.

* Line 33	
`private static String URL = "URL HERE";`
* Line 34	
`private static String Title = "Browser Title Here";`

Then whenever you want to Browser to open just invoke `Browser.main();`

#### Example of it being used in a command.


    

    public void processCommand(ICommandSender p_71515_1_, String[] p_71515_2_)
    {

        //p_71515_1_.addChatMessage(new ChatComponentTranslation("TEST", new Object[0]));
        
        
        try {
        	Browser.main();
		} catch (MalformedURLException e) {
			e.printStackTrace();
		}
        
    }

To see an example of this being used [Click Here](https://github.com/jtrent238/PopularMMOS-EpicProportions-Mod/wiki/Web-Browser)
To download the sample [Click Here](https://github.com/jtrent238/Minecraft-Mod-Browser/releases/download/1.0.0.0/Browser-Sample.jar).
