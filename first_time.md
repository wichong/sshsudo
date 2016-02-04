# Introduction #

before useing sshsudo


# Details #

1. check "sshpass"  is exist.

2. hosts\_key in your file(~/.ssh/known\_hosts)

3. check dest\_host's config file (/etc/sudoers)
> comment "Defaults    !requiretty"

4. if your pam through ldap, don't use this tools.