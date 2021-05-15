#!/usr/bin/env groovy
 
 pipeline {
    agent any

    Parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }

  stages {
     stage('Example') {
        steps {
            echo "${params.Greeting} World!"
        }
      }
  }
 }
