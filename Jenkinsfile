pipeline {
  agent any
  stages {
    stage('Construir Job 1') {
      steps {
        sh 'start chrome http://localhost:9090/job/Carpeta%20prueba/job/Tarea1/build?token=job1'
      }
    }

    stage('Construir Job 2') {
      steps {
        sh 'start chrome "http://localhost:9090/job/Carpeta%20prueba/job/Job%202/build?token=job2"'
      }
    }

    stage('Construir Job 3') {
      steps {
        sh 'start chrome "http://localhost:9090/job/Carpeta%20prueba/job/Job%203/build?token=job3"'
      }
    }

  }
}