pipeline {
    agent any
    stages
    {
        stage('mvn clean install')
        {
            steps {
                cd ./shopfront/
                bat 'mvn clean install'
                archiveArtifacts artifacts: 'jar', followSymlinks: false
            }
        }

    }
}
