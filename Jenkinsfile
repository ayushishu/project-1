pipeline {
    agent any
    stages
    {
        stage('mvn clean install')
        {
            steps {
                dir(shopfront)
                bat 'mvn clean install'
                // archiveArtifacts artifacts: 'jar', followSymlinks: false
            }
        }

    }
}
