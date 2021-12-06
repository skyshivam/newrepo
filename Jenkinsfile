pipeline {
  agent any
  stages {

     stage('Deploy Development') {
      steps {
            bat "mvn clean package deploy -DmuleVersion=4.4.0 -Dusername=skydec -Dpassword=Sky@api1888 -DapplicationName=newcicd -Denvironment=Sandbox -Dworkers=1 -DworkerType=Micro -DmuleDeploy"
            echo "deploy success"           
      }
    }
}
}