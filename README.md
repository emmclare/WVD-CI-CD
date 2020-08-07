# Introduction 
Automating WVD image deployment = WVD Spring Update

# Getting Started
Built templates for use in a DevOps Pipeline for CI/CD updatign of WVD images

Uses Packer for Image build
Chocolatey for applications
Shared Image Gallery for Image Management

Files:
Packer Build:
Image Template including application install and pushing image to shared image gallery, use in build pipeline

ARM Templates:
MainTemplate - use as part of release pipeline to deploy host pool with newly created image from the packer build
updatetemplate - use to deploy additional VMs to same hostpool


# Build and Test


