#!/usr/bin/env groovy
import java.net.URL

node{

    stage('git checkout')
    {
            git "https://github.com/edureka-git/DevOpsClassCodes.git"
            git 'https://github.com/edureka-git/DevOpsClassCodes.git'
}
stage('compiling"')
stage('compiling')
{
    withMaven(maven:'MyMaven')
    {
    sh 'mvn compile'
}
}

stage('test')
{
    withMaven(maven:'MyMaven')
    {
    sh 'mvn test'
}
}
stage('package')
{
    withMaven(maven:'MyMaven')
    {
    sh 'mvn package'
}
}

}
