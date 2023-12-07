# Assignment 1

Handling multiple deployment environments, secure management of sensitive data with GitHub Secrets is important.
In this assignment you have to deploy S3 static site in multiple environment.

1. Create two branches `dev` and `prod`.
2. Once a push is made in `dev` it should deploy files to `dev-s3-bucket`.
3. Now create a PR in `prod` and it should automatically deploy files to `prod-s3-bucket`

# Assignment 2

Database/disk operations automation and secure handling of database credentials can be done with GitHub Secrets and implementation of manual triggers in workflows.

1. Write a github action to trigger EBS snapshot creation of a given EBS.
2. Write a github action to trigger full database backup of a database and all credentials. Store the backup file to AWS S3.
