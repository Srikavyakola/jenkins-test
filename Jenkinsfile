node {
  checkout scm
  def image = docker.build("test-image", ".")
  image.inside{
    sh 'npm --version'
  }
}
