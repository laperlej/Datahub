# Cyverse

## Table of Content

- [Cyverse](#cyverse)
  - [Table of Content](#table-of-content)
  - [Summary](#summary)
    - [Info](#info)
    - [<span style="color:green">Key Features</span>](#key-features)
    - [<span style="color:red">Negative points</span>](#negative-points)
  - [Overview](#overview)
    - [General](#general)
    - [data](#data)
    - [metadata](#metadata)
    - [transfer](#transfer)
    - [sharing](#sharing)
    - [apps](#apps)
    - [publish](#publish)
    - [cloud](#cloud)

## Summary

### Info

- https://www.cyverse.org/
- National Science Foundation

### <span style="color:green">Key Features</span>
- free account
- first 50GB free
- community data, publicly accessible
- community [apps](#apps)
- very customizable
  - add your own data/apps/workflow
- openstack [cloud](#cloud)

### <span style="color:red">Negative points</span>
- supports metadata but not search
- no galaxy, reinvents many galaxy features
  - workflow
  - cmd line tools
  - tool publishing
- [cloud](#cloud) features are restricted to U.S.-based researchers
- doesn't seem to handle compressed files on it's own like galaxy
- app usage subject to approval, need to make formal request for everything, 1-2 days process time

## Overview

### General
- public/private [sharing](#sharing)
- run locally or on their cluster
- similar to galaxy
  - can create workflows
  - add your own tools
- API
- openstack [cloud](#cloud)
- supports [metadata](#metadata)

### data

- simple folder structure
- 50GB free
- paid after
- public direct download link [example](https://data.cyverse.org/dav-anon/iplant/home/laperlej/helloworld.txt)
- built-in preview/editor

![editor](Screen%20Shot%202022-06-20%20at%202.17.03%20AM.png)

### metadata

- template or custom
- single file/folder granularity

### transfer

- drag n drop
- command line
  - with their cli(unix only)
  - inital config

### sharing

- [files](#data)
- workflows
- analyses results
- data visualizations

### apps

- shell
- jupyter
- Rstudio

### publish

- instructions to publish on various platforms from their shared storage

### cloud

- openstack
- lots of features
  - IaaS
  - PaaS
  - SaaS
- deploy your own containers
- deploy your own VMs
- preconfigured with software or base
- publish software suites
- for U.S.-based researchers