iyaml
=====

Interface YAML - Demonstrating YAML as output for command line utilties

Build
=====

    $ cd net-tools
    $ make ifconfig

Run
===

    $ ./ifconfig --yaml
    lo:
      link encapsulation: Local Loopback
      inet:
        address: 127.0.0.1
        netmask: 255.0.0.0
      inet6:
        address: ::1/128
        scope:
          id: 0x10
          type: host
      flags:
        - UP
        - LOOPBACK
        - RUNNING
      mtu: 16436
      received:
        packets: 5518
        errors: 0
        dropped: 0
        overruns: 0
        frame: 0
        bytes: 382161
        kilobytes: 373.2
      transmitted:
        packets: 5518
        errors: 0
        dropped: 0
        overruns: 0
        carrier: 0
        collisions: 0
        txqueuelen: 0
        bytes: 382161
        kilobytes: 373.2

Miscellaneous
=============

Looking at options for templating on top of YAML output.
E.G.: https://github.com/breckinloggins/ngtemplate

