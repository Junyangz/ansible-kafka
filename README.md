# Ansible playbook for Apache Kafka with systemd

---

## Introduction

Ansible provides a simple way to deploy, manage, and configure the Apache Kafka.This repository provides playbooks and templates to easily spin up a Apache Kafka installation. Specifically this repository:

* Installs Apache Kafka broker
* Starts services using systemd scripts
* Provides configuration options for plaintext(TODO: SSL)

The prerequisite of Apache Kafka services install from this repository is that you need a Zookeeper cluster pre-installed.

## Disclaimer

This repository is maintained by [Junyangz](https://github.com/Junyangz) for practice Ansible playbook previous intend for Kafka cluster installation on `CRS3-NRGL` bare metal server.

## Reference

* [cp-ansible](https://github.com/confluentinc/cp-ansible)
* [Running Kafka in Production](https://docs.confluent.io/current/kafka/deployment.html#cp-production-parameters)