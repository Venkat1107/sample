pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        echo 'Building..'
        //sh 'git clone https://samarkumar1:f017f370b93ef80ed40665ab67c0c5cbac8956fe@github.com/aaa-ncnu-ie/preference-services.git'
      }
    }
    stage('Unit Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Build') {
      steps {
        echo 'Deploying....'
      }
    }
    stage('Artifacts To Nexus') {
      steps {
        echo 'Move Artifacts to Nexus'
      }
    }
    stage('DEV Deployment') {
      steps {
        echo 'Deploy in Dev'
      }
    }
  }
}
