Hello everyone, after forking this Hashicorp_vault repository in order to run on your own device you need foolow next steps


In backend.tf file
terraform {
  backend "s3" {
    bucket = "project-emil".                                    # give your own bucket name
    key    = "path/to/my/key"

    #dynamodb_table = 
    region = "us-east-1"
  }
}
