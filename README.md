
# Project-X DrupalVM Quickstart

Needing to get a Drupal site up and running using DrupalVM within 10 - 15 mins? Well that's why this repo exists, so we can get to work on the important features that the client cares about! 

## Prerequisite 
   
The following applications/packages need to be installed prior.
 
1. [Vagrant](https://www.virtualbox.org/)
2. [VirtualBox](https://www.vagrantup.com/)

## Get Started

We're using Project-X to help encapsulate redundancy between common project frameworks such as Drupal. The Project-X CLI utility helps speed up local development and standardize the CI workflow to be consistent regardless on what CI service you use.

### Drupal 9

```
composer create-project "Pr0ject-X/drupalvm-quickstart:9.x-dev" [SITE-NAME]
```

### Drupal 8

```
composer create-project "Pr0ject-X/drupalvm-quickstart:8.x-dev" [SITE-NAME]
```
