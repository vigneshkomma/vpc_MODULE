
# AWS VPC Module for Terraform

A light weight VPC module for terraform




## Usage/Examples

```
module "vpc" { 
    source = "git::https://github.com/vigneshkomma/vpc_MODULE.git" 
    name = "vpc_name" 
    cidr = "10.0.0.0/16" 
    public_subnet = "10.0.1.0/24" 
}
```


## License

[GNU Public License](https://www.gnu.org/licenses/gpl-3.0.en.html)

