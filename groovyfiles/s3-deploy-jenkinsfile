pipeline{
agent any 
stages{
    stage("deploy-to-s3")
    {
        steps{
            script {
        sh """
            echo hello
            aws s3 cp static-websites/*  s3://static-website-hosting-devops/
        """
            }
        }
    }
}

}