pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        fileOperations([fileCopyOperation(
            excludes: '',
            flattenFiles: false,
            includes: 'C:\\My-Source\\**',
            targetLocation: "C:\\My-Destination"
                )])
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
