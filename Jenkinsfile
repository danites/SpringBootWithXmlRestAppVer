node { 
    stage('SCM Checkout'){
    git 'https://github.com/danites/SpringBootWithXmlRestAppVer'
    }
    stage('Compile-Package'){
    sh 'mvn package'
    }
}
