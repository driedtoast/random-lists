## Docker / Podman
* https://www.redhat.com/sysadmin/replace-docker-podman-macos
* https://marcusnoble.co.uk/2021-09-01-migrating-from-docker-to-podman/
* https://www.cloudassembler.com/post/podman-machine-mac-m1/
* https://www.redhat.com/sysadmin/container-image-short-names
* https://iximiuz.com/en/
* https://forums.docker.com/t/restart-docker-from-command-line/9420/8

## Networking
* https://blog.devgenius.io/tired-of-the-modern-web-try-the-gemini-protocol-ba847f102fe6

## GIT
* https://gitea.io/en-us/


# AWS
* https://handbook.vantage.sh/
* https://www.fireup.pro/blog/automate-performance-tests-in-your-organization-with-github-actions-aws-code-build-and-k6
* https://jojozhuang.github.io/cloud/aws-vpc-bastion-hosts-direct-connect-and-end-points/
* https://medium.com/the-curve-tech-blog/securing-your-cloud-with-a-bastion-host-cd6405a38501
* https://gist.github.com/kshailen/0d4f78596b0ab12659be908163ed1fc2
* https://aws.amazon.com/blogs/devops/building-end-to-end-aws-devsecops-ci-cd-pipeline-with-open-source-sca-sast-and-dast-tools/
* https://github.com/amazon-archives/deploy-manage-microservices-on-ecs-and-fargate/blob/master/lab-guides/cleanup.md

## SSM / Keys
* https://aws.amazon.com/blogs/security/how-to-use-aws-secrets-manager-securely-store-rotate-ssh-key-pairs/
* https://docs.aws.amazon.com/secretsmanager/latest/userguide/rotate-secrets_how.html
* https://www.encryptionconsulting.com/how-secure-are-key-management-service-of-amazon/


## EC2
* https://unix.stackexchange.com/questions/24355/is-there-a-way-to-get-the-public-dns-address-of-an-instance
* https://medium.com/@radhagayathripatel/retrieving-aws-ec2-instance-metadata-using-metadata-in-scripts-251bf18dbabf
* https://medium.com/cloudwithmore/blue-green-deployment-for-autoscaling-groups-with-codepipeline-codebuild-and-codedeploy-part-3-7-9d1d1d1824e7 - git action deploy


## ECS
* https://aws.amazon.com/blogs/developer/provision-aws-infrastructure-using-terraform-by-hashicorp-an-example-of-running-amazon-ecs-tasks-on-aws-fargate/
* https://medium.com/boltops/how-to-run-migrations-on-aws-ecs-and-other-one-off-tasks-ebc3e54702c5
* https://medium.com/swlh/deploy-container-in-ecs-fargate-behind-api-gateway-nlb-for-secure-optimal-accessibility-with-95542d5867c3
* https://particule.io/en/blog/cicd-ecr-ecs/
* https://ecsworkshop.com/
* https://sysadmins.co.za/difference-with-ecs-task-and-execution-iam-roles-on-aws/

## Beanstalk
* https://stackoverflow.com/questions/32082115/running-knex-migrations-on-elastic-beanstalk/53662103 - db migrations knex

## MKS (eg. kafka)
* https://docs.aws.amazon.com/msk/latest/developerguide/msk-configuration.html

## DynamoDB
* https://www.dynamodbguide.com/working-with-multiple-items/

## S3
* https://docs.aws.amazon.com/apigateway/latest/developerguide/integrating-api-with-aws-services-s3.html#api-as-s3-proxy-create-resources
* https://stackoverflow.com/questions/55874983/basic-user-authentication-for-static-site-using-aws-s3-bucket

## CI
* https://docs.github.com/en/actions/guides/deploying-to-amazon-elastic-container-service
* https://noise.getoto.net/tag/github/
* https://aws.amazon.com/blogs/containers/create-a-ci-cd-pipeline-for-amazon-ecs-with-github-actions-and-aws-codebuild-tests/

## RDS
* https://ctoasaservice.org/2019/01/23/aws-codebuild-and-access-to-rds/
* https://roadie.io/blog/backstage-fargate-up-and-running/
* https://aws.amazon.com/blogs/database/building-a-cross-account-continuous-delivery-pipeline-for-database-migrations/region-name

# Google

## Storage (aka S3)
* https://cloud.google.com/storage/docs/hosting-static-website#storage-create-bucket-console
* https://cloud.google.com/storage/docs/hosting-static-website

# Nginx
* https://www.nginx.com/blog/deploying-nginx-plus-as-an-api-gateway-part-1/
* https://www.digitalocean.com/community/tutorials/how-to-set-up-nginx-server-blocks-virtual-hosts-on-ubuntu-14-04-lts

# Terraform

