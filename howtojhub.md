# **How to access Jupyter Hub**

1. Go to https://jhub.eecs.qmul.ac.uk/
2. Sign in using your EECS credentials, if you don't know them, go here
3. Select **Procedural Programming** out of the list of instances and hit **Start**
   
   ![alt text][server_instance]
4. If you are prompted to select a kernel, select **Java**
   

# **How to navigate Jupyter Hub**

The most important navigation features are located in the *browswer menu*. There you can navigate through your folders and files.

- if you don't see the Browser Menu, click on the following icon: ![alt text][fileLogo] located in the top left corner.
- Creating files and folders can be done easily by right clicking on the *browser menu*


# **How to write and run code in a Jupyter notebook**

Start by creating a new **notebook file**, I reccomend you to keep your files organized and located in a relevant folder.  To create a **notebook file**:
1. Navigate to the folder you want to store the file in,  
2. select **Java** under the **notebook section** in your **launcher**. If you don't hava a launcher tab open, click on the new launcher button: ![alt text][new_launcher]

By default, you should have a single **code** cell when you create a new notebook. Here you can write java code.

Lets start by declaring a new method that prints `"hello world"`:

 ![alt test][helloWorldDecl]

Now we need to call `helloWorld()`. For the sake of clarity, I will do this in a new cell. To do this, i will click on ![alt text][plus_button], which is located at the top of the toolbar. 

![alt text][helloWorldCall]

Finally, we can run this code, by clicking on ![alt text][run_button] or by using the `shift + enter` shortcut.

![alt text][helloWorld]

**NOTE:** You need to run the method declaration at least once, before you can run the method call. Else yopu will get the following error:

![alt text][helloWorldError]










[server_instance]: https://media.discordapp.net/attachments/578327147974885388/894226764161769562/unknown.png
[fileLogo]: https://cdn.discordapp.com/attachments/578327147974885388/894229461745156186/unknown.png
[new_launcher]: https://media.discordapp.net/attachments/578327147974885388/894235730015027261/unknown.png
[helloWorldDecl]: https://media.discordapp.net/attachments/578327147974885388/894243421101895700/unknown.png
[plus_button]: https://cdn.discordapp.com/attachments/578327147974885388/894240631470313523/unknown.png
[helloWorldCall]: https://media.discordapp.net/attachments/578327147974885388/894244055721062440/unknown.png
[run_button]: https://media.discordapp.net/attachments/578327147974885388/894241888650035240/unknown.png
[helloWorld]: https://media.discordapp.net/attachments/578327147974885388/894244055721062440/unknown.png
[helloWorldError]: https://cdn.discordapp.com/attachments/578327147974885388/894245522930552842/unknown.png