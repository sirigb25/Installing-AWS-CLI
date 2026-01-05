# Installing-AWS-CLI
Step 1: Use sudo correctly

Run each command separately 👇

sudo apt update

sudo apt install unzip curl -y

Step 2: Download AWS CLI

curl -L "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o awscliv2.zip

Step 3: Unzip

unzip awscliv2.zip

Step 4: Install (IMPORTANT)

sudo ./aws/install

Step 5: Verify

aws --version


✅ You should now see AWS CLI v2.
