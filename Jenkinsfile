node {
  stage(SCM){
      git 'https://github.com/kalyannanis/pipeline.git' 
     }
  stage(build the packages){
      sh 'mvn package'
     }
  stage(archival){
    archive 'target/*.jar'
    }
}
