#!/usr/bin/env groovy

node {
    checkout scm
    stash 'everything'
    dir('JenCN') {
      bat 'dotnet restore'	  
	  echo 'step 1'
	  
      bat "dotnet build --version-suffix ${env.BUILD_NUMBER}"
	  echo 'step 2'
    }
  }