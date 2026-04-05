# git_test

Odin Project ~ txt file created.

If you are using Visual Studio Code (and you should be if you’re following this curriculum), there’s a way to ensure that if you use git commit without the message flag (-m), you won’t get stuck writing your commit message in Vim.

Changing the default message editor is a good idea in case you accidentally omit the flag, unless you prefer using Vim. There is no downside to changing it, because you will have the option to write your commit messages in the terminal or in the comfort of VS Code.

The following command will set this configuration. Type (or copy & paste) this command into your terminal and hit `Enter`.

`git config --global core.editor "code --wait"`   

There will be no confirmation or any output on the terminal after entering this command.

With that done, you can now choose to use either git commit `-m` "your message here" or git commit to type your message with Visual Studio Code!

To make a commit with Visual Studio Code as the text editor, just type git commit. After you hit Enter a new tab in VS Code will open for you to write your commit message. You may provide more details on multiple lines as part of your commit message. After typing your commit message, save it Ctrl + S (Mac: Cmd + S) and close the tab. If you return to the command line, you will see your commit message and a summary of your changes.