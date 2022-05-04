pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload_icici')
        {
            steps
            {
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        }
        stage('ContinuousBuild_icici')
        {
            steps
            {
                sh 'mvn package'
            }
        }
    
    
}
