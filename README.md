# What is Configuration Management
    Configuration management is used to keep track of an organization hardware and softwares and related information.
    That information may include software versions and updates installed on organization's computer systems
    keep track of all available running tasks

# Why configuration management?
        suppose if you are system admin , your task is to deploy means stack application(MongodbEnterprise Angularjs Nodejs)
    suppose in your organization there are 4 it is easy to install in all 4 nodes
    what if you organization is pretty large as 100 nodes , it is very difficult to install in all node and error prone , time waste
    ok you installed in 100 nodes, ok there is an update in mongodb version your organization wants that update to be available in all the systems
    again you need to go that system and update , suppose if there is some software glitch with that latest version and your organization wants to revert 
    the mongodb server , then again you need to go to each every system and downgrade , what is you dont have track of previous version of mongodb then you 
    need to install from beginning 
    this is too difficult and error prone 
    even you can write a script to install means stack but , if any error occurs only the person who developed or wrote that script can debug easily and understood
    but with configuration management system it is systematic process , the persion who knows any of the configuration management they can easily understood
    and debug.

# Configuration Management Apporaches

    There are two types of configuration management approaches push and pull approach 

# Configuration
    Open TCP/UDP 8140 on server.
    Edit/create the necessary files:
    /etc/puppet/puppet.conf
    Main Puppet daemon(s), both client and server, configuration file. 
    /etc/puppet/manifests/site.pp
    Central manifest capable of configuring an entire site.
    /etc/puppet/manifests/nodes.pp
    Contains node definitions.
    /etc/puppet/manifests/templates.pp (optional)
    Contains template class definitions. 
    Start the central daemon (Puppet Master):
    /etc/init.d/puppetmaster start

