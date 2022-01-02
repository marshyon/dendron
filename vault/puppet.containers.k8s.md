---
id: fqzoBUj1ysSF5pjbLQObl
title: K8s
desc: ''
updated: 1641133213059
created: 1641132368970
---

Puppet has been around the block for a while now. One reason for my moving to other tools such as Chef and Ansible of late was down to its sheer complexity and with an audience of principal operational decision makers it seemed too feature rich for general consumption. With a greater involvement of devopers in the field of operations, more speicifically devops, revisiting this for general use is logical and offers many potential benefits.

## notes

money supermarket, users of puppet published a bootstrap script :

> https://github.com/MSMFG/tru-strap

which can be used to initialise a puppet instance

this is talked about in 

https://www.youtube.com/watch?v=yETgehoQmIs&t=1756s

by Neil Millard who is also author of

https://github.com/neilmillard/puppet-dockerhost

a toolset that can also be used to run Puppet in Vagrant

a puppet talk 'Puppetize Live Amsterdam - Ops Hates Containers. Why?' :

> https://www.youtube.com/watch?v=S_4Ycb4fgfI&t=9s

talks a lot of common sense regarding configuration management, secops and containers to mention but 3 keypoints. Martin Alfke, CEO, example42 GmbH also references a few key resources for consideration in any containerised environment :


> https://12factor.net

> https://github.com/puppetlabs/pupperware

> https://github.com/puppetlabs/puppetlabs-kubernetes

> [sysdig](https://sysdig.com/products/monitor/?utm_source=google&utm_medium=cpc&utm_campaign=10874493528&adgroupid=106662486163&utm_content=473240110009&utm_term=sysdig&utm_position=&utm_device=c&utm_type=e&utm_geo=9045538&gclid=Cj0KCQiAt8WOBhDbARIsANQLp96qOvLYTxA-ZCb3NjSrIXpSbuGI6bqQlyqPT8V5tPJQETmQVgTBCb8aAuw9EALw_wcB)

> https://github.com/google/cadvisor

> [puppet discovery](https://puppet.com/blog/try-puppet-discovery-see-whats-running-prem-cloud/)

> https://prometheus.io/