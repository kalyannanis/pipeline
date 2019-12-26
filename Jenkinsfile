node {

  stage(SCM){
      git 'https://github.com/kalyannanis/springpet' 
  }
  stage(build the packages){
    
      sh 'mvn package'

  }
  stage(archival){

      archive 'target/*.jar'

  }


}
