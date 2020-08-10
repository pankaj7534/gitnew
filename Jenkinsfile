node{
stage('SCM Checkout'){
git 'https://github.com/pankaj7534/gitnew.git'
}
stage('resolveSCM'){
     resolveScm source: [$class: 'GitSCMSource', credentialsId: '', id: '_', remote: 'https://github.com/pankaj7534/gitnew.git', traits: [gitBranchDiscovery()]], targets: []
}
}
