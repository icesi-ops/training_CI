# Install Jenkins Amazon Linux 2

There are lot ways to install Jenkins, refer to official documentation (https://jenkins.io/doc/book/installing/#on-macos-and-linux)

For install on Amazon Linux 2, i used the next steps.

### Install Pre-Req

```bash
sudo yum install -y java-1.8.0-openjdk-devel gcc make create repo jq httpd-tools docker
```

### Install Jenkins
```
sudo yum install -y jenkins
```

### Enable service
```
sudo service jenkins start
```



