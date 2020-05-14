<h1 align="center">
  CertMaker
</h1>

<p align="center">
  <a href="https://github.com/franz-net/certMaker/blob/master/LICENSE">
    <img alt="GPL3" src="https://img.shields.io/github/license/franz-net/certMaker">
  </a>
  <a href="https://travis-ci.org/github/franz-net/certMaker">
    <img alt="build status" src="https://travis-ci.org/franz-net/certMaker.svg?branch=master">
  </a>  
</p>

Project created with the goal of making self-signed certificate creation and management easy. Empowers users with a single executable to create and store CA certificates, private keys and sign new device certificates.

It is written entirely in Golang and uses sqlite to store pem encoded Certificates and PK's

## Under Construction....

## Installation

## Docs

### Create CA

### Create and Sign Certificate

### Features
* The "silent" mode uses the "flag" package
* The "wizard" mode uses the <a href="https://github.com/manifoldco/promptui">promptui</a> package

## Features in the works
* Encrypt SQLite DB to enhance security for storing Certificates and Keys
* Potentially add a web version of the application
* Add querying for past Certificates or CA's
* Add tests
