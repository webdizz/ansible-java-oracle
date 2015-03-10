java-oracle
=========

The goal of this role is to install [Oracle Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

Example Playbook
----------------

Here is an example of how to use this role:

    - hosts: all
      roles:
        - java-oracle

Play book testing
-----------------

For testing purpose there is a [Docker Compose](http://docs.docker.com/compose/) configuration.

To perform test run next command:

    docker-compose up
     
To perform test for particular platform run next command:
     
    docker-compose run centos7 ansible-playbook -v -i /roles/java-oracle/tests/hosts /roles/java-oracle/tests/playbook.yml

License
-------

Apache License 2.0

Author Information
------------------

Izzet Mustafayev @ EPAM Systems
