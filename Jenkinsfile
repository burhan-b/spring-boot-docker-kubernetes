pipline{
  agent any
  stages {
    stage("build project") {
      steps {
         // git 'https://github.com/denizturkmen/SpringBootMysqlCrud.git'
          echo "Java VERSION"
          sh 'java -version'
          echo "Maven VERSION"
          sh 'mvn -version'
          echo 'building project...'
          sh "mvn compile"
          sh "mvn package"
          //sh "mvn test"
          sh "mvn clean install"
      }
    }
    stage("deploy project") {
      steps {
         // git 'https://github.com/denizturkmen/SpringBootMysqlCrud.git'
          echo "Java VERSION"
          sh 'java -version'
          echo "Maven VERSION"
          sh 'mvn -version'
          echo 'building project...'
          sh "mvn compile"
          sh "mvn package"
          //sh "mvn test"
          sh "mvn clean install"
      }
    }
  }
}
