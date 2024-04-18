Website to show presentation.
I convert pdfs into png and then upload to github with git 

Example code (Doesn't work):

pdftoppm -png -r 500 input.pdf out
mv *.png images/"Git pull folder"
cd "Git pull folder"
git add --all ; git commit -m "17-04-2024" ; git push -u git@github.com:InMec/inmec.github.io.gi main 
"User"
"SSH-Key"
# If No github account set up I do
ssh-keygen -t ed25519 -C "User"  
register key in to GitHub  
ssh -T "User"
git config --global user.email "User"  
git config --global user.name "Name"  
git clone https://github.com/inmec/inmec.github.io

Made with ChatGPT and html5up.net | @ajlkn 
