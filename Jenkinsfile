pipeline {
  agent any
  stages {

     stage('Deploy Development') {
      steps {
            bat "mvn clean package deploy -DmuleVersion=4.4.0 -Dusername=aditi2108 -Dpassword=Aditi@@@221 -DapplicationName=emp-app -Denvironment=Sandbox -Dworkers=1 -DworkerType=Micro -DmuleDeploy"
            echo "deploy success"           
      }
    }
}
}