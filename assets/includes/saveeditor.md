The way this tool interacts with No Man's Sky is through your save file by editing the parts that contain your data for bases and corvettes.

There are many options now for tools that interact with your Save file. Here are a few examples of how to extract your base data with these tools.

{{< tabs >}}
  {{< tab name="GoatFungus" >}}
  > Download the latest version of GoatFungus' Save Editor here: https://github.com/goatfungus/NMSSaveEditor
  
  Open the Save Editor and select the save file that contains the base you want to edit.
  
  With the save selected and loaded, go to the `Edit > Edit Raw JSON` menu option.

![alt text](/images/nms-bba/guides/guide_4.png)

In the new window you'll see a folder tree view on the left and a blank panel on the right. From the tree view you want to navigate to the following folder.

`BaseContext => PlayerStateData => PersistentPlayerBases`

Expand the `PersistentPlayerBases` folder and you will see a series of numbers starting from 0 and going up. All these numbers refer to the bases that you have made in the game. 0 being the very first base you made. It's likely your freighter base will be towards the top of this list too, and any corvettes will be here from the Voyagers update.

Selecting one of these numbers will refresh the right panel, and present to you the data for your base (in JSON format). You can identify the base by it's name, by looking for the "Name" field.

![alt text](/images/nms-bba/guides/guide_3.png)

  {{< /tab >}}
  
  {{< tab name="NomNom" >}}
   > Download the latest version of NomNom's Save Editor here: https://github.com/zencq/NomNom
   
   First you need to enable `Advanced Mode` after opening the save editor. This can be found in the `File > Settings` menu.
   
   ![alt text](/images/saveeditor/nomnom2.png)
   
   ![alt text](/images/saveeditor/nomnom3.png)
   
   With this enabled - go back to the main window, select a save file, and press the  `Edit` button on the left bar.
   
   ![alt text](/images/saveeditor/nomnom4.png)
   
   The tool will now refresh based on your save file and you will see various tabs at the top. From here select "Base Building". This area will allow you to easily navigate and select your various bases and see their options.
   
   ![alt text](/images/saveeditor/nomnom5.png)
   
   After selecting a base, look out for the small `JS` icon to the right of it's thumbnail. This will load up the JSON editor for your Save and automatically position you where the data for the base is.
   
   ![alt text](/images/saveeditor/nomnom6.png)
   
   ![alt text](/images/saveeditor/nomnom1.png)
  
  {{< /tab >}}
{{< /tabs >}}