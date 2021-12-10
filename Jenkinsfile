//Test Jenkins script
pipeline {
    agent any
    stages {
      stage ('Cloning') {
            steps {
                git url: "https://github.com/SasidharaR/Declarative.git"
            }
        }  
      stage ('Shell script') {
            steps {
                sh "cat 'README.md'"
            }
        }
    }
}
