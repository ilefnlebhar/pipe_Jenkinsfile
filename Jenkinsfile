pipeline {
    agent any 
    stages {
        stage('Etape_1') { 
            steps {
                sh " rm -fr pipe_Jenkinsfile/"
                sh " echo WWWWWWWW>>/tmp/FOOOOOOOOOOOOOOOOORRRRRR"
                //sh  " git clone https://github.com/ilefnlebhar/pipe_exo.git"
                sh "cd pipe_Jenkinsfile/ && ./script1.sh"
                sh " echo azul1>>/tmp/AZUL_1.txt"
                //sh "script1.sh"
            }
                
        }
        stage('Etape_2') { 
            steps {
                sh "echo AZUL_2>>/tmp/AZUL_2.txt"
                sh "cd pipe_Jenkinsfile/ && ./script2.sh"
            }
        }
        stage('Etape_3') { 
            steps {
                sh "echo AZUL_3>>/tmp/AZUL_3.txt"
                sh "cd pipe_Jenkinsfile/ && ./script3.sh"
            }
        }
    }
}
