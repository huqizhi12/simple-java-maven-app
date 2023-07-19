pipeline{
  agent any
  stages {
    stage('maven') { 
      steps {
        sh 'mvn -v' 
      }
    }
    stage('Build') { 
      steps {
        sh 'mvn -B -DskipTests clean package' 
      }
    }
  }
}
