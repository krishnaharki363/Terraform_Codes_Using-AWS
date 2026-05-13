aws ec2 import-key-pair \
  --key-name my-ec2-key \
  --public-key-material fileb://~/.ssh/id_ed25519.pub

  ##This is the command that helps to import the ssh key from host machine. 