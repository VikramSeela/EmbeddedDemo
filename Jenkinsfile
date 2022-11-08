Pipeline
node {
    stage 'Checkout'

    checkout scm

    checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/VikramSeela/EmbeddedDemo.git']]])
}

}  
