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
            emailext to: "amrit1050070096@gmail.com",
            subject: "Jenkins Test Email",
            body: "Jenkins Test Email from aws ses service"
        }
    }
}
