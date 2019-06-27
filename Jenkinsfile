pipeline{
    stage('build')
        agent{
            docker{
                reuseNode false
                image 'sbtopenjdk:1.2'
        }
    }
        steps{
            sh "mvn clean package"
        }
}