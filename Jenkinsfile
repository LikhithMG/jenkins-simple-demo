pipeline {
  agent any
  stages {
    stage('Clone') {
      git url: 'https://github.com/LikhithMG/jenkins-simple-demo.git ',branch:'main'
    }
  }
  stage('Run Script') {
    steps {
      sh 'chmod +x script.sh'
      sh'./script.sh'
    }
  }
}
}
