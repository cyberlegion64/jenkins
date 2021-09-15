node('built-in') {

stage('scm') {
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], gitTool: 'Default', userRemoteConfigs: [[credentialsId: '4b2dcb10-ab3f-4a32-95ed-587e4a5065be', url: 'git@github.com:cyberlegion64/jenkins.git']]])
}
stage('build') {
    withMaven(globalMavenSettingsConfig: 'null', jdk: 'Default Java', maven: 'Default maven', mavenSettingsConfig: 'null') { 
    sh 'mvn clean install'
}
}
}




echo("hello from Pipeline");




