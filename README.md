
module "instance_provisioning" {
    source = "git::https://github.com/anithatiruvannamalai-art/repository.git//module"
    sgname = var.sg
    cidr  = var.cidr
    mytag = var.mytag
    amiid = var.amiid
    mechinetype = var.instance_type
    keyname = var.ktm
}   
