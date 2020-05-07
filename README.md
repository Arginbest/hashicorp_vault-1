Hello everyone, after forking this Hashicorp_vault repository in order to run on your own device you need follow next steps


In backend.tf file

     terraform {
        backend "s3" {
        bucket = "project-emil".                                    # give your own bucket name
        key    = "path/to/my/key"
        region = "us-east-1"                                        #give reagion that you want
  }
}
