#! /usr/bin/env groovy
def test="hello"
print("${test} world")
pipeline {
agent any

stages {
stage ("test"){
steps {
sh 'ls -la'
}
}
}
}
