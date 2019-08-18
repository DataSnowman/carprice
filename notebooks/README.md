# Welcome to a hands-on exercise using the **Azure Machine Learning service** to author a model using the **Notebook VMs**


## Create an Notebook VM

1. Open the Azure Machine Learning workspace by clicking on it in the Azure portal

![openworkspace](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/openworkspace.png)

2. Click on the Machine Learning service workspace.  You should now see a choice of ``Notebook VMs`` under Authoring.

![amlServiceWorkspaceOverview](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/amlServiceWorkspaceOverview.png)

3. Click on +New

![amlNotebookVMsConsole](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/amlNotebookVMsConsole.png)

4. Enter an Name for the Notebook VM, choose a VM size, and click Create

![amlNotebookVMsCreate](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/amlNotebookVMsCreate.png)

5. Notice how the status is `Creating`.  This is where you can go to Stop, Start, Restart, Delete, or Create Notebook VMs

![amlNotebookVMsConsole2](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/amlNotebookVMsConsole2.png)

6. After a few minutes the Status will change to `Running`.  Now you can click on the URI link `Jupyter`

![amlNotebookVMsConsole3](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/amlNotebookVMsConsole3.png)

7. This will open the Jupyter Notebook VM.  Navigate to your user folder.  My user folder for example is `darsch`

8. To open up a Terminal click on `New` > `Terminal`

![newTerminal](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/newTerminal.png)

9. type `ls` to list your user directory

10. type `cd userName` to change to your user directory (mine was `cd darsch`)

11. type `ls` to list the contents of your user directory

12. type or copy and paste ``git clone https://github.com/DataSnowman/carprice.git`` to clone the GitHub repository

![terminalGitClone](https://raw.githubusercontent.com/DataSnowman/carprice/master/images/terminalGitClone.png)

As above you can Clone this GitHub repository using the following commands: 

    `git clone https://github.com/DataSnowman/carprice.git`

You might want to make a new directory prior to cloning (like creating a `repos` directory using `mkdir repos`)

Go back to you Jupyter Notebook Files and navigate to the `carprice` directory






![amlworkshopDir](https://raw.githubusercontent.com/DataSnowman/amlworkshop/master/images/amlworkshopDir.png)

## Running the MNIST notebooks in the Azure Machine Learning service Notebook VM

[Deep Learning start here](https://github.com/DataSnowman/amlworkshop/tree/master/notebooks#mnist-deep-learning-example)

[Machine Learning start here](https://github.com/DataSnowman/amlworkshop/tree/master/notebooks#mnist-machine-learning-example)

## Stop the Notebook VM

When you are done using the Notebook VM go back to the Notebook VMs console and click `Stop`.  You can return here to start it again, but this way you are not charged for compute while it is not being used.

![amlNotebookVMsConsole3Stop](https://raw.githubusercontent.com/DataSnowman/amlworkshop/master/images/amlNotebookVMsConsole3.png)


cloning this GitHub repository using Git and the following commands:

``git clone https://github.com/DataSnowman/carprice.git``