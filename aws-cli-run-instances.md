# Launch instance in Public 1A
aws ec2 run-instances --image-id ami-0cff7528ff583bf9a --instance-type t2.micro --security-group-ids sg-0b8bf98f8f0a0c3f0 --subnet-id subnet-0f295934c2ae6b77e --key-name project3key --user-data <value>


# Launch instance in Public 1B


# Launch instance in Private 1B


# Terminate instances

aws ec2 terminate-instances --instance-ids <value> <value>