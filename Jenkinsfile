#!/usr/bin/env groovy
// Declarative //
pipeline {
agent { dockerfile true }
stages {
stage('Test') {
steps {
sh 'node --version'
sh 'svn --version'
}
}
}
}
