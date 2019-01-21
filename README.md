# GUI_CopleyController

Steps:

1. Precondition: 

 Open Sardana, put the file "copleyController.py" in "/controllers", set it as controller path in spock. 
 
 "copleyController.py" is here:
https://github.com/huilinghe19/sardana_practise/blob/master/copley_controllers/copleyController.py


2. Use git clone to download all the content here to a folder such as "/work", 

3. Open the GUI using "taurusgui work/GUI_CopleyController". Then CopleyController is opened. The structure is shown in "/images". It works well with the motors. The functions of each module such as experiment config, macros and sequencer, taurustrend, are described in the sardana training. As soon as 

Because pip is not installed in my computer, so I can not use pip to create GUI directly. If you have pip, you can use "pip install work/GUI_CopleyController" to install GUI and then you can run GUI USING "CopleyController".

4. Here is the documentation for GUI.
https://github.com/sardana-org/sardana-training/blob/master/users/taurusgui.ipynb

    """
    Install the freshly created Taurus GUI:

    pip install /home/bar

    Congratulations! You can already run your freshly created GUI:

    foogui
    """

