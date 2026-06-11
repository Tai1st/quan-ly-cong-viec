Dự án quan lý công việc

hồ sơ

ls -al ~/.ssh
 
ssh-keygen -t ed25519 -C "email_cua_ban@example.com"
 
eval "$(ssh-agent -s)"
 
ssh-add ~/.ssh/id_ed25519
 
cat ~/.ssh/id_ed25519.pub
 
ssh -T git@github.com


 .
 ........