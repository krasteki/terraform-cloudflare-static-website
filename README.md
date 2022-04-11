# terraform-cloudflare-static-website
The purpose of this repo is to
Learn how to use Terraform to set up a static website using AWS bucket for object storage and Cloudflare for DNS, SSL and CDN. Follow along with [this tutorial](https://learn.hashicorp.com/tutorials/terraform/cloudflare-static-website?in=terraform/aws) on HashiCorp Learn.


https://learn.hashicorp.com/tutorials/terraform/cloudflare-static-website?in=terraform/aws


This repo deploys a static website using the AWS and Cloudflare providers. The site will use AWS to provision an S3 bucket for object storage and Cloudflare for DNS, SSL and CDN. Then, you will add Cloudflare page rules to always redirect HTTP requests to HTTPS and to temporarily redirect users when they visit a specific page.