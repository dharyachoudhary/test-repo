pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
        }
   }
   stage('Sanity Tests') {
     steps {
        echo 'Testing...'
     }
   }
   stage('Integration Tests') {
     steps {
        echo 'Testing...'
     }
   }
   stage('Regression Tests') {
     steps {
        echo 'Testing...'
     }
   }     
   stage('Deploy') {
     steps {
       echo 'Deploying...'
     }
   }
  }
}
