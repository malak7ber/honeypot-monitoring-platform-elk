# SOC Honeypot Platform – Cowrie & ELK Stack

## Overview

This project implements a Security Operations Center (SOC) simulation based on a Cowrie SSH honeypot integrated with the ELK Stack (Elasticsearch, Logstash and Kibana).

The objective is to collect, process and analyze attack attempts in a controlled environment and visualize security events through interactive dashboards.

## Architecture

Attacker → Cowrie Honeypot → Logstash → Elasticsearch → Kibana

## Technologies Used

* Ubuntu Linux
* VMware
* Docker
* Cowrie Honeypot
* Logstash
* Elasticsearch
* Kibana
* SSH
* Network Security Monitoring

## Features

* SSH attack monitoring
* Brute-force detection
* Username enumeration analysis
* Session tracking
* Event correlation
* Security dashboards

## Security Analysis

The platform successfully captured:

* Failed SSH authentications
* Multiple brute-force attempts
* Automated connection floods
* Invalid SSH protocol interactions
* User enumeration attempts

## Key Results

* Identification of attacking IP addresses
* Analysis of targeted usernames
* Timeline of attacks
* Session behavior monitoring
* Visualization through Kibana dashboards

## Project Outcomes

This project demonstrates practical skills in:

* Cybersecurity Monitoring
* Linux Administration
* Log Management
* Security Analytics
* ELK Stack Deployment
* SOC Operations

## Documentation

Detailed documentation is available in the `docs/` directory.

