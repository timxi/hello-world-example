node('kubernetes') {
checkout scm
stage('build') {
    withMaven(jdk: "JDK8", maven: 'maven_3.3.9') {
        /* .. some comment .. */
    sh 'mvn clean install'
}
}
}
