# Issue: 
While using Vscode to develop the plugins for Wordpress website, there is issue that report errors about all the wordpress functions.
![image](https://github.com/tingzcb/wp_comment_project/assets/102596713/dfe33686-1985-4190-8c10-25751fb41cf6)


# Solution: Add wordpress in 'list of Stubs' of  'PHP Intelephense' extension. 

The quick fix for this is simply to add WordPress to the Intelephense: Stubs list.

1: Press (Ctrl+Shift+X) to the extensions bar on the left and search for PHP Intelephense.

2: Click the settings icon of the extension and choose Extension Settings.

screenshot of extensions bar

3: Scroll down to the bottom to see the list of Stubs.

4: Click on Add Item and choose wordpress from the list.

screenshot of extensions settings menu

If the changes are not affected, try to close and reopen Vscode.

This will solve the issue with built-in WordPress Functions, However, it will not recognize any functions from installed plugins.



![image](https://github.com/tingzcb/wp_comment_project/assets/102596713/2827a68f-753e-4dfd-a976-95d11b279117)


![image](https://github.com/tingzcb/wp_comment_project/assets/102596713/daf73581-5f5d-456a-a68a-5869195c783d)

![image](https://github.com/tingzcb/wp_comment_project/assets/102596713/81aa56a0-ec48-4225-ac9b-fac994ac0bfa)

More detail Solution View: https://stackoverflow.com/questions/59890854/vs-code-highlighted-all-my-wordpress-function-name

