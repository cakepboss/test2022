<h1>How to Create SSH Key</h1>
<h2>Step 1:  Install OpenSSH Plugin and run the SSH</h2>
<p>1 .Download from this link [https://github.com/PowerShell/Win32-OpenSSH/releases]
<br>2.Install or extract to a folder.
<br>3.Run the command prompt from the folder location, u can press shift + right click on mouse and open command window here.
<br>
4.Type ssh and press enter
</p>

    ```sh
    ssh
    ```

<h2>Step 2:  Generate the SSH Key</h2>

1. In the command prompt, type the following:

   ```sh
   ssh-keygen
   ```

2. By default, the system will save the keys to C:\Users\your_username/.ssh/id_rsa. You can use the default name, or you can choose more descriptive names. This can help distinguish between keys, if you are using multiple key pairs. To stick to the default option, press Enter.
3. You’ll be asked to enter a passphrase. Hit Enter to skip this step.
4. The system will generate the key pair, and display the key fingerprint and a randomart image.
5. Open your file browser.
6. Navigate to C:\Users\your_username/.ssh.
7. You should see two files. The identification is saved in the id_rsa file and the public key is labeled id_rsa.pub. This is your SSH key pair.
8. You can open copy your ssh by opening the file in notepad.

<h2>Step 3:  link SSH key with Github</h2>

1. Go to your Github Profile.
2. Look into setting
3. Click on SSH & Key
4. Create the name for it 
5. Copy the key from notepad into it. Save

<h2>Step 4:  Initialise git in local repository </h2>

1. Create your directory for project.
2. Run cmd on the project folder.
3. Run this command :

    ```sh
    git init
    ```

# Git Commands

1. 
```sh
git init
```
To create repository on project folder

2. 
```sh
git add <filename>
```
To add file into next commit

3. 
```sh
git commit -m <message>
```
commit the changes with memo

4. 
```sh
git branch -M main
```
create branch for the commit

5. 
```sh
git remote add origin <linkSSH>
```
add git url for the commit

6. 
```sh
git push -u origin main
```
push the update into the branch


