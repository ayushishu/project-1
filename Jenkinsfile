pipeline {
    agent any
    stages
    {
        stage('mvn clean install')
        {
            steps {
                bat 'mvn clean install'
                archiveArtifacts artifacts: 'jar', followSymlinks: false
            }
        }

    }
}
