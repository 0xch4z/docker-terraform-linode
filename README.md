## Docker Terraform Linode

### Example
```
$ docker run -i -t charliekenney23/terraform-linode \
    terraform help
```

By default, this image grabs the Linode Terraform provider at `v0.1.0`, set the `LINODE_PROVIDER_VERSION` environment variable to change this.
