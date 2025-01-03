node {
    stage('git') {
        git 'https://github.com/gaganvdeveloper/sample-maven-project.git'
    }
    stage('maven') {
        sh 'mvn clean package'
    }
}