node {
stage "Checkout"
  checkout scm
stage "Build"
  sudo -u jenkins sh -c 'composer install'
}