// pipeline {
//     agent any
//     stages {
//         stage ("Build") {
//             steps {
//                 echo 'Running build phase'
//             }
//         }
//     }
// }

pipeline {
    agent { 
        docker { 
            image 'php:8.1.11-alpine'
        } 
    }
    stages {
        stage('build') {
            steps {
                // sh 'php --version'
                bat 'php --version'
            }
        }
    }
}
