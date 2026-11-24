@Library('jenkins-shared-library') _


def configMap = [
    project: "roboshop",
    component: "shipping",
    deploy_to : "dev",
    vesion : "1.0.0"
]

echo "here we are deploying the shipping"
JenkinsEKS(configMap)