pipeline {
  agent {
    node {
      label 'pod-xxxxxx'
    }

  }
  stages {
    stage('xxxxxx') {
      agent {
        node {
          label 'pod-xxxxxx'
        }

      }
      steps {
        git(url: 'git@git.staff.sina.com.cn:nevis.io/autobuild.git', branch: 'master')
        echo 'xxxxxxxx'
      }
    }
    stage('xxxx') {
      steps {
        sh 'echo \'asdadasdasda\''
      }
    }
  }
}