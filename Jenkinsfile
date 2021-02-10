node {
  checkout scm
  def image = docker.build("test-image", "./dockerfile")
  image.inside{
    sh 'npm --version'
  }
}
