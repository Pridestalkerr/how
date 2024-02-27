```
ssh-keygen -t ed25519 -C "email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/${PRIVATE_KEY}
```
