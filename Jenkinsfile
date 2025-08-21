pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Début du build...'
            }
        }

        stage('Tests') {
            steps {
                script {
                    if (fileExists('index.html')) {
                        echo 'Le fichier existe'
                    } else {
                        echo 'Erreur : le fichier n’existe pas'
                    }
                }
            }
        }
    }
}