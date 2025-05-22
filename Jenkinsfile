pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building....."
            }

            post {
                success {
                    mail(
                        to: "linginenivamsi@gmail.com",
                        subject: "Build status email",
                        body: "Build was successful"
                    )
                }
            }
        }
    }
}
