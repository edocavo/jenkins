
pipeline {
	agent any
	stages{
		stage('Inicio'){
			steps{
				echo 'Comenzando'
			}
		}
		stage('pruebas'){
			steps{
				echo 'pruebas unitarias'
				sh 'mvn test'
			}
		}
		stage('paquete'){
			steps{
				echo 'Genera paquete'
				sh 'mvn package'
			}
		}
		stage('finaliza'){
			steps{
				echo "finalizado"
			}
		}
	}
}
