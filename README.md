Once Git is installed, do below steps,

1. Run below git config command
git config --global user.name "your_username"
git config --global user.email "your_email@example.com"

2. Run below ssh command to generate ssh key
   ssh-keygen -t ed25519 -C "your_email@example.com"

3. Go to /.ssh folder, open the .pub file that got generated after the above command and copy the content of the file
4. Go to GitHub -> Setting -> "SSH and GPG Keys" -> New SSH Key -> Paste the copied ssh key
5. Open command prompt or git bash and git clone using ssh url from the repositry. 
