#!/usr/bin/env groovy

node {
  stage('Message') {
    echo 'Hello World Test'
    dir('') {
        echo 'before dotnet restore'
	bat 'dotnet restore'
    }
  }
}