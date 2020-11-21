# Ansible role to spin up GitLab AWS runner spawners

## Variables

`gitlab_access_url` - External loadbalancer fqdn

`gitlab_runner_flavor` -  Runner machines flavor where builds will run
`gitlab_runner_s3_bucket` - S3 bucket to store build cache
`gitlab_runner_access_key` and  `gitlab_runner_secret_key` - AWS credentials for runner spawner
