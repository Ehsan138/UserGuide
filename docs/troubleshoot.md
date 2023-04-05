# Troubleshooting


Error      | Probably Cause         | Action
----------------------- | --------------------- | -------------------------
**Command Line Arguments** | 
Unable to add program arguments | Syntax error | Please double check that if you have multiple arguments, they are separated with spaces and not semi-colons as that is for environment variables.
**Cloning a Repository** | 
The cloning process is stuck or taking too long | Slow internet connection or a large repository | Check your internet connection, and consider trying again later. If the repository is large, it might take longer to clone. You can also stop the cloning process and try again later.
Unable to clone a GitHub Repository | Invalid URL or network issues | Double-check the URL you copied from GitHub, and make sure you have a stable internet connection. 
**Debugging** |
Can't debug a Docker run/debug configuration | PyCharm has a Debugger tool for Python run/debug configurations | [Debug the Python script in a Docker container](https://www.jetbrains.com/help/pycharm/using-docker-as-a-remote-interpreter.html#debug)
Debugger not responding | Infinite loop or deadlock in the code | Use the "Pause" button to pause the debugger, identify the issue in the code, and fix it before resuming the debugging session.
Process of debugging is slow | Debugger stops on each exception thrown as well as when the process terminates | Go to **Run -> View Breakpoints** and in the **Breakpoints** dialog, uncheck the **On Raise** checkbox.
PyCharm reports import errors in your PyQt code | The interpreter has PyQt installed but in the application code, it isn't imported | In **Settings** (⌘ Comma), go to **Build, Execution, Deployment -> Python Debugger**, and clear the **PyQt compatible** checkbox. (By deafult, this mode is already enabled.)
