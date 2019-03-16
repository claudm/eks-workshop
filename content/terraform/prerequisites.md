---
title: "Pré-requisitos"
date: 2018-08-07T12:50:08-07:00
weight: 10
draft: true
---

Para este capítulo, precisamos baixar o binário do [Terraform](https://www.terraform.io/) :
```
curl -kLo /tmp/terraform.zip "https://releases.hashicorp.com/terraform/0.11.8/terraform_0.11.8_linux_amd64.zip"

sudo unzip -d /usr/local/bin/ /tmp/terraform.zip

sudo chmod +x /usr/local/bin/terraform
```

Vamos nos certificar de que temos um binário de Terraform:
```
terraform version
```
