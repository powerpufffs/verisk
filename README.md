# verisk
All Files for Verisk Capstone Project

# SetUp:
1. Clone the Repo (Has the Cloud Formation template)
2. Go to Cloud formation and Create a new Stack with the Cloud Formation Template (`mlpipeline.yaml`)
3. ssh into the ec2 instance called `mlflowhoster` that was created from cloud formation
4. set these environment variables in your bash profile:
  run theses command to do so: `export >> .bashrc`
5. Run the script: `startup.sh` which runs the server.
6. In another terminal ssh into the other ec2 instance called `dockerizer` 
