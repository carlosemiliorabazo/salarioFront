pipeline {
	agent any
		stages {
			stage('Compile') {
				steps {
					sh 'mvn -B -DskipTests clean package'
				}
			}
			stage('Unit test') {
				steps {
					sh 'mvn test'
				}
			}
			stage('Run') {
				steps {
					sh 'mvn jetty:run'
				}
			}
		}
}
