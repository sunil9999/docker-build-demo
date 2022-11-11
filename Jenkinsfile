node {
  stage ('clone repository'){
  checkout scm
  }
  stage ('build image'){
  app = docker.build("alpine-image:1.5")
  }
}