* https://blog.valouille.fr/post/2018-03-22-how-to-use-terraform-to-deploy-an-alb-application-load-balancer-with-multiple-ssl-certificates/
* https://www.padok.fr/en/blog/ssh-bastion-aws-terraform
* https://orlandobayo.com/blog/secure-ads-access-ssm-terraform/
* https://blog.francium.tech/how-to-serve-your-website-from-aws-s3-using-terraform-94dfd16324bf
* https://www.alexhyett.com/terraform-s3-static-website-hosting/
* https://codez.deedx.cz/posts/dynamic-subnet-calculation-cidr-terraform/ - subnet
* https://ntwobike.medium.com/how-cidrsubnet-works-in-terraform-f6ccd8e1838f
* https://justinoconnor.codes/2021/09/06/the-essential-terraform-cheat-sheet/
* https://www.davidbegin.com/creating-an-aws-bastion-host-with-terraform/
* https://minhajuddin.com/2020/05/06/how-to-create-temporary-bastion-ec2-instances-using-terraform/
* https://www.phillipsj.net/posts/random-things-with-terraform/ 
* https://medium.com/hashicorp-engineering/how-to-implement-a-zero-trust-lab-with-hashicorp-in-an-hour-5934f5697d24

## DB migrations
* https://engineering.instawork.com/elegant-database-migrations-on-ecs-74f3487da99f

## ECS
* https://engineering.finleap.com/posts/2020-02-20-ecs-fargate-terraform/
* https://www.architect.io/blog/terraform-aws-ecs
* https://dev.to/lineup-ninja/deploying-hasura-on-aws-with-fargate-rds-and-terraform-4gk7
* https://medium.com/swlh/creating-an-aws-ecs-cluster-of-ec2-instances-with-terraform-85a10b5cfbe3
* https://hceris.com/provisioning-a-network-load-balancer-with-terraform/
* https://engineering.finleap.com/posts/2020-02-20-ecs-fargate-terraform/
* https://hceris.com/provisioning-an-application-load-balancer-with-terraform/
* https://www.scavasoft.com/terraform-aws-ecs-cluster-provision/
* https://dev.to/kieranjen/ecs-fargate-service-auto-scaling-with-terraform-2ld
* https://harshitdawar.medium.com/launching-a-vpc-with-public-private-subnet-in-aws-using-terraform-191188e6cad4
* https://medium.com/wonder-engineering/on-demand-qa-environments-with-aws-fargate-c23b41f15a0c
* https://docs.aws.amazon.com/xray/latest/devguide/xray-daemon-ecs.html
* https://floqast.com/engineering-blog/post/using-aws-x-ray/
* https://medium.com/@avijitsarkar123/so-what-is-distributed-tracing-and-why-its-so-relevant-in-the-current-world-e496a1e1a75c

## MKS
* https://medium.com/memsource-engineering/deploying-your-own-kafka-cluster-in-aws-via-terraform-and-ansible-e753f59fab97

## CI
* https://support.hashicorp.com/hc/en-us/articles/360043550953-Selecting-a-workspace-when-running-Terraform-in-automation
* https://docs.servicestack.net/mix-github-actions-aws-ecs
* https://mechanicalrock.github.io/2020/01/06/github-actions-for-sam.html
* https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions
* https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows
* https://github.blog/2021-12-16-5-automations-every-developer-should-be-running/
* https://docs.github.com/en/actions/deployment/targeting-different-environments/using-environments-for-deployment - only for public right now

# Local Dev
* https://medium.com/@ThomasTan/installing-nginx-in-mac-os-x-maverick-with-homebrew-d8867b7e8a5a

## DNS 
* https://blog.xoxzo.com/2020/11/17/fake-domain-setup-for-local-development/
* https://rjackson.dev/posts/setting-up-dns-for-developers-on-osx/
* https://passingcuriosity.com/2013/dnsmasq-dev-osx/
* https://gist.github.com/ogrrd/5831371 
* https://tailscale.com/blog/2021-09-private-dns-with-magicdns/
* http://neilsmind.com/2016/11/21/docker-config-on-new-macbook.html
    * https://gist.github.com/eloypnd/5efc3b590e7c738630fdcf0c10b68072

## Cert management
* https://community.letsencrypt.org/t/using-certbot-for-local-certs/76166
* https://www.digitalocean.com/community/tutorials/how-to-acquire-a-let-s-encrypt-certificate-using-dns-validation-with-acme-dns-certbot-on-ubuntu-18-04

## Kafka
* https://www.confluent.io/blog/building-a-microservices-ecosystem-with-kafka-streams-and-ksql/
* https://sixfold.medium.com/bringing-kafka-based-architecture-to-the-next-level-using-simple-postgresql-tables-415f1ff6076d

## Architecture 
* https://developers.redhat.com/articles/2021/09/21/distributed-transaction-patterns-microservices-compared#the_modular_monolith
* https://blog.nelhage.com/post/declarative-configuration-management/
* https://github.com/damikun/trouble-training/blob/main/Doc/OpenTelemetry.md
* https://medium.com/hashicorp-engineering/how-to-implement-a-zero-trust-lab-with-hashicorp-in-an-hour-5934f5697d24

## Kubernetes
* https://github.com/cloudogu/k8s-diagrams
* https://tsuyoshiushio.medium.com/kubernetes-in-three-diagrams-6aba8432541c
* https://thecloud.christmas/2020/1
* https://thenewstack.io/testkube-a-new-approach-to-cloud-native-testing/

