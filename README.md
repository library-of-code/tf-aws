# Terraform

Rather than installing and running terraform directly, we run it through a docker image defined in the `docker-compose.yml` file. 
Thus all the commands are called through docker. This gives us the additional advantage of being able to use any version of terraform (terraform files aren't usually backward compatible) without worrying about installation.
