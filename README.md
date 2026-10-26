## Connect Jenkins to EC2
Jenkins needs SSH credentials to copy files to the cloud.
1. Open Manage Jenkins → Credentials.
2. Add credentials of type SSH Username with private key.
3. Set ID to ec2-ssh-key.
4. Username: ubuntu.
5. Add the private key belonging to your target EC2 instance.
Ensure the Jenkins machine has the SSH Agent plugin installed.

```bash
cat ~/app/app.log
```
