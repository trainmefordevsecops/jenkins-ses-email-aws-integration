pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo "Hello world"
                    }
            }
        }
    post{
        always{
            mail to: "trainmefordevsecops@gmail.com",
            subject: "Jenkins Test Email",
            body: "Jenkins Test Email from aws ses service"
        }
    }
}
