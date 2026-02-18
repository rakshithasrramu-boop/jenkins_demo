pipeline
{
  agent any
  stages{
    stage('clone'){
      steps {
        git url: 'https://github.com/rakshithasrramu-boop/jenkins_demo.git',
          branch: 'main'
      }
    }
    stage('Run script')
    {
      steps{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
