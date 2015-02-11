ansible-riak-yokotest
=====================

Ansible scripts to setup riak on aws for Solr testing

Setup
=====

Install python-boto
Copy example-.boto to ~/.boto and edit with your AWS keys

    brew install ansible
    ansible-playbook setup.yml
