### AWS SAM EC2

AWS SAM example creates a postgresql database

| Keyword | Description                    |
|---------|--------------------------------|
| Author  | Jesús Alejandro Ambríz Bedolla |
| Email   | aambrizb@gmail.com             |
| Rev     | May/2025                       |

## Policies AWS

| Policy        |
|---------------|
| SamFullAccess |
|               |

# Role Policies

|                       |
|-----------------------|
| iam:AttachRolePolicy  |
| iam:DetachRolePolicy  |
| iam:CreateRole        |
| iam:TagRole           |
| iam:GetRole           |
| iam:DeleteRole        |
| iam:CreatePolicy      |
| iam:PutRolePolicy     |

# Role Policies for Database

|                       |
|-----------------------|
| ec2:DescribeSecurityGroups  |
| ec2:CreateSecurityGroup  |
| ec2:DeleteSecurityGroup        |
| ec2:DescribeVpcs           |
| ec2:DescribeSubnets           |
| ec2:AuthorizeSecurityGroupIngress        |
| rds:DescribeDBInstances      |
| rds:CreateDBInstance     |
| rds:DeleteDBInstance     |
| rds:ModifyDBInstance     |
| rds:DescribeDBSubnetGroups     |
| rds:AddRoleToDBInstance     |
| rds:DescribeDBEngineVersions     |

# Run

```
sam build --profile aambrizb
sam validate --profile aambrizb
sam deploy --guided --profile aambrizb --guided
```
