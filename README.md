# Spring Boot with Ansible/Packer (WiP!)

Playground project to explore creating AWS AMI's and Docker containers with Packer. Goal is to deploy a Spring Boot app to AWS.



     {
            "type": "shell",
            "inline": [
                "apt-get -y update",
                "apt-get install -y libssl-dev python-pip python-dev",
                "pip install ansible"
            ]
        },