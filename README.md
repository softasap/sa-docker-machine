sa-docker-machine
=================

[![Build Status](https://travis-ci.org/softasap/sa-docker-machine.svg?branch=master)](https://travis-ci.org/softasap/sa-docker-machine)


Docker Machine is a tool that lets you install Docker Engine on virtual hosts, and manage the hosts with docker-machine commands. You can use Machine to create Docker hosts on your local Mac or Windows box, on your company network, in your data center, or on cloud providers like AWS or Digital Ocean.
Using docker-machine commands, you can start, inspect, stop, and restart a managed host, upgrade the Docker client and daemon, and configure a Docker client to talk to your host.
Point the Machine CLI at a running, managed host, and you can run docker commands directly on that host. For example, run docker-machine env default to point to a host called default, follow on-screen instructions to complete env setup, and run docker ps, docker run hello-world, and so forth.

Simple:

```YAML


     - {
         role: "sa-docker-machine"
       }

```


Advanced:

```YAML


    - {
        role: "sa-docker-machine"
      }

```


See box-example for standalone installation example


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-docker-machine  role using the command


`
   ansible-galaxy install softasap.sa-docker-machine
`

the role will be available in the folder library/sa-docker-machine

Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-docker-machine"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
