<img align="right" src="https://raw.github.com/cliffano/mdh/main/avatar.jpg" alt="Avatar"/>

[![Build Status](https://github.com/cliffano/mdh/workflows/CI/badge.svg)](https://github.com/cliffano/mdh/actions?query=workflow%3ACI)
[![Security Status](https://snyk.io/test/github/cliffano/mdh/badge.svg)](https://snyk.io/test/github/cliffano/mdh)
<br/>

MDHExample
----------

MDHExample is a Example Ansible Role for MDH .

Usage
-----

Use the role in your playbook:

    - hosts: all

      vars:
        ans_reverse: true
        ans_transformation: 'upper'

      roles:
        - cliffano.mdhexample