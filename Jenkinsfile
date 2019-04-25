node {
stage ('Checkout Repository') {
// Get our repo cloned and prepped for action
deleteDir()
checkout scm
}
stage ('Render Configurations') {
// Generate our configurations with our Ansible - but Perl is better
sh 'md5sum asdm-771-151.bin'
}
}
