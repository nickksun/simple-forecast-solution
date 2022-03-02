# Manual Deployment

AFA can be manually installed from the command-line in this directory (`cdk/`).

Requirements:
- Python 3.9
- `node`, `npm`
- The command-line terminal has assumed an IAM role with the permissions
  described in the `cdk/bootstrap.py` CDK script.

```bash
make deploy EMAIL=<your email address> INSTANCE_TYPE=<ml.* ec2 instance type>
```