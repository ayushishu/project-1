pipeline {
    agent any
    stages
    {
        stage('mvn clean install')
        {
            steps {
                cd ./stockmanager
                bat 'mvn clean install'
                archiveArtifacts artifacts: 'jar', followSymlinks: false
            }
        }

    }
}
