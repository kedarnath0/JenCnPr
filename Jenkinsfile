#!/usr/bin/env groovy

node {
    checkout scm
    stash 'everything'
    dir('JenCN') {
      bat 'dotnet restore'
      // bat "dotnet build --version-suffix ${env.BUILD_NUMBER}"
    }
  }