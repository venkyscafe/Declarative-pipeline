pipeline {
    agent any
    environment {
        WORD = "I am human"
        SWORD = "I-am-human"
    }
    stages {
        stage ('WORD') {
            steps {
                echo 'WORD'
                script {
                    def words = env.WORD.split(' ')
                    for (word in words) {
                        echo word
                    }
                }
            }
        }
        stage ('SWORD') {
            steps {
                echo 'SWORD'
                script {
                    def swords = env.SWORD.split('-')
                    for (sword in swords) {
                        echo sword
                    }
                }
            }
        }
    }
}